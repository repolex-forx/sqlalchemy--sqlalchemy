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
│   │   ├── 0b7557a30a94b38c816499dc7e854214120b68cf.nq.gz
│   │   ├── 0be0131a448f43aa4969792aa0158551163ce499.nq.gz
│   │   ├── 0e15f047502bd3c17d008f95737119e0e3188658.nq.gz
│   │   ├── 1ffed8432e282aa57ecde9f3e4ca778a1756ddc0.nq.gz
│   │   ├── 4022b1359d30daa7b7fcb0fbc8e7a4e2ac4b0551.nq.gz
│   │   ├── 40ded34819bb2a65ef02042bf60e075d65123592.nq.gz
│   │   ├── 4d78d5f3ab1bc5b4d41f086fecc5acc36ead45af.nq.gz
│   │   ├── 7626fc5aab8b625bb6e48e7374d4622efc7f1e5a.nq.gz
│   │   ├── 8ce1d43bb568fa3123c4f040d50713d998b80b83.nq.gz
│   │   ├── 94ac052104cd07ae0dace2d1b1ac6a7144412c44.nq.gz
│   │   ├── 967171f5afd1e5c04e786052ea82f2813023db2b.nq.gz
│   │   ├── a454f2e87da26226cad7e7089abed7ca152cc329.nq.gz
│   │   ├── ae3f1bc240ae4449a1700612cb98f0d85bd28317.nq.gz
│   │   ├── ae5e73cbc144239738d394ccbc835965bde2b39a.nq.gz
│   │   ├── b3db76d449966de741201e47b58062d2ac8d1dc8.nq.gz
│   │   ├── b59f4d1a4a81144ac58e9d39bc2c36893741f818.nq.gz
│   │   ├── bdf8f4ca80ed2a49bb4f1beea57ca5e1061681cf.nq.gz
│   │   ├── c081749aa65d148fea40adc940fa7ebbfb892224.nq.gz
│   │   ├── d12392c38d570b4a3c14a02c75e2ea9476c34ffb.nq.gz
│   │   ├── d689e12595bc25d8bcb31c84d3d6d29cb47258ba.nq.gz
│   │   ├── dfc633b08b49f8b7ed083af3b274d28df2fbe316.nq.gz
│   │   ├── e07cf69deff7e2a9152b41385c4505f1acaa958b.nq.gz
│   │   └── f5b5696afddacdd7c5a5ede716e7241e5fa5c97e.nq.gz
│   ├── lsp
│   │   ├── 0b7557a30a94b38c816499dc7e854214120b68cf.nq.gz
│   │   ├── 0be0131a448f43aa4969792aa0158551163ce499.nq.gz
│   │   ├── 0e15f047502bd3c17d008f95737119e0e3188658.nq.gz
│   │   ├── 1ffed8432e282aa57ecde9f3e4ca778a1756ddc0.nq.gz
│   │   ├── 4022b1359d30daa7b7fcb0fbc8e7a4e2ac4b0551.nq.gz
│   │   ├── 40ded34819bb2a65ef02042bf60e075d65123592.nq.gz
│   │   ├── 4d78d5f3ab1bc5b4d41f086fecc5acc36ead45af.nq.gz
│   │   ├── 7626fc5aab8b625bb6e48e7374d4622efc7f1e5a.nq.gz
│   │   ├── 8ce1d43bb568fa3123c4f040d50713d998b80b83.nq.gz
│   │   ├── 94ac052104cd07ae0dace2d1b1ac6a7144412c44.nq.gz
│   │   ├── 967171f5afd1e5c04e786052ea82f2813023db2b.nq.gz
│   │   ├── a454f2e87da26226cad7e7089abed7ca152cc329.nq.gz
│   │   ├── ae3f1bc240ae4449a1700612cb98f0d85bd28317.nq.gz
│   │   ├── ae5e73cbc144239738d394ccbc835965bde2b39a.nq.gz
│   │   ├── b3db76d449966de741201e47b58062d2ac8d1dc8.nq.gz
│   │   ├── b59f4d1a4a81144ac58e9d39bc2c36893741f818.nq.gz
│   │   ├── bdf8f4ca80ed2a49bb4f1beea57ca5e1061681cf.nq.gz
│   │   ├── c081749aa65d148fea40adc940fa7ebbfb892224.nq.gz
│   │   ├── d12392c38d570b4a3c14a02c75e2ea9476c34ffb.nq.gz
│   │   ├── d689e12595bc25d8bcb31c84d3d6d29cb47258ba.nq.gz
│   │   ├── dfc633b08b49f8b7ed083af3b274d28df2fbe316.nq.gz
│   │   ├── e07cf69deff7e2a9152b41385c4505f1acaa958b.nq.gz
│   │   └── f5b5696afddacdd7c5a5ede716e7241e5fa5c97e.nq.gz
│   └── repolex
│       ├── 0b7557a30a94b38c816499dc7e854214120b68cf.nq.gz
│       ├── 0be0131a448f43aa4969792aa0158551163ce499.nq.gz
│       ├── 0e15f047502bd3c17d008f95737119e0e3188658.nq.gz
│       ├── 1ffed8432e282aa57ecde9f3e4ca778a1756ddc0.nq.gz
│       ├── 4022b1359d30daa7b7fcb0fbc8e7a4e2ac4b0551.nq.gz
│       ├── 40ded34819bb2a65ef02042bf60e075d65123592.nq.gz
│       ├── 4d78d5f3ab1bc5b4d41f086fecc5acc36ead45af.nq.gz
│       ├── 7626fc5aab8b625bb6e48e7374d4622efc7f1e5a.nq.gz
│       ├── 8ce1d43bb568fa3123c4f040d50713d998b80b83.nq.gz
│       ├── 94ac052104cd07ae0dace2d1b1ac6a7144412c44.nq.gz
│       ├── 967171f5afd1e5c04e786052ea82f2813023db2b.nq.gz
│       ├── a454f2e87da26226cad7e7089abed7ca152cc329.nq.gz
│       ├── ae3f1bc240ae4449a1700612cb98f0d85bd28317.nq.gz
│       ├── ae5e73cbc144239738d394ccbc835965bde2b39a.nq.gz
│       ├── b3db76d449966de741201e47b58062d2ac8d1dc8.nq.gz
│       ├── b59f4d1a4a81144ac58e9d39bc2c36893741f818.nq.gz
│       ├── bdf8f4ca80ed2a49bb4f1beea57ca5e1061681cf.nq.gz
│       ├── c081749aa65d148fea40adc940fa7ebbfb892224.nq.gz
│       ├── d12392c38d570b4a3c14a02c75e2ea9476c34ffb.nq.gz
│       ├── d689e12595bc25d8bcb31c84d3d6d29cb47258ba.nq.gz
│       ├── dfc633b08b49f8b7ed083af3b274d28df2fbe316.nq.gz
│       ├── e07cf69deff7e2a9152b41385c4505f1acaa958b.nq.gz
│       └── f5b5696afddacdd7c5a5ede716e7241e5fa5c97e.nq.gz
└── blob
    ├── 000479f09d178f2fcfde02594fc10de12fe0c302.nq.gz
    ├── 0019bcd68e1cf1ff69610072c01b7701c4d62e6a.nq.gz
    ├── 002ff2d36c4fa1532da49d2fd26e69b8046b007d.nq.gz
    ├── 004caf84946038e4e31fe0532a366373981c5f47.nq.gz
    ├── 006971f6e38f0b19914af3b84959cf4cb815a3f5.nq.gz
    ├── 006b8905554b55fecefa313658105d30905fa05e.nq.gz
    ├── 007edd5964c98b28a836f97fa4d3313df70213b3.nq.gz
    ├── 009c83c0d49e117ca5c919ec9ebf1f621323bb6b.nq.gz
    ├── 00a17896c8f6637e111aa588c18a574042434c55.nq.gz
    ├── 00a7ca335cff5c71724afe52a964e7230e58349d.nq.gz
    ├── 00b0db9cca3f95ee30f676f6451dc90304625b1d.nq.gz
    ├── 00cffa63d6940ed9c7298926a9cada58b29158db.nq.gz
    ├── 00d2e6f6a105477532a3464791d1696ef7d4f93e.nq.gz
    ├── 010d1a2c02314f68c028e56260289a24c1e5e75a.nq.gz
    ├── 01114c51e99c4253123f855f77bb26cf43a40825.nq.gz
    ├── 01319aff0c8ba896d68ec6804c646c154359bcda.nq.gz
    ├── 0142367ba49e07218a4f821de2cc9c102b9207c8.nq.gz
    ├── 015f65bdf0485d07168b7675a50cf4be7de86add.nq.gz
    ├── 018a46cd7df196bf18f82b3917646e1301cca753.nq.gz
    ├── 01b1b10d32805d27af52e114bf08541bb3d3f6e6.nq.gz
    ├── 01bb954499e4eebf51604784cd75a64aa82b7b5a.nq.gz
    ├── 01c2d18f0b13fb833636eff0ab74a0df6570efe2.nq.gz
    ├── 01cb0056ee9bb771cb3d199bb9dd122b62bc3747.nq.gz
    ├── 01d5646cce14218ffb3e5b22b10713a796d30890.nq.gz
    ├── 01daf65d1a0be6835cc1d43286a0d40a20591aa8.nq.gz
    ├── 01e4efbf13a6458ae5dcfecbcde93675b81e973b.nq.gz
    ├── 0203dbf7d5dfe33316b94250afd6e8b9bd678d0c.nq.gz
    ├── 02248fa592a81c1004a9cdda24c1ee70283d0b83.nq.gz
    ├── 022f547463c5bef08d2a73b924a2a8051d3e938e.nq.gz
    ├── 022fce094349807b406147592d4ba2231eaa6788.nq.gz
    ├── 023ab70b7ec08b5c022808e34a0b976fc85d7b85.nq.gz
    ├── 0256c6fd98a90e772d35b9bfbdeda3327f4d9840.nq.gz
    ├── 025ad4daaf71f2f98705637af18500f2d83e33f0.nq.gz
    ├── 02a361d4b4e602c064e75940ca916a37622d32bf.nq.gz
    ├── 02d34bbb0c0d712f4383460af43f10461e612b6c.nq.gz
    ├── 02deebdca953cb24d7724a4bd29b1cb8cdf4ecbf.nq.gz
    ├── 02e0147076a76d84db83dd103d057bba436d210e.nq.gz
    ├── 03045f6980d75d41f26d07d9ddcdc616a73ef85c.nq.gz
    ├── 03197b00f903a5d80f6be0ecce82b5679ec47b75.nq.gz
    ├── 0327205ce9dd78ffb95d0c2ced39fd593ce3351a.nq.gz
    ├── 03673eb4d42b71bb6835f99faadec529873e74f7.nq.gz
    ├── 03a0d1202d4ccce3b42861d3201562fa0b3d0c88.nq.gz
    ├── 03b0f76ec3e76924888b3b8a7ebcc2726e61b795.nq.gz
    ├── 03cb891a23491c091fbf17f15e205f6bc24d6bad.nq.gz
    ├── 03d827ea7efd163f18495cf9f44ae92f95a23ffd.nq.gz
    ├── 043f6f8ee7e67df83b24dccd3911d05cfebad8e7.nq.gz
    ├── 045d44968793b0d0cfeaf42ead38af6c3de3088d.nq.gz
    ├── 047c743e0d9786d67cd010f105a685c75f3344fa.nq.gz
    ├── 04800ffc00f2ce130820b948e8dac94efff14eed.nq.gz
    ├── 04950674aede35a462071bb44db8fcb78063ffd9.nq.gz
    ├── 049e4a45e50064f352a21f57eab7322132e11103.nq.gz
    ├── 04bdc24fa4e46313ad4bae44b56feaf037107b19.nq.gz
    ├── 04de56f0101f5ef34844bed2074f866c532f7e11.nq.gz
    ├── 04e5b49f7e692d32df4d69a59c6d2412b2af329d.nq.gz
    ├── 04f3ca67d6023819fd3f6cbaf6054420a445b84f.nq.gz
    ├── 04f9b5110c47a20deb4a4dcd6ce8156d5412c86d.nq.gz
    ├── 0507b7c5b6f90a6c07e3156b624017a4b32479a4.nq.gz
    ├── 05291ec0ea1687a98ebe3341df3e549bdf895f74.nq.gz
    ├── 053619f46f0631ffd9616f9db78bca9b2700751a.nq.gz
    ├── 053770e1c89375c4827367be0841035d46b4987e.nq.gz
    ├── 0548a79268e430774f2413db72c6d241caba706a.nq.gz
    ├── 054c55492268025c3145244828d42ad904c5f12b.nq.gz
    ├── 056e7ef70293fb9bd25d71785f870a0d5b482042.nq.gz
    ├── 059d7a100e71e4388f8c09a3c1aecc39fe707aff.nq.gz
    ├── 05ad46d6ccc2609478f72276e92cdce9b08f806b.nq.gz
    ├── 05aff5f36cf92fd89162f9312aa49c83a97861cd.nq.gz
    ├── 05d0f21105a76f7512c1e9d8c7f94ee23d823ba6.nq.gz
    ├── 05d9efd7865bb4404139705f38a4210617c4f7c0.nq.gz
    ├── 05e0d7f0dec19327cf16432ee2415d9b345a9296.nq.gz
    ├── 061ba59b2ec0e30ed08506b05f9c65098e44f21a.nq.gz
    ├── 061dbc6daf7ca4bf70d4d69cfcb3598864ae05f0.nq.gz
    ├── 061f8de96acbd6540a484c043b3da2c1df1c3d69.nq.gz
    ├── 063427134b185b2ea12abf14e9882da65d84810d.nq.gz
    ├── 06363e2c7231d651d3e2b7eafb3e268dba15f0eb.nq.gz
    ├── 0639a7d9501a2f612876dcae0c9a64690da4917a.nq.gz
    ├── 067e842c35b4c2fd4497278aa2135ff362ddf46c.nq.gz
    ├── 068264c720bbac79a0b2c472076b9ff029d53bfe.nq.gz
    ├── 068a4d0a1cb86bebb17cbbd89e9a06cd2697729f.nq.gz
    ├── 069835ff9ec3f460a2549fcb53bab90c626ee27c.nq.gz
    ├── 06d839d54cb2c371a835a1eaf60f710159097c83.nq.gz
    ├── 0703ea9a20de596e7de054492c941fc6c842ceaf.nq.gz
    ├── 070fb4cb5ec12e06d6711d9557928b439262bd41.nq.gz
    ├── 0728bba47f581a8d4242b7533facb5a0ee8004d4.nq.gz
    ├── 074a6a71a8369972246e1f9080ab00194f31df10.nq.gz
    ├── 0763fe70cd905cfbe3d68f132877b943f04a2eee.nq.gz
    ├── 07815a583db4f59db931de508caafd2045d5cbfa.nq.gz
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
    ├── 085d8cf444c91e150cfb34d975d4b33074a39718.nq.gz
    ├── 08663baf4fc08951d2964668812a8daa40e5ebb2.nq.gz
    ├── 087d0adba1303b4e78efd95bfee24ae284752994.nq.gz
    ├── 088705a0e6c648df365f9b19ebfea5991d057d35.nq.gz
    ├── 0888257f20fe473c3c493923ae85d804c29c00da.nq.gz
    ├── 089541848b9d1d1564b1edc339eda93877f726b1.nq.gz
    ├── 08989d8c2aa9be1dc58415dae350c6cf59bffd74.nq.gz
    ├── 08d55dbdb753d80b3d1a44ff0a5eb789846790eb.nq.gz
    ├── 08df106ce267b31e9d2186a974ef5d1062642aea.nq.gz
    ├── 08f08f913c9bbd6475dcc72fc4b237a246b25f87.nq.gz
    ├── 08f21ba6f126ffbf0f026fc1ae7b5999b38d0788.nq.gz
    ├── 08fe45f8ce11072340470794b77ddac4af661ba9.nq.gz
    ├── 0903befe9aae093cda6e86a49c5a4e33364a7cbf.nq.gz
    ├── 090827709da5d372ed680db0ce12e98a91e238ba.nq.gz
    ├── 09094508adfccea88488e83e2754afae68b21d3b.nq.gz
    ├── 090a27412980c3b79c9d398fa04b477a847cc375.nq.gz
    ├── 092d0d50858104af1b27b1a2eaa66844fa0b71c8.nq.gz
    ├── 0937568e2fa7539e058b6d840cae3fbd349a5f05.nq.gz
    ├── 0957638676bcdbbf0322ae29637bf2a5bfca68e0.nq.gz
    ├── 09598069d49619a8d67842d1d6a225b3daf33f34.nq.gz
    ├── 0961b435b111e4732172197489d8c76828526f42.nq.gz
    ├── 09abfae55b15c9a723870466522dc8fc724559a4.nq.gz
    ├── 09cc9f0b68e91322bf0cb3ee172aa37002ee7809.nq.gz
    ├── 09e34691e8c2c45a67a541c55bc0587f4c9b6760.nq.gz
    ├── 09ed89bfbc4a199f44fa39187bcc180514f6d288.nq.gz
    ├── 0a0f23a707871d52c96e5d66381fd7e2725bdf42.nq.gz
    ├── 0a480ec11ba2b58a6d86910195ab6e55cc041bb0.nq.gz
    ├── 0a92b7f5a40bf45448a4e5d8e6b3b984bd9fbd93.nq.gz
    ├── 0a9e992a32be70deea0a654aeaa8b8da3aba20c8.nq.gz
    ├── 0aa75930a866ccc4d2d8605ba7fca88b01fa95ce.nq.gz
    ├── 0aabdb9be2b35ee6c0dedebe65e051ad45378a42.nq.gz
    ├── 0aca6cd0c97e38e6d7b872d7aa0728b724b63847.nq.gz
    ├── 0adc382f1ea7932bd83c98949117a08aec289b18.nq.gz
    ├── 0ae4260dcefd65ceb97ad3b86e3cd709e3a5071f.nq.gz
    └── 0af70975ab4e9d7a407b706d7b1b12a8cecdc2de.nq.gz

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
*Parsed on 2026-04-01 by [repolex](https://repolex.ai)*
