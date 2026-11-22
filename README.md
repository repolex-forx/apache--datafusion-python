# Repolex Knowledge Graph of apache/datafusion-python

RDF knowledge graph data for [apache/datafusion-python](https://github.com/apache/datafusion-python), parsed by [repolex](https://repolex.ai).

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
rlex download apache/datafusion-python
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 878e5d3b8d373bca19671af43e49dfb1890f8da2
│   │   │   └── chunk-001.nq.gz
│   │   └── aa88d6540ca0b037347b959788ea32700509b98a
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── aa88d6540ca0b037347b959788ea32700509b98a.nq.gz
│   └── repolex
│       ├── 878e5d3b8d373bca19671af43e49dfb1890f8da2
│       │   └── chunk-001.nq.gz
│       └── aa88d6540ca0b037347b959788ea32700509b98a
│           └── chunk-001.nq.gz
└── blob
    ├── 0026d61625f281179821fb678e9a712103c32c45.nq.gz
    ├── 005d8b80a0fd4608e42ff459cdd7e7061a347b29.nq.gz
    ├── 008bd43bcfe51a0f0f964f3a03e867a33db4d365.nq.gz
    ├── 00d5946a5ef2de9635006e471a67d2ce42a74be8.nq.gz
    ├── 00efb65559137278a20ff4e3fe0bf91a4d2458dd.nq.gz
    ├── 01813b0320e5a3b7c59dc71edc1507d93315f0df.nq.gz
    ├── 018c3b95fdf378f9c6db364d81c27be6c5e64891.nq.gz
    ├── 01c38b9f86783827d828d85e83938137d27a278b.nq.gz
    ├── 03ca993e7e4475368bc26cc1f89059f8974bf758.nq.gz
    ├── 0492c6c76c64e98fa84c397c074d148a08d35304.nq.gz
    ├── 0599dd49e70bdf8766e75f7462f18abe07fafa5d.nq.gz
    ├── 05cb6b2082c6575ebac7c37209215b2c3bc2301e.nq.gz
    ├── 05ec8dc22de805c4c51e5df1cab6f1851fd73bba.nq.gz
    ├── 05f9249b02573fced766deabc1fe599b4f6cef56.nq.gz
    ├── 0612cc21ef94da3d383501fd5f8d4c3978b81378.nq.gz
    ├── 07005fd0f068bbd9a7abca60383ff9ae1fcbd7d5.nq.gz
    ├── 070d157835c4e9d71e29e09937e34b77537eec42.nq.gz
    ├── 07b912a8ba68c2c9aa68b3effdcee4d5cb1b4d2b.nq.gz
    ├── 081366b20220bb0fbcda5aa1afc1684369590460.nq.gz
    ├── 083bcbbd2c333f56d581fadc9143f134db5c36e5.nq.gz
    ├── 087b276727a3b961e7adddd7b30d970d5243267e.nq.gz
    ├── 089cb9a97cdc17dd7d38381c97b2b562bc694817.nq.gz
    ├── 08dbc4400ffed3bb03cf4431cf3ebbb67cf229fb.nq.gz
    ├── 08f494dee04b3d863f6035812d6d1467aad73ba4.nq.gz
    ├── 08f4f054d376e0be8666ce51e1f9e2b32ee76ac7.nq.gz
    ├── 091dcbc1808c8bb556863102a3879dd6ceb3afaa.nq.gz
    ├── 0944881bbb46565f2766ad9883f502aebf28c97c.nq.gz
    ├── 098b4f3b386ba879bd74cd26ddb5e3a3cfca3f1f.nq.gz
    ├── 09d6a7eb7fc990fff3b526ab5d8994c699a3f66f.nq.gz
    ├── 0aa045c7922630f73243f09dc64a53ce86c4c8c0.nq.gz
    ├── 0b198a1911171352a98789c05008a1ae639229fe.nq.gz
    ├── 0b3cc4b2b42c0f00da870dcdde85d1299d5f0929.nq.gz
    ├── 0b52c4e098b54bb66586b7b2e95c2764529a2072.nq.gz
    ├── 0b7bebcb3704c261c16a36917ae6cc17d4d1c979.nq.gz
    ├── 0b874e37d5a178edd1c827349cf27d68b56dfea2.nq.gz
    ├── 0b973de9811f2dfc5c478b431af040962536e9cd.nq.gz
    ├── 0c0f1a5757efa7cfd4f137c76a450a46ac541803.nq.gz
    ├── 0c80d31aeb7223d288413721e122c7cdfb827b35.nq.gz
    ├── 0c941063687e25f3dae34d7bd100cd79c9b924ed.nq.gz
    ├── 0c949c34a011525237ce98d8a77c394bbe0287f9.nq.gz
    ├── 0d0c51f13019406271d759914e30a388f98ef787.nq.gz
    ├── 0d25c8847bd930b7e969eb2cbf68edb177a671eb.nq.gz
    ├── 0d86680e8ce09cbf3796b9556dd8680489453781.nq.gz
    ├── 0e073185ebf982a47510cc2fed047461ddb342d6.nq.gz
    ├── 0e1171ea96d99847d7b0e4aeb4dcffd257fc065f.nq.gz
    ├── 0e6571a1db4a18522f14727b971ef7beb56679f0.nq.gz
    ├── 0ef194afeedfd36b4739087bfde1834a7909a570.nq.gz
    ├── 0f2e4b824d051db683af85f7adf2b8092b7daede.nq.gz
    ├── 105f1632ddb33932e82435e1cb8bc9f3d495a20c.nq.gz
    ├── 107dd9370cfb20b7c94af49297f8495ad8a0c9ed.nq.gz
    ├── 10ca1dd125c4c425f25905593bb5986b437c198a.nq.gz
    ├── 1141dc0923fcc66a405c042abfb9f9470562748c.nq.gz
    ├── 11961521f4c258370b097fd8d8bc772a19d1bdb8.nq.gz
    ├── 11d8f4fcd3966408b3260d72dee572ca309e0c26.nq.gz
    ├── 128c3f4c250d35dcb7cbe79f514117ba7ee26113.nq.gz
    ├── 12ab0a3c3b530ce10da4963701f89f19a7a66e11.nq.gz
    ├── 12fc43bdcc7da52f52b9a6574d95c3306f1955bb.nq.gz
    ├── 134d41cb613e9ae8708bafaa2ef1de276abc8beb.nq.gz
    ├── 137765fe12fdcb3987ce9fbb900022cb2088641d.nq.gz
    ├── 139c300a2aefa67d06156ab34d88c55a3c19e631.nq.gz
    ├── 13a83393a9124bf6ec36540556b4808abd47e206.nq.gz
    ├── 13e98a3b353900eb86e0a1f62c67042dda1d6647.nq.gz
    ├── 1401a493871f1206787122fba675e291ce5016db.nq.gz
    ├── 145dd6f102d675423ebfda55c9a2f2166c9cbb6e.nq.gz
    ├── 1505ec3e66c04e4dd5cb8c9914980f1a310c9a09.nq.gz
    ├── 156d3bcc246cf8a510b5c8b2bc450b30dc1030c6.nq.gz
    ├── 1604399278fcbd83255eafa111b7582d421ca07e.nq.gz
    ├── 161f2e1e4b190998ff3f17b84dcc0f256a8e9bb4.nq.gz
    ├── 1670e2bd0c82ad601933ff23b5de51796fde0584.nq.gz
    ├── 16ab17f1391ea89141d2467811cb3a06b53c0ce4.nq.gz
    ├── 16c3ccc2aad12106748d4818e5509bcb7f536217.nq.gz
    ├── 16faaf9d51f62a81b314a044ddb5062a09fb6d33.nq.gz
    ├── 187ea6846c61f92295e4df286946a4b27c17e11e.nq.gz
    ├── 18b90943fe825df4d8d29b9710b60fd6dea65cbf.nq.gz
    ├── 18f96da97023b25dc1e0f3f8cee29a03674d38e6.nq.gz
    ├── 1a91a04dfb455f0187586a43d9f0c02a0de1af4a.nq.gz
    ├── 1aca9ea95ea7fed712b6deb48dc06f51ca61ff3c.nq.gz
    ├── 1b106501164b7a0704efa817d03e14acf77311cf.nq.gz
    ├── 1b2bbfcd98e0675d64dfa184fa7b31f53c8f754d.nq.gz
    ├── 1b44bffacdaf54d3153d1baf86ecc4669ab6952e.nq.gz
    ├── 1b6987e7fee5fe56bd8e9b353843d6905c94d01f.nq.gz
    ├── 1b98fdf9e343064e4a5f67e67d786448a2740460.nq.gz
    ├── 1ba68023245eeb33ef3350611a21f6ad8631e4ad.nq.gz
    ├── 1c08acd1a6e7ec8c8905cdb48646260e2f0ceb04.nq.gz
    ├── 1c4b8db4cecec28d5a2872a9c9f68a52af90de57.nq.gz
    ├── 1d92cc0d4c5861e6dbe790593084a492ddd39b32.nq.gz
    ├── 1d984710c3a053e8b381c9235c92535a24e7f512.nq.gz
    ├── 1d9d7038526aa4baf9fbc1963bef7fae2e72cfca.nq.gz
    ├── 1de5848b16cadb8eec015601d9ef41e0805736c4.nq.gz
    ├── 1dfa0ed2f4bef8404992999e62d763aff1391556.nq.gz
    ├── 1ef4406f7e459140e3cd91768582cf41402158dd.nq.gz
    ├── 1f40bbdad710a5ff0c76d259fdd7aed7d1703b68.nq.gz
    ├── 1fe5f2c7fb9a3ba7ab1e7e295a0c8abd04645065.nq.gz
    ├── 201fa287e405f85933bf17b5b39f2f41c6519d4e.nq.gz
    ├── 2057ec410485caf64d8edee96d597812623288fb.nq.gz
    ├── 21bfb6e35b616a692c63893c756fc81fb85f7d9f.nq.gz
    ├── 22829ab7ce94686a28b2be74d8471735d5036c65.nq.gz
    ├── 23132d60dcfaf152f37ef26163f279fd5b2f55d1.nq.gz
    ├── 2326ba7057e5c195d760eec78ccf579124a0617f.nq.gz
    ├── 23467ed4c6d2c0ec8bc8c1aeafe3572a127739b9.nq.gz
    ├── 23570ff702ad292ae10f6ddce888dc9ebaf29ac3.nq.gz
    ├── 23c066156863330f04f27ffffab066444c03355a.nq.gz
    ├── 24c2bb8176a01d04e7477c22439b93658b9183fd.nq.gz
    ├── 24d52792132746075b63640892c14bb95a3b6250.nq.gz
    ├── 24d56ed90fb436491b7a11725bca7b21b85e4066.nq.gz
    ├── 252defc24adadbbb8cce3b802b3a4126791206a7.nq.gz
    ├── 25a1e76b3d865ec6622c5a070ed4f5aad6f2d9ad.nq.gz
    ├── 25f75d1f874ecb76b9cdd1958383776c8176532b.nq.gz
    ├── 262366a8a7b116171ecfabf38d973fb77f7680d3.nq.gz
    ├── 263f034b8a75a4d3d4c265c33554cb22e0435f2a.nq.gz
    ├── 264cfd342f1631a57e5af0592414390620ee1b0a.nq.gz
    ├── 26ed7281d385b8e5b05632df527abaec062533a8.nq.gz
    ├── 26f1303c480010630ad83b08bc91a1f3785d4579.nq.gz
    ├── 274f2a9b1a63d19ec164d1ec5e5be26f8794ece0.nq.gz
    ├── 275759f685a9eb2964ea1889a62f73159d41a1aa.nq.gz
    ├── 2956ad64c0d58a0111c4043fb13ed3e691549837.nq.gz
    ├── 29e5d9880d8968e75e23344c9fc88809f9603064.nq.gz
    ├── 2a3466eec7571631d0d541970b87deae2eafa27a.nq.gz
    ├── 2a35635c2fcbfe338342281a8fea8786733d4748.nq.gz
    ├── 2a577033825325664d500efcdcac8fd2979494b9.nq.gz
    ├── 2b82d1bac48d78a7c970f90a77317f59ae19bd48.nq.gz
    ├── 2bfce0e2d27b6dc17698af0b8a5430ff6d49149f.nq.gz
    ├── 2c1d217f8643208cb943e92071d2e012be02c8d1.nq.gz
    ├── 2d3bc4b760f8b185250b8b54b2d79d4ec8e897e9.nq.gz
    ├── 2d867f29da5f8a982f819b41aa3ecefb2df9b0e6.nq.gz
    ├── 2df549de25f6805a1e150a8efe45876e31692025.nq.gz
    ├── 2e50ba75eeb10112adcd51f9de82a3512200da89.nq.gz
    ├── 2e6f8116645a4db1e941ac22e90f4107fb855b95.nq.gz
    ├── 2f0315c40076d3910ca01ce3ccc84aa6fb811faf.nq.gz
    ├── 2f0a0b67d0e06127187410b395fca7bbb987630f.nq.gz
    ├── 3000794813d67c3684435967f240b06cb4d2493a.nq.gz
    ├── 3022a6db8446a0c919425ebe475bdb5d5169f427.nq.gz
    ├── 3047ea39efbdc3abc0ff1a24a7e9bebacbaf9ccf.nq.gz
    ├── 30a2d5e4f098b91e1001f901f68aaf98094e563f.nq.gz
    ├── 31fcdbe0147af87d35b3ffb4fafbae0a96166ea1.nq.gz
    ├── 33338bf54f1789894886973570e6c0e87c056053.nq.gz
    ├── 33c2b274c7a93b14cf45901933a1ff1fde992864.nq.gz
    ├── 34a4b6bf3127c19b97684af3778ae454701ac47e.nq.gz
    ├── 34c8c5c9fefa766894d31672f5090e703ed9a760.nq.gz
    ├── 34f7bde1b68c8d8c01938e6f810d79bb2a257ec9.nq.gz
    ├── 35268e3a9e98c906e26fc715a65ea1a7f329a07f.nq.gz
    ├── 35c3fa79b39fc48e89f274f6f595b166a2b0972b.nq.gz
    ├── 36a6087d9b012fa807b85462acf6eac93d5e6ae7.nq.gz
    ├── 3711427de1c1d78a3588e56e8add2768950a8061.nq.gz
    ├── 3763c7cb88a3bb7268163926169d52db14644b63.nq.gz
    ├── 37be0bc9d01ef0d23708993e75bacc87950ff20a.nq.gz
    ├── 37c0b93f6e81be641911b2b85c9d78887a7df0e1.nq.gz
    ├── 384ef92109f6976115d72091bdfbe2e68b79a97f.nq.gz
    ├── 39030db7fead40a44752d87641143e8461eb9862.nq.gz
    ├── 391c94dbce252d0a4c2a33033550f0ac15039da9.nq.gz
    ├── 392bfcb9e4960f248b4e2a2ea5b1d9d3e3c7a4a7.nq.gz
    ├── 3968f0d249c836a713be153309fa8f0475af778e.nq.gz
    ├── 396acbe978f23f221e259448899eb361f5cc26ee.nq.gz
    ├── 39e48f7c39b6045e7298c8fa29ac06d10dae04c9.nq.gz
    ├── 3a77e08a31f0d5dfb0c2de54c80ccdbc623c6858.nq.gz
    ├── 3b16180bb4c2583c4bb753925fe3ad360f29eae5.nq.gz
    ├── 3b8331b4b72abaa102da2c469a7a412bdfa3085e.nq.gz
    ├── 3b9ff84ff9e1b79f18ce57a1812afd917af6c184.nq.gz
    ├── 3be296c816b7b8d9b07f744a3eac1f7268632089.nq.gz
    ├── 3cc9fbd5ab4850f7cfda5fdb71db153151df9b51.nq.gz
    ├── 3d6e51cfe016dfca994cbdebc8c15660344c57a5.nq.gz
    ├── 3d8c3c1c73551d061dc8df97a801d9ce6d503fde.nq.gz
    ├── 3e27a852d0a8b3e139ddc3e17d55d8a2d3f1793a.nq.gz
    ├── 3e57680995276df33e85234f4783ea143f3c8314.nq.gz
    ├── 3e8e229f9db908a2bbcef63825a33732877dd3f3.nq.gz
    ├── 3eae866bc160f728f9397d82631819795ad13ba5.nq.gz
    ├── 3eec936c25cdda273fac89dd87b6f6018380500f.nq.gz
    ├── 3f5c575252b40af0b0c49a34f1a3c92c27c71651.nq.gz
    ├── 3f7310ba755fdecaf1ad368b25722f95e6943363.nq.gz
    ├── 3f848bb475f23a33ce37bee616dac43937a53c09.nq.gz
    ├── 3f97f00dc903f0086ff5f92ae9d410c1d4b5e9f9.nq.gz
    ├── 400246a8228fe8dbbb80276fb5c87ae2068a7144.nq.gz
    ├── 4058e8a6e8322be24a3a3cbc7a68aa57cc0a8028.nq.gz
    ├── 411e602919df88ca161e4dad7edf17337cc61885.nq.gz
    ├── 41cab515fff93fd8e2142ad76e050bbee4c7449f.nq.gz
    ├── 41e0dbc4cd8fe87086d04d71005486c2adab0ab0.nq.gz
    ├── 426338aea73a862dafaec20ccff2c4e1dac2b081.nq.gz
    ├── 42d104c0ca872752d4132352d7deb35e19a16f44.nq.gz
    ├── 42e3970fb63e635d5b11fc81937a1435e6d24219.nq.gz
    ├── 434fd9b57aef1b47c7ed2b2c43459c0cfb04edf1.nq.gz
    ├── 437deb16574ad4913879de0b5d6123ed5a962c92.nq.gz
    ├── 43aa327d4151be14ddd8404239cf42836202d315.nq.gz
    ├── 4426bd245c8ba85c58e3bbe87bf6b33bb01135ec.nq.gz
    ├── 4471c6d1518a43a6d8d80759fd2e994864be4945.nq.gz
    ├── 453ff6f4ff1da37a1a501eb78c154e27b88efe42.nq.gz
    ├── 45787f98f162120f257e82133dd638960ccc28a3.nq.gz
    ├── 45df4c6cec84cd1fa8b4e66672473a9c351f2b6f.nq.gz
    ├── 4663f61481be9eda110cffe979a6d508320daa4f.nq.gz
    ├── 46ce551d24d916b53c17b413823864af3cf361d1.nq.gz
    ├── 46ec5d2394e7c556f9f8342538e7ef97ff35603f.nq.gz
    ├── 47dc3e3d863cfb5727b87d785d09abf9743c0a72.nq.gz
    ├── 484d0c0592712aa194ace8b724c588e55f5bf04d.nq.gz
    ├── 4878d8b0e106f29b3f2c5a37c8388525e5b97e87.nq.gz
    ├── 487b9fbb90b88431c06b03d1d65f08da2b9b788d.nq.gz
    └── 488d9a11e28fa47948a056404d8c64103a41a539.nq.gz

10 directories, 200 files
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

[apache/datafusion-python](https://github.com/apache/datafusion-python)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
