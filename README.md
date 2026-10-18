# Repolex Knowledge Graph of nussl/nussl

RDF knowledge graph data for [nussl/nussl](https://github.com/nussl/nussl), parsed by [repolex](https://repolex.ai).

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
rlex download nussl/nussl
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 17368d4082c4ebffc76462221cf9bcaa595f7ac8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 17368d4082c4ebffc76462221cf9bcaa595f7ac8
│           └── chunk-001.nq.gz
└── blob
    ├── 0087cc84bd038f61fed758dcc99aa4264530f54b.nq.gz
    ├── 0178f4dede7b2d7cd1f39cac135fff23f0673d18.nq.gz
    ├── 04a00af90d576ff17fa40f33c566e631fdc04954.nq.gz
    ├── 051900254b83927c68b2a19dc0950e6c63de60d2.nq.gz
    ├── 07769ee483c55cc582a3870c42c3b314b25d00f0.nq.gz
    ├── 07919987cd10f7963edb001898c9ce9cd6c73f8a.nq.gz
    ├── 07eeab4996a75e11803bbddf3f143e7df8370866.nq.gz
    ├── 08997fb7d327c1e751764a8cc37a528724b1fcce.nq.gz
    ├── 08a0192901ec10521a5d68a6871e069cd90ff27f.nq.gz
    ├── 093a3c3fc189b239c15cadee99becee20e78949c.nq.gz
    ├── 0a002b81716a462a6e0223610c419beba3e597cf.nq.gz
    ├── 0a15c69258caec171821e543117e9e250eeddf4a.nq.gz
    ├── 0a9438a7defa7ff8117f659a7d521c0a26ac8696.nq.gz
    ├── 0af2b4f3ff4eb90c179ae00776d99b18e1d73182.nq.gz
    ├── 104653375ca2a8e5993579afb5acd105ec004f83.nq.gz
    ├── 11fc491ef1dae316f2b06bbb40eaba9c757fdfd1.nq.gz
    ├── 134948041272b606ff354830243f81877a6215dd.nq.gz
    ├── 13d84cc3efe144806c274ea7640ed638d501bf44.nq.gz
    ├── 13e6c077d55d17a9f2d102f9c611b029ede52861.nq.gz
    ├── 14f33a53b0546745609ab2b092b27421b5b39c3a.nq.gz
    ├── 150bc3776844f44bd4bdd82de3304721fdb13639.nq.gz
    ├── 15481fffce03981d0bfa4996b16391a3949631ec.nq.gz
    ├── 16af4b3d1de9a183a23641f44e88127b33f2bbff.nq.gz
    ├── 17765fe78b5b475e7c6af82b95efe98f2fce7c4e.nq.gz
    ├── 17c5a232b346d4835a612f6250a0d395cdc3776a.nq.gz
    ├── 185d9b9ce96e8e67f6623638ca092a46b3393a4a.nq.gz
    ├── 187e19f728203d544295d12fbf87e2d795c1f443.nq.gz
    ├── 1a345cb92ef56d009dbcc15a8b83175d9715dc2e.nq.gz
    ├── 1d69610a554878fcf2c0d48dcecd700919ee9108.nq.gz
    ├── 2119f51099bf37e4fdb6071dce9f451ea44c62dd.nq.gz
    ├── 21423eb4debf40513c9898bb90484d978c85d106.nq.gz
    ├── 21d3a4ebe0755e04ea75476c0b180cb44f6ad6a1.nq.gz
    ├── 21f3639913f22842fd356b1b9572c5fd5e3c6c23.nq.gz
    ├── 224d0e580be3e890617159d62d3262f6982cfb6e.nq.gz
    ├── 22949e971f6245903dbac834e885ac7e8e37f0fd.nq.gz
    ├── 22d49dbc323b13575f2d2f5981d2190d17ee0d83.nq.gz
    ├── 24c7a13a52fb2b73f4de1230c0ad755e6d4ee74a.nq.gz
    ├── 27d2f394d007ab8719ed705983c5171f90ad3dfd.nq.gz
    ├── 2913d58a91f8d888bc4d1da53ebadf936f692bb2.nq.gz
    ├── 2b238f88e9ef1903c84af7dbad4fa9e85211d20e.nq.gz
    ├── 2c1b997c358566546b700fffae5914250f687d31.nq.gz
    ├── 2d1c6561792e975d5a56f851b9f5767945471fb8.nq.gz
    ├── 2d8ef91b31ae6dd854269adf3eb80a76532f9b6a.nq.gz
    ├── 2dc956006fe1f4098a9bc5c023ec9b9dcfa1df1b.nq.gz
    ├── 2dfbacdb913fd3c622ec6531508883c2edd415c2.nq.gz
    ├── 2e28e80959c46bcbb48ee43b0d43a8eb38a78fe7.nq.gz
    ├── 30f6417ea89e6b9fd8f2cadffd6343a164801804.nq.gz
    ├── 321c268f8d5c19ec85247166be0fed905b05cc92.nq.gz
    ├── 32cf5db8550d1a6d6e957c62b228b72edd206fae.nq.gz
    ├── 348faa23c416c822810e6a17eba6c33850e0c9bf.nq.gz
    ├── 36012587c261913d0eab5573eb9c922fd0a82796.nq.gz
    ├── 37229df363abb15816b692b76be34a65a7056fcf.nq.gz
    ├── 37de41f1ec76e7e8ea196e32600c457b01560ecd.nq.gz
    ├── 39293360707a76e72e8cf4568027d85eb34206e9.nq.gz
    ├── 39e4f780487266228b99ea65d66498023d6d8d16.nq.gz
    ├── 3a3e7f7cf41d263b3c4380e0dc89dc060c135bff.nq.gz
    ├── 3c20079c6a7e8673b26a55cea743c94c854c2010.nq.gz
    ├── 3c2697a2df80f9b9651567c6891a45b5f3981a00.nq.gz
    ├── 3dc6a21992651b121d84d12824fffa31d6d60188.nq.gz
    ├── 42710da61095db87c49e1078879976d07ac39f63.nq.gz
    ├── 43d83c42c32fc9c56af25477e26b3b74d0701cee.nq.gz
    ├── 445f7b411a6c6e35b399eac49aa1680d6cc80fc4.nq.gz
    ├── 44dbacd8e2df4e8d553e17e6ff72af98b5867d25.nq.gz
    ├── 476266dcbfe6d5e4568af0dd47826b3188889cbd.nq.gz
    ├── 4802e40b82e8ff6626924c0c2f13fedd96581ac0.nq.gz
    ├── 4b210e62f85b45ad071dc7b2363219badf5fd699.nq.gz
    ├── 4b32e974824ea147fce7e35244fda60aeabb7b25.nq.gz
    ├── 4b974190b02e7f7dbf266282bb15885af3189374.nq.gz
    ├── 4c5047af04e0e4ad6c82b0d6a88e8e11ab2ea70d.nq.gz
    ├── 4c57be16709c980350b3934f126110b36a33a1af.nq.gz
    ├── 4f94c0082af4addc5c70131fd3d2eed96f93d452.nq.gz
    ├── 501f2768c4605820bbafc6c2f46a9da275301286.nq.gz
    ├── 519c42823147320df82db2f25dbcf7b8c25cc2a3.nq.gz
    ├── 51ffda5c4e6afddddf044ae9b3762e45dba3f8fa.nq.gz
    ├── 543170a15aaa75bf23bcb11e45441859bdb8d3bf.nq.gz
    ├── 543376fc58251392e085b1edb3fab506ca0c05b4.nq.gz
    ├── 56b0517afbc840f2b358678580f21c60338c7512.nq.gz
    ├── 57ab55ef2fc068ead39cfc59a676de247580402b.nq.gz
    ├── 57c127660964c63b9f3fb1c70ff538f48bf3a8df.nq.gz
    ├── 593b1b7b6910000e3bae830167df2f2c04009320.nq.gz
    ├── 59b5b876413dbceb481fcd1634a7f7a414f60e77.nq.gz
    ├── 59e8eef59b92c785ce503e4942f5a103f74ea1ed.nq.gz
    ├── 5b56e5a4e346ca5b422532f55b5b52156a8b15a9.nq.gz
    ├── 5b81036c7b2ac2650a1e3e83e96256c6d340f6a3.nq.gz
    ├── 5bb03b923be7713d9639cc84da4a5d7681fd345b.nq.gz
    ├── 5c74b309a39718c45d008a0c6eef3090c963f8ed.nq.gz
    ├── 5c8431fa23c53b292b33e2b1063d7ed4194ee534.nq.gz
    ├── 5dd2f468e12bd99e654ebc32be84ddfdb8a0ad43.nq.gz
    ├── 5dd34b870c30d5ee2a2292d42bd46a5e0bab6fcf.nq.gz
    ├── 5e39f3323112224612b6fdc3dce2b337015f71ca.nq.gz
    ├── 5fa0b4f93124e1103f27dd6554d40f91748d0661.nq.gz
    ├── 60ac46605798230dc241ed03a9f7963eb55f6af2.nq.gz
    ├── 612e75d7f8b0ac464d2580276325063e822e6356.nq.gz
    ├── 6180f711f7c4f76689f65bcf33842ee8426c0155.nq.gz
    ├── 6314abb013cc9c1f87fd24afaf9f131b75e97493.nq.gz
    ├── 632cbd36321faeb196c08d5c1319c449902868af.nq.gz
    ├── 648349bcb672fdf584e6d700f50505e559771aec.nq.gz
    ├── 66be26fc0daf5cef1fa36cf6a16d3fa6355f5603.nq.gz
    ├── 66eebbc9a1058ab87162c2a71d236d66accb1a4e.nq.gz
    ├── 670bdaa423ab7d5759780a28bd378eb5de8f7254.nq.gz
    ├── 671fa18c37572d4fc1d64fb885c8234570c700be.nq.gz
    ├── 6754e60fff6c541d1d31817bed44a5e575831c49.nq.gz
    ├── 67ae61508627c1c3beb5ab59e9193875168a2c31.nq.gz
    ├── 67d3056a81d90aca75c21e1c855754ea194ac1e0.nq.gz
    ├── 6804949e56d574619672e6ab7ec0eb7afa00113c.nq.gz
    ├── 687a82d5a8755f0eb701599791e16d84558f936e.nq.gz
    ├── 68d37351abdfcc280a65f941e9a94c2dc745dd8a.nq.gz
    ├── 697a19a1b33cea1325881586217757082035a1d3.nq.gz
    ├── 6a7a8a2e0beda971bd6c53e82dbfbbc4dffab512.nq.gz
    ├── 6c8848bf5aa5a000fa66fc829febd762776b627c.nq.gz
    ├── 6c887be129a82957da82855e5b92ef209e70c7ed.nq.gz
    ├── 6c97a332641379191416e8507be8fdd25114f478.nq.gz
    ├── 6d006468ef0c4067640ca214367f26eb47dee262.nq.gz
    ├── 6d072dc73c169b0936f5b07c8a9e87cfe4edbab6.nq.gz
    ├── 6dbb3ae0efa518e49b95f79726c2d257c0003a84.nq.gz
    ├── 6f480ede6972b1f376b6b6885105a06bd3157cf4.nq.gz
    ├── 6ff546201b89209cd51ea4f8021ab0fd923108d6.nq.gz
    ├── 708eac9d6cdd9f4b7564ded64e2b623fa651fb59.nq.gz
    ├── 709cf06ada1f0fd4d2a8fb535e03e49e967e8f5b.nq.gz
    ├── 7120425db3ed9b7a121f567bab2a455fba08f14d.nq.gz
    ├── 728488a596f3493ccdd9a1f1453a6845e0671aac.nq.gz
    ├── 74795f25553eaf32ca9d6c121547da78e70de951.nq.gz
    ├── 747b6ea547252748861ebb4f405d89f9cbebbaf2.nq.gz
    ├── 758d64dece1d1da68bc21628b9d355a37c6753e4.nq.gz
    ├── 75ca2fbaeeeeeddb326636fc17ea452ce00b6132.nq.gz
    ├── 764d2f6950a746072ad37be0fd94a81a328fe222.nq.gz
    ├── 76f8fac5e9fb75c1783a1e0a0a3f035926d0454a.nq.gz
    ├── 78a66f699fa407f88b663d68de12bd7236ded6da.nq.gz
    ├── 799f1cb802fc48ecbf004ffd8a1b18b3f0e0e422.nq.gz
    ├── 7a882b2e60f8129da05124d671b287845a181e3e.nq.gz
    ├── 7b14ecc40e9489e68a430238603aa8d1980a1b29.nq.gz
    ├── 7c7c30a829193322fcb3b45d49dabf6311bf8850.nq.gz
    ├── 7d47d1b16561c3ee02f6889b9095769eb4d7cc50.nq.gz
    ├── 7d8a71673ff06a0022f9c78e37a9e063cce7472e.nq.gz
    ├── 7dc45a4de6dabdc76f57f2e6f0412426adc2b328.nq.gz
    ├── 7f70d79bbcc10ab1928fe1b70e9b86de29ae2b85.nq.gz
    ├── 804db0f18d0106e6d4f91626e1fd8b6b6f1b4919.nq.gz
    ├── 80f11888203db755d40252b059c1427517d2e383.nq.gz
    ├── 812e1ace0703a0f8e778049b3b47bff3d8916522.nq.gz
    ├── 81d6d51321999bcad33b460138bb0883f6a00bdd.nq.gz
    ├── 829175f87ccecd7a371a20795901904027343db1.nq.gz
    ├── 835455647af12473197ad22cba483bced04cedfa.nq.gz
    ├── 84eee67776eb7f160d0eb1c60965daacb940645e.nq.gz
    ├── 8563de593531b9e59c6a8da317cb5e164145bee4.nq.gz
    ├── 86da66e2f0419e7795a5f410fa7344bc0abcbcff.nq.gz
    ├── 875df7d3b4f96da6ca81db03d0017a862b00f8d6.nq.gz
    ├── 88754b4f93df79a90b814cefaf148d32280d5d03.nq.gz
    ├── 89e4aa80e3b4e9f17ef18be64b150d29e09a1873.nq.gz
    ├── 8f9aca4b149687d19b236a1c2b4d77ad6f4da6ed.nq.gz
    ├── 91f145959f31df90cac700ad7599646c4817b1c1.nq.gz
    ├── 9390a8ee06dd04193ac18bbcf924d0b7c5bbb660.nq.gz
    ├── 93f964b4890a99eb363a8158a2da73e43b95d8d8.nq.gz
    ├── 944a3efe37c786bb84de1fa6669863e754a092ae.nq.gz
    ├── 94ba71e75e738e4368ba5cdcff11661ad8815fa7.nq.gz
    ├── 964b67f20fb10cb9aab068ff92de30e831d15eb8.nq.gz
    ├── 980cb068a75066cdccac276b241b89d569bf6416.nq.gz
    ├── 9927b014bf248edb4ed8699d06f53518b8b47140.nq.gz
    ├── 99a3ef233bfcbab5b475bbb76286911640f90b03.nq.gz
    ├── 9c73c8aa436db494b71c5596bc147f9170ea895f.nq.gz
    ├── 9d3f602558240c937d525bb11e3354d9845425b2.nq.gz
    ├── 9ddffc927d18861b7dff5567e9bee6cc1646c561.nq.gz
    ├── 9df71b05432d7b94b423aab0d24b19f428975055.nq.gz
    ├── 9e3aef67374303569fe4f5f43b60cbc897734d9a.nq.gz
    ├── 9f392577bd930fb59283e6d08a06c0738f9009b2.nq.gz
    ├── 9f6a76f1fb15dff808413581fc587f1024ae2f1f.nq.gz
    ├── 9fe1c3628d72b95c34e525bbedef31a9d0c77105.nq.gz
    ├── a0838a8034aa923d7931ee62f8a0bf8067fe01f5.nq.gz
    ├── a0de6d799a415e0215509d44071f77cb5a061cb1.nq.gz
    ├── a1e7b9cc40f88f02b400e7eb2254742c82dd49ee.nq.gz
    ├── a2901f8d19f3cf5a0b64c09b7987a43e6689bfd2.nq.gz
    ├── a2c6667eb3ca976e9b25e609fd9a9494c0137472.nq.gz
    ├── a2e083de7b33578ef3cbebb152a7a925473b134a.nq.gz
    ├── a423dd12be75a1fe845a36f65a444508c8e24cf0.nq.gz
    ├── a6e4fe97ea8e2eee6272e787dd625f096e07ace0.nq.gz
    ├── ae834bb392ea9bab8ac5307dcf84f8d1b1ff41ab.nq.gz
    ├── b042f861072d81ba1e203e959b4316acf27382ef.nq.gz
    ├── b2f0dbed00120393eb7daffc096dfbb35c1359d5.nq.gz
    ├── b2f65965ea270143c65ccde702c37e693f3bead9.nq.gz
    ├── b3d4a0e06ef13990296ff16c2a41f0ae495136f5.nq.gz
    ├── b66b1b1f9224caf4457bbe3e0389b7949cb4b498.nq.gz
    ├── b717668b54770bd57ce38937296037c74bff8db1.nq.gz
    ├── b7f4e7f26969581b8a3f0d2cd1dc2aaf04dcc1d9.nq.gz
    ├── b81df8793b206a4a3f1ef1db8d3506c983974c4f.nq.gz
    ├── b84cdc7ab611b4f861b60d2a96109cc1c200d534.nq.gz
    ├── b98796c52c617410f052372236abdf494da66d5f.nq.gz
    ├── ba844ede7dd04049875976708c0843a2128a4836.nq.gz
    ├── bab6b24d29e18824b03f12311bb4fbfa94eb7f92.nq.gz
    ├── bd296e8e1671fb23d78fd3e23e127e114220c082.nq.gz
    ├── bdb50bbfd3445a42cc6543a2d4b1407eb74c05af.nq.gz
    ├── bdfecb4624ac024de29080f040893c8ee366df4c.nq.gz
    ├── be42ff5f50fc629115b8f92c3cc8b903962d60c4.nq.gz
    ├── bff15e963ea29fb5020a4510fad318b43d198dc7.nq.gz
    ├── c00daeac64ff8134b0e2583fea13952cd3f4b2f8.nq.gz
    ├── c25384e26a079074097764f7cbb96116fcdc1b5c.nq.gz
    ├── c3dc72399034ca6d0894ff518f40a76eea03730c.nq.gz
    ├── c3ffedf025be4626c87fc8275324bf3d5071bfed.nq.gz
    ├── c6ea31aa654b8f4e51a3bc7458f9158050e16cf1.nq.gz
    └── c91e295fdffa3bc1fff1d01aed35f131be9999c3.nq.gz

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

[nussl/nussl](https://github.com/nussl/nussl)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
