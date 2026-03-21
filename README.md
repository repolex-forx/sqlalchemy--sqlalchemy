# Repolex Knowledge Graph of sqlalchemy/sqlalchemy

RDF knowledge graph data for [sqlalchemy/sqlalchemy](https://github.com/sqlalchemy/sqlalchemy), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download sqlalchemy/sqlalchemy
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 0e15f047502bd3c17d008f95737119e0e3188658.nq.gz
│   │   ├── 4d78d5f3ab1bc5b4d41f086fecc5acc36ead45af.nq.gz
│   │   └── 94ac052104cd07ae0dace2d1b1ac6a7144412c44.nq.gz
│   ├── lsp
│   │   ├── 0e15f047502bd3c17d008f95737119e0e3188658.nq.gz
│   │   ├── 4d78d5f3ab1bc5b4d41f086fecc5acc36ead45af.nq.gz
│   │   └── 94ac052104cd07ae0dace2d1b1ac6a7144412c44.nq.gz
│   └── repolex
│       ├── 0e15f047502bd3c17d008f95737119e0e3188658.nq.gz
│       ├── 4d78d5f3ab1bc5b4d41f086fecc5acc36ead45af.nq.gz
│       └── 94ac052104cd07ae0dace2d1b1ac6a7144412c44.nq.gz
└── blob
    ├── 000479f09d178f2fcfde02594fc10de12fe0c302.nq.gz
    ├── 0019bcd68e1cf1ff69610072c01b7701c4d62e6a.nq.gz
    ├── 006b8905554b55fecefa313658105d30905fa05e.nq.gz
    ├── 009c83c0d49e117ca5c919ec9ebf1f621323bb6b.nq.gz
    ├── 00a17896c8f6637e111aa588c18a574042434c55.nq.gz
    ├── 00d2e6f6a105477532a3464791d1696ef7d4f93e.nq.gz
    ├── 010d1a2c02314f68c028e56260289a24c1e5e75a.nq.gz
    ├── 01114c51e99c4253123f855f77bb26cf43a40825.nq.gz
    ├── 01319aff0c8ba896d68ec6804c646c154359bcda.nq.gz
    ├── 018a46cd7df196bf18f82b3917646e1301cca753.nq.gz
    ├── 01cb0056ee9bb771cb3d199bb9dd122b62bc3747.nq.gz
    ├── 02248fa592a81c1004a9cdda24c1ee70283d0b83.nq.gz
    ├── 0256c6fd98a90e772d35b9bfbdeda3327f4d9840.nq.gz
    ├── 025ad4daaf71f2f98705637af18500f2d83e33f0.nq.gz
    ├── 02e0147076a76d84db83dd103d057bba436d210e.nq.gz
    ├── 03a0d1202d4ccce3b42861d3201562fa0b3d0c88.nq.gz
    ├── 03b0f76ec3e76924888b3b8a7ebcc2726e61b795.nq.gz
    ├── 03d827ea7efd163f18495cf9f44ae92f95a23ffd.nq.gz
    ├── 043f6f8ee7e67df83b24dccd3911d05cfebad8e7.nq.gz
    ├── 047c743e0d9786d67cd010f105a685c75f3344fa.nq.gz
    ├── 04800ffc00f2ce130820b948e8dac94efff14eed.nq.gz
    ├── 049e4a45e50064f352a21f57eab7322132e11103.nq.gz
    ├── 04bdc24fa4e46313ad4bae44b56feaf037107b19.nq.gz
    ├── 04f3ca67d6023819fd3f6cbaf6054420a445b84f.nq.gz
    ├── 05291ec0ea1687a98ebe3341df3e549bdf895f74.nq.gz
    ├── 053770e1c89375c4827367be0841035d46b4987e.nq.gz
    ├── 0548a79268e430774f2413db72c6d241caba706a.nq.gz
    ├── 054c55492268025c3145244828d42ad904c5f12b.nq.gz
    ├── 056e7ef70293fb9bd25d71785f870a0d5b482042.nq.gz
    ├── 05ad46d6ccc2609478f72276e92cdce9b08f806b.nq.gz
    ├── 05aff5f36cf92fd89162f9312aa49c83a97861cd.nq.gz
    ├── 061ba59b2ec0e30ed08506b05f9c65098e44f21a.nq.gz
    ├── 061dbc6daf7ca4bf70d4d69cfcb3598864ae05f0.nq.gz
    ├── 06363e2c7231d651d3e2b7eafb3e268dba15f0eb.nq.gz
    ├── 068264c720bbac79a0b2c472076b9ff029d53bfe.nq.gz
    ├── 069835ff9ec3f460a2549fcb53bab90c626ee27c.nq.gz
    ├── 06d839d54cb2c371a835a1eaf60f710159097c83.nq.gz
    ├── 074a6a71a8369972246e1f9080ab00194f31df10.nq.gz
    ├── 0763fe70cd905cfbe3d68f132877b943f04a2eee.nq.gz
    ├── 078a08037ef8f7adcb0d1fbbab0b6c8eefc4ec07.nq.gz
    ├── 079ff775dff740a91b888fd6eb5d3c6b615bb2ec.nq.gz
    ├── 07a13caee49bfbb29bdef38322dd740951127dab.nq.gz
    ├── 07ae2a2151505aa723975e8f9e2bbd30eae43c4f.nq.gz
    ├── 07f053980cd1b7960633487c7742853172747e12.nq.gz
    ├── 07fedbe311550b40ef86ac66809bb446b39b02ac.nq.gz
    ├── 08663baf4fc08951d2964668812a8daa40e5ebb2.nq.gz
    ├── 088705a0e6c648df365f9b19ebfea5991d057d35.nq.gz
    ├── 0888257f20fe473c3c493923ae85d804c29c00da.nq.gz
    ├── 089541848b9d1d1564b1edc339eda93877f726b1.nq.gz
    ├── 08989d8c2aa9be1dc58415dae350c6cf59bffd74.nq.gz
    ├── 08d55dbdb753d80b3d1a44ff0a5eb789846790eb.nq.gz
    ├── 08f08f913c9bbd6475dcc72fc4b237a246b25f87.nq.gz
    ├── 08f21ba6f126ffbf0f026fc1ae7b5999b38d0788.nq.gz
    ├── 09094508adfccea88488e83e2754afae68b21d3b.nq.gz
    ├── 090a27412980c3b79c9d398fa04b477a847cc375.nq.gz
    ├── 09598069d49619a8d67842d1d6a225b3daf33f34.nq.gz
    ├── 09e34691e8c2c45a67a541c55bc0587f4c9b6760.nq.gz
    ├── 09ed89bfbc4a199f44fa39187bcc180514f6d288.nq.gz
    ├── 0a0f23a707871d52c96e5d66381fd7e2725bdf42.nq.gz
    ├── 0a92b7f5a40bf45448a4e5d8e6b3b984bd9fbd93.nq.gz
    ├── 0aca6cd0c97e38e6d7b872d7aa0728b724b63847.nq.gz
    ├── 0afac7df390c6bcb58a53b210a0f6aeec76ae950.nq.gz
    ├── 0b279754f7677afc0de19396b5b574b65e7e26f3.nq.gz
    ├── 0b69f32ea5c01ba3d9f2abcce0912f4d2dcae927.nq.gz
    ├── 0b7a218ca8e14cd90bee324ecd53b68e25b4e63f.nq.gz
    ├── 0b933db4785ad8e75c80c4457e07912c76cefb11.nq.gz
    ├── 0bb2e51a49ea50c1712dabbd8facc225b12f27ef.nq.gz
    ├── 0bec280830e4004944828bc07964fb4d6a0b61df.nq.gz
    ├── 0c04e34b2ed23c147270fe14823ed83286b4e49c.nq.gz
    ├── 0c0a3ce9cd9f15c46b5de63b4af23e59dea71c22.nq.gz
    ├── 0c4647d8186c2d54a2d661e97e9dcd594442a352.nq.gz
    ├── 0c7fc6f8d373fe64abfdf28020ec6d80005a6024.nq.gz
    ├── 0c8aa2fe018ba92e5054ff08d51927a045b42f1c.nq.gz
    ├── 0ca331f189f8c702361bee6b160430c6c81686ba.nq.gz
    ├── 0cb4bb195aab8147d52d8e9735d53618a2492b05.nq.gz
    ├── 0cbaf33ea7ad3e657b9515399301c39989a2f22a.nq.gz
    ├── 0cf775e4d27aa9c00220aeb89dfc13e8b129a734.nq.gz
    ├── 0d91d12a4810088e982111f1a81071922cd53869.nq.gz
    ├── 0dda58affa6ad7452e69536d957e56c605b07e3e.nq.gz
    ├── 0df297743755a7db40d8a0d34ff76fdaf68ca13f.nq.gz
    ├── 0e86565bd9491074ffc87a08d0aa5f2abb266d1d.nq.gz
    ├── 0ed2288adcfa95b5f58cd6899b29a649b986c198.nq.gz
    ├── 0ee4a1bc5ad7cab6171c57fe9ca12e935f8030b3.nq.gz
    ├── 0efb56c26341858d20f2ce1ab574e5b65b5f18d1.nq.gz
    ├── 0f18e167eba35030e8d0bbd7aeefd002f2cbec58.nq.gz
    ├── 0f19854e9db7cd71f2fea7ae09729f5d0f653359.nq.gz
    ├── 0f3119d2c0a39b44e6bc6a48515ccdcd8012cbb9.nq.gz
    ├── 1021f4e99e3e2638fdc0af4a149fdf56d569b541.nq.gz
    ├── 102c20966729a37e7054043a73ecfa0e7d50ca59.nq.gz
    ├── 104d67f4075ce7814b2a476851b40a8f659d7d23.nq.gz
    ├── 1063606eaec8eeb5852223c932763e3d8e80ef7e.nq.gz
    ├── 10cf9f6b225d1fe71b84067f3af25de60cb14acb.nq.gz
    ├── 10d73cb8d6404a8644b57c3894dcf4dfa355c070.nq.gz
    ├── 116fb74eec8bc43b88d1747e1aa89281c167b995.nq.gz
    ├── 117e365713c21bb4d7fa449c1955ee6947096e85.nq.gz
    ├── 1186e8eacf6ca36bb20e59baafee99e162bce610.nq.gz
    ├── 120f6a147413f9d4451afa6a098bb81a6374c559.nq.gz
    ├── 121d8de40a5549c0064b947f59c8bdcc160d487f.nq.gz
    ├── 123014908bebbfb7ecfa1d15daaceb272fabe05b.nq.gz
    ├── 126f95289e86d5f76823d25bb6049cc70e2aa1ba.nq.gz
    ├── 12fe1576cace6d926f693cac62a6c6ff0fc186a1.nq.gz
    ├── 13042ed7a5e173a0ff2b35bba6ffba31b5c4735a.nq.gz
    ├── 1321afe34e97cb05413363f97e5f8fdb9fe48808.nq.gz
    ├── 1330f88b63628cc2fa579b6a86c8164a33000df2.nq.gz
    ├── 1374e05f51e2ee547ed9a2cecae9867632a732f8.nq.gz
    ├── 139597f9cb07c5d48bed18984ec4747f4b4f3438.nq.gz
    ├── 139f4df7ee7505134cc0ef28ad185f5f90c3fb44.nq.gz
    ├── 13df0f349a26aad55e26dc5734dff12e866c2eda.nq.gz
    ├── 13e4183906b3e9d138727e0ad98dce62d995dcd8.nq.gz
    ├── 140018f662fd61e0e429f64f193130f841cad863.nq.gz
    ├── 141a645995537e9e87ed2e2e69941ca6b022cbec.nq.gz
    ├── 146b96b2a73425fb01bc9d8ab52ed4f699607542.nq.gz
    ├── 1492f6abd89766b792488afee7ddd9d0eec55ed5.nq.gz
    ├── 14b85420c9c5df131dca10e110592e5730b89536.nq.gz
    ├── 14cd1902bc7cca00a0d7205a152d109ce74e473f.nq.gz
    ├── 14d13bd6f5d782db2ead12d5bfe864c609390165.nq.gz
    ├── 14d3f8216c9c3429d9483ff32941ae3e39537eb1.nq.gz
    ├── 14f9c5210504a50414500ab35567c38c818c178f.nq.gz
    ├── 1510689f9f2e05e7ae7758bc3f459523374fbf58.nq.gz
    ├── 152263617e706659acf3beebbba55222bf819a8d.nq.gz
    ├── 156ab47c03841b58b7fbfad3f5fd9f9b70832060.nq.gz
    ├── 158326e1e2debfdb8a45c0ae4e87d7afdd178b80.nq.gz
    ├── 15961c703a4f6ec2799cef8c8010fdd3f450ba9a.nq.gz
    ├── 159c5acfe96cfda75cf44de2af0d6ccbc0754537.nq.gz
    ├── 161dce08757bb4d9d790aeb3f73e46e87605076c.nq.gz
    ├── 166c2af8688cf86caaf6a768ccd3f2d78ee89a4d.nq.gz
    ├── 16a4f3540f2f70f2a18a4cc8af491123944312bc.nq.gz
    ├── 16cdafebcca42d859298ff60efbddbb23648cf8b.nq.gz
    ├── 16fef5128d8ebb96fe49bba4c9a98adde5063f16.nq.gz
    ├── 170324fa30c422a65d4f0e7c4f064b5cf1e100c7.nq.gz
    ├── 170cfdad03e8eb7ac71eeeb3328543979dc02cd7.nq.gz
    ├── 1719de51671915374eca24658be895a3efa931b0.nq.gz
    ├── 1724dd6985c613d87daf4a8d87c1fea9a283b0d8.nq.gz
    ├── 172caaa517db9a8b130a0c2cf6611023cf0748f2.nq.gz
    ├── 17a6f59b2070b2399f90e0f4619dba76adeaa851.nq.gz
    ├── 17b3cff5f7316b48a6576b7dfded90916b602de6.nq.gz
    ├── 17c2e7dc679e4632c92ca53ffcbf258241fe82c5.nq.gz
    ├── 17f4335b03ee8cec04e76a8c0ea727a35da96d56.nq.gz
    ├── 17f7eccdaba85d04c0592a44e559bc1be3e5d818.nq.gz
    ├── 17fb075ac40394f590816f23f931ba7c41639d8d.nq.gz
    ├── 18360c4d7da22a9badb8317ac2c4f9ad5eb7721c.nq.gz
    ├── 18476fc491b8433b57d74be50443ed89354dd312.nq.gz
    ├── 18803c75fff78dbb23d11b001f6e8c17c40eb46c.nq.gz
    ├── 188668be7942a6ae7e8b743cdd08615b261a2989.nq.gz
    ├── 18904cc38611f7b65d6fcda27f633fee374fa4af.nq.gz
    ├── 18940ed5f866d903d93605823d88d5b62f499365.nq.gz
    ├── 189e6566cfca85d481d5840f5a39b82ca3f42612.nq.gz
    ├── 189ebea0ece11817b0c304f2a143c0e4cfe266c6.nq.gz
    ├── 18a97e3f788dddab2cee3bc69f7134d4203fd20e.nq.gz
    ├── 18ac4f554bc10130fd8a29fa121862d0a4f72cb7.nq.gz
    ├── 18ad347b2c457203e2505bd2fc068793ef50e61b.nq.gz
    ├── 19599a57828286e2a2877e7ba8e40a98ebc6597a.nq.gz
    ├── 19a7b07c151f10ff322d986afa825ac1c7093ca3.nq.gz
    ├── 19cb2bfb415be701461f5f205524486182785c5e.nq.gz
    ├── 19d3ed491c125f7a21767ea00fca4d90c1997ee2.nq.gz
    ├── 1a3664f7de7a13bae5cafcaab4f0e01a8427565e.nq.gz
    ├── 1a4c251a47698e14428ff852d5c6b8ed1a5bd37d.nq.gz
    ├── 1a935e3ff026e10fb8a1860996e0f91834190875.nq.gz
    ├── 1ad56037d2c9b96f93546df9e42bed89cde8c2bd.nq.gz
    ├── 1b633d1bcf060c9982c9d8b317addf21d24fafc7.nq.gz
    ├── 1b75d670c1f27a776cedfd00050caf0295fb1fa1.nq.gz
    ├── 1bb07e6af4a445ea3bee047389e5823b578a3367.nq.gz
    ├── 1c4efdee27a5eca4c7f90ddbb890fadc6244826c.nq.gz
    ├── 1c5a3ba76f158ab37d3bae2cbf30cd222abda1ba.nq.gz
    ├── 1c6482313377108ac98525f1a1cddd132aa50da4.nq.gz
    ├── 1c7cd9f303d48f3c01d5649891af0e2dce214732.nq.gz
    ├── 1ca5983fd528ab97fadcdc1b4be8c451cd4a9ee2.nq.gz
    ├── 1d172f71a45203afe9f842fa81e80ec81ba9a513.nq.gz
    ├── 1d2b3446e40f0aba6e6820d0232c7301f46be5f5.nq.gz
    ├── 1d75137a0429a96cf5ae43ff10d3722ec5a62f4a.nq.gz
    ├── 1d8010c8ae68feb82a0f32c2b98f521fbc4073ba.nq.gz
    ├── 1d8ac29aabe81cf7242708e5a6febcac35d1b530.nq.gz
    ├── 1dadbaaee436ada45958ebc1ce2dc124df15f637.nq.gz
    ├── 1db1137e0850f4d77017204647efa05d2ecb879d.nq.gz
    ├── 1db674078fe3d050c7912f235ae954cce485d250.nq.gz
    ├── 1dc56b053b063b5527c2bbc295222e05e8645fd8.nq.gz
    ├── 1dd6494d77194a93d6a961bade0aeed547a9d3b0.nq.gz
    ├── 1e0b179290c0901c3d0accb0a12f082c179a2c05.nq.gz
    ├── 1e323dea2b054d11f40fda107a6a1ee253f86f3e.nq.gz
    ├── 1e72790df00e78c99677ad394fa0d3788b6f229a.nq.gz
    ├── 1e893f86a87e5068ed07400d942ffd74a1cfc993.nq.gz
    ├── 1ea5dfd1de0435b188a9c92e762e4a473aca5c3d.nq.gz
    ├── 1ef1f698d331b28589720698d159c68a331c5f26.nq.gz
    ├── 1f2261cfcc23499ebe90cbbecc78ecfbb3fb30f0.nq.gz
    ├── 1f2c7fcf8622953deaf4a4b82ed97035edf6445a.nq.gz
    ├── 1f31544e06527a02997a149dbc056ce80af13493.nq.gz
    ├── 1f4a4da4ba71dcd25aa441d616e310e1d2de57b1.nq.gz
    ├── 1f4bdc85f5f792333144a101c89768c8afc7b291.nq.gz
    ├── 1f8a23f70dc945793ac2bb3cff9dba59ba9c2e73.nq.gz
    ├── 1f98176a8147c8c16440cfe5bf2d9e2338b64ec8.nq.gz
    └── 2006f577a88895cf10515addc721868916788b38.nq.gz

6 directories, 200 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |

## Source repository

[sqlalchemy/sqlalchemy](https://github.com/sqlalchemy/sqlalchemy)

---
*Parsed on 2026-03-21 by [repolex](https://repolex.ai)*
