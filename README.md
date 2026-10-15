# Repolex Knowledge Graph of scikit-hep/decaylanguage

RDF knowledge graph data for [scikit-hep/decaylanguage](https://github.com/scikit-hep/decaylanguage), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download scikit-hep/decaylanguage
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── abe8e624aaf1aacb73b9139510b69eee65738077
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── abe8e624aaf1aacb73b9139510b69eee65738077
│           └── chunk-001.nq.gz
└── blob
    ├── 0291a1117ac221ba1ff7083cb4e63ec68107e6c7.nq.gz
    ├── 02a068f628740593e68a06d54c288bb1104f9b5a.nq.gz
    ├── 03cfe7775f6ea30536641527493e3a358c4a1e26.nq.gz
    ├── 042ce4beb9c3345d079c36f1366ecfde3e82a0f8.nq.gz
    ├── 077e08f2622dcb80fc18f89b20013bcd6b4f50ea.nq.gz
    ├── 07b3c64daa431add521ba0c4732d868f5227737e.nq.gz
    ├── 09648a327a87741c80d5024fc12ca0a37128b60b.nq.gz
    ├── 099f63ecacdbfc93590a688f7f88eba1dada0636.nq.gz
    ├── 09d627e2d1c88848bf72d2ed03f536ed906bbd13.nq.gz
    ├── 0bcd98b72bfc8540df106888e5bc8c3322859538.nq.gz
    ├── 0c0bed8bf10b444274d0c9a0a2ae54eea1b9d6ab.nq.gz
    ├── 0c745fe3e4a1bf8fe8e45eec41679fafcdec6463.nq.gz
    ├── 0cd8fce7520dbc8168be59c2da1ab05a9e2cffee.nq.gz
    ├── 0f5f66dab2380a814b438e230942c698c04557ba.nq.gz
    ├── 0f9aa04e5302f403a9382e7f90329a1b730102b9.nq.gz
    ├── 0fff26ce290ef7b74dbbc7e516d49bba74a04468.nq.gz
    ├── 10677cd8d99a1a833ceb0e6379ac8152f7cab65a.nq.gz
    ├── 10be605a8ffaa37b30464e33e925cd6bf33faa76.nq.gz
    ├── 11cd82b7e7b713be6d1e318cd93ef1bb2ef78b2a.nq.gz
    ├── 12f5dc2cb6ad7c679d061c03dc591b8a803e3f3d.nq.gz
    ├── 1409d492d3969892556bfa2247caabd0c107acf0.nq.gz
    ├── 18b94abc228c83891f6d7fe24addbf8f08368d20.nq.gz
    ├── 193b6bb0426cfc82288a155787b6ba55ee31ca1b.nq.gz
    ├── 1b38794c1fd76f4d8148c5fb87a9f64f3644af31.nq.gz
    ├── 1b44eea75e60e00ceb376995cb12a929ed07dcee.nq.gz
    ├── 1ba736fb85b18c6d0d05a1c4a7172d1dd0cadcb0.nq.gz
    ├── 1e142ec5880041493c2e43363d44c38a72c076ef.nq.gz
    ├── 1fcc08353a9b2080256dc9359035d4db6297113b.nq.gz
    ├── 20cd0619bff1efa74a5c057d387e512b16438790.nq.gz
    ├── 211e8d60707d18a0825b0579287510dd25b9abb0.nq.gz
    ├── 22aa9871941f3714a0242e8279ad8314d2045685.nq.gz
    ├── 24ef1c3a6a9b84b45861034a70f9228f38ac5cee.nq.gz
    ├── 2587eda6a18f15ce10734ee237835a6ba7904b05.nq.gz
    ├── 2600519e6251434877846e5e8ce5e762518029ac.nq.gz
    ├── 26aabae14f150603b11350aa53d1ff47fc55c516.nq.gz
    ├── 26e263e1c4ba6cec8ae28d08dc6adccc7df06592.nq.gz
    ├── 272ee23015edf4b0f94ce4e679af3c594bfc7c10.nq.gz
    ├── 275bd5dda98b9f3a6beed61cd6df06069d2dd8c3.nq.gz
    ├── 2a13e4d29e7c68accc1049260d1263961dc06275.nq.gz
    ├── 2a5f7a194072de8daa36babe9ae032dee69add97.nq.gz
    ├── 2a95bb625ed16a964a90a5b75dae7251e0cbb5cc.nq.gz
    ├── 2ae00da73014a566c389b1fb832f4921417a66a5.nq.gz
    ├── 2aee120754643856aede6f4a0e164b97bbd168ac.nq.gz
    ├── 2c0116f24d39312ef2a9533c7cdfae22c40b1847.nq.gz
    ├── 2c4fe8b8e59bc38687def6f250688e6cc08911a6.nq.gz
    ├── 2ccab20b393391a5fd0ed9d89447c2280b55ae14.nq.gz
    ├── 2d95e5110736216ca14ea0b97b524e25702a500d.nq.gz
    ├── 32350611c00c8e4d18b42bf966f5c9afb433f1f9.nq.gz
    ├── 336f3589ed4cfdfeaefe40cff68041a4e85c1b09.nq.gz
    ├── 3615225a6f339b00aaab741b1308ad6f6d4125a3.nq.gz
    ├── 3623896f9287f059adc6f18fa4f0abf6d036ae86.nq.gz
    ├── 3734dd75b69097666ef7d3ee10d998a491bc6d1a.nq.gz
    ├── 3740d5be6b23447a068c24ed1627c5c36f86fb11.nq.gz
    ├── 38b670ac7dc3c34e01498e9a265a518e56985d64.nq.gz
    ├── 39eb0e4cbd9d78075cd49ad0d473090a8ff7411e.nq.gz
    ├── 3a40ee49f52a2ba19d0aa35d6e1683c2e7702dba.nq.gz
    ├── 3a57cf7e06829780f4a997ee6cba8aeb7f81418c.nq.gz
    ├── 3b766cf4bd6a18e8236d2791523f13588ef8ff16.nq.gz
    ├── 3ce12767d290e90735b7d942950ba969f5ec1162.nq.gz
    ├── 3f8759a499e20e03b29a7672072cb20cc05fc8c2.nq.gz
    ├── 4000618e99f9c8ad55aaf9fbbc9057794bfc1252.nq.gz
    ├── 4002a3133577cd776ed0ece18c69fdf596459653.nq.gz
    ├── 4128eab3883d30209db288cafc62a4595adfc4c9.nq.gz
    ├── 4130e944cc3a0462eec6305e5ba8c388cfcf132f.nq.gz
    ├── 4142a310162a300cd013f3053144f01968f3e712.nq.gz
    ├── 43f5388e541aecce795baabdb68b85995e716c90.nq.gz
    ├── 44fb090313eeec7e87b1980e02dad2bef7622e8a.nq.gz
    ├── 4522f0f65934a005bc58505ac3e097ea26cbb9e8.nq.gz
    ├── 45d55f605e59b0c662dca90df09ad29fcf0f1cb3.nq.gz
    ├── 46f682d6d6b5b427b34eb809a210fdcdf79a41c4.nq.gz
    ├── 4a40aecc15ea6b8d4652ad256c3a85d223e1dbf5.nq.gz
    ├── 4c061085c573499675e729aabdd4d1f72d738cc7.nq.gz
    ├── 4def19a426fe58cbc9a31b173753336ac9836517.nq.gz
    ├── 4f267d3e866c75317b7d5ba714bff0d72fa2d615.nq.gz
    ├── 506389333e6ecb5ddf2b0dbfc32bc27441fce36f.nq.gz
    ├── 511a1fa4db857cd9ce7bb3fc677f96b3ae84f4dc.nq.gz
    ├── 51ac126583ef81fe2ddcedc6f2591132ca9ecf84.nq.gz
    ├── 537f3a2236d5eac47d46782cf7905285c6896056.nq.gz
    ├── 5387782f4e7c32bb2afcd0a333a3ab0ab7811e6d.nq.gz
    ├── 53b42aeca68ac0afe6cd6d819feb20687381242e.nq.gz
    ├── 53ccde6ba79ea359917e3d34903f96d3a0b21103.nq.gz
    ├── 53efbe1939ac1f2d66f0c6a82c52ad56b3cd7357.nq.gz
    ├── 54ee91ddf3e0f25c3d78765d2a5291deaf08c3ab.nq.gz
    ├── 56b3d116737326bb75d4a9684f02f77ff12fc9c6.nq.gz
    ├── 5701a71f1ae55103d5467612d983131539c75abf.nq.gz
    ├── 57c4d914f2baefeb00648c35bedc19c1907c2704.nq.gz
    ├── 57fab8ed7b06b8fff0fedea2809b4fff09f0e607.nq.gz
    ├── 585b3c713eca60f9ff78d0e35b8093326ce630ca.nq.gz
    ├── 585d9ea8dba5ae872d2a656b897def6fd7499b53.nq.gz
    ├── 58928bddafdca1852bba1ca206fb976a6da568aa.nq.gz
    ├── 58f771a5907bda5696ab76e75e4f3db8250b6838.nq.gz
    ├── 590722a0450da68a5987d3986f6a0c495fb2cd69.nq.gz
    ├── 590a193ae3e3ba53818a94757ce942b1ae02dd84.nq.gz
    ├── 59deec625d1b1d9474dffdff2d7a64b9e81ad1cf.nq.gz
    ├── 5a8ee5df1767fc52153c700ae80867fb3beaf9d8.nq.gz
    ├── 5a9ed4e63b68deb2aa7fc829282963a7264379e5.nq.gz
    ├── 5ab775921c65e546c0313ce949c8325f9513c2d2.nq.gz
    ├── 5aef26c61bc80c566c940a53079b4850ef639421.nq.gz
    ├── 5bb2b22f78faec68eeed9a623c15cad2747c9eba.nq.gz
    ├── 5c5a934f8dbac24cb91b713d35cd613e58fd353e.nq.gz
    ├── 62253fa8ae3c416276ef089744baec2f3c2f4c42.nq.gz
    ├── 6314d75eae6609ccb804e20db7279a40692a63f4.nq.gz
    ├── 6378f9085a77f61fbae06b30edd65abb19fed56e.nq.gz
    ├── 6497fc6d55b8cf93f70886640d2debb87fbe7e93.nq.gz
    ├── 65319bd7415f9cc298df307feb29057f6ec498c9.nq.gz
    ├── 66a768a3f5580c42bd596f885eba8f8f4f29dafc.nq.gz
    ├── 68e2494933595dfc0692cffc637ad31a1172aa10.nq.gz
    ├── 69309d481121546e767af6f7a83f1f85ef889bd3.nq.gz
    ├── 69dd5027c91683ef8ff24d5d614106238ebf35e8.nq.gz
    ├── 69e0faa62b5a1a58e5360aa5bf6cc70d45664a58.nq.gz
    ├── 6c237c6472d685b7a8134c79f275d18af7bae5ed.nq.gz
    ├── 6c8fea5393ae36ba198bbfa98d7436e56b470cdb.nq.gz
    ├── 6d1946dd3f93644ae00b8796c44d1fcde1a13f65.nq.gz
    ├── 6decd477e6cfdde5e507fa312ecd4a0b054aa5be.nq.gz
    ├── 6eda29fde0cf31534488d290a1c14be2d792ec9a.nq.gz
    ├── 6ee63dccebe2b9cca1d0a3ae92c4d90c13fe2dd7.nq.gz
    ├── 702a1830a5da7460871973578955c7c58690cd83.nq.gz
    ├── 72b062ddcd269ce1feca4d0e5389df2c635ab865.nq.gz
    ├── 737f90edf6eef1bdee066fcfc72f3ea79d9f6474.nq.gz
    ├── 73b475bf3685cf834dbd6ac9ff49221b496e39c1.nq.gz
    ├── 74fe9e5fcfec89d5fb5e2031c4d1a09e13359e5a.nq.gz
    ├── 7a654744b09419a3a675162e018f6f97c394e61d.nq.gz
    ├── 7b2ab8696c976036897de17e690784f4854b3093.nq.gz
    ├── 7bd96f7f634a76f0af6b9ecce9ea136c6f1a5eb3.nq.gz
    ├── 7dc72ef95f71dc2b0ca86b41ee00a1ae40965b11.nq.gz
    ├── 7f5b1049b33724f0beeb88c1a204fcaf8283198c.nq.gz
    ├── 807b325d3b4445a05a43d02bbff71d5e876d4b5d.nq.gz
    ├── 80c8592b4677b35e29d9e120f6c533f49f8e47d4.nq.gz
    ├── 80f5d6fbab1b912568fd66c83a4909fcb1f914dd.nq.gz
    ├── 813c26a9ca0aa238ac075a3f864c256b323d4a64.nq.gz
    ├── 8211551853c2f97704f6e0786b2e59361925140c.nq.gz
    ├── 82f0d20b49d9278687e705b7bef0da3335e667e4.nq.gz
    ├── 830d384bba77b26aaad3092bd1786708a892bf81.nq.gz
    ├── 83fe7d84b6d44046c8a1c956350839401feae54d.nq.gz
    ├── 862bd9d423bff36aba0f4162add4f634c5b07f41.nq.gz
    ├── 8916c0eecb1f97ecd2f1140cd474f2b8991127db.nq.gz
    ├── 894fea2a26f24e32d368f0093d29125ed5d97b32.nq.gz
    ├── 897cb7722f356686f0dfd93849c653953851fc04.nq.gz
    ├── 89af09ff826ac6e247259d0ef2b4b5785286740d.nq.gz
    ├── 8a0b214d1e8ed3c3323aa1c2e17fd40cb2643127.nq.gz
    ├── 8b13673c14657c63f5a23c7b514f9fca0725174f.nq.gz
    ├── 8b6d82e44e64f505b5d5261e5870776e6f730d4b.nq.gz
    ├── 8ddd25f851b7f37c028e392e88c6efafe5f298ce.nq.gz
    ├── 8ec9514bac764bd31ea456c625b4a6df482fe0dc.nq.gz
    ├── 8ed61fd838e77e295c47d419612b413484a85878.nq.gz
    ├── 8f9c284771af799dc51cfd3656aa39ff0e262a2e.nq.gz
    ├── 8fe48b94802dc5b6cf3b814b295885a34d43adb8.nq.gz
    ├── 911beec41bab4829afc949ccd92569cba52d0045.nq.gz
    ├── 92fa582462c58efbdcf94d320cb330f6df884ba7.nq.gz
    ├── 9424d059840efd5b363bba484d2fc04acf7d3e3a.nq.gz
    ├── 9525985acffaa41dcf17c05666dfd675fb09f000.nq.gz
    ├── 95a9fd70b1eda96966edc784f0f66396c31c30cc.nq.gz
    ├── 962ee80dd346dbf13d62cfc057cba5d46549808c.nq.gz
    ├── 976f49db2dbabf5eb14c7ed8d2ed71d9acf1e800.nq.gz
    ├── 982d7dfc867c48f9eb19bc08727df9245a8e38d0.nq.gz
    ├── 987df5ea3214da7e9239e107a45c0cfc8a06fa34.nq.gz
    ├── 98d0d437869914e9340f0ce9a119139c88b8479c.nq.gz
    ├── 99612c21fc2f2d5bdd47dcd14f8259bb6197517c.nq.gz
    ├── 99f962cb00b9780701e065e6e732cbb08c5d8104.nq.gz
    ├── 9a5c8105b887167dd975c8c8df0c3fd52a0181d1.nq.gz
    ├── 9abb4852083da70b48c260b2505bcc6ed4734b13.nq.gz
    ├── 9b1946d63857e2e01fe27074dea70afce63c267f.nq.gz
    ├── 9cdfc67d75111d9fd6d9d0f46b3b8bcae13959b4.nq.gz
    ├── 9ce789c14d58ec647ab61b4d606face2cebb79db.nq.gz
    ├── 9f4286e2283c2349e1ff2fa58d50d03081a03d47.nq.gz
    ├── a139a1fc8d3ddd3b8510083cecc8cfa6b94e996b.nq.gz
    ├── a24cfded0189578b32393ec99a68b75bd9faa3a0.nq.gz
    ├── a288c59b77ffe229f94d5ad76989723d3dde7296.nq.gz
    ├── a6be4e0cb17c00ace5751a4b703ff65d00e5d462.nq.gz
    ├── a6e84160c01a3065e3866bdd843f829b1e75aca7.nq.gz
    ├── a7b4e59238d0eb081e84121b9badb7a70f875fd8.nq.gz
    ├── a84fdd266a6f5abbc9e6bf278a016c7460a41f5c.nq.gz
    ├── ab7e6f98b85d1ea18b505950618b91f267544a41.nq.gz
    ├── ac7b6bcf35e98139c791cb5c4b94f08849972d65.nq.gz
    ├── ad5a52d664379c6e43338c81468f51b08d7bcfd1.nq.gz
    ├── ad8959894c48a91783be44075189476e528cb052.nq.gz
    ├── add49284eba7d466ee13522e90b822d344217a78.nq.gz
    ├── af2602e63ea74f74e731159b22593106ca47e427.nq.gz
    ├── af4be976232134ab3e22221658883eb047265f23.nq.gz
    ├── af656b078f84bdd986bb0fbf990e26724246c1e8.nq.gz
    ├── af961ed24dad91131128092968551505260bb5d1.nq.gz
    ├── b092c3323e195cf0d41381620b93b6267c8b239e.nq.gz
    ├── b11954b518299c33d3d78d5077bcd61996cba4b2.nq.gz
    ├── b2001700d2caae146e52f2040947e7585f47cd0c.nq.gz
    ├── b27acaa4eb35b634db5f502d286a62397df710bc.nq.gz
    ├── b2b2e89aff1c6960753acfbcda5cbbe634063610.nq.gz
    ├── b41cd68f39472c6994fd9081f9ce44529e89ec9c.nq.gz
    ├── b66308d9d9aebf58405b3d00d3c2f54c35288db1.nq.gz
    ├── b6a174761529f8bec5f1456c72dd0883a047b08c.nq.gz
    ├── b862c11e43edbd34afe249242ad64d5c9540451e.nq.gz
    ├── b8d40dd8055aedd7260e51ed3a079c49a8618635.nq.gz
    ├── b98a725e151f1098ca476cffd8d967c3cf223282.nq.gz
    ├── b9fe052df9fec408e51112fa930d96a7423c6dc1.nq.gz
    ├── ba19889d56dcf4814fd60f5260f9a5021d537e2d.nq.gz
    ├── ba1ec360db6e44fc045924963f3cd5f0f5673bf2.nq.gz
    ├── baef9088af2e595e8f47d006d6e0ba03400460f3.nq.gz
    ├── bb01f2bbcb3544fcf4a8c1764bdd3a41194edc7b.nq.gz
    └── bbff992bec4d41650285d9ff657d2347575056fd.nq.gz

7 directories, 200 files
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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[scikit-hep/decaylanguage](https://github.com/scikit-hep/decaylanguage)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
