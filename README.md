# Repolex Knowledge Graph of pypa/setuptools

RDF knowledge graph data for [pypa/setuptools](https://github.com/pypa/setuptools), parsed by [repolex](https://repolex.ai).

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
lexq download pypa/setuptools
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5a13876673a41e3cd21d4d6e587f53d0fb4fd8e5
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 5a13876673a41e3cd21d4d6e587f53d0fb4fd8e5.nq.gz
│   └── repolex
│       └── 5a13876673a41e3cd21d4d6e587f53d0fb4fd8e5
│           └── chunk-001.nq.gz
└── blob
    ├── 00a16423f448e7773f5e6dc9b365efe80f40a778.nq.gz
    ├── 00c9743ed0a2664039060ef149d30f165bf2f465.nq.gz
    ├── 00d34bc7d8c85126dbae716ebfa48e35b0833222.nq.gz
    ├── 00fee625a5c195fdb6e2f0fa6518da02daa75d16.nq.gz
    ├── 01328592b2dad80f4d16c55cd9db9829b3c650f1.nq.gz
    ├── 01356d69b97c95a6d41818e5c2c50a299146bef4.nq.gz
    ├── 0148f157ff3bf8bd728c82f49cd3d1cd9cb5a43e.nq.gz
    ├── 01864511b0f52a6bf944f70b5e15b75364791935.nq.gz
    ├── 023857d499b2d3874cfd6dabc7460ed111f134c9.nq.gz
    ├── 0250031d722d3a97e2d501fcca7a716080d6a877.nq.gz
    ├── 0276a3fae10eb367af326543bcd69e62432b2f7b.nq.gz
    ├── 02daa5914a82da08293dc1675e75c11ed3fb2bd8.nq.gz
    ├── 031cb77c17ba8d8a983448268851d612e05e80d1.nq.gz
    ├── 036167dd951e70ad543775529d5ce3f6d6544c71.nq.gz
    ├── 04a4abe5a9e61596f97dc3d1b0b3da93a558158f.nq.gz
    ├── 052a5850f91fb37f7cc9df065bd5f0bc4b65dbdb.nq.gz
    ├── 0600663d00e9dc28b523bd6c8e1855d0a9d61206.nq.gz
    ├── 06e51af299d0fe15f7618f803cfb8ff52d199cf7.nq.gz
    ├── 07811aab27ad7fcd2303883024243e2f52c2bbcb.nq.gz
    ├── 09572f1780ad3554e93d8309547e9bc802a60371.nq.gz
    ├── 097e86de0720126a1390d728f7e50a4f89cac77f.nq.gz
    ├── 09a8a2e126c8bb009dbbe61c5c4bd5e358744996.nq.gz
    ├── 0a523bece3e50519653c4d7a38399baa487fefa1.nq.gz
    ├── 0b3774906487ec45fb77671c66313d2d8047b177.nq.gz
    ├── 0b551d11be0200b4e9c620d1af387ff7c2752096.nq.gz
    ├── 0b797c6ec025f92d00cfe9ad059f033556d05862.nq.gz
    ├── 0c20eff3da75223a5ca76a1743b7c5b8fa1dc1f6.nq.gz
    ├── 0d162647d55777d7afa1bf1e44a6c200a3f82419.nq.gz
    ├── 0d1f7edf5dc6343538563a8caa7de6829752c4f9.nq.gz
    ├── 0e79e8a882be74fe76c80ccf49a9cd68fb636fd4.nq.gz
    ├── 0f8a1692ba96f5e03167e7307c1c2ff5776b74d6.nq.gz
    ├── 0ffa3116d609614d7d15766552cf86f2b55966af.nq.gz
    ├── 1206c462d4fcaa670a816e201bb88b27dfc9cf88.nq.gz
    ├── 121a0febda1b37523da5074f14cc04301efa60bf.nq.gz
    ├── 12228d414b6cfed7c39d3781c85c63256a1d7fb5.nq.gz
    ├── 1231b32d20fc0524ea50f6a70d7e017211c69e9b.nq.gz
    ├── 130e6fb53b0bd9670bdcfe6d4bc7fcf8fd90416e.nq.gz
    ├── 1321ce9308a68f00cf2f839d4ba02869c16ec26f.nq.gz
    ├── 147288f3037d99c3b290aa676075ce6934ddd3f5.nq.gz
    ├── 14c8981e441dee59afa715853c87a84796b931fc.nq.gz
    ├── 157693de6530e7354c2e23e1e672800edd3bc206.nq.gz
    ├── 166fcd584a80442a351b6c620987b2b0721635c3.nq.gz
    ├── 167e234a530053b60d4bf6d51b12598723433a8c.nq.gz
    ├── 16b13022913f62ba86df6b2480d22e3119cdb8cc.nq.gz
    ├── 1714c041f7a23e1ecbfc3245bf964f75c13734ca.nq.gz
    ├── 17279ac421fce8cb8e062048549615e7f36aea9d.nq.gz
    ├── 19ca601458f99c50a6cceec1e70ce70ebd39e9cb.nq.gz
    ├── 1a02010bb2af2be0487730d6a32080877b9ac220.nq.gz
    ├── 1a1d3a05da544b98ff84d03ecbee1185b2eb45f7.nq.gz
    ├── 1b323a5dec4727c685b6b48a74cd0ed40bcba783.nq.gz
    ├── 1b436d76586cbcf38164548f3fc849ce1a3ff600.nq.gz
    ├── 1b493fba3bba254884e5ea52c3d5531a0d65ccf7.nq.gz
    ├── 1b4ffb33187b65b4378925c472071c845bcecc26.nq.gz
    ├── 1bb5a44356f00884a71ceeefd24ded6caaba2418.nq.gz
    ├── 1d93b6193be40883b113265aac44ccd775075a0d.nq.gz
    ├── 1dfff2cd50ff87b8cef9d936f1fc9d4a2478b136.nq.gz
    ├── 1e00ffacb182c2af206e5dd9d9fbc41d236da0d1.nq.gz
    ├── 1eb430c6d614a5daea4139badc09c222a4b0e72a.nq.gz
    ├── 1ed01380978c4cb699ad7585e02b0359b8a728db.nq.gz
    ├── 1f50fa50880e02ea7adf64e94a234af25f8284c7.nq.gz
    ├── 1f72a25542494abd0861372e9f2aa9b098bda893.nq.gz
    ├── 1fc51d244a78058329c56a618b092e466715e565.nq.gz
    ├── 1fdb9dac1fa3f121a634082515d1a305fc09793c.nq.gz
    ├── 208f59476350e742bc4273dac842fbfb0bc0f817.nq.gz
    ├── 20b31d4681377745bc2ddaeaf5f0074b4050e5ba.nq.gz
    ├── 20b8ce6b9bba21bd709b77249bdcae5b4119e9ca.nq.gz
    ├── 20fbbfc1c095baf9f8c72902b24296b50ad3ab9d.nq.gz
    ├── 21695a74b5107c96ba4bb2cbca6b7f259dacd330.nq.gz
    ├── 2223ee9c8cab2495034a57d4585625feb81a8330.nq.gz
    ├── 225d65515368576ffcab762ce14ceabc7e4e3451.nq.gz
    ├── 225e2eee01238571c50595eb104e0b70d5f503c4.nq.gz
    ├── 23596fda930cde864e643152ec706b6149f130f2.nq.gz
    ├── 238ce896505d1d9edcfe42265b30a051247063e1.nq.gz
    ├── 24199c246d44a6874ad991c2f3492ca30fc10f27.nq.gz
    ├── 24216c5c1feb8b6017f71d096124e5db0aac5bd2.nq.gz
    ├── 248db98f97951aeeee0222131417e73074cc72d2.nq.gz
    ├── 24bb8180f960a2cd62f352a41241e107e9521750.nq.gz
    ├── 251600e6d1b6f7d38f6fee0b91de34d31b2124d0.nq.gz
    ├── 253f6b1b7ebd711fdc6bbbab3b56897061bab515.nq.gz
    ├── 2570607399a3ae13cb92db65a9171d955d3248c6.nq.gz
    ├── 27471c7e252f402eda93bd7c98d8195243862010.nq.gz
    ├── 27de01d019b807f47ca00a36787e90fb63807beb.nq.gz
    ├── 27ea717a78e19f50599844b76ee1c68c2e802ed4.nq.gz
    ├── 296d3193ab429f64bc5f3bfdcad7ee6e1050dc6d.nq.gz
    ├── 2a9e50837a4f42b2f4d82b3668fa4d629c0f4609.nq.gz
    ├── 2b78022934d89599e642a10f861b382947031be9.nq.gz
    ├── 2bbf2d58d3cabc0db4ae6ca795b0ecda46f9e677.nq.gz
    ├── 2c43729b09ea5e5bf9d8c0708e63c69b5114a279.nq.gz
    ├── 2c5beebe64eb9d747088cf117082a546330b29f3.nq.gz
    ├── 2c74f06b976f3c3ea977667a5c16c0e7f201a558.nq.gz
    ├── 2cc433a4a55e3b41fa31089918fb62096092f89f.nq.gz
    ├── 2cd0a0a8ede8ecb8d0c5ae55c8c3b09559239ed5.nq.gz
    ├── 2d468845e5d802a1c2891f6ed31d43c0fed26ec2.nq.gz
    ├── 2e92580d20626e6f5ebb112acc70da97bee589f0.nq.gz
    ├── 2f650e174637c665245856651624aa21e5d074b3.nq.gz
    ├── 3038891afec8d4e6608ae4209365cf31f94b7f41.nq.gz
    ├── 304196f81e11a168c9894f966e4a617ebf4ed53c.nq.gz
    ├── 3079be69bf880f47e64dbf62993f0e54754b7315.nq.gz
    ├── 30ab368913061aa4b7935e65f5696f7d8cffcf4f.nq.gz
    ├── 3200e601f970271fdde3fcc74f9af4423655a79d.nq.gz
    ├── 32214fb4400035788bfe5c0de42dad106a4f54f1.nq.gz
    ├── 326cb346145ec7e3a1dd0384c33d4125131feaae.nq.gz
    ├── 32b1d2b98ac987e8361f60362b8bdabcdc6fb1c8.nq.gz
    ├── 335b275fa7575b0a7c525a713fbe0252ad2d956f.nq.gz
    ├── 33d235d976e39db426aaff628b8b9bb5b832dcb6.nq.gz
    ├── 3439f861bcecc3ebd1079ed7fb4487bd8e66c725.nq.gz
    ├── 349041ecb65ce06671286bc142c27eb5102f2fbc.nq.gz
    ├── 3516c9f0396cc14d4ee246160a425447aad03abe.nq.gz
    ├── 3582f691ef578a419555c6ffbba6a619310517a6.nq.gz
    ├── 35b415c2653d138eed04a7cf8d7916da5edf283d.nq.gz
    ├── 35b6b0e050c654bd9eff711ec3b94bea9adff2af.nq.gz
    ├── 3653be096f11b77c71f58679d6e4a108903668a5.nq.gz
    ├── 36a8b092279780d730fd0a3cc20c1c76bd72c8a0.nq.gz
    ├── 36c4290d8ff482240d7d41e0ed8c7157081ff96c.nq.gz
    ├── 38ca7bdff7a651101bfe7db71188e0972fdbb375.nq.gz
    ├── 38cdeafd21f1eab74d3f49f069bac093d7694f84.nq.gz
    ├── 39a24b04888e79df51e2237577b303a2f901be63.nq.gz
    ├── 3a5327436f9b1d9eae371e321c491a270634b3cf.nq.gz
    ├── 3b9fc926f6ffc41673630fbf5775e6f4ad638b18.nq.gz
    ├── 3bdfa0b35aedb4665ac1f127c016392162869832.nq.gz
    ├── 3c7c2d1bd6ac84dfaf82a0906d34cb30f69b9dc3.nq.gz
    ├── 3c7de5fb7fd2fcc1bbb60b5c3977e82c3aa2f898.nq.gz
    ├── 3c931bbd4fd9046702d850a18877622651882d7a.nq.gz
    ├── 3da7141573c9d932d008a9e98fa030213d944e6e.nq.gz
    ├── 3dfc46dd97e0a50b457b7f291cf4f40612acfd56.nq.gz
    ├── 3e63cbe12aefc3b52a5d1ca2fe3e1ca2e172e29d.nq.gz
    ├── 3ea50eebfe3f0113b231a318cc1ad6e238afd60d.nq.gz
    ├── 3eb9c01ecbbdcdf7b79d8840ee91c2fe7a734a1c.nq.gz
    ├── 409d21faa2caeb8a53fed10e4266f7cccc764d23.nq.gz
    ├── 41193d4f717344546f8c70ad18b268a04740129b.nq.gz
    ├── 41ad609edd407ac93f87731d07435a25a3d6435d.nq.gz
    ├── 41d30c33d4d647d0f19172a01ed7795396cb4409.nq.gz
    ├── 42ce7b75c92fb01a3f6ed17eea363f756b7da582.nq.gz
    ├── 42d0164ff1d580325057c7166a238025da7c8e67.nq.gz
    ├── 42f1d7ef309663498fd2b4d691aa71e14be34e63.nq.gz
    ├── 43d77c23fad426be237b9f91a6d98d7c36233d84.nq.gz
    ├── 4559193774fabc6c381f4cec2c725d9b805de1b4.nq.gz
    ├── 45969b1145d546ebab617967b010b742edcd7e55.nq.gz
    ├── 46138d2fd7d9f1215a2d077f7d5e8e129451dc42.nq.gz
    ├── 47bb5af5e4b9c78c8b7e3657594562115750db8a.nq.gz
    ├── 47cce582ac8307a18d24358adbb5d8f6c405f088.nq.gz
    ├── 48609367a058c95a0a7e54a1b6dd815225d3375e.nq.gz
    ├── 495337a9a5815e3d2a0aefa584b8ee81f5136d95.nq.gz
    ├── 497b0645217512ae2ba8ff61341fd2bbfa3648cd.nq.gz
    ├── 4a7fb9c9e7a0c4a0ca2a3ab608ffab6acf10bb3e.nq.gz
    ├── 4abc3dcd04b7380757b5d65c1fd6b838260b30f4.nq.gz
    ├── 4ad186e8ec61b92967ea1c12cdca51d00e82dd15.nq.gz
    ├── 4bb099e01ba3eaeeb0adce1faebd33965267c2a2.nq.gz
    ├── 4bf63cfe2032df883ddee14f1898f9ae68751fbb.nq.gz
    ├── 4cbc3b2c6b7dc4205b6fcd4b21119f56d13761b1.nq.gz
    ├── 4e8116a79ca80d60657542a23b4bbcbc3c518eaf.nq.gz
    ├── 4e84f218323e6ad67adfbce07cea5a16e91a311c.nq.gz
    ├── 4e908ea1741945802f1ddb01ecc9197f48f824bb.nq.gz
    ├── 4f612bd51c4ac1d272318ed6fb96e4aeb57e3e27.nq.gz
    ├── 4f990eb1c3cc67c61ea17f791430651e91040f18.nq.gz
    ├── 508b02e4fce3fa9463b7466138cca7414db0e9b9.nq.gz
    ├── 50e6c2f54f38db5bf5175a7a4db219815785f1bc.nq.gz
    ├── 52b58af32a28817deeaf592cc795f311434e39e7.nq.gz
    ├── 530cc108d4743ed26fdf0dd7a8eef204d309b5de.nq.gz
    ├── 532da899f7dc02f9fea9a44c429086b98fe043d8.nq.gz
    ├── 54866cb261614eb1e077b478bf584a8f789bbee7.nq.gz
    ├── 54cbb8d2e7bf41de4e187613718879f2a4c3d8d3.nq.gz
    ├── 54f99acbfac68c2be8283174ea64f1730a795e49.nq.gz
    ├── 55699b1ea68247f72a382dc11cd2b5c4b07d24fd.nq.gz
    ├── 571c1ed5f770edb9b323143e1f8ce61bf1dfa3f0.nq.gz
    ├── 575fbfb35105eb82faee5a368781ecf818379354.nq.gz
    ├── 57e3d840d59a650ac5bccbad5baeec47d155f0ad.nq.gz
    ├── 5890933bcb85e7a1f5bca660d3aa311b71884e5d.nq.gz
    ├── 58a31283171bc72c34139e0f1004a668a9dc0075.nq.gz
    ├── 58a4d9f36606d3be8c288418568b0f2e1ef8bcf2.nq.gz
    ├── 58a823dd3904cf105ed432e458a45d94948fbb4c.nq.gz
    ├── 58bc6a55e24fd2b0b170e4499c6095e934313827.nq.gz
    ├── 5972a96d8ded85cc14147ffc1400ec67c3b5a578.nq.gz
    ├── 5a8ab061009f1cd87a53ce51eff3bc9e9a632273.nq.gz
    ├── 5a97ee7cd8b98f3a5487c0a0b0a80ffde5ff4dfd.nq.gz
    ├── 5b435fe111346d026ba20bbbf68994282e8b64c7.nq.gz
    ├── 5c1d8bbc02a6624cf8e957c40e6f761c1575d180.nq.gz
    ├── 5c69047b2eb8235994febeeae1da4a82365a240a.nq.gz
    ├── 5cb383227e52f71e3cda4053436b8a4ff167fc94.nq.gz
    ├── 5d03c91102fa62d252adcbd858053e2e3d7ca7ef.nq.gz
    ├── 5d26b0d1ae2d21b77e24b692d5a7e1fd01296edc.nq.gz
    ├── 5d487bda2df44ae79053f927f2bb703d0216f123.nq.gz
    ├── 5d7d3869ec5cf53dabab4c79fcddbe0618ad38cf.nq.gz
    ├── 5e39618dca4ad6c3f0d4c8cb20af59ab85fb0eba.nq.gz
    ├── 5e8e768223ea40d7a629111db181a946cf8ca5b0.nq.gz
    ├── 5ec6df3dfeb1a3bb6961348d760838eb453be86f.nq.gz
    ├── 5ef27c897a4df35a2a6923b608a5e04a0a38b9ee.nq.gz
    ├── 606654f86c556d51832ac8c2b5a7bcbf94c2507c.nq.gz
    ├── 6146abde60cf74089882b8d60bcdcbf60f8cedc0.nq.gz
    ├── 61b4575aa0318029c103f40af179cab20ed179b2.nq.gz
    ├── 61ef7d6dd02d0a26d3373299cd2efa792fb23165.nq.gz
    ├── 628c2e4f6585cd3ac91ec52f1c679a4a55ce7a83.nq.gz
    ├── 6420117987041c052142deea6b16884cdb435c2f.nq.gz
    ├── 64d8840378beac0076112c70820782da31fbf9b4.nq.gz
    ├── 6562ac7778349cd1f0bfc286ea91b9eb1a822b82.nq.gz
    ├── 65c3cd99cc7433f271a5b9387abdd1ddb949d1a6.nq.gz
    └── 660459a1102eed0da597ebd7c1a38cb4eee99791.nq.gz

8 directories, 200 files
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

[pypa/setuptools](https://github.com/pypa/setuptools)

---
*Parsed on 2026-04-22 by [repolex](https://repolex.ai)*
