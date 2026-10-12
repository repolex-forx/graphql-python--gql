# Repolex Knowledge Graph of graphql-python/gql

RDF knowledge graph data for [graphql-python/gql](https://github.com/graphql-python/gql), parsed by [repolex](https://repolex.ai).

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
rlex download graphql-python/gql
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6ccc0cc2c27e95b19bf2871e7ec3e1b48283c6a0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6ccc0cc2c27e95b19bf2871e7ec3e1b48283c6a0
│           └── chunk-001.nq.gz
└── blob
    ├── 0049d5c257ea7c9b37c5e98460460216f9b4b0f6.nq.gz
    ├── 00bd8a0f70590ec277b8e11134664ec58eba3adf.nq.gz
    ├── 01dfb20f2195b7ece6c2e789590825142fcdc908.nq.gz
    ├── 020ee0e4bd6e048c6746e9b1bcd10a7fddfc578d.nq.gz
    ├── 035f196fbefb8373b8c956a8d5da962707cefe5f.nq.gz
    ├── 0712be32e286c5b1bb285361ce3a35963fa6aaab.nq.gz
    ├── 0794cc471df419e8494cc87a36770008a706e408.nq.gz
    ├── 09d517424592f27a790c2fa8a79f65b60467b804.nq.gz
    ├── 0bbed2f5f1caee64a436f59d7d8058579c135f0a.nq.gz
    ├── 0c135d3a510f4a13e80d73257ee7b80353dfc592.nq.gz
    ├── 129e88564e77b41a0dfa795986950ae99cfa7f66.nq.gz
    ├── 141776c3546b0a7ed487f1cdedffc5a14c14a34d.nq.gz
    ├── 18b1cda190b5d78a620066e58a068cb8aad9efa7.nq.gz
    ├── 1b489a9515e7edf0536f9e339f9989fd7eb64059.nq.gz
    ├── 1c13ed00f25b36b8d03da9f987c908115508c0a6.nq.gz
    ├── 1ccf744e8af99e9014cb6c84b2bd8b4d129e6d01.nq.gz
    ├── 1ceadb12895363f7f0770af24f915a50e626fd3e.nq.gz
    ├── 1d179f602873a2a548ffcda62e99d9eb5bf4bff1.nq.gz
    ├── 1eaf0111aef1493f9723fb804fde10de12662bb1.nq.gz
    ├── 1eb51b4e1c9d6a7aec8ddb5229d02a24fdfc657d.nq.gz
    ├── 1eddd042b2a104d290e77158ef58e80c797e987c.nq.gz
    ├── 2103db8f6966301e5d598048d568857eb8c4f272.nq.gz
    ├── 211a1e4cab6f1e14b9c28b71d50dac5e7b40138a.nq.gz
    ├── 236a3321151d6afad59dd79978bf454d7faaad07.nq.gz
    ├── 25bb25fe07cf03c5bdfd7e440100bda81d5f5fd5.nq.gz
    ├── 261b4e0155907b1adbe424d49e6feafbc51e72c2.nq.gz
    ├── 2c4804db798260e3bad107b99e91c2544be5f9a1.nq.gz
    ├── 2da0f2044af3a1205dad008266662eeede8e6086.nq.gz
    ├── 2ef2016a8e7517aa71d66de6eadfe39f71677dde.nq.gz
    ├── 2fb6722c4adac8ba02609ca2958db363fa4fb620.nq.gz
    ├── 301d5cb9918fcb5d288e73c08e7dfcd331e68cb6.nq.gz
    ├── 302c226aee11b6c7b301f570a5b1caa145a65165.nq.gz
    ├── 3142248776427734d51c4bed9cb63d859ee840c1.nq.gz
    ├── 32b131c9b39c01abf091315d084fbf2d2c3136c7.nq.gz
    ├── 3535f0a284e30dbd894679736afb6597b4aae61f.nq.gz
    ├── 37d8f64e54e73befa16bfef0a600657e25096eab.nq.gz
    ├── 3904dc54e9ddd7523fca57518eab67ef1e8bf8e2.nq.gz
    ├── 3d7c3958b5df8ddedfb66e58eab07570adea6a5a.nq.gz
    ├── 4005694cd62b40626823b3c8998635bbdec14788.nq.gz
    ├── 412448f95c52c43f2817a29c7b9b9d267cc8ed36.nq.gz
    ├── 41cebd99864a31b0c279ff1d1a637c6a9256cf6b.nq.gz
    ├── 458f2667b483c389481f9b0f8f8c7234f9a0ccd7.nq.gz
    ├── 45f01d82a5d82672ed52cfd4be1e544aa7a0b3a1.nq.gz
    ├── 47043b98baae1937aeaab3c98062b009f4313378.nq.gz
    ├── 48dc8e52994052fcb99bb0dbbe2e020baf7dfbe0.nq.gz
    ├── 497caed50471ea9e0de790932aa34c3de45c6f5e.nq.gz
    ├── 4a73742c117371e30e9b5e5691ddb7147cc6f151.nq.gz
    ├── 4a7ec15a1d7d64dbb797b59f78793245f5d3bcf5.nq.gz
    ├── 4b36b5af77f7c3fc200ec49ed8604d39259d3510.nq.gz
    ├── 4c9a6aa04a25f7d3d910050865befeb9238670bf.nq.gz
    ├── 4d083d54ceb37c9c0c631d03f27c8fe409c1ebfa.nq.gz
    ├── 4e4e6ffb56e60267a52344540db1d717d3392383.nq.gz
    ├── 4f5f425b3e9098ba29f94341fbe0453055b11d60.nq.gz
    ├── 4feadee63a8cc765d50a45b96e0fe0a4d23eb8bf.nq.gz
    ├── 526c97badda46b9d894429f82c0d321cace4870a.nq.gz
    ├── 52bc27a4a6da2cb1d25712d40482e46d7c5047e0.nq.gz
    ├── 533b80f185cb38d88fa0e65478692a6ca426d778.nq.gz
    ├── 537c8673af5ab9b52f98958466d66edf2999cdd1.nq.gz
    ├── 544af51ddf3bf55d03b3cdaf656d59f3f40f26ec.nq.gz
    ├── 54aa650fa817603283f7b1330d52feaf0d960066.nq.gz
    ├── 556037f0e49eb2b29de011c0f7c710700865820d.nq.gz
    ├── 585f5c5937c6b8a60bcea5b6688ae8d4ca5fea7f.nq.gz
    ├── 593c46b66e8d768c90d59ae3c233f2be977c7728.nq.gz
    ├── 59d870f66b7989c3e4fa8a2a1f72a8f038350b22.nq.gz
    ├── 59e732dad36bf227b09e6d89c8e880cf391e5250.nq.gz
    ├── 5effea7994ee360ae15ef33edd479e8e90d37628.nq.gz
    ├── 5f412a331d43399813f596ac04a1028425970967.nq.gz
    ├── 5fb3480f6b40d654fb2e7b8defcf029316986b92.nq.gz
    ├── 61aef7cb1fc5f658f44e7b3281e5b6310a5d9972.nq.gz
    ├── 61e80fa059b50617bb71cdb80f56041e097edcd1.nq.gz
    ├── 6406b089d9d494fee81c8bc69428fec82c57f320.nq.gz
    ├── 658e3eff6c68a94d624dc2fc0277c9313d42179f.nq.gz
    ├── 67c2e739c6d008b244415846f656a3faaf67eca2.nq.gz
    ├── 690c301563acae1d3bc713b87443830dffe5475a.nq.gz
    ├── 69169425112355ddff14d79027f970fc9b6d997b.nq.gz
    ├── 69c71bce64e83c789eaaba638b9aefaad79546ee.nq.gz
    ├── 6d084599d0d720ef252c6b5e06acba54c086552a.nq.gz
    ├── 6d248e71bc0dab7907a5013741134461023a1b2f.nq.gz
    ├── 6dc331ac69a290c1959957cfff6be168bada4632.nq.gz
    ├── 6f1daaf7a0a3bb89afc393ad29b52fc2dc339b43.nq.gz
    ├── 6f30c8dad1321f2b5e9684abd4173c5c5f0e8edb.nq.gz
    ├── 6f7ba0ce9815a9289fba521c2883e5edd03035e7.nq.gz
    ├── 7058b198fa9987cd6f2b97ef89ac5eece8a1eb2d.nq.gz
    ├── 70750f8e1d41ae0f1ec904dd19b7788897413eb8.nq.gz
    ├── 72924711258eb7686b18f7769826f34b4368c621.nq.gz
    ├── 72c7265a1dbc5305c285892c8a24ee9c1f54eca1.nq.gz
    ├── 734c393bed12b5dc1f9cd185969086c872fba3d8.nq.gz
    ├── 747126b3bf43d3a4e7b1f016351124b881936c41.nq.gz
    ├── 78952d0f165838c303cf27b09054c00f5200c7b9.nq.gz
    ├── 78a07a02a4ebe434c1d2357b2a96024ba2518995.nq.gz
    ├── 7a0ce10a7d39d377cd14b7ecb0e99a33d23b9e36.nq.gz
    ├── 7a72f9a658f3eb3a2fa52227d484a4212d9a94bf.nq.gz
    ├── 7c9fc9b68972d4210323c9c9574b451f86b450fb.nq.gz
    ├── 7de4a12aa810d32d1f5788f9580ad997e10e35e8.nq.gz
    ├── 7dff7062e002eff5c751a3ccdfbc68d129cc1809.nq.gz
    ├── 7ff33950965e9c921f6dfa5d67745c36c185239d.nq.gz
    ├── 82879f7d737a057a13507654060b74257c96bc29.nq.gz
    ├── 87278c5aea005b3f2cf0ddbfcd412cf750f1bde4.nq.gz
    ├── 885d2fd243a5c7b9f44e203e5fe14929dcaa36ca.nq.gz
    ├── 88612464d34e927a41a6746e446778e7ecbdd872.nq.gz
    ├── 8a5a1b32ca0a35915b8cff4e885fa0817bb75a1f.nq.gz
    ├── 8b3971e5ecdb5c9d75c0a2945620c5c5999a0e31.nq.gz
    ├── 8b8f4d6794d1c6d0cb3d9360c22fba6d1c58f362.nq.gz
    ├── 8df8b22b09bad0deff65fe8e5d983dd38f47e345.nq.gz
    ├── 8e7455e27581b42b27535a213cf8a95caad1da7a.nq.gz
    ├── 8f314f346dcddbc94990ea998ebae71d0aaf2bb1.nq.gz
    ├── 9007f54a8ebee74585ffbab069ff97bb60e2b5c8.nq.gz
    ├── 92fc59ab14216e279366377a10e38529ed074637.nq.gz
    ├── 932648240cf2dcb008d14fdb89ff1eddce1ecda8.nq.gz
    ├── 93c1078c7103b16fbf2f0d8bffc8e081086f2a39.nq.gz
    ├── 93e1892618e3569e9deee6a039b6ca19197768a5.nq.gz
    ├── 94eaed2bbe38dd9088b0f889cbb8ac4ae105f7ee.nq.gz
    ├── 9534b018135ed7d5caed6298980c55e8b1d2ec82.nq.gz
    ├── 97118cae1d9674f8d05d4f4e5abf47a36dde514e.nq.gz
    ├── 979bb99b568db8f0de4d26233875bb27470f9fcc.nq.gz
    ├── 9a924afd21d0810b397dc23c02efce35dd413a5a.nq.gz
    ├── 9af372f78bf9ac5fbe0f92c3fa685c5d854fa411.nq.gz
    ├── 9dba88c275038aa3e78e78d3a0eacb8fddb21972.nq.gz
    ├── 9e3cdd9f913393019ee785c4f36b3dd80553dadd.nq.gz
    ├── 9e42d432aa09a80e3923ec92de6fc4a836dd4cd5.nq.gz
    ├── 9e5ff4aa1551d57925ff773c62c13cbf45e928af.nq.gz
    ├── a3087d78d58bedbe895b0a32003c746c6002c032.nq.gz
    ├── a54c594c82ec00bd65d26605a0d6f69fdbd55cf6.nq.gz
    ├── a60ce0b0617508464a5c05113e4f272ca5dc60fe.nq.gz
    ├── a6a04d40197b9daddc3bb5cfa77d2331f9322b93.nq.gz
    ├── a709b1a932cba9ef9b90a46457e717d17a503415.nq.gz
    ├── a83c476717b7a35ad4b10a49ec4580fa0b5534d2.nq.gz
    ├── a84acc5442a969f7bf9d808479770ac3bc46474f.nq.gz
    ├── a888d7500bbb241a121c2d69109c4d10e5b13290.nq.gz
    ├── a8f6cac622701d55dbb6f622c9b67b78c1a40660.nq.gz
    ├── ac178bc607e9102c16b42d390eb3aa1b28170e31.nq.gz
    ├── ad4fe755a437c1819c43001fb6d008d9fcea5a2a.nq.gz
    ├── b03c2b93ff1c0a0fdaaec425ff6a2d9ee8f6e5aa.nq.gz
    ├── b3a2aed0324ee54657e23c7c84caea9641d506d0.nq.gz
    ├── b41c8b438ba8696247410da44e98efb77af28ddf.nq.gz
    ├── b6169468a1066009e97a83cc35cfbdb7b495fb1b.nq.gz
    ├── b7f11dcb8b89ea6a47b16d729479ffb92f9e4b36.nq.gz
    ├── b835abeefbccc3fd2c1f287c5d1bd11e968667db.nq.gz
    ├── b8a9ea9ab3aadb514a4d09b8d011106750e3e146.nq.gz
    ├── b8ac42c00d59881ece5787f60ac830e1b62da15b.nq.gz
    ├── ba5ca136f285a5a0186c76449543d5ba75bfe992.nq.gz
    ├── bdab546ba49302ad07698118293e8da988b1ba3c.nq.gz
    ├── bf2da116e6e2e526c92b24fa4342cb0a29008ad6.nq.gz
    ├── c080da46d4036d27e996c7533f0af00070996b2b.nq.gz
    ├── c2c1b4e8b6966b000612a0e76c73fd627c0536de.nq.gz
    ├── c2f810e081e1ae880063d0d6bdd9085f0ab2f422.nq.gz
    ├── c3237093a4d517a4349abb614b0c0f24530f62ce.nq.gz
    ├── c3b49d5cd98f269854baa7bfbce63019533a7574.nq.gz
    ├── c42e4d04701de1f4d33096e8a7db8c78b27f39c2.nq.gz
    ├── c674abcd28e5d175514990791129ff89b95797ff.nq.gz
    ├── c8bcd147b7b1d9d36241c14115c50dc081288bef.nq.gz
    ├── ca67090828b576082df5118cf6309f4d54a22781.nq.gz
    ├── ca81b12baac4abc8239aedbf90da0b500401f1e2.nq.gz
    ├── ca8b62525835e25899c6b0804268df1ddfac7508.nq.gz
    ├── cbf912a25e84614c27b31516781f3736e9b41d0d.nq.gz
    ├── cc930ec27a0eab152aa06c7a85b6f5313ee8c540.nq.gz
    ├── ccdebb4aeea8bda42b50e5c3358f28ccb1214f31.nq.gz
    ├── cef561f71a80f27c908ac008899405fe5427e378.nq.gz
    ├── d03dbf1f6e3b38654b6883c1b64582625105a807.nq.gz
    ├── d0ab36f2aa19f53f0f8e36b1b96044ac1b1da686.nq.gz
    ├── d2e1a346fd4c3b61cff2b85980c7f5c85b0c9a40.nq.gz
    ├── d43a2722334a15b5740fdeaba40c31c4cc5d2120.nq.gz
    ├── da1a48c963699e967bd7573cb1bd8fcaee16d50c.nq.gz
    ├── def3372e41c44521ec161379437eef0a668ef610.nq.gz
    ├── df613afc29a03d205daf6a21231f02a612bb8f77.nq.gz
    ├── e0d97aa8f89f2550216bdc9708df3edcc091ca5f.nq.gz
    ├── e0ec51a43f34a7e7a5f69571d928e32e47ee7746.nq.gz
    ├── e16ded9269e900434eaf4d7abcd75d7c3c092a7e.nq.gz
    ├── e2ab4f9687ee66a9ef7c4999d3286c0b38bebfba.nq.gz
    ├── e30655b518efd116327d309e0925e468b54c6eac.nq.gz
    ├── e46a4c01e804aa4b649bd40af6c13d5981c873d4.nq.gz
    ├── e64a100203122762b0891139f2028501db707301.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e7e413cd2740bda0ef1eb94e97adbe782dddb377.nq.gz
    ├── e80e91ee2c0437ac05e5bfe634af06705d96d858.nq.gz
    ├── e848774528de3d1fa279c8f5aa470d5e537fc92a.nq.gz
    ├── e89898a5835500c828b64fc894387a8694acf275.nq.gz
    ├── e8ae47992a3073c149d985b315c531d921c099df.nq.gz
    ├── e8e4fb7d0fd4654a6981efa939954a23207c4e03.nq.gz
    ├── ecdb1cef9e02d39efde3996e051ae0a1c65ad08a.nq.gz
    ├── eea8f4edaf783800bd3b3b6a1ba955b69c054e85.nq.gz
    ├── ef14defdb8c3fed8a3795a2b7c6a5631317e9910.nq.gz
    ├── efa7e1bcf76b2a35885ba9c9deae3045a793fe86.nq.gz
    ├── f0d9523d0e08f88372340264abafaaaddc7ed661.nq.gz
    ├── f14a4ea1df539f0b1499b060191ad18699a3ecb5.nq.gz
    ├── f155161867d41fb82484cf9624d1c7514ba6e1f1.nq.gz
    ├── f291c1d03dfd1024763f2ead7a4f3e696907f8a0.nq.gz
    ├── f2ff24efb161e0a5d4be56a9d09393bec16f15cc.nq.gz
    ├── f5fddad49ec3aedbbe9404ce2750cbf2b0803497.nq.gz
    ├── f75c5f3299ff09f610e6a2c6173e84538cba5109.nq.gz
    ├── f79714e459be67a240a0c37e5be5f519e9258f00.nq.gz
    ├── f7f0f5a752a6765e53c162aa3c39e59673b3751f.nq.gz
    ├── f85b583ab1e7d12737f764d3bfc67858db4d85b2.nq.gz
    ├── f87854e2071359c003347f6bfb5ac69dfc6c97d9.nq.gz
    ├── f8f93d64373fca3b90398b81f7dee4dc77708158.nq.gz
    ├── fb0688b93fadfe9264d19c9306bbada7e44e2d99.nq.gz
    ├── fb335bf490161df7b42af469d80b0f7d9f5cbb4f.nq.gz
    └── ffa1a1b372c8e1cba459815102ebd539bbbbf46d.nq.gz

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

[graphql-python/gql](https://github.com/graphql-python/gql)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
