# Repolex Knowledge Graph of glue-viz/glue-jupyter

RDF knowledge graph data for [glue-viz/glue-jupyter](https://github.com/glue-viz/glue-jupyter), parsed by [repolex](https://repolex.ai).

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
rlex download glue-viz/glue-jupyter
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f71a1589bdb3e5d00780938aafacc61e5ecf4bb0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f71a1589bdb3e5d00780938aafacc61e5ecf4bb0
│           └── chunk-001.nq.gz
├── blob
│   ├── 03341bfa43d688d08286a2fbc1a68a42f66241c5.nq.gz
│   ├── 04678a1d46bd7704080e3e9d51d6d445839e0be9.nq.gz
│   ├── 073c6ab7b72d1727af2382c85c2c548f84cac8d5.nq.gz
│   ├── 08a76f67f5ec34a1b781768a8f1b04f1f6fc6fe8.nq.gz
│   ├── 0913c55039f652d2347acf5fc8c24e16bd49ed1e.nq.gz
│   ├── 09ee2e3221eace262425a5c8bc7871c5102e608b.nq.gz
│   ├── 0d1ff893c46e11edb1de8b9021dd7e3fa9ea6df2.nq.gz
│   ├── 0d334338fec39d0ba5be825b93243f730de4f53a.nq.gz
│   ├── 13aa25e534c4b4fa2537ad3edbe8f0a6d1dba130.nq.gz
│   ├── 13d4bb7d3191060d6cb327b91ff900b264159933.nq.gz
│   ├── 14f156445e49f612229ba4488ae435fdbdb833cc.nq.gz
│   ├── 15203daf3c7f1969b8184bbf2de8c9cf0b7993ed.nq.gz
│   ├── 17512b8e9ad45f7e459403e17035ad7b3801bb72.nq.gz
│   ├── 17d975668ff5e2d985db999e45d26a9f14c30efb.nq.gz
│   ├── 1a1198fd071705283a021286eecd12509ce80e60.nq.gz
│   ├── 1b3377524717876081779b92ee58f12e564a7e57.nq.gz
│   ├── 1c1ed22df7a6c90bab947eadeca5b62e7308eae7.nq.gz
│   ├── 1e025c53392e95949f2adec336c369a4d7e00afc.nq.gz
│   ├── 2148fc131de32146bd27aaadf9bdbdbe84050289.nq.gz
│   ├── 2158c7e9d595cf966a447c9321dfdc57c51bb2ee.nq.gz
│   ├── 22427250aa9f97c6eae7d230d5c02473a8ea7454.nq.gz
│   ├── 231eea844ff9872ec8c3bee0ad5daf8a7b64a803.nq.gz
│   ├── 2519ef64de74f89cec860698e653db142a84db4b.nq.gz
│   ├── 2844ec32b849e01d5831b2f683a9bd557b451695.nq.gz
│   ├── 298d7f159a7f86779442f4af12b1318ac13c89ef.nq.gz
│   ├── 29e4fd024316bcd93c5d58fc614e1327acd18558.nq.gz
│   ├── 2a817fe6da5698dc42c0d5c98a721b371045dd30.nq.gz
│   ├── 2aab9df2587df283c2958cdc6ca3b32121aaf512.nq.gz
│   ├── 2ddc446ead32aee8ec177d69280e9ddbfeb59659.nq.gz
│   ├── 2f0a06ca5f39c04f3c8a9013846760bf627fcd58.nq.gz
│   ├── 308c1401fb5eabd466ccf9946cfda731ce712407.nq.gz
│   ├── 30a53b85c2920f8545128b0ad1151ce1906a46e8.nq.gz
│   ├── 30cff0fb55d3334fdad95e059a0ae094ddac9323.nq.gz
│   ├── 32c3132c8995e0705c7542d939d8b0a51f99a852.nq.gz
│   ├── 3306bb74d5b48067e1d6f14796c01960e7f1c1a2.nq.gz
│   ├── 350f5e01516a67b7465359a325fd9e472f964855.nq.gz
│   ├── 35549df2211caf03d65d17f3941e7c8e6eb2a973.nq.gz
│   ├── 3ac403bb73feb5f9ad7f3cdce0023ddcee1fb1c8.nq.gz
│   ├── 3b2bf9d822191f9ac8b7ada7951ea4905ee40ced.nq.gz
│   ├── 3c07f306a4256d0f7271e8d0efa64696f9fea0b6.nq.gz
│   ├── 3eb3ae81e1a2e3ee174a795b9dd1e25fb5ecd54b.nq.gz
│   ├── 3f2f2da3451ad414514bc8a4e9c77780eeb687ba.nq.gz
│   ├── 405e23cb241b960be4f83cb0950a7d0eb230734c.nq.gz
│   ├── 416e091dc568a2240a66e1d7ed6b4e5a3105063a.nq.gz
│   ├── 437772817e099eb18795cc8b622ea72cbdc47f5f.nq.gz
│   ├── 45f71307d003019082f9069a4c446c2b5bb85d07.nq.gz
│   ├── 4718d08a858c6770a39300ce743a99938c70e243.nq.gz
│   ├── 49aa5096506b27c24c1bda906684506b0bd9ed14.nq.gz
│   ├── 4ab3cf340b36c9b98794af6dc1fc7b7259ab8f90.nq.gz
│   ├── 4f1e887f48806bf2e0c37e3b7fea8f55183712d0.nq.gz
│   ├── 53136ac41404772769b5c7d9c0d8f2d6b8fbb913.nq.gz
│   ├── 564d75f5dfdc5e40b99b98e00f8324e2c9ae9cf8.nq.gz
│   ├── 57727955bc2edd8856e9dd9b4c2e3924cfaf0c9c.nq.gz
│   ├── 590d9f294355107908a3ed759d5a52625eca7fa8.nq.gz
│   ├── 591545ec42a2ade8b43871f855a7e7546f03b0a9.nq.gz
│   ├── 5de76062c08ba9b7fa042ae8f5fc218e8b2483a0.nq.gz
│   ├── 5e05c059003ca2bcabca5aabb7349004c3e15a8a.nq.gz
│   ├── 5e4e1c474cad1c9884ac200894551a9840653107.nq.gz
│   ├── 5f1e1ba03110ac7f1435248c2fc848df6273fe9c.nq.gz
│   ├── 617f9b95a1738274bb7cfa5cf3a92dfd24045f70.nq.gz
│   ├── 67369354906d5c880665968407f7e7adce8ea6cb.nq.gz
│   ├── 678810bc93dca2ff6a51352173690c8b6734833e.nq.gz
│   ├── 6794f4a6676ffcd676175e6d5fad3ab6b050d8df.nq.gz
│   ├── 699ecdb1be648215f6fd15d85df575f813a45c95.nq.gz
│   ├── 6a1f0f7e34838234429838dccb7083a2ede90b15.nq.gz
│   ├── 6d483b4c40a7512213e841dc830dd1536a0b5b82.nq.gz
│   ├── 6d4c431b368b27a4b4288105d88f945f16983f74.nq.gz
│   ├── 70094094100428c63d04212203359cad64eb2b70.nq.gz
│   ├── 7266c704a0d7f05891bad016752dac2ddc1161b6.nq.gz
│   ├── 73de8bfdb3c9578e45951dca92cd2365725aab3d.nq.gz
│   ├── 758519f5a14316964020938df550e16b0b2901f0.nq.gz
│   ├── 77a2638d068f6ad907fab88589de708415469b9c.nq.gz
│   ├── 77d7c4ce6a96c6f3320eaad6ce2bfb47af1adfc2.nq.gz
│   ├── 7814ecdf40d884df85b621331a11c55fb739d677.nq.gz
│   ├── 7817926c68e144c43156408512825ae056161f70.nq.gz
│   ├── 7b462e7e70f0b70eb9c4ecc119015dd1d1e17b56.nq.gz
│   ├── 7ed010175588b14611b0c796576ebe1a48e4b707.nq.gz
│   ├── 81c4fb9b35014644d1412f23f7c634dbcc94b735.nq.gz
│   ├── 828e3db499832df4b1a65bea5db0fcc271d75422.nq.gz
│   ├── 859cd92fa722772333fa364534b7e1dc9e282264.nq.gz
│   ├── 859e5d689b7b0c0b02451ebc83691e0a31646163.nq.gz
│   ├── 87a853d99898dbed9cdcbd569e8079d1e3354940.nq.gz
│   ├── 88a7d3c50b8e194474cdcde6ce6ff7a914a8e4b2.nq.gz
│   ├── 897e5b5d1a02fee22ae4a7ab3f7c4ce2ab03976b.nq.gz
│   ├── 8b838cabcbeabd36edf8996ec386575efbf3b18f.nq.gz
│   ├── 8ecc4f779dc154ac1e4680b3d8f0c3dcc0cfdb47.nq.gz
│   ├── 8eff27c6b366ca10393fc6182bf33d3edf2320dd.nq.gz
│   ├── 90d45723417a4b5f6f10e49076f70a8fc10e3f9f.nq.gz
│   ├── 93dfe92b9c98e009c2f75b6477817411d3a15585.nq.gz
│   ├── 962603bf4274026d55b2f26dba9e0f14daaccd54.nq.gz
│   ├── 98cc24472169f2b7854a9db9dd800af40d3df4db.nq.gz
│   ├── 9909060988000a779f921294f112397071267469.nq.gz
│   ├── 99d48773767dfeca4ba084e05e777e298b1ee081.nq.gz
│   ├── 9a14ebfb9ac3f5260fab80d95442462dd69c8d41.nq.gz
│   ├── 9ad768a34ccf641258bca5f8161221ac934eccba.nq.gz
│   ├── 9c3ec0a2e5fadd7b97f1c0492ed41320d1bd3781.nq.gz
│   ├── 9e0971da481ee5d9a3ce27ac8d108ce9fb21d955.nq.gz
│   ├── a0690d434f897cb2b65e171e72e2c7006c0f1c8c.nq.gz
│   ├── a1d964aabbe20d13684cdda9aa7a0d25b57e9402.nq.gz
│   ├── a450128a3936975b2b6ee53efd0638ad60a538fe.nq.gz
│   ├── a57246adf9e7d43107685f92246b7b4bbc488678.nq.gz
│   ├── a598f42be9d0616b64d9d6b7c430bcf90956e953.nq.gz
│   ├── a5aac5a1f517e5e7d608dec12bc278502115ff71.nq.gz
│   ├── a6711097ee581a6742338bfb94baf955190bb341.nq.gz
│   ├── a749bff4f5c4edb58cb2288c9eaf3c8854a967b5.nq.gz
│   ├── a7e02bd0835843f7211fba376849253b37b66d97.nq.gz
│   ├── a8142f25cd7ae3461d19274e4b9d080db62aa7d2.nq.gz
│   ├── aa79a2d7320a7b7039891f525ed539eeb03984a9.nq.gz
│   ├── ab2478393528effd9178fbf7b5347ad15734311c.nq.gz
│   ├── ad19a274a25c41ca37b40f22f362bc1cbe6283a1.nq.gz
│   ├── ae3d6d023259c5867b74d07b4de3e2560f548bd0.nq.gz
│   ├── aea323582c5aa7fc1ea71df404f651d515fecd3f.nq.gz
│   ├── b0d5c22e4daf0de51c092577c6b61c3ede036dbb.nq.gz
│   ├── b0ef4f6aea7c542dfbf8432cc08699d62cffd696.nq.gz
│   ├── b4347147a941293575317ebeb47dabe98668e2f4.nq.gz
│   ├── b7f8c551b7dc36e9bf692cb6ceb1ef8b67833fe6.nq.gz
│   ├── b8f89320bf1b45321665f27856d70345f68f4aa1.nq.gz
│   ├── ba32827b5e05f33302e7727e5069f6715dcfd5c4.nq.gz
│   ├── ba692e13428d99b95db53e4b57fe55732770da26.nq.gz
│   ├── ba76190d200d0bfea129fa514de2e2f8aa47cf5d.nq.gz
│   ├── bc4c4bf83c863bdc7b8a23ef25caf70203161e8b.nq.gz
│   ├── bd082f70cf05ee6301f42a1078a481fef68f1f95.nq.gz
│   ├── c0e8571798229e5651e594073feeaf004911b38d.nq.gz
│   ├── c244342b091865320fbe799fe1a2245a90b4f9f8.nq.gz
│   ├── c2cef2dbee0e38bd9f2f27383227c69156bc1af0.nq.gz
│   ├── c3df46f18001a17691afe1d6ab979174e4129618.nq.gz
│   ├── c70521cef8d745bbae473921103d5745b639e1c3.nq.gz
│   ├── c750779981ad1c64bfec041fd1d629bae3a7239b.nq.gz
│   ├── c997635b49b4c23480299253ad2d0f9adae6d17f.nq.gz
│   ├── c9a34fc33d221c982fd19add5e4fda2fdc4c2840.nq.gz
│   ├── cb32450a60cc18c8e2ddeb81ca72ff71e6b3e485.nq.gz
│   ├── cc67a70352b060873ed15f5e3bbbe7140b3be98a.nq.gz
│   ├── cc85105bf88630c586ae361a397997794bfee4d3.nq.gz
│   ├── ccf271c6895fdfc5812406fb0c1c564ba0d7c3bb.nq.gz
│   ├── cd4b51f54fae817c0fa74405083679d88db71c7a.nq.gz
│   ├── ce551aa8f6a477729626b5a7343a54f756383706.nq.gz
│   ├── cf07b02eeb5a8c8f4bdc8a40d76042d84c1a5fde.nq.gz
│   ├── cf5baaf1549c49b68291725bd3f177fa05e93f7a.nq.gz
│   ├── d14d5c5283f8c6153e155c811e4ae3ec446a965f.nq.gz
│   ├── d4f39862945e633cd5f85e7929144b665906956d.nq.gz
│   ├── d5cedfbe0cdb77c282b5f0547b121668155ef23d.nq.gz
│   ├── d69413b5c6ed513d42441aac3a00e5c4e6e4b5df.nq.gz
│   ├── d708f8be315cf481ef6d108e39196d906a341e83.nq.gz
│   ├── d824b84ae16cbab74d86786bc5ca6577e55ab936.nq.gz
│   ├── d89bb9dded869d753023c1e89ba37b0cb690fd93.nq.gz
│   ├── d9e31cad5762210b2d42b192ecaff16bd077ad8d.nq.gz
│   ├── db578fb0f2d7ee776168d3020b759b4c2ef261b8.nq.gz
│   ├── dba9a2bad418cf4aa3e60830b68f3712f1fbbe2e.nq.gz
│   ├── ddb4c4782010d011a56730ea833ffd607a0f49e9.nq.gz
│   ├── dfa77b428c59fd6cc6033168b4e84e24c73cd439.nq.gz
│   ├── dff247a6d16f42772a4aabb1ac773adcd5cd1e84.nq.gz
│   ├── e3c5abfa90882c1ad303b5baaea76edc2b670d1f.nq.gz
│   ├── e4be918416202ff8d7d777d8c4d56c874f749466.nq.gz
│   ├── e5ef00f5728a0b76219ec3b1ae35d35953502b73.nq.gz
│   ├── e64f98afc25645f912e357eb4751fe90efeaee36.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e90db35b0bed782b42014ee7c1abe63f314a5730.nq.gz
│   ├── ea2f1f3e18a5820fb0f4421c8c4d60beb01bc1d3.nq.gz
│   ├── eb31d78cbc440fb117b09b9947d49a86cfa22b91.nq.gz
│   ├── ec5cb5fc413ee8d63fa189c865c87ef2742743c1.nq.gz
│   ├── ed819f2efaf781d92e0026c777704a5ec1d4aba1.nq.gz
│   ├── f2efc8a14d124e3a3bb4d0d131356ffd165e20f7.nq.gz
│   └── fd098c8698e555a825b2af6db62fea6af39c6e9e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f71a1589bdb3e5d00780938aafacc61e5ecf4bb0.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 171 files
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

[glue-viz/glue-jupyter](https://github.com/glue-viz/glue-jupyter)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
