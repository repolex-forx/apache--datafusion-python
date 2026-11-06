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
│   │   └── 878e5d3b8d373bca19671af43e49dfb1890f8da2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 878e5d3b8d373bca19671af43e49dfb1890f8da2
│           └── chunk-001.nq.gz
└── blob
    ├── 0026d61625f281179821fb678e9a712103c32c45.nq.gz
    ├── 008bd43bcfe51a0f0f964f3a03e867a33db4d365.nq.gz
    ├── 00d5946a5ef2de9635006e471a67d2ce42a74be8.nq.gz
    ├── 00efb65559137278a20ff4e3fe0bf91a4d2458dd.nq.gz
    ├── 018c3b95fdf378f9c6db364d81c27be6c5e64891.nq.gz
    ├── 01c38b9f86783827d828d85e83938137d27a278b.nq.gz
    ├── 03ca993e7e4475368bc26cc1f89059f8974bf758.nq.gz
    ├── 0492c6c76c64e98fa84c397c074d148a08d35304.nq.gz
    ├── 0599dd49e70bdf8766e75f7462f18abe07fafa5d.nq.gz
    ├── 05cb6b2082c6575ebac7c37209215b2c3bc2301e.nq.gz
    ├── 0612cc21ef94da3d383501fd5f8d4c3978b81378.nq.gz
    ├── 07005fd0f068bbd9a7abca60383ff9ae1fcbd7d5.nq.gz
    ├── 07b912a8ba68c2c9aa68b3effdcee4d5cb1b4d2b.nq.gz
    ├── 087b276727a3b961e7adddd7b30d970d5243267e.nq.gz
    ├── 089cb9a97cdc17dd7d38381c97b2b562bc694817.nq.gz
    ├── 08dbc4400ffed3bb03cf4431cf3ebbb67cf229fb.nq.gz
    ├── 08f4f054d376e0be8666ce51e1f9e2b32ee76ac7.nq.gz
    ├── 0944881bbb46565f2766ad9883f502aebf28c97c.nq.gz
    ├── 098b4f3b386ba879bd74cd26ddb5e3a3cfca3f1f.nq.gz
    ├── 09d6a7eb7fc990fff3b526ab5d8994c699a3f66f.nq.gz
    ├── 0aa045c7922630f73243f09dc64a53ce86c4c8c0.nq.gz
    ├── 0b198a1911171352a98789c05008a1ae639229fe.nq.gz
    ├── 0b52c4e098b54bb66586b7b2e95c2764529a2072.nq.gz
    ├── 0b973de9811f2dfc5c478b431af040962536e9cd.nq.gz
    ├── 0c0f1a5757efa7cfd4f137c76a450a46ac541803.nq.gz
    ├── 0c80d31aeb7223d288413721e122c7cdfb827b35.nq.gz
    ├── 0c941063687e25f3dae34d7bd100cd79c9b924ed.nq.gz
    ├── 0d0c51f13019406271d759914e30a388f98ef787.nq.gz
    ├── 0d25c8847bd930b7e969eb2cbf68edb177a671eb.nq.gz
    ├── 0d86680e8ce09cbf3796b9556dd8680489453781.nq.gz
    ├── 0e073185ebf982a47510cc2fed047461ddb342d6.nq.gz
    ├── 0e6571a1db4a18522f14727b971ef7beb56679f0.nq.gz
    ├── 0f2e4b824d051db683af85f7adf2b8092b7daede.nq.gz
    ├── 105f1632ddb33932e82435e1cb8bc9f3d495a20c.nq.gz
    ├── 1141dc0923fcc66a405c042abfb9f9470562748c.nq.gz
    ├── 11961521f4c258370b097fd8d8bc772a19d1bdb8.nq.gz
    ├── 11d8f4fcd3966408b3260d72dee572ca309e0c26.nq.gz
    ├── 12ab0a3c3b530ce10da4963701f89f19a7a66e11.nq.gz
    ├── 12fc43bdcc7da52f52b9a6574d95c3306f1955bb.nq.gz
    ├── 137765fe12fdcb3987ce9fbb900022cb2088641d.nq.gz
    ├── 139c300a2aefa67d06156ab34d88c55a3c19e631.nq.gz
    ├── 13a83393a9124bf6ec36540556b4808abd47e206.nq.gz
    ├── 13e98a3b353900eb86e0a1f62c67042dda1d6647.nq.gz
    ├── 1401a493871f1206787122fba675e291ce5016db.nq.gz
    ├── 145dd6f102d675423ebfda55c9a2f2166c9cbb6e.nq.gz
    ├── 156d3bcc246cf8a510b5c8b2bc450b30dc1030c6.nq.gz
    ├── 1604399278fcbd83255eafa111b7582d421ca07e.nq.gz
    ├── 161f2e1e4b190998ff3f17b84dcc0f256a8e9bb4.nq.gz
    ├── 1670e2bd0c82ad601933ff23b5de51796fde0584.nq.gz
    ├── 16ab17f1391ea89141d2467811cb3a06b53c0ce4.nq.gz
    ├── 18b90943fe825df4d8d29b9710b60fd6dea65cbf.nq.gz
    ├── 18f96da97023b25dc1e0f3f8cee29a03674d38e6.nq.gz
    ├── 1a91a04dfb455f0187586a43d9f0c02a0de1af4a.nq.gz
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
    ├── 1ef4406f7e459140e3cd91768582cf41402158dd.nq.gz
    ├── 1f40bbdad710a5ff0c76d259fdd7aed7d1703b68.nq.gz
    ├── 1fe5f2c7fb9a3ba7ab1e7e295a0c8abd04645065.nq.gz
    ├── 2057ec410485caf64d8edee96d597812623288fb.nq.gz
    ├── 21bfb6e35b616a692c63893c756fc81fb85f7d9f.nq.gz
    ├── 23132d60dcfaf152f37ef26163f279fd5b2f55d1.nq.gz
    ├── 2326ba7057e5c195d760eec78ccf579124a0617f.nq.gz
    ├── 23467ed4c6d2c0ec8bc8c1aeafe3572a127739b9.nq.gz
    ├── 23570ff702ad292ae10f6ddce888dc9ebaf29ac3.nq.gz
    ├── 24c2bb8176a01d04e7477c22439b93658b9183fd.nq.gz
    ├── 24d52792132746075b63640892c14bb95a3b6250.nq.gz
    ├── 24d56ed90fb436491b7a11725bca7b21b85e4066.nq.gz
    ├── 252defc24adadbbb8cce3b802b3a4126791206a7.nq.gz
    ├── 25f75d1f874ecb76b9cdd1958383776c8176532b.nq.gz
    ├── 263f034b8a75a4d3d4c265c33554cb22e0435f2a.nq.gz
    ├── 26ed7281d385b8e5b05632df527abaec062533a8.nq.gz
    ├── 274f2a9b1a63d19ec164d1ec5e5be26f8794ece0.nq.gz
    ├── 2956ad64c0d58a0111c4043fb13ed3e691549837.nq.gz
    ├── 2a3466eec7571631d0d541970b87deae2eafa27a.nq.gz
    ├── 2a577033825325664d500efcdcac8fd2979494b9.nq.gz
    ├── 2b82d1bac48d78a7c970f90a77317f59ae19bd48.nq.gz
    ├── 2c1d217f8643208cb943e92071d2e012be02c8d1.nq.gz
    ├── 2d3bc4b760f8b185250b8b54b2d79d4ec8e897e9.nq.gz
    ├── 2d867f29da5f8a982f819b41aa3ecefb2df9b0e6.nq.gz
    ├── 2df549de25f6805a1e150a8efe45876e31692025.nq.gz
    ├── 2f0315c40076d3910ca01ce3ccc84aa6fb811faf.nq.gz
    ├── 2f0a0b67d0e06127187410b395fca7bbb987630f.nq.gz
    ├── 3022a6db8446a0c919425ebe475bdb5d5169f427.nq.gz
    ├── 3047ea39efbdc3abc0ff1a24a7e9bebacbaf9ccf.nq.gz
    ├── 30a2d5e4f098b91e1001f901f68aaf98094e563f.nq.gz
    ├── 31fcdbe0147af87d35b3ffb4fafbae0a96166ea1.nq.gz
    ├── 33338bf54f1789894886973570e6c0e87c056053.nq.gz
    ├── 34a4b6bf3127c19b97684af3778ae454701ac47e.nq.gz
    ├── 34f7bde1b68c8d8c01938e6f810d79bb2a257ec9.nq.gz
    ├── 35268e3a9e98c906e26fc715a65ea1a7f329a07f.nq.gz
    ├── 36a6087d9b012fa807b85462acf6eac93d5e6ae7.nq.gz
    ├── 3711427de1c1d78a3588e56e8add2768950a8061.nq.gz
    ├── 3763c7cb88a3bb7268163926169d52db14644b63.nq.gz
    ├── 37be0bc9d01ef0d23708993e75bacc87950ff20a.nq.gz
    ├── 37c0b93f6e81be641911b2b85c9d78887a7df0e1.nq.gz
    ├── 384ef92109f6976115d72091bdfbe2e68b79a97f.nq.gz
    ├── 391c94dbce252d0a4c2a33033550f0ac15039da9.nq.gz
    ├── 3968f0d249c836a713be153309fa8f0475af778e.nq.gz
    ├── 3a77e08a31f0d5dfb0c2de54c80ccdbc623c6858.nq.gz
    ├── 3b16180bb4c2583c4bb753925fe3ad360f29eae5.nq.gz
    ├── 3b8331b4b72abaa102da2c469a7a412bdfa3085e.nq.gz
    ├── 3b9ff84ff9e1b79f18ce57a1812afd917af6c184.nq.gz
    ├── 3be296c816b7b8d9b07f744a3eac1f7268632089.nq.gz
    ├── 3cc9fbd5ab4850f7cfda5fdb71db153151df9b51.nq.gz
    ├── 3d6e51cfe016dfca994cbdebc8c15660344c57a5.nq.gz
    ├── 3e27a852d0a8b3e139ddc3e17d55d8a2d3f1793a.nq.gz
    ├── 3e57680995276df33e85234f4783ea143f3c8314.nq.gz
    ├── 3f7310ba755fdecaf1ad368b25722f95e6943363.nq.gz
    ├── 3f848bb475f23a33ce37bee616dac43937a53c09.nq.gz
    ├── 4058e8a6e8322be24a3a3cbc7a68aa57cc0a8028.nq.gz
    ├── 411e602919df88ca161e4dad7edf17337cc61885.nq.gz
    ├── 41cab515fff93fd8e2142ad76e050bbee4c7449f.nq.gz
    ├── 41e0dbc4cd8fe87086d04d71005486c2adab0ab0.nq.gz
    ├── 42d104c0ca872752d4132352d7deb35e19a16f44.nq.gz
    ├── 42e3970fb63e635d5b11fc81937a1435e6d24219.nq.gz
    ├── 437deb16574ad4913879de0b5d6123ed5a962c92.nq.gz
    ├── 4426bd245c8ba85c58e3bbe87bf6b33bb01135ec.nq.gz
    ├── 4471c6d1518a43a6d8d80759fd2e994864be4945.nq.gz
    ├── 45787f98f162120f257e82133dd638960ccc28a3.nq.gz
    ├── 45df4c6cec84cd1fa8b4e66672473a9c351f2b6f.nq.gz
    ├── 4663f61481be9eda110cffe979a6d508320daa4f.nq.gz
    ├── 46ce551d24d916b53c17b413823864af3cf361d1.nq.gz
    ├── 46ec5d2394e7c556f9f8342538e7ef97ff35603f.nq.gz
    ├── 47dc3e3d863cfb5727b87d785d09abf9743c0a72.nq.gz
    ├── 484d0c0592712aa194ace8b724c588e55f5bf04d.nq.gz
    ├── 4878d8b0e106f29b3f2c5a37c8388525e5b97e87.nq.gz
    ├── 487b9fbb90b88431c06b03d1d65f08da2b9b788d.nq.gz
    ├── 488d9a11e28fa47948a056404d8c64103a41a539.nq.gz
    ├── 492d57643ddd6b55dff310b0027ac8083b25d39e.nq.gz
    ├── 49ebae372b387d3789b8bd0d63c201c3074d2ae0.nq.gz
    ├── 4f00449d87d05caad30ec8b12018eff2113263f4.nq.gz
    ├── 4f04967f25f48bb2c266e843c449ce5a36acaaf2.nq.gz
    ├── 4f1d41c6b0b2fdcc39a07329672574387f92fbae.nq.gz
    ├── 4f81e569cdbb2c44a9992fe09ede25ca07c8d14f.nq.gz
    ├── 4f9c3c5164f0481661ca448240fef39974ab9359.nq.gz
    ├── 4feaac0281e30ef869e30f2c37b3ba26d66ded7a.nq.gz
    ├── 502f1c2a1b03190454703efb6c48e3c17f72f15c.nq.gz
    ├── 5043eeb51c70bdda488c4f3c8d46e58fde6b87f0.nq.gz
    ├── 5142b918e9e61105f0938e0dd90061b7623f4acf.nq.gz
    ├── 51ea8fa4fb195e1105d8cee0cb1c1d1926420c58.nq.gz
    ├── 52a2da00bf0f45ba237094ac5e466e6dc252a50a.nq.gz
    ├── 5331666954e4ca5cb0805edf309b691971405e74.nq.gz
    ├── 5406678241aeb10bc6956680a112c095e2bba68f.nq.gz
    ├── 542b36ea35df46bf39dc89b57b035fbfe2cc527d.nq.gz
    ├── 549257b8673bf40df2d0041d8c92529d3863a2c2.nq.gz
    ├── 5600dab98b550b9fffd76416dec76e6d11883ce7.nq.gz
    ├── 5639a821f5b980ab2e424577508ff235595c2509.nq.gz
    ├── 5654547aca5021ef9bad6605e81b1288536b2a38.nq.gz
    ├── 5660489d4e69f9fc79d13c99c9139b911728f212.nq.gz
    ├── 57d22bd31029f1eae623047300b513a2f260b7dd.nq.gz
    ├── 58776d36960c4a46b4960550944e35f569354271.nq.gz
    ├── 5967d181e20c4822b343e7951f618a59d206f4b3.nq.gz
    ├── 597ce059ddc771a47baee51c7a8750ea98d26bf0.nq.gz
    ├── 5aa1e4e9cea86f7279333b1b5d41a15022084a72.nq.gz
    ├── 5af4aafeb1464c968aecb8ce027d7c175cbfbe7e.nq.gz
    ├── 5aff70059f6506e045848bfa9c040a14e6ed2546.nq.gz
    ├── 5b31f77080093ccd115a6dca74acce705e01a458.nq.gz
    ├── 5ba64052aa0d01a8cd1ad1d736b083606bc9f39a.nq.gz
    ├── 5bb16563be824abfad5c1f9cb58a0013e0c72a2c.nq.gz
    ├── 5dac463df3458187cb832a184c96b8b7d1683607.nq.gz
    ├── 5e4e3800121866117bc494b55c84053e654591b0.nq.gz
    ├── 5f3177b3d06d5b7f6d00b5ec29a034e48f1e9521.nq.gz
    ├── 5f9bd11e884cdb7af0c48310aeccb23389be6247.nq.gz
    ├── 614d823279a7151e6945479ccd75ce4630a308b0.nq.gz
    ├── 618439d1af69be30e5529151037f84f23f463855.nq.gz
    ├── 622858913a7fb115b33f4858cef22dbaa377854f.nq.gz
    ├── 6298526f5a079d0ffde94b123067e706b66eec12.nq.gz
    ├── 6353ef8cc0f31e6c319aafb093999af1e8b667ab.nq.gz
    ├── 645ded188b370746bd220b49a8b17ee629adb488.nq.gz
    ├── 64be19f63b71395baa226122e7bea2fb706cefac.nq.gz
    ├── 65ea49b04686351727c40c340f59be4d436f593c.nq.gz
    ├── 6655edb0ad452df88975d0a6f355ba80e2b29d9d.nq.gz
    ├── 67c0b245a5dbea6f7bcf928d228f76482ad93bba.nq.gz
    ├── 6838a116065db23b80a5170eb8251080ebed0e70.nq.gz
    ├── 687f946760b059a463901537403ed81a1adfab69.nq.gz
    ├── 68c2a17fef33e6c5857206eac6f60e2f23cc76d4.nq.gz
    ├── 68cc32cb739b7d8dd29e96b4cccff44cfa827ecd.nq.gz
    ├── 68f8057af46557bc41af640e96019853b3f9cf89.nq.gz
    ├── 6927632b965d70b579de5749cb47e8f66a2453a5.nq.gz
    ├── 69771b8be1feb6c5a5d467285c8e3e8c1922f22a.nq.gz
    ├── 6ab83ac0669e5828a262d6fb776925cec2133d19.nq.gz
    ├── 6b6037695ac8a1df64ca9072af6b7e3dacc689ae.nq.gz
    ├── 6ba0ece995a3c2fc090bdccfe829e516b64a358b.nq.gz
    ├── 6bd88321cd4aa012ec71799859aa02d483753b7d.nq.gz
    ├── 6dae6bc626f2969aa5ed9b7cfb43a390ed0e2a52.nq.gz
    ├── 6e204b3f5f220bcbe54f4cf829434cf5b71c8703.nq.gz
    ├── 6e36ad61652bb5bf9ef8d575ce4b9aad6d5e105a.nq.gz
    ├── 6e8a53b6f06b5aead7431535cfe437fa191b7edd.nq.gz
    ├── 6f11c1383ef3150e3481a39e0922da77f75f9ac2.nq.gz
    └── 6f84b876efe7319c082ce28010c66e625fc4706b.nq.gz

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

[apache/datafusion-python](https://github.com/apache/datafusion-python)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
