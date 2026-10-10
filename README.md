# Repolex Knowledge Graph of psf/advisory-database

RDF knowledge graph data for [psf/advisory-database](https://github.com/psf/advisory-database), parsed by [repolex](https://repolex.ai).

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
rlex download psf/advisory-database
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cf08884a2c39176985d607953b2416e1aad1c8b0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── cf08884a2c39176985d607953b2416e1aad1c8b0
│           └── chunk-001.nq.gz
└── blob
    ├── 0069fe9d1e8af21b4caa1c3f6bdd817a20f0e8ed.nq.gz
    ├── 0099996c4384755d40b1a5e252863ed3dc96e22a.nq.gz
    ├── 00ce560d4315ab7efe266eb12efa5a6faa819b01.nq.gz
    ├── 00f1246e39ca309bc22ea88706f6c60fa1958e03.nq.gz
    ├── 0161bd20d2c002f2759239d50cd4182c43a9c34b.nq.gz
    ├── 027d7b2e82231495a9cb279ec61dd17ef7ec1638.nq.gz
    ├── 04a1ab26b37db90ed32d855239df884379385a73.nq.gz
    ├── 04cd35834d221bfe96dd0e2ada11bd9d4d196816.nq.gz
    ├── 05a87ceedaa61d631e1e318db1a45f3216d75adf.nq.gz
    ├── 07413fcb22dac929826de9ddedb265ffcdcfe8a3.nq.gz
    ├── 0867837644a4a627b2ceca11aa08b86ede15e3b1.nq.gz
    ├── 09bfbc27571986f5999c2df4e4b510c48af0a3d7.nq.gz
    ├── 0a7d326ae655b02bde7b76b739bfa809359c3bc9.nq.gz
    ├── 0cf388c051bc12fdf12fdfed86623a8d3e5f7acd.nq.gz
    ├── 0debb52e5cd870386836db497b2a4aa74dae2611.nq.gz
    ├── 0e7d26ab2dcbec9d9df76c450eb03edb838baba3.nq.gz
    ├── 0f79679a6d465a62d6a0b343561234e4e4d38988.nq.gz
    ├── 10b9494bc14dbf08ad3853a558c77a9f7b527a9f.nq.gz
    ├── 112bea631a2f75301d78657fa26857fa8e3de8dc.nq.gz
    ├── 1145ddc79c7e47caf3aab67d4c2491e3ff4e0cdb.nq.gz
    ├── 114b958573e3e6486af884a9b024d8210afeae9f.nq.gz
    ├── 11f9877b5786e10b9f1b5eb0f9127f9a6d9c440c.nq.gz
    ├── 1201d9c68f1fd8c161fb9d70635eec7b49ad7a86.nq.gz
    ├── 1275051db014422eb7cecf5ba07f619f70b2154f.nq.gz
    ├── 128f8c25a69f1e20c6f5df43fca300706793d229.nq.gz
    ├── 13da6b68a9ea078dbf4c5a77fb23d5f9c518e3f9.nq.gz
    ├── 15a8db0462c36029d2af0c1f2a92d1f4324e12ed.nq.gz
    ├── 15d9d4c6b71e4851f7d5300476f5b7af9aa77026.nq.gz
    ├── 167e1e097d73cbbdbf0748f8b2b380c09ab209a7.nq.gz
    ├── 1717fbfb49affcad9a461c944f1baa7351bace71.nq.gz
    ├── 186eed3ff88069e7d9dd427dba32f8d7bb430302.nq.gz
    ├── 19047865021095284dc7fdccedc8a92b8aee1703.nq.gz
    ├── 1a05b71e27e1a14e0d004df191997b19eb971a8d.nq.gz
    ├── 1a8c10c7f48078390095733f1f24727eef41c201.nq.gz
    ├── 1b344281dcbfc9217361e0a4d3bba2c7326192fb.nq.gz
    ├── 1dc329672581fe54ffccff6dd8a027372118d091.nq.gz
    ├── 1f19385bf582e8e24f70f0ae1f5c0d020ff87b34.nq.gz
    ├── 1fd38ca01261298f0ecfa991efe1e8d08af50ee0.nq.gz
    ├── 20035d5c7c1a45b59210bca70dbc0dd1048f91f0.nq.gz
    ├── 207c2892a50ba3d5f7a4f8c08af1a540e4b8888f.nq.gz
    ├── 20a87d3b66165099110e0905f8b12c575b97b1f3.nq.gz
    ├── 2106c1b0e96f549ee5c0a472998b9938b8bb502d.nq.gz
    ├── 21d61692058ba18492db3d0d9364d507643230f5.nq.gz
    ├── 2696e17e90e59b7dfcecca522bd275d5eb551e76.nq.gz
    ├── 273dc484bfe776de71c698633bd776cd856c2057.nq.gz
    ├── 2a81876df49b4017385339fbb57ca5ef87eecb7b.nq.gz
    ├── 2b3d2251948e35b9cdf6e4a22d11f4e240375853.nq.gz
    ├── 2c0a93ac534e0dbb930093bda16f6cf08438cbc8.nq.gz
    ├── 2cf3b940aca8d408163df9ac54bed587a5690c67.nq.gz
    ├── 2cf8f6ef59e4a51e5c91a9d5e777d4506738b044.nq.gz
    ├── 2ea9f5a4851cf534f90ba7f31e74b19eb1ee1ddd.nq.gz
    ├── 2f29c93e9ac53dc58d7d283cb827f88e8f542974.nq.gz
    ├── 2f5b3007ec89a34c6a99dc8a30102a2d443d14bc.nq.gz
    ├── 3133c71200a00fece9f56fd17767ec54d449003e.nq.gz
    ├── 31f28357f7e7da6c11703aac1d1a96743d7e9ba1.nq.gz
    ├── 323927390b9112ef1c2457c161dd0a645231f234.nq.gz
    ├── 327afd5eba2cf7dc759c4d9b2230bae1191b5df3.nq.gz
    ├── 327b91ae2273f3427f38e16a0abdf69cc20d5a70.nq.gz
    ├── 34070c258fccac4e9e7233cd221c1c0544fd50b2.nq.gz
    ├── 3633139ed3c94367ac92c69a8ea1105bb50527a8.nq.gz
    ├── 36e0366bad26f19d08884d9d80b701b9df4c4a60.nq.gz
    ├── 3a307c8c6a1071b7555325e8b08f4db0ffdd8809.nq.gz
    ├── 3ba386ca2135a4c443082b7763776aa5eaeebb55.nq.gz
    ├── 3c8102cce422effa3f8f9382417760321439ca17.nq.gz
    ├── 3cd59a64d10c90f44bb01ad04f52978e566854c9.nq.gz
    ├── 3d5419267d0fa6ddab0c99dc331d7ec3f89ccb7f.nq.gz
    ├── 3db67d973eae8d4f66858ddb455f9da46e1c2b23.nq.gz
    ├── 3f55a5d803f59458afcca748c0a870c8942976e8.nq.gz
    ├── 405976193ceb75d27da37b76656d552db7a472dd.nq.gz
    ├── 405acfce542e51dca4bffde4478878bda2a68cdd.nq.gz
    ├── 41bc348bdd9ed2f688e7c3801e3d2e7b9f32affa.nq.gz
    ├── 43199774eef72e091784ade6cabd6a60cc2ad043.nq.gz
    ├── 440c6cd52c2cdbaa4eec97f9433407765611af2a.nq.gz
    ├── 453fac5fb60d21c3b74651a3c8dba5396b3d8f34.nq.gz
    ├── 493daecbe38de6495f6f99478db775083dde51ff.nq.gz
    ├── 49a0674ac8bb4d040132ffaf147182d97e1f8660.nq.gz
    ├── 4ab56702c965bb1c8824085266b66c30bb7f92aa.nq.gz
    ├── 4b04b4a1dfecd43397ae1326bfe61a22fc56fb26.nq.gz
    ├── 4b1528c6fd14f7c1e5f968de4f292b140e539f6c.nq.gz
    ├── 4bfee296712951bda1ec6ecdfedb16a452b85dd0.nq.gz
    ├── 4d629e01cbdd523114929534988ce71f8a3e1ec7.nq.gz
    ├── 4e506022d1e8fd1d54e580c088273e8c1b0987b7.nq.gz
    ├── 4f4aaa3a52f8d0e1cc77167b5d25ee41ce760e04.nq.gz
    ├── 50836202e50e4f4d1f22184cf89284c9899cbd53.nq.gz
    ├── 508719ccdcd0fdf82b4773e9d6c55009f98ab57f.nq.gz
    ├── 50c18a41ca202c9c6cbb7cc7b2fa2f4cbe3d45b3.nq.gz
    ├── 51a71ea3023804f7c1d4b7b45e93485e66e6d68a.nq.gz
    ├── 567e46863ebd4686f9e4f85f7f8dc2fa87751b17.nq.gz
    ├── 58dba88dedef71e5daae9e1cbb405dc6d66ffd77.nq.gz
    ├── 5d8064794bed252666b29a9bba1f762498172ba2.nq.gz
    ├── 5eb4b94c0d60c5f6960b85acd3016286ec9d38fb.nq.gz
    ├── 5fc72063e480d182b5e855c13940e70affe11684.nq.gz
    ├── 60cc10a893a797b3957420655b60fa76fbdead98.nq.gz
    ├── 65e634471e684783d1943a386641da357d4b7acf.nq.gz
    ├── 66f8d087bf00a014fd6c67580dcf0e5417cbcadf.nq.gz
    ├── 674106005855c449fcc97936ad49daef0780c149.nq.gz
    ├── 6782b45773779c43cf0cdd3158358a88b7ff70f1.nq.gz
    ├── 67a1a78543c6594eeaaf1ea3ec5cbcbd6099d65b.nq.gz
    ├── 68bc17f9ff2104a9d7b6777058bb4c343ca72609.nq.gz
    ├── 69af5d924fbfdaca4c40fc78794d2f7d8bf9dfbe.nq.gz
    ├── 6b555776ddaa275056399ad164819abdc5cb4fa0.nq.gz
    ├── 6bddfc5241872f4b4d102bd151310fe3924e7fbf.nq.gz
    ├── 6c30f9137b0bfeb5d077fe15819cd23cd2b88268.nq.gz
    ├── 6cb5917b240976ae71c977c7d228a1efaab37434.nq.gz
    ├── 6e814d8abe4a6e15234133b451d54d2e079db3ea.nq.gz
    ├── 6ebe22b20e92e561782df719666e403104893c36.nq.gz
    ├── 727487a4b8659d65ee6e03cf4e9f9d666cd4d7c2.nq.gz
    ├── 728c70af28ac884649da6932a8f4e73257228f74.nq.gz
    ├── 7500c24df0940081b01393b5140ca9341323aa91.nq.gz
    ├── 756bdd797d548889124506b9d508eb82a3ba2a77.nq.gz
    ├── 76cf500f861fcd7f4d2fcbcecf6e4f4b65b77a1a.nq.gz
    ├── 7cc67a77f0b2d03cc3725cc2ff78b290d3a375f0.nq.gz
    ├── 7e630367f353c56ede42fc29026dcfca99c6167d.nq.gz
    ├── 7eb2b0e6551f438dfd9d8c38bbb1f0df2d178476.nq.gz
    ├── 8092d47934a22420a6ce5696c5f4689782d62da6.nq.gz
    ├── 83f17f39230a0280f61eb83d81de190f674fa024.nq.gz
    ├── 8408198a6001e3f1d59329e45ad7908dfc685087.nq.gz
    ├── 843a9ca0875c4f5e118d3fc9e14d74bbfe54349d.nq.gz
    ├── 84e170a49b6eb267b7b7f9767f8c0bb4999e5281.nq.gz
    ├── 852da069faa0f2334bedd2be04cc67d934aee59d.nq.gz
    ├── 87ae416e97c3e7222561f36b1ffe5e7b3d780ba6.nq.gz
    ├── 88a0526b4def8b623abdbd8f6fcf155789a1e262.nq.gz
    ├── 8b592c2e777ebe9d552f772d9c9f504f1136ba4a.nq.gz
    ├── 8bf80ed2f3f3c23d4dff46544b9021085aca1fbe.nq.gz
    ├── 8cd06fff650e7bdc3d37ac91130c2220b3aaa14a.nq.gz
    ├── 8cebe5c77692ae4c2f57b1c129327e2fb3005e92.nq.gz
    ├── 8ebbc47077d2e93026850f0faa9d1c3a39a5ac64.nq.gz
    ├── 8eedef47548e1caf387b5491c7abfa7ecbb0b1fa.nq.gz
    ├── 9060acac620afc505503387846e3e411f130bc4b.nq.gz
    ├── 90a728581289fbe551be5a44790e3e8f68b60207.nq.gz
    ├── 90b83a5c6156ed8664f64b58fbda1361af92d8df.nq.gz
    ├── 919296e3710c33e65d1836ed76141f267fe1ed48.nq.gz
    ├── 953e7cdce9cf638a5196bded004d4e6136aa13db.nq.gz
    ├── 9717c8c31857941a906189d0df7caabd74db861b.nq.gz
    ├── 97d9527c8c0ea19441e2b4cce33a78321c87e61d.nq.gz
    ├── 99433e81aafe9740f5e2c19376d46ad3d6f4c071.nq.gz
    ├── 9b5341cca643e2cdce944d964eacd8b509a39929.nq.gz
    ├── 9b58279d2beba36a8609bc39d3bf6ede4ded9859.nq.gz
    ├── 9d234ddbca545ecbb4fbc36e3eea30061300e00d.nq.gz
    ├── 9def8179467deeb6f0bd6fd308d996f9422ea4f9.nq.gz
    ├── a20095bbaa1cf1b9c249d3cc12f0bf9cbd0cce38.nq.gz
    ├── a23d8e02a582cd045c4bcc63ad513c1b421f3ef7.nq.gz
    ├── a31939642c080eb93e0b193a394b08c494628909.nq.gz
    ├── a54d56b555f4383c467a6234e7f23f26ed8d5d21.nq.gz
    ├── a77535b5d82f4dbaeb850bcd5a703fec0c43eebd.nq.gz
    ├── a7f1bf553731fdca6bc53437f1ae8e8e83065e2a.nq.gz
    ├── a90d59555c19e77e933805499b77a9d3b3eb19ed.nq.gz
    ├── aa59eece50e7b71641849da0beb0b7bb03bd0473.nq.gz
    ├── abc3a12d2199bd2c3c03ba0c1794ecb30c047aee.nq.gz
    ├── abc9a714ce18cce32de14e31c20d884d68060a28.nq.gz
    ├── ad64fb9aa184e79e47423f70e6887d0c11342fd4.nq.gz
    ├── ae99d6f0c29d95ac6b0567743d6129c55e606803.nq.gz
    ├── aeb16da2bec0c84b5f09b6d524029872172a2e5b.nq.gz
    ├── af6fd77e0b3d23827bb047f549101fb06470b8d3.nq.gz
    ├── b0320af1a0a701ec3a96fea3c6c2d6bebcda3702.nq.gz
    ├── b105d00ea7fbcd7d3634b9d773433997221991ae.nq.gz
    ├── b1f9e7b4e3a1a07594c1b8e5fda9c049e1c595a5.nq.gz
    ├── b48a28d44b0c00e754285311345480f9aed26632.nq.gz
    ├── b5db03f34db6859c0acc8380339522d6646f5677.nq.gz
    ├── b6769bc8dcf848685c0ecb75d4a06ed225ea2209.nq.gz
    ├── b778ba74406b470727fbd74fe943864018d00fea.nq.gz
    ├── b83fc3236e2a16b1b5688991d51cbc481b76b97c.nq.gz
    ├── b8d8f68d164d3b9bd9cecbc77cf9e17ac2afca2d.nq.gz
    ├── bb57e8bf3533b7425e9d26f18883f8ca7edb8a0b.nq.gz
    ├── bb80c22d008c5945a7125c9c2bbc7242ffb28c94.nq.gz
    ├── bcbdbcba8c5553d565cb514a82561ed78f534243.nq.gz
    ├── be1dd85c51eafd5bcba589daa77bc3e01abda02b.nq.gz
    ├── bf4ed7d6e39b387bbb309af1fe029d344767b31b.nq.gz
    ├── c216962c6aeb948b72f2cd1ed61b662514d1d22f.nq.gz
    ├── c2b96ae9c541eb85bf8c8a802d0698643b389ad6.nq.gz
    ├── c5e8fc2dbe2d92c697e2e21e1739cfd781b7e50e.nq.gz
    ├── c6041197b3d8d9441eb7e5ec3e405be36903beb2.nq.gz
    ├── c6b782e712e488396059e1d08b6c3991fd662e35.nq.gz
    ├── ca37181ad620cda26b5bb1a456ce622531c43543.nq.gz
    ├── cc8ab6ba1ec49f1b5b0e96d162b21553fc89c489.nq.gz
    ├── cd4503307b304f2404818de4a1263bf36a39f619.nq.gz
    ├── cd6c584796474678afc8b229b083cc24438a4531.nq.gz
    ├── d006142d02517187f3c5736e874d387e8bf7dfb2.nq.gz
    ├── d1a3262f8e2d4c7eca5a31c5f43351567cc3298d.nq.gz
    ├── d401ce9ed3bee26936fce4800e787757406547b7.nq.gz
    ├── da6ab6cc8f333d7e89a99812866df8f24374d47c.nq.gz
    ├── dc28ce01fc1fc29e8626a11851c44ee371298cb1.nq.gz
    ├── e11d0bbbbf84199020c65bd17b15aa291ae3cfe9.nq.gz
    ├── e1d86f2e5b353cb67b8ed917c50c59ef61930f4f.nq.gz
    ├── e1f9e3e81bd5dd227572fd2def29ff59aa5ba8a4.nq.gz
    ├── e246382570df2dd09ff8aea44a7f3c21841d1f04.nq.gz
    ├── e3245d339fa7cc08c595cb471092dc1e5c5219fc.nq.gz
    ├── e42b30d7669ab2b64d8a6d49fb108bc46555d60a.nq.gz
    ├── e51373e34e69189273361313242419280f8318fa.nq.gz
    ├── e67443e434e4bf4e54841f193e14cc2f474b8912.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e83c90c93d65875f4e26e7943df71dfd9105bf59.nq.gz
    ├── ebf4a59b0ee5f92a55135f8d9932a7e947ff663e.nq.gz
    ├── edc2d1189a785b5556659ff7f7673f8dabc11f3d.nq.gz
    ├── eddee41310f65e53f7fd1f36e4164c45274d6ab7.nq.gz
    ├── f0958e7b6dfdc063e9017bd457fec174dc39975b.nq.gz
    ├── f22228f4b7c21b5dd880b2499cf458e06613fd83.nq.gz
    └── f295ceaf3b24305e6834f5ec4ba52b6fa6c478d5.nq.gz

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

[psf/advisory-database](https://github.com/psf/advisory-database)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
