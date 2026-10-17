# Repolex Knowledge Graph of rasbt/mlxtend

RDF knowledge graph data for [rasbt/mlxtend](https://github.com/rasbt/mlxtend), parsed by [repolex](https://repolex.ai).

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
rlex download rasbt/mlxtend
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1aee767ef57b84a8191511a08955c583b65de382
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1aee767ef57b84a8191511a08955c583b65de382
│           └── chunk-001.nq.gz
└── blob
    ├── 0042b4ad8d081a0cf6076c21b4da7f5d2d5014fc.nq.gz
    ├── 00b450c2475c4983a13ec62e2335ae611bdaf929.nq.gz
    ├── 00d3eaaee2983b8f4f614d3686a148e11b9101d7.nq.gz
    ├── 012d9b938be38c65a2c14150fe1175d79ca2c01b.nq.gz
    ├── 01af617341e023772b15c43daba574acd0a1b402.nq.gz
    ├── 01dae2d3cf11dd4a36d8ea28140fb81d69fa19dd.nq.gz
    ├── 01e2db775f88041471629190fcc15aacbd30e558.nq.gz
    ├── 01e560d0688e68d2160b8b322c5d52c3db2ce082.nq.gz
    ├── 02abfbcfbc6eca249bed2d06d8018d15109f1305.nq.gz
    ├── 03754534f81f1d5b9a6505953836890c679c6502.nq.gz
    ├── 04829e9f10d615119a06e2364e153eb2e0755634.nq.gz
    ├── 0491e957a0cd16309648ce2b6a50a693ff2614ce.nq.gz
    ├── 0660a617bdfe01c3e19a4bf93e21571aa1ea78b7.nq.gz
    ├── 06a71517fa59ebebf77d76763f14b276a8c346a1.nq.gz
    ├── 06ee902fb290f37d1ba550e62d949c58db04d9f9.nq.gz
    ├── 07e3382e983f52ae39c43e57c94819085a4dc99c.nq.gz
    ├── 0823f45bd8524ee8f52b74e2148094b4c8c93288.nq.gz
    ├── 083a4c3588331d434e99b3ecd5887a3a36c4cf0a.nq.gz
    ├── 085c274cd7d14fa9c63d76fcca75fe7f77fcdcc6.nq.gz
    ├── 08ad2a0e94170da5f4617f48f74bcab700d9a791.nq.gz
    ├── 08ea19d5ae6d985007d09d3e5a8e26df18bd17c6.nq.gz
    ├── 091093775ecc7226902bd674681fffb252760117.nq.gz
    ├── 0941d761830d2b568d1c39e5f1aece0ae6915d28.nq.gz
    ├── 09649badac70187c76ef033676464c74b21891a9.nq.gz
    ├── 09ed94147dbad464e1b0be5b6fe4c377bc994788.nq.gz
    ├── 0a25e9595c291dfda6aace6d4c07dfda03ac831c.nq.gz
    ├── 0a2c3b0f56bc8b981c4b3be4d6394f644adad89a.nq.gz
    ├── 0a8aece0a666cb347c88aa7807ee54085dd95e61.nq.gz
    ├── 0b7d8b6475215816eccc3abe55b53b57388d68e5.nq.gz
    ├── 0c8bc650a6053851784e8573b66f5cd0aeea6fac.nq.gz
    ├── 0d07c446d2b82af54c4f85c3b1fee0f7edf6305e.nq.gz
    ├── 0dd0b63c8ae74dd4699aa15462a1c8bbf408172e.nq.gz
    ├── 0de225e62a103c3090a3114501abd914b1ae8b02.nq.gz
    ├── 0e58bdbac97159f34027973eac4e5b60bbb2fcdb.nq.gz
    ├── 0ec321e2806154e419f2ac30cc3d6b7e35ee2437.nq.gz
    ├── 0fa80e470e0a219dde2e3a1a1dd1e4d31e027425.nq.gz
    ├── 0fe0fb3fb05cbe3a8169bf635325498f2eca8e08.nq.gz
    ├── 100f24aa2191ba4177cc09f33a45519ff13374e6.nq.gz
    ├── 109ca509d361beded009b2497a2ee27ed5455ee6.nq.gz
    ├── 109f80df0de2acfc5a940a1b50c63e43585531c0.nq.gz
    ├── 1171e69338da301b6ac02990910bc29eb6378d25.nq.gz
    ├── 12397b0eb45ac757166b0e157a7c1a52e87ee3ff.nq.gz
    ├── 12735fdab39dfebd8434bb513c7aed20e75c4ab9.nq.gz
    ├── 12be3d90e11d901457b665ed0402ff3c0f7064f2.nq.gz
    ├── 13337b5b48bc6192013f21f7bce491951246317f.nq.gz
    ├── 1398bf680d593f81a9490d536e56b57a3ad366b9.nq.gz
    ├── 13a6f0a2d50b83ec2449f2bb1665aa15484b829f.nq.gz
    ├── 13a995eff571bdf0098f1b570dccc88e980f28be.nq.gz
    ├── 13c0870c7479d2581e072f2f201057d63a69093b.nq.gz
    ├── 13d8cdcb6fb8df5f0a134e1a22e6b584722eb9c8.nq.gz
    ├── 1451bdb389ba1ad69e1efddde901494f682832b9.nq.gz
    ├── 1496c14ebd959232a3197733b9f0d9b63ac4e0bf.nq.gz
    ├── 14fc6d96a3635368c275087af959f60c6103e9f9.nq.gz
    ├── 167005bc81f8d95931a16aa53d597045d042f017.nq.gz
    ├── 1690a0a74f85f19329b8a1d76382166b85101534.nq.gz
    ├── 16d159c6d667a15b4f018ca8e0903dba19fac4f2.nq.gz
    ├── 1704224f30b1e1513c67ff233648f80ed4293310.nq.gz
    ├── 171afd804faa2db50e6dbe5c4365e8e329eb0eea.nq.gz
    ├── 17602107b5832c0e03b0f40bb601fb190326afee.nq.gz
    ├── 180e22ceed954e115b4139b2d2e15fdc8d7fc989.nq.gz
    ├── 18ca41771e94257e4f9f264414b87a65dbf3f707.nq.gz
    ├── 18d14087984b35196a441c739109128b22f4cadc.nq.gz
    ├── 1969f84de45405c57b47de417c0704314af8ce5a.nq.gz
    ├── 1b0a3615f405b28f191884e44e0e2f0cf29b7ee2.nq.gz
    ├── 1b6d9d2ec45811c4f7927a4a0628fb07dac7ae1e.nq.gz
    ├── 1bc4c15a507402b1f03885f26ad58416ba1a59fb.nq.gz
    ├── 1d3c98d5f13ccff7c57f6c2365804b479e40a94f.nq.gz
    ├── 1d5d80a12aa6c51fc5c13ca306957424953169ba.nq.gz
    ├── 1dec5697a68d2ba456770a747deb33f16fbc6b7a.nq.gz
    ├── 1e954a5509f79079ace6d4c006ef49ceca31255e.nq.gz
    ├── 1f0417a5d4d9713ed1ddcfe0cbdb91da24273143.nq.gz
    ├── 1f82fe8002a305a7aaa88aea6299ff263341c494.nq.gz
    ├── 1f88669069069552dc96036f59ce43b135019671.nq.gz
    ├── 2042a71976dfc99fd94a3277b07bf6d33a35e77b.nq.gz
    ├── 20505414275d4006ed9c9a2f239eb9c27c634bb9.nq.gz
    ├── 21923694a68a6a252ee18801bc3a6b2d80ce1aa8.nq.gz
    ├── 21f3d13b03d3cdfe9c67e39fa860d012b3a42f8f.nq.gz
    ├── 2289bb66a25873b22dbf6b8ccdd82c83f35cb23d.nq.gz
    ├── 22ff52fc75ff846024b9d3be77982792c362641c.nq.gz
    ├── 23265bdff2307fc7f9b339e59b7a602001f54631.nq.gz
    ├── 23275500f2c4cfb75e02bdac7a251014b0b5b543.nq.gz
    ├── 23ab557ba33ddc28109a94d2c9bcd27889467297.nq.gz
    ├── 23de95e9df413417424305bd2b96d307284e61ae.nq.gz
    ├── 242e5a3c1dd237cbe51c10ca84da94793e8fb011.nq.gz
    ├── 244e4dcc30898d0378679c47f135de33b24bd9b7.nq.gz
    ├── 24eb0bb85feb8a317fba0854c113a5a57f9a866c.nq.gz
    ├── 24eeb49753ddc687de04127ea2766ed628c3f28d.nq.gz
    ├── 259ab5ddf29584e73e75e9e03f06dff19e89ad75.nq.gz
    ├── 25b28b5924eca89c1b2104ddbfa095a679bf0b9a.nq.gz
    ├── 25fa67c62276fa9090c42aa75e8de113b028f7a2.nq.gz
    ├── 2669f9ba4df1530e8b37579e2c5ff5f82cf25fa4.nq.gz
    ├── 27c22999a8aa660d6ec5b962e669bd813453acd9.nq.gz
    ├── 27fffc94efb958f4471bb81046d2f887b42e40e0.nq.gz
    ├── 29a7165a39590ef461c283b4a05c3739d069ae8c.nq.gz
    ├── 2a1f1801b129d2c80047823fa45dff8a7b40b08c.nq.gz
    ├── 2aa4ab24d60ac6e452dcef92101960271140fe1a.nq.gz
    ├── 2b32396e03dbec0ab9cac360dcb121e3b53de9d3.nq.gz
    ├── 2bd066cf5490c006a5ec0af92f4d7c87c9455b16.nq.gz
    ├── 2c25723d98d0ec0b0d6113725625f6048a5dd77a.nq.gz
    ├── 2d681cd623e66b09e2733a4630aee54b40486739.nq.gz
    ├── 2ddec5f76d17b9f890929f479669f4caa53c5267.nq.gz
    ├── 2e3f0ae1a440fd6a96b37113495f4a33ef2b014f.nq.gz
    ├── 2ef72aeb78f4f0fbc4c96840017a4168d3b15219.nq.gz
    ├── 2f1691560615b0ffe02cc91e61e925682125ca56.nq.gz
    ├── 2f4f1de56ae9998046839eff3edec290bc30f6de.nq.gz
    ├── 302a2a73b2291aca342c05eabb809ec33559b1be.nq.gz
    ├── 30aa12dd651b1a318917e9f693a1267219583fad.nq.gz
    ├── 30e3faeaf7ea78d396cc74d350a0e456dc459560.nq.gz
    ├── 31bf32121ac209477600d826805b3c7de37b8db2.nq.gz
    ├── 3224f0b17d4298718e04ff9b0da6b3fea274e043.nq.gz
    ├── 332eebeabbda0541036ff4852de7a08aede6c42d.nq.gz
    ├── 3395068ecb805ec418a03ab107375f01bd429251.nq.gz
    ├── 340839a86930e32a9fd9e359433555870e9e7bf2.nq.gz
    ├── 3461d8090a98c4de86411cd3b54dea9037403bbc.nq.gz
    ├── 3462c0b475bea89b50942e34fe2317c7a6754ecb.nq.gz
    ├── 34703693c68ed9d5aa0e78b2d84693654e4306ba.nq.gz
    ├── 353a966e7903bf87388bb5fd7f552f070c30021c.nq.gz
    ├── 35b62bbb99a90a4d1bcc9a7602c7c3a52c22058a.nq.gz
    ├── 35ea9c50d42c3530b13104554538531295223491.nq.gz
    ├── 36063e123ad1be665fce898382391aaab9128df6.nq.gz
    ├── 36a114f0058814f784b875b45c5f54eae4e7462e.nq.gz
    ├── 36b6cff8c7b204081f8e96026d76694c330d1031.nq.gz
    ├── 36f67f830eb8c7f0457009cbedb4e671c4fd1f93.nq.gz
    ├── 376f518e7bd282a05f4b7c542a03f5ca14db75f6.nq.gz
    ├── 392acb66595f3dbf64b568c92cfdac2bdd64cd76.nq.gz
    ├── 39405644068764a28de4579b260e5c9bf3324198.nq.gz
    ├── 39e897cb27bb3d5c8b753a2d48d2446dc611c5ef.nq.gz
    ├── 3aaf213205f956d319c3e877757035439a66c8e7.nq.gz
    ├── 3afaeb78c9c464122349e77d7de9b9897cd15b28.nq.gz
    ├── 3b7210b64aeee48346ffdb257057ee0f4fcaef8e.nq.gz
    ├── 3b81e0bf7152413ec0dca445687712cd34c3c4d0.nq.gz
    ├── 3c565866b842d90a52a6beab34638d52df3ab41e.nq.gz
    ├── 3cab2c236f186b48ec97ca937856e9ff72dfc0c3.nq.gz
    ├── 3d02f28d1368f086aa3869981704bcf8288e40e4.nq.gz
    ├── 3e49930d21547974ded5e4d54243c81335aa038d.nq.gz
    ├── 3e4caf662d7c4aeafe382ea6e2ff9eff5fa1fe04.nq.gz
    ├── 3eccb0a9a4dcae4cd170ab0bad47c908859af51c.nq.gz
    ├── 3ff1abc7cf8e86772d01f9ea8e9e35102e11a98b.nq.gz
    ├── 4013815b5b97d63d2d041ac68e0f82c9533f1a54.nq.gz
    ├── 4188cfd298926ea02f731bb6fafbb454b17b2823.nq.gz
    ├── 4297bbe4ab48fe3053f81d8681727de9b44a932d.nq.gz
    ├── 439e3ef12bbf3d43e9d1d7ad59580ae5664484a0.nq.gz
    ├── 43a40568a1b242181d1203b598e0c01ed5bc87f1.nq.gz
    ├── 43da5176fcef08be77be0cc51295a22f7686bf74.nq.gz
    ├── 457c3a315b42c51aa79207187a2a473dd9d5e7b1.nq.gz
    ├── 45b3619eac3c6ee255171c0f1b94cf547ce03d3f.nq.gz
    ├── 4617c9d981cbfd853a1f26f2fc23551f5db55343.nq.gz
    ├── 46d033e6dba11d5c0d005e3ecc28c374662d17ac.nq.gz
    ├── 46dafd82d7808e454bc99bd02ef870a8217800ee.nq.gz
    ├── 46e73f004ff96f930fb025f5d66c782ed578c2fb.nq.gz
    ├── 479a32634d0efc7cfaa0a04a2d3bf472fbb974ef.nq.gz
    ├── 47d8cebf5610f6abbeff9ad2a2f9306ef7e2ca49.nq.gz
    ├── 47fbb989709a32ee7adb72339f070ae7e1683163.nq.gz
    ├── 482a9be4ee3118aba17e3b33b2eb370929290c63.nq.gz
    ├── 48390ddb654ec2c9c05a8f940831100f447f0333.nq.gz
    ├── 488e4c04ab8f4a0d5dcded237b159ba615f9bd83.nq.gz
    ├── 48eaed24b6edf06a095b5c066cf9e99b2ac5a98b.nq.gz
    ├── 48fa42a7bf24d9da3145922ac11b3e9a8be253e8.nq.gz
    ├── 49016f9c59033798876ee59e99b08c766ee2f7b2.nq.gz
    ├── 4932defe15dde29e819e78ef3fc6382df41655f3.nq.gz
    ├── 4a5684e6873a51f509d109c41bb153bdc91be1db.nq.gz
    ├── 4ac4a36fdfbdad1e475901860830b2fa999bbad1.nq.gz
    ├── 4b0502342f529d300e7d193fa759eee8d8be6af4.nq.gz
    ├── 4b1c5c826f234e030e5a3fad01455d38c863e9e6.nq.gz
    ├── 4b2118fdceffe6a49fdcb6b5942c255b7ec3bcdb.nq.gz
    ├── 4bc0c60777c992447e04d126ddab2d5c8c293e22.nq.gz
    ├── 4bf794a1a337a0df4571f17734bab2549849ee10.nq.gz
    ├── 4c3a365a9b14f265833a04eda390ea9de7ab4a29.nq.gz
    ├── 4d0737f95040e4adafc1e1a2ce19cba81444992c.nq.gz
    ├── 4d290d49435321fb6981e6436cf118819f6a81dd.nq.gz
    ├── 4d5dfebd3fe31f6b2c55950abde40986ae957917.nq.gz
    ├── 4d9c8bd6a411ac6f4ab608a7a53ed2551fe999f1.nq.gz
    ├── 4e703fe51bdc4734d17429765e8dd673c6f29b1b.nq.gz
    ├── 4e8f236e73f13e3d634910b8c0ce85d9b2f5c8ae.nq.gz
    ├── 4f745694fd8315adb43673643312ebfdf253556f.nq.gz
    ├── 4ff422ee2f7307d6dac28bf0dbd23cdcdc222c97.nq.gz
    ├── 502f31a64df0405471e89fc135ea779a2d051ae3.nq.gz
    ├── 5083eaad35b3a241ac5058e9be13e4f58c3d6dff.nq.gz
    ├── 5094d2dd083d0f051bfadba887bed29ec6493b72.nq.gz
    ├── 50c754fb5e5c14e75f72c442318d7b5a96196492.nq.gz
    ├── 50f52cba393b9d0a3c6e728fd50533258d92a97e.nq.gz
    ├── 513bfbd169980cdb6571910f9049fa907a4478ff.nq.gz
    ├── 515e7e6dd8ad9c44b2eed58dbc813352343f10d9.nq.gz
    ├── 51a89acd54bbec5c0a434906950431d2f7199438.nq.gz
    ├── 528c11177e7a03c15f42a967beba6008123e7c30.nq.gz
    ├── 52eccc3ebb95722bf6e82b8398a265586d29be47.nq.gz
    ├── 5340ab3b2393d20b1e4ac48663953288e4f09ca8.nq.gz
    ├── 5364ab98420444641df03ff378b4766eaca03c43.nq.gz
    ├── 53d54aaec6dc56237eabb1271c83f2cb59d753b6.nq.gz
    ├── 543772eb389f8fb873e7e27f7d49767b728d2b1e.nq.gz
    ├── 548ba89ca9747f017c78ea777aa26185c4827e46.nq.gz
    ├── 54b66cec6af8f8abb90573971fa211057d16d84a.nq.gz
    ├── 54ee7eba1d4214859cd630620d64177fac4d1066.nq.gz
    ├── 56924a499634694e27929cec7b4502a8305fb0cf.nq.gz
    ├── 57096c873d16711937597dddd66c45c499bdcfa6.nq.gz
    ├── 574526c34861efb8a30948233fd2ab5b7e94cb80.nq.gz
    ├── 577c7ac11f7a5681d8fad5ffa32c647a9cc5dba4.nq.gz
    └── 57f4f8cc477ad9069a4fb70603fe3002a5179438.nq.gz

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

[rasbt/mlxtend](https://github.com/rasbt/mlxtend)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
