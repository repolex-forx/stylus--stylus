# Repolex Knowledge Graph of stylus/stylus

RDF knowledge graph data for [stylus/stylus](https://github.com/stylus/stylus), parsed by [repolex](https://repolex.ai).

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
lexq download stylus/stylus
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c5b0b90476d102ef730118099707b9fa026a4313
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── c5b0b90476d102ef730118099707b9fa026a4313.nq.gz
│   └── repolex
│       └── c5b0b90476d102ef730118099707b9fa026a4313
│           └── chunk-001.nq.gz
└── blob
    ├── 001524d41042e37f25248a5f78682e810a2303fe.nq.gz
    ├── 0064888583e0959adb081316bdb69c9c66e035fe.nq.gz
    ├── 006806280b515012d1dc0babc27cfc1636b63e1b.nq.gz
    ├── 00a41b89d880cd1483cbe30183eeba657df5d4a2.nq.gz
    ├── 0101baf0f1d623b9bcde079c3e071c23e37d035a.nq.gz
    ├── 0133512a02f634c07629e67dce76e4b2842197fc.nq.gz
    ├── 014dbead71aa21a07ce4a99f77650e9a99771fdd.nq.gz
    ├── 01551e86f54b00ef76963c32a5790a715821c234.nq.gz
    ├── 01b098a7ec60cd79a0e837c9d72e29f361e3f871.nq.gz
    ├── 01f108529dd2de458f27c79dd615f08ca8bc6c62.nq.gz
    ├── 020fc656334b499c43fe7d42f935920ea2224a6c.nq.gz
    ├── 0311687e79e75bc95b59083fcb2a9c7e598695bc.nq.gz
    ├── 031837181aefe207c03658e1a6bebee753e6548a.nq.gz
    ├── 031bb0c872899d7bda2f553589d3f0e9f63a14d7.nq.gz
    ├── 033b16e553c425058ab951c06dab66b322582b81.nq.gz
    ├── 038781dac2a5f38b7446b24d262cac44bf6f3194.nq.gz
    ├── 03e4cf701ca07234bc6f6bb5e66315cdb309e770.nq.gz
    ├── 045e3a14e75da3d3570dc309698a515a9ded6b37.nq.gz
    ├── 048644aaadee7d24c9f0726ea32cef060d40f6ab.nq.gz
    ├── 04a0da76a1e2dd386698753d9f0c931672f1f2d9.nq.gz
    ├── 04b3b913caec0fee6c569e5528e99fdaec5f90b7.nq.gz
    ├── 0508eb2d07788a7051384bcc09a27fbd08f30c63.nq.gz
    ├── 052dcd943a61e9bf4c1c38b8aaab480f270e9d4e.nq.gz
    ├── 058a2360d7b30fe32e0e15447614a03be5596dc1.nq.gz
    ├── 05e94ed84f65e65bf2647ec1c4283edf2c62dd97.nq.gz
    ├── 05ee8a9289fa2dde7bee1e422a402e3a5794d9bf.nq.gz
    ├── 0609fbce5143704d52d8a157676e9e036a4d7026.nq.gz
    ├── 06110d88ea93b92dd89038a5afa8caa0eff0c6aa.nq.gz
    ├── 0611a2e8575f94debd5ba6558986f33e3ef64cb2.nq.gz
    ├── 06429ad5dd715f384b9a9a111762187b548bc791.nq.gz
    ├── 064abb5a4fc4643f992f41a8eb3b7d18189de43d.nq.gz
    ├── 06aeec67460778dfc031ad65ee3837310a9e7751.nq.gz
    ├── 06d238bdfbb00dc653aa478ad88173c18c9e03b6.nq.gz
    ├── 06edf6ccb49510ef85e33f648cb45cc3645a47b6.nq.gz
    ├── 06ef29ad85427b5a227591bc285927d790ad758c.nq.gz
    ├── 06f749d7ab4ccfd2f97a71387338132e10709b9b.nq.gz
    ├── 0705cf39670d80ad9e818a1e023fef4bab449209.nq.gz
    ├── 07071237ca861aa950095c9ea42f787c4438178c.nq.gz
    ├── 07119162542d79b40a13b5cf828334e3fed66220.nq.gz
    ├── 07275b52bb191a6e88afc60876899017f70543bf.nq.gz
    ├── 07b28c1151dad6cfeb8edba3279909c49b7cde7d.nq.gz
    ├── 07be1465bbaeb2d5f7368199ae8211f5dbb12a20.nq.gz
    ├── 0818fca1e56e13ea8519de68728c1e77f5440be9.nq.gz
    ├── 082cc9097241c375b4d1a1d605e6c9fe343c2196.nq.gz
    ├── 08b9e7c3f6d5b7b0c931de6bba4f9abb16ca518d.nq.gz
    ├── 08cf8f41f2c7bdcf89679c51262dc0faa3928c71.nq.gz
    ├── 08da49c7cd79596b4aa419d6528d27992ff840a9.nq.gz
    ├── 08f01419254330f0155f00638365c7030316138a.nq.gz
    ├── 090a58d966bdc45abdf884b69c68da9bec65c01d.nq.gz
    ├── 09e2032d3db6f6d0a5fd2794d54a748286c021eb.nq.gz
    ├── 09fb5690147d76825fc8918ac8ea1d1e194a9b40.nq.gz
    ├── 0a74941696344833d72c32f9f79c6a63f3b4195d.nq.gz
    ├── 0aadf0e79dc275f52b1ef60df37447c6ae5430e9.nq.gz
    ├── 0b280ac8f1f2157eb6f34218780a3f5f718f8f67.nq.gz
    ├── 0b49b8c5119a7c5e08c7a4c1ce78a5354e5b1def.nq.gz
    ├── 0b779c1cfd3a83f754a5221d802af8bb0e8a92b8.nq.gz
    ├── 0baaa56ff42409cee23780ff8eb80242d37fa026.nq.gz
    ├── 0bd552afe99f93a06930fb533e3c1db114e467dd.nq.gz
    ├── 0be86a4013671f37de18ead31c1515df89505cfb.nq.gz
    ├── 0becd82b3ace18988b004e55097a2918e7df30a5.nq.gz
    ├── 0c443f970537a8e3e80a31f16c6f955032e96b64.nq.gz
    ├── 0c72996bf6d4c18be0865f1987c2d442bf5c3e02.nq.gz
    ├── 0cb4fe21f499cbb7b4c183050dc941e9f3b5b8ad.nq.gz
    ├── 0cfed46878c77967873603cb504e290af692fbd6.nq.gz
    ├── 0d4f1293ee9e134b013749121ddd9e01abaaced8.nq.gz
    ├── 0d6ec842bc447140b3f126d17f71c18caedafdd4.nq.gz
    ├── 0d92df1cad073646670fba4797fad0d1b8c29ead.nq.gz
    ├── 0da01d09caff17fafa4bb53260f73c9c0a63c2ca.nq.gz
    ├── 0de07a99710210dadc5c885ae4ab119fe9ffa6c6.nq.gz
    ├── 0de8f0aa10c430cf66e58c7b17841782d19e0bca.nq.gz
    ├── 0e3319c1eb203309a52cef5693fe323509ef45a4.nq.gz
    ├── 0e786ede797429cfb96f571921316dfe957de91c.nq.gz
    ├── 0e81e0274ac61fa124a8462ba343af9cbba001a1.nq.gz
    ├── 0f2f1f89562901727449f04a27b6867ddd5447a7.nq.gz
    ├── 0f5373b7cb2a07d44d60a46c9bceddb35cbc1437.nq.gz
    ├── 0f6c1b2d1d3283252e64d48c289df2a5b81686cb.nq.gz
    ├── 0f8bddb2299cb3413744a0e096a9dfc5a6ccfa5d.nq.gz
    ├── 0fad5d6e1091f2475bff603be2e6059c23da3647.nq.gz
    ├── 0fb1cf672273968cd6bd5d2876d934cd2676025b.nq.gz
    ├── 0fcb80f5b1e293ea7807c8ad87b27d8e084726a1.nq.gz
    ├── 0fd295852527f3459e54b364953b822c88f75a5d.nq.gz
    ├── 0fda4499699b125eceb357e8e7423c96effb1728.nq.gz
    ├── 0fffe12d214a03fe1612f4f34bbb3c3db4dbb7ab.nq.gz
    ├── 104ae05d928d6aa4cc34b4cba2233edaf83f3a0f.nq.gz
    ├── 10536fdd4c4a0774e956d5ce1d9bf9a70fa4cada.nq.gz
    ├── 1076f3540f238711f18937300f229e37027a9867.nq.gz
    ├── 108958a0b29c82df2e17e4c68d74eae500d948d3.nq.gz
    ├── 10b40471e2c63c8378e41ac3a173ab5084c75897.nq.gz
    ├── 10e7897353f0cb6b3aabdc893764517898927ea2.nq.gz
    ├── 10f3ea30a2d105391ed113ae17dc4be7ff946010.nq.gz
    ├── 11597bd1d99f9f0aea5ccaba98f9aec27d2084cf.nq.gz
    ├── 1181adf52d6e1cc83a1637db29a061503bf71615.nq.gz
    ├── 1184fd78063bb8d44088fc56ac64569267325f0a.nq.gz
    ├── 11e1378bcf7ee13d74b48cd1e254bc80b222901f.nq.gz
    ├── 11e4e74c97115d2c4d8908bc4d915270876ef73a.nq.gz
    ├── 1205c6d27d177260e6f4049220600fb163b74762.nq.gz
    ├── 1242161c68ac246efad33915696c1be9cc6b96fd.nq.gz
    ├── 12791e981e121e362bc0dfec05c070b960f8a74a.nq.gz
    ├── 1296f4218347d7fddbc700347ea91f3a63eae76b.nq.gz
    ├── 12e4810587984a1a4b8cb88df6f7b8540eae2ab8.nq.gz
    ├── 13162428ab608bfaae4790e9353a50ba8e16ff02.nq.gz
    ├── 1404c78d652a4d4da5b3eeba830f7c54c66732b7.nq.gz
    ├── 142691a66a28288644bced4b8a033f8d2e0d3a1b.nq.gz
    ├── 15153c6a55e98ab1c3f1a8eb08f9c247fa568f03.nq.gz
    ├── 152a1743e21d57f5272a71d4a07868554fb016d9.nq.gz
    ├── 15c26961aa9a30d59eeb42425e1cb649bd33edd2.nq.gz
    ├── 15d369af7cc79948314c16e923b1561bfe10d49e.nq.gz
    ├── 15f8e04ec94e2b5509840ab31de9b6c42c43fe27.nq.gz
    ├── 15fbd3b659742c72f0e0fa7c4903d45b8878f86b.nq.gz
    ├── 16126c1af609f7bcc819ad4ecf3aff43f4a2a130.nq.gz
    ├── 162cfe7f890229e92b76eabb54fa382a778a8357.nq.gz
    ├── 16622ab59a78c3eea190a35e1e895a8959c580a9.nq.gz
    ├── 1691e8549e63336d4856779fd418c6b883904f3d.nq.gz
    ├── 169ac268c38652d337dd3082b7a35c7a72a31263.nq.gz
    ├── 16a415c48f31a1ad72180545e0a7feef62397d72.nq.gz
    ├── 1751daca25e38d1a478c69419952622f64bcf31f.nq.gz
    ├── 1835fc0629706fae0f83a7aa6876ddd0ae24b911.nq.gz
    ├── 187336e2b27263e14cd4dc866ebce215ed06e6f5.nq.gz
    ├── 18a5e2babc051708d3e4c33e2ac7eae8bf3ef122.nq.gz
    ├── 18d1561df316e61c7cae8d4067ff06c3597b0f39.nq.gz
    ├── 18df11c8bd26197497baccd7dcbd8ba594144972.nq.gz
    ├── 18f3c2fe592b79fdb526194c5519735fb9951969.nq.gz
    ├── 19dba9d256b92e6c936dca2827146a6118758d7e.nq.gz
    ├── 1a3643f88facc394f45e10bc5dc29618051044d7.nq.gz
    ├── 1a732dbf3d1f595af43d87f5f90f6b20787f49d0.nq.gz
    ├── 1a77d71a19486cb34d84cf208b24d96970d9c397.nq.gz
    ├── 1af8585f1a22f56ec527d980a3f7ddaefe7924fd.nq.gz
    ├── 1afb563a9fa482b2903da2098b37679771a7d954.nq.gz
    ├── 1be4903852b215f6c4ddb2defc9ad7a686fb2f0d.nq.gz
    ├── 1bf23eb25675293a1ab161c728aa3f1c8e80262a.nq.gz
    ├── 1c0e9f8ef4c0b0d7703c0b5d5c1424b9eaf84343.nq.gz
    ├── 1c3a07878ade5d3d88243f8e0f2a9481566ce7bf.nq.gz
    ├── 1c74c0fdfd31e98de9df1dcbf8a9351eee2a2ff5.nq.gz
    ├── 1c8b58f3a2c6b183a1779d44c1ed43df24cc739f.nq.gz
    ├── 1cca1333c0a0f0f969c553ba0043d2b8be358963.nq.gz
    ├── 1cee7597bc84bdda62bdb3e5b2f61d5c60883835.nq.gz
    ├── 1d384d36a41bf0b981b6335ecc8676f3ac881723.nq.gz
    ├── 1d6b19f68b11ddac046b21271218f7c903e4012f.nq.gz
    ├── 1d81a682998d0f03485a810db2f3d63847620e53.nq.gz
    ├── 1da816b750885adb4220f9ea7c7d909347e289ae.nq.gz
    ├── 1dc921ad5c30ab636b9c7520be10274952d7a98d.nq.gz
    ├── 1def81b11cabacb39c3ca769f5489272c59ffb0e.nq.gz
    ├── 1e1348d4810504c6745a3d751351c20cfd783a08.nq.gz
    ├── 1e7644103411132b4b3f50dafe1fee12fa4600af.nq.gz
    ├── 1e81666c43d592ebc876af34639fb3d1ff2d49c1.nq.gz
    ├── 1ebd9889467d23da55dffc6c2d0ee45d905fc65b.nq.gz
    ├── 1ec15a2cc827ea5c5fde59dcfb9c81e836073fc0.nq.gz
    ├── 1f1e40eb4a4af724392cd7882b78a0908a47f69e.nq.gz
    ├── 1f31182d52b6d04a1fa3b2274590ba02a134fcfc.nq.gz
    ├── 1f8e76f025093deffec82f4203086aaab8ce2e59.nq.gz
    ├── 1f8f488fc1baadaa40aa4387e49fb72241cbf097.nq.gz
    ├── 1fbff554d923c9da2e367940717d0adc0213227f.nq.gz
    ├── 1ff59e5b50986efa1ef2ce55ffe6246111edf076.nq.gz
    ├── 20caef4dc8eb121c0c8a20c2dcc1303519c25991.nq.gz
    ├── 2127b2d8f80707367ae71e951f2603d86d416cf5.nq.gz
    ├── 22121d4571190f4f78384f4f29eaa0cb8f563c75.nq.gz
    ├── 224d071a38886a93e4ad96bdd848c64cb6040e6f.nq.gz
    ├── 22b548a2264eebb0bc880037ed2b13cbdee83095.nq.gz
    ├── 23e761332972ae98ffe6ab660685d218f9d0fa33.nq.gz
    ├── 2403566ea76bda7c0c34f766a36e40d5e57a91cd.nq.gz
    ├── 24514c31bacf5f3a260b83296b58d099412d09d3.nq.gz
    ├── 24f488689b0ff17f04b0b9f342aebd6d0dfb2fb4.nq.gz
    ├── 256f1a531836b79235ee23bb83748aef56056faa.nq.gz
    ├── 259921c70644aaca48fec36896d39eab1d137076.nq.gz
    ├── 25b2f2bb5713320d62524cd070eef94ef1ccdaee.nq.gz
    ├── 2632987fdf4a274c629db3ace0665ce40ae05fc0.nq.gz
    ├── 2636764cb645c1aa58ac5bfce7692d4809831f67.nq.gz
    ├── 263c671dff161e1561e096e37d1650a919bf8685.nq.gz
    ├── 263fcda40d5c2134fbddbcd7dd56018b95f226bf.nq.gz
    ├── 264b0b162c88e4e860693532f96edc19fa397495.nq.gz
    ├── 2672373eb81f52ec6b70c321383dc24c1c4bf9fe.nq.gz
    ├── 26827297b2cf500b90f8aa5543d85d51fe8701fa.nq.gz
    ├── 26a6e1ea0c57a438e273c02c805414df443d3e97.nq.gz
    ├── 26d57d25f10a9a6290747e8d9287debf4444e384.nq.gz
    ├── 2732b79606ef36b56ee95887eda5b508bb098f82.nq.gz
    ├── 274b2fe2b91eade3ba00e5b787c2f29100f0ee8f.nq.gz
    ├── 27515178bab8a24122560f58bb2c887d198a0867.nq.gz
    ├── 276b33e6a08669696675342580c3fbadd0620768.nq.gz
    ├── 27842dcceca23c79783cbe7c03af53703b0bfbf1.nq.gz
    ├── 2785e0780c670f8b53d92f9338b59e22fc07d95a.nq.gz
    ├── 283c96ca12cdf39e9db4f270940637fc98010056.nq.gz
    ├── 28ae17c22d0c5d549cc003eccc7c046e4e7cd5a4.nq.gz
    ├── 29573309aba1b2de919a519f010e55b794952714.nq.gz
    ├── 29f115362d28e92de60980b940351501cd22e224.nq.gz
    ├── 2a0998443a1a733b0ab316075f22f8a0ff8a2ac6.nq.gz
    ├── 2b62377d5676404353a773a52ec354d87a32471e.nq.gz
    ├── 2bb0ef05d1cc703bb8c7b9f45bdfc1759fd6bc0e.nq.gz
    ├── 2bed2dbfdcde749d728244b3f57f07e1a04767c7.nq.gz
    ├── 2c0ffcc65cf2113fb4a7a2109a113344d98fab78.nq.gz
    ├── 2c4411f24e6119dd617e19149ad661b993230d35.nq.gz
    ├── 2c445ca5e4249ec225b48e411a886b49882fc3cc.nq.gz
    ├── 2d177cd6310e490ac88cfd822b8fb12160f1e0ad.nq.gz
    ├── 2d65dd3dfc60f27dd2dad8541692c3feffbb2271.nq.gz
    ├── 2daca50f7d9dd8fc4f66b9298850c3accaec4cd4.nq.gz
    ├── 2e60d8342faddd6b6a2f7bf1ed342a3dad6dbe31.nq.gz
    ├── 2e7eed3340e8b82f3796c71dd094900c45f3fac2.nq.gz
    └── 2ef8bd87e5356ad7132e9b6ba7d49c06da63ab5c.nq.gz

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

[stylus/stylus](https://github.com/stylus/stylus)

---
*Parsed on 2026-04-10 by [repolex](https://repolex.ai)*
