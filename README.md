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
│   │   ├── 4022b1359d30daa7b7fcb0fbc8e7a4e2ac4b0551.nq.gz
│   │   ├── 4d78d5f3ab1bc5b4d41f086fecc5acc36ead45af.nq.gz
│   │   ├── 94ac052104cd07ae0dace2d1b1ac6a7144412c44.nq.gz
│   │   ├── 967171f5afd1e5c04e786052ea82f2813023db2b.nq.gz
│   │   ├── a454f2e87da26226cad7e7089abed7ca152cc329.nq.gz
│   │   ├── b3db76d449966de741201e47b58062d2ac8d1dc8.nq.gz
│   │   └── c081749aa65d148fea40adc940fa7ebbfb892224.nq.gz
│   ├── lsp
│   │   ├── 0e15f047502bd3c17d008f95737119e0e3188658.nq.gz
│   │   ├── 4022b1359d30daa7b7fcb0fbc8e7a4e2ac4b0551.nq.gz
│   │   ├── 4d78d5f3ab1bc5b4d41f086fecc5acc36ead45af.nq.gz
│   │   ├── 94ac052104cd07ae0dace2d1b1ac6a7144412c44.nq.gz
│   │   ├── 967171f5afd1e5c04e786052ea82f2813023db2b.nq.gz
│   │   ├── a454f2e87da26226cad7e7089abed7ca152cc329.nq.gz
│   │   ├── b3db76d449966de741201e47b58062d2ac8d1dc8.nq.gz
│   │   └── c081749aa65d148fea40adc940fa7ebbfb892224.nq.gz
│   └── repolex
│       ├── 0e15f047502bd3c17d008f95737119e0e3188658.nq.gz
│       ├── 4022b1359d30daa7b7fcb0fbc8e7a4e2ac4b0551.nq.gz
│       ├── 4d78d5f3ab1bc5b4d41f086fecc5acc36ead45af.nq.gz
│       ├── 94ac052104cd07ae0dace2d1b1ac6a7144412c44.nq.gz
│       ├── 967171f5afd1e5c04e786052ea82f2813023db2b.nq.gz
│       ├── a454f2e87da26226cad7e7089abed7ca152cc329.nq.gz
│       ├── b3db76d449966de741201e47b58062d2ac8d1dc8.nq.gz
│       └── c081749aa65d148fea40adc940fa7ebbfb892224.nq.gz
└── blob
    ├── 000479f09d178f2fcfde02594fc10de12fe0c302.nq.gz
    ├── 0019bcd68e1cf1ff69610072c01b7701c4d62e6a.nq.gz
    ├── 006971f6e38f0b19914af3b84959cf4cb815a3f5.nq.gz
    ├── 006b8905554b55fecefa313658105d30905fa05e.nq.gz
    ├── 009c83c0d49e117ca5c919ec9ebf1f621323bb6b.nq.gz
    ├── 00a17896c8f6637e111aa588c18a574042434c55.nq.gz
    ├── 00a7ca335cff5c71724afe52a964e7230e58349d.nq.gz
    ├── 00d2e6f6a105477532a3464791d1696ef7d4f93e.nq.gz
    ├── 010d1a2c02314f68c028e56260289a24c1e5e75a.nq.gz
    ├── 01114c51e99c4253123f855f77bb26cf43a40825.nq.gz
    ├── 01319aff0c8ba896d68ec6804c646c154359bcda.nq.gz
    ├── 018a46cd7df196bf18f82b3917646e1301cca753.nq.gz
    ├── 01cb0056ee9bb771cb3d199bb9dd122b62bc3747.nq.gz
    ├── 01daf65d1a0be6835cc1d43286a0d40a20591aa8.nq.gz
    ├── 02248fa592a81c1004a9cdda24c1ee70283d0b83.nq.gz
    ├── 0256c6fd98a90e772d35b9bfbdeda3327f4d9840.nq.gz
    ├── 025ad4daaf71f2f98705637af18500f2d83e33f0.nq.gz
    ├── 02d34bbb0c0d712f4383460af43f10461e612b6c.nq.gz
    ├── 02e0147076a76d84db83dd103d057bba436d210e.nq.gz
    ├── 03045f6980d75d41f26d07d9ddcdc616a73ef85c.nq.gz
    ├── 03197b00f903a5d80f6be0ecce82b5679ec47b75.nq.gz
    ├── 03a0d1202d4ccce3b42861d3201562fa0b3d0c88.nq.gz
    ├── 03b0f76ec3e76924888b3b8a7ebcc2726e61b795.nq.gz
    ├── 03d827ea7efd163f18495cf9f44ae92f95a23ffd.nq.gz
    ├── 043f6f8ee7e67df83b24dccd3911d05cfebad8e7.nq.gz
    ├── 047c743e0d9786d67cd010f105a685c75f3344fa.nq.gz
    ├── 04800ffc00f2ce130820b948e8dac94efff14eed.nq.gz
    ├── 049e4a45e50064f352a21f57eab7322132e11103.nq.gz
    ├── 04bdc24fa4e46313ad4bae44b56feaf037107b19.nq.gz
    ├── 04f3ca67d6023819fd3f6cbaf6054420a445b84f.nq.gz
    ├── 04f9b5110c47a20deb4a4dcd6ce8156d5412c86d.nq.gz
    ├── 05291ec0ea1687a98ebe3341df3e549bdf895f74.nq.gz
    ├── 053619f46f0631ffd9616f9db78bca9b2700751a.nq.gz
    ├── 053770e1c89375c4827367be0841035d46b4987e.nq.gz
    ├── 0548a79268e430774f2413db72c6d241caba706a.nq.gz
    ├── 054c55492268025c3145244828d42ad904c5f12b.nq.gz
    ├── 056e7ef70293fb9bd25d71785f870a0d5b482042.nq.gz
    ├── 05ad46d6ccc2609478f72276e92cdce9b08f806b.nq.gz
    ├── 05aff5f36cf92fd89162f9312aa49c83a97861cd.nq.gz
    ├── 061ba59b2ec0e30ed08506b05f9c65098e44f21a.nq.gz
    ├── 061dbc6daf7ca4bf70d4d69cfcb3598864ae05f0.nq.gz
    ├── 061f8de96acbd6540a484c043b3da2c1df1c3d69.nq.gz
    ├── 06363e2c7231d651d3e2b7eafb3e268dba15f0eb.nq.gz
    ├── 067e842c35b4c2fd4497278aa2135ff362ddf46c.nq.gz
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
    ├── 08236f7991d1771687c9d274582e7161f3fc3f6f.nq.gz
    ├── 0829607cd9c4edd37425ff989147ee1cb78ef7b1.nq.gz
    ├── 082b7c80fa57ca9f63bfb80da333f76304bb6d3c.nq.gz
    ├── 0855cf138792781391ddf917c771e7d9bf6a1ed4.nq.gz
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
    ├── 0957638676bcdbbf0322ae29637bf2a5bfca68e0.nq.gz
    ├── 09598069d49619a8d67842d1d6a225b3daf33f34.nq.gz
    ├── 09e34691e8c2c45a67a541c55bc0587f4c9b6760.nq.gz
    ├── 09ed89bfbc4a199f44fa39187bcc180514f6d288.nq.gz
    ├── 0a0f23a707871d52c96e5d66381fd7e2725bdf42.nq.gz
    ├── 0a480ec11ba2b58a6d86910195ab6e55cc041bb0.nq.gz
    ├── 0a92b7f5a40bf45448a4e5d8e6b3b984bd9fbd93.nq.gz
    ├── 0aca6cd0c97e38e6d7b872d7aa0728b724b63847.nq.gz
    ├── 0adc382f1ea7932bd83c98949117a08aec289b18.nq.gz
    ├── 0afac7df390c6bcb58a53b210a0f6aeec76ae950.nq.gz
    ├── 0b279754f7677afc0de19396b5b574b65e7e26f3.nq.gz
    ├── 0b69f32ea5c01ba3d9f2abcce0912f4d2dcae927.nq.gz
    ├── 0b7a218ca8e14cd90bee324ecd53b68e25b4e63f.nq.gz
    ├── 0b933db4785ad8e75c80c4457e07912c76cefb11.nq.gz
    ├── 0bb2e51a49ea50c1712dabbd8facc225b12f27ef.nq.gz
    ├── 0bec280830e4004944828bc07964fb4d6a0b61df.nq.gz
    ├── 0c04e34b2ed23c147270fe14823ed83286b4e49c.nq.gz
    ├── 0c0a3ce9cd9f15c46b5de63b4af23e59dea71c22.nq.gz
    ├── 0c2aa1b56d0103608e113f35e18e7654624c7b01.nq.gz
    ├── 0c4647d8186c2d54a2d661e97e9dcd594442a352.nq.gz
    ├── 0c516413366900e1712602270019b79ed0a30c00.nq.gz
    ├── 0c7fc6f8d373fe64abfdf28020ec6d80005a6024.nq.gz
    ├── 0c8aa2fe018ba92e5054ff08d51927a045b42f1c.nq.gz
    ├── 0ca331f189f8c702361bee6b160430c6c81686ba.nq.gz
    ├── 0cb4bb195aab8147d52d8e9735d53618a2492b05.nq.gz
    ├── 0cbaf33ea7ad3e657b9515399301c39989a2f22a.nq.gz
    ├── 0cf775e4d27aa9c00220aeb89dfc13e8b129a734.nq.gz
    ├── 0d91d12a4810088e982111f1a81071922cd53869.nq.gz
    ├── 0dda58affa6ad7452e69536d957e56c605b07e3e.nq.gz
    ├── 0df297743755a7db40d8a0d34ff76fdaf68ca13f.nq.gz
    ├── 0dfeb3184573958c9c24dfec43346188f7cf460f.nq.gz
    ├── 0e208854e3f91d9ee530d4e8387c3ecafb4da747.nq.gz
    ├── 0e328238563a48d2e11415fae168608a7e787f36.nq.gz
    ├── 0e86565bd9491074ffc87a08d0aa5f2abb266d1d.nq.gz
    ├── 0ec494bae47b499fe6afadce9ffc3528d36dbceb.nq.gz
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
    ├── 10accde90f9e288993c7565b710e5cae9e157331.nq.gz
    ├── 10cf9f6b225d1fe71b84067f3af25de60cb14acb.nq.gz
    ├── 10d73cb8d6404a8644b57c3894dcf4dfa355c070.nq.gz
    ├── 10f7b4e808d542aa2cd7ea0e6e2ee70ccd23771a.nq.gz
    ├── 11455a5905f82ab3782c1cd753c39c71e8d1dff8.nq.gz
    ├── 116fb74eec8bc43b88d1747e1aa89281c167b995.nq.gz
    ├── 117e365713c21bb4d7fa449c1955ee6947096e85.nq.gz
    ├── 1186e8eacf6ca36bb20e59baafee99e162bce610.nq.gz
    ├── 119dbd85bc456e6ee5447feda976e1cc10ce4612.nq.gz
    ├── 120f6a147413f9d4451afa6a098bb81a6374c559.nq.gz
    ├── 121d8de40a5549c0064b947f59c8bdcc160d487f.nq.gz
    ├── 123014908bebbfb7ecfa1d15daaceb272fabe05b.nq.gz
    ├── 126f5045642c54e4429e0ddeb3aa79b194d8ccf5.nq.gz
    ├── 126f95289e86d5f76823d25bb6049cc70e2aa1ba.nq.gz
    ├── 12f62dbdb5f9b61d2d45e2c1eac2e9ef8a82e561.nq.gz
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
    ├── 147d26d2cf88e861ef6c3b0cb5cddaafe8589a1c.nq.gz
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
    ├── 1603c98734b802456da73c47257f96809a2fd584.nq.gz
    ├── 161dce08757bb4d9d790aeb3f73e46e87605076c.nq.gz
    ├── 166c2af8688cf86caaf6a768ccd3f2d78ee89a4d.nq.gz
    ├── 16a4f3540f2f70f2a18a4cc8af491123944312bc.nq.gz
    ├── 16bb06676d699ed17207f1498b2244025798f0c4.nq.gz
    ├── 16cdafebcca42d859298ff60efbddbb23648cf8b.nq.gz
    ├── 16fef5128d8ebb96fe49bba4c9a98adde5063f16.nq.gz
    ├── 170324fa30c422a65d4f0e7c4f064b5cf1e100c7.nq.gz
    ├── 170cfdad03e8eb7ac71eeeb3328543979dc02cd7.nq.gz
    ├── 170e526d96d7af107209f4f69a69fa51410422c9.nq.gz
    ├── 1719de51671915374eca24658be895a3efa931b0.nq.gz
    ├── 1724dd6985c613d87daf4a8d87c1fea9a283b0d8.nq.gz
    ├── 172caaa517db9a8b130a0c2cf6611023cf0748f2.nq.gz
    ├── 175d962343184c6a3f001b5bcc6dc4ae8574d13d.nq.gz
    ├── 179beeae8e9a8675da48493cccef90653a115f08.nq.gz
    ├── 17a6f59b2070b2399f90e0f4619dba76adeaa851.nq.gz
    ├── 17b3cff5f7316b48a6576b7dfded90916b602de6.nq.gz
    ├── 17c2e7dc679e4632c92ca53ffcbf258241fe82c5.nq.gz
    ├── 17e42906b5a91ba8b88d00b8fb69a0b3365639fb.nq.gz
    ├── 17f4335b03ee8cec04e76a8c0ea727a35da96d56.nq.gz
    ├── 17f7eccdaba85d04c0592a44e559bc1be3e5d818.nq.gz
    └── 17fb075ac40394f590816f23f931ba7c41639d8d.nq.gz

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
*Parsed on 2026-03-23 by [repolex](https://repolex.ai)*
