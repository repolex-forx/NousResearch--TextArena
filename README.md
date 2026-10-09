# Repolex Knowledge Graph of NousResearch/TextArena

RDF knowledge graph data for [NousResearch/TextArena](https://github.com/NousResearch/TextArena), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/TextArena
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2f20590f0993255221975cffa1890dcc550bf6a5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2f20590f0993255221975cffa1890dcc550bf6a5
│           └── chunk-001.nq.gz
└── blob
    ├── 0023e1a7a135fe45afdcd3c977fe01125042fbff.nq.gz
    ├── 00760f9feda8df3739909575171e91c751d6d738.nq.gz
    ├── 00b52a74fe0f8585ee172d6456d9a52e06e7965e.nq.gz
    ├── 01329ddc8245f5a31c97a616105fc1b06ae7bf0d.nq.gz
    ├── 0171444be049ac5cbabdd95f030b52e58690fb41.nq.gz
    ├── 02bf4bdb6bb87f53608da12fb378ea33a93a86a5.nq.gz
    ├── 053ed442c532fcf17e84d3210a7554e7d16ec141.nq.gz
    ├── 077912173902d44bf0c4a20cc682335842ef98c9.nq.gz
    ├── 085cada59f097d1b62ae6c20765fd7af9c846402.nq.gz
    ├── 0864104f919a9c8cdaf3c6c3c3b3f2de125de834.nq.gz
    ├── 0919a5cee36d265bcc5ee67e1d487077126ed926.nq.gz
    ├── 09600b8c495ae59750ced6f83184edb413f884e3.nq.gz
    ├── 0b3cfbfdb5d8d3b95497010e7b03fbdf74e5a438.nq.gz
    ├── 1024a14a5baa6ce0b6af80d2f8b4dfc46c07189d.nq.gz
    ├── 1070d56b19b446198cbaf730e6a480f4ee264224.nq.gz
    ├── 11410a8582aec8976c4018c0e2fabb0ec5620009.nq.gz
    ├── 123c5cd351cac2b8ead5413bc084629d7ff651de.nq.gz
    ├── 131bd07946d279f207fdac96d7bbecfbcd686bc9.nq.gz
    ├── 1456732ae760f89eb57b5ddbdf1454144e6bb0c3.nq.gz
    ├── 14afed8264a98bd1d3bb7caa66fa4415811e3772.nq.gz
    ├── 1619c585cb90d0c5e8c9b06e0a85ffb379c0725d.nq.gz
    ├── 16738919b51e16250f41969b00c12791ac3113f7.nq.gz
    ├── 17cc376a3ee9d7df5504d8f4ab1b4ab88642e7cd.nq.gz
    ├── 17d51ced25efd0341586a13779488b01e1b15a2e.nq.gz
    ├── 1886b3132ec5629c419969efc278e6e28be7b5e4.nq.gz
    ├── 19b534f5c5ce718d020cebcefea8e7fb90a59655.nq.gz
    ├── 19e6ea4255b6f01b052ac82d99031642f7bbd7a5.nq.gz
    ├── 1a34362e8cc20808351a577461a71543f56203e0.nq.gz
    ├── 1bff9703b3fc50db0f560ef9599732708eeef34f.nq.gz
    ├── 1e20fe2ee070a906030f16ba8ab44b7164e30466.nq.gz
    ├── 1f884189628100309616fdcf9cad9422dc480878.nq.gz
    ├── 2100e12e4be165b0b193abc0d5f4e09a55c82af5.nq.gz
    ├── 22cbfe718c70f40f5d25b873a21b0b0a464f94dc.nq.gz
    ├── 2376b9a194b46c0790e197c91b7249e5f88ac09b.nq.gz
    ├── 276420ec93972945f90a21343f7c9582f49fb82c.nq.gz
    ├── 27843995461d82e97ab6da411ed6f4590469011e.nq.gz
    ├── 28ea3332f0a9bdb5910ff7043fa33e4691671a22.nq.gz
    ├── 2ad37a3f75a84e1de452eb0100ce66830629847a.nq.gz
    ├── 2b510629bb69b3486424c6e9e8d2b748876b1213.nq.gz
    ├── 2ccc3bf5a583b97afae00a3e8480d9eb7c89067e.nq.gz
    ├── 2d0ad644caabbddcf4a5119ebe58162b23d77093.nq.gz
    ├── 2dac679179cb88cfd9a2fe93012872c949c2baa5.nq.gz
    ├── 2ebe8379c59af7e18188be603e61ad31b66b085c.nq.gz
    ├── 2ed2cd333a5e99e41765dec11307aa0d8edba3a0.nq.gz
    ├── 2efbcd7360bff10d20ad322ed761c1a3f1cc2027.nq.gz
    ├── 2f3798b358c6710a38a66dd705a0cad280484721.nq.gz
    ├── 3028fbf765f1e3d08b53daf34b035b2faa8217b2.nq.gz
    ├── 308064d0c4037f67a9bfcc332a92b81802fc7a14.nq.gz
    ├── 3278fac4a67cfdfc48cdaf1ce6a87fcd39d3443e.nq.gz
    ├── 32b431deb71cc464eddfd178b121101933576220.nq.gz
    ├── 32cc3c6e7149c9f4dece6c8f903a14d9b1171708.nq.gz
    ├── 37b695aa49eea5d8de649430d58ef4c99c5eae8e.nq.gz
    ├── 38bc536e714da5b557fa5e6cb19e64f6cd547e06.nq.gz
    ├── 3a3f7f4bab2d6c587acf17776b5db767cd3a5a3d.nq.gz
    ├── 3b0520cfe33cc4b1576a10db5f773ec3a007ee03.nq.gz
    ├── 3b25ccad7d19a2046eddd67b1f5d695b09341f0a.nq.gz
    ├── 3ba13e0cec6cbbfd462e9ebf529dd2093148cd69.nq.gz
    ├── 3c084d99a1f7a6613e4170411d4b02b6cdbdd35f.nq.gz
    ├── 3ce6214fbfe15c38ae8a2e3b9a607e5e1d29734e.nq.gz
    ├── 3d83e03006da68e3800d28bd79366460fbc9b5ff.nq.gz
    ├── 3e6e62b831b5fcbf0585d0dce75ccc5e4ccb691c.nq.gz
    ├── 3ee4dfeaca0c01cb7bd874086ea643c49fdf78b5.nq.gz
    ├── 418c0c44de8ab054135692163839c441dfa146e4.nq.gz
    ├── 41a1c1ddc391449b7d51a203f10adbd49267df55.nq.gz
    ├── 41b2b83ad583a2b8ca31aec07275298361412f68.nq.gz
    ├── 428d26605e25b96bda6b83263f69cc83e0b573cc.nq.gz
    ├── 4353ec0d756f39e4c5f42988bbe98c19b96afa2d.nq.gz
    ├── 4369c306b236e6ca79ad514f2b653bfd2370dc23.nq.gz
    ├── 45c7294f107694b19a42b6619a5292665a3a77fd.nq.gz
    ├── 47bc5462da8374bdcf53a7339bd48a7e28567676.nq.gz
    ├── 4816d66edfa38150fda26f6685a592c7c466da26.nq.gz
    ├── 485ae10ebdaf3c50a982480fb8390087589bef72.nq.gz
    ├── 4a28c11808c3bad5ec076bbb013c737112a76327.nq.gz
    ├── 4aa116493f6e4443f6bb5a191b8b4b4d49ed70b6.nq.gz
    ├── 4b2de300b8fb21ab462537e9802672b9ff834870.nq.gz
    ├── 4b464c3c3e687708b58df9ad9bbd57e4b7f261b5.nq.gz
    ├── 4bf27bca0eaa5c641c288c9f08da822bf330e37b.nq.gz
    ├── 4cc2698bd50cd1d854162ba822c5ef350642ed2d.nq.gz
    ├── 4d04f1677aaa2a348f3f79f7da90f3b25e0e0384.nq.gz
    ├── 4e2d1aecb2659dc6389a8ed939b82397a03470ce.nq.gz
    ├── 4e91603a1ac28ee59e80ab7a9be32cee742b7cff.nq.gz
    ├── 4e9e8bb0c6b94bc9691992406144e3cbb9ee5465.nq.gz
    ├── 4efb2524db0f13f2b78dd8585d5fd465d0c9c85e.nq.gz
    ├── 4fede02d806f1e880dbbf0818a62a977e3ee2e63.nq.gz
    ├── 500289d28c1ad00e3fa42f3129b4da976ef6d492.nq.gz
    ├── 502657c87e5ad0987191fb498bcd1967f396cb88.nq.gz
    ├── 505d2d71fe9ba09e49eca64c5579459795fdbce9.nq.gz
    ├── 50742cdbde4814a26b73d43aa93cfa3577494aea.nq.gz
    ├── 50c8f11a8b91b60a83114922092f7fe519ef8bba.nq.gz
    ├── 50f3b7528c1922ed669b3325c38037f5a603cba7.nq.gz
    ├── 52503955aaac4b77bacd07c132a9c1b3770dcf20.nq.gz
    ├── 52bd059e8c9c4491bf426c24c8b0fc3d1142a570.nq.gz
    ├── 5374633be49cdec3c9c4524eaab41b5430cfce2a.nq.gz
    ├── 5500fa2a74547bafeb995c1e8137d41b647e57d3.nq.gz
    ├── 55020a9e2d729f185cf61dbf7f39713cae87fe82.nq.gz
    ├── 5502583763f27ab75c572952c02ec37743a0ea66.nq.gz
    ├── 550aec225078d1775c2ac8f0a85425e1c0cd020e.nq.gz
    ├── 57f3f6156798441686da027ec0ba199a6581a198.nq.gz
    ├── 57fd253d67034b781ed06ee9c9a2e2983898a929.nq.gz
    ├── 581404c2ea320b9bd4ed30cec66ae7feadfb172b.nq.gz
    ├── 581942bc973bf22befc7eafd22dc6cdf68a6ce51.nq.gz
    ├── 596ba09931c970f842ff36b4dbad56efadb0b75c.nq.gz
    ├── 5a4b55041f8bb122da8d5e7cf94aa23055bfabf4.nq.gz
    ├── 5b1cbf3ec666c98e64b7861d08e197d3c2a3486a.nq.gz
    ├── 5b6617fe2c74e6a4be6a37d7d69deb16630d1965.nq.gz
    ├── 5b6a775497479fcee14fc1e66518e9e6a4b2bb23.nq.gz
    ├── 5bb589da19b6b2eceeb9730baa97b1540fbaa9d7.nq.gz
    ├── 5bd003371b444f872435e3fe1fc984a30a6b31c5.nq.gz
    ├── 5cc7d767301a2cd47060fbfdee49f57234557fa9.nq.gz
    ├── 5cca063a6c9136ca86fab11e188699f4772ddfb9.nq.gz
    ├── 5f6f2ac8adf416aae1b8a3aebd9332c03fe521d8.nq.gz
    ├── 60e8af49fbee0bddb3aa6b38d8657e3b1e5cb72e.nq.gz
    ├── 61376296d41d55adafb2162cf8e89544b144e39c.nq.gz
    ├── 620b165528bf0c758aad28d29fce50d5a524db6e.nq.gz
    ├── 62272a27c0a169f2ea2ffb7bac2441200bc95325.nq.gz
    ├── 63f8fed15eee9c2a376ca848e9b2792e1c431d7e.nq.gz
    ├── 647b3eacbd2477ed687459bb5171e8be1d300002.nq.gz
    ├── 656e0e1824fa27ed5212422751b4cb96894f734f.nq.gz
    ├── 6894ad7c49a0b3a64210af32954f4d049d934ea0.nq.gz
    ├── 69762b7e22aee32a44c5d635a07b8d93356bb7d0.nq.gz
    ├── 69a43f4e5f2e2983c3fac48cc24786e235eac613.nq.gz
    ├── 6a843b3b04afdd2da31b8df47782b5f69754c087.nq.gz
    ├── 6b97006e45854b6565785992f8f75e0123850dd2.nq.gz
    ├── 6bb3e54181f4e2dd2d1ede3ad903834a09aab2d5.nq.gz
    ├── 6ca595f679f21aa7cb48aabf319bbdd6a90b4a6a.nq.gz
    ├── 6cd8cc9eac0abb3a6c3d28c9564f98958a53fc72.nq.gz
    ├── 6d0be43f26efeb28b5828d4a2ec6b74db739523c.nq.gz
    ├── 6fdb3b1aaaa7d6cee665ab8d5f1b6e4e114b9e5c.nq.gz
    ├── 701d236c333319140cab191168c7ece97fb26a82.nq.gz
    ├── 70c9b65bed52ec4973606f5f6d2acb6686ac6811.nq.gz
    ├── 70ca5caf50c69445e2d3a09a199688ae91f5b810.nq.gz
    ├── 726fb6a1c1a55d0a53aec2ee0dd5dc0ed3b71bee.nq.gz
    ├── 75b922230ed41618b7d47f817200dfb42f1c3ea1.nq.gz
    ├── 78c0121fe72b453aab32d6e66ce3762a847907dd.nq.gz
    ├── 79b4d05f743d478dcc46f3968fde417f3b6224f1.nq.gz
    ├── 7a62dec3f01f65a42c8a38519a4a7e2620fb37e8.nq.gz
    ├── 7a7775e0da050d6a3c89483224e4181cc4726fc0.nq.gz
    ├── 7b65a96a30d5e3ef7363329bd1c31348404518e1.nq.gz
    ├── 7c11e072207c711abfdb75f4577cb81e065439e5.nq.gz
    ├── 7c4c1e59faac9cf74f9f53fc8fa11c74f1699630.nq.gz
    ├── 7c96ac5bbfb8a1d027fbdd69eb4d9ca7948bfbd3.nq.gz
    ├── 7d1ae4ef283ef93771b0bf93535814c96a6247f5.nq.gz
    ├── 7e96f9cac295bc4a3396a8450218e24e0a029401.nq.gz
    ├── 7f67c4fe224bddcefd7a5da6ad10bf70bb91830b.nq.gz
    ├── 815f93bb9f3d294d156430931f43a995364dfd21.nq.gz
    ├── 8351862cb9975b492b7a1e861ff39d0cd56c2b07.nq.gz
    ├── 83bb330e04f2a83a66503ee7e15b5730c6b50708.nq.gz
    ├── 83fca73ba99130b8d6530ecbae8910b61d519cf1.nq.gz
    ├── 855b0a4be48552631f5da8dfd15f19bdd6dd8d9b.nq.gz
    ├── 85edde560296b643498da7292eabd09740682dd8.nq.gz
    ├── 862d3757b55a4b7a2d69c2eb225003816d4cb0b5.nq.gz
    ├── 862fccf64ff1edd4cc58acc565f5d17d8077735c.nq.gz
    ├── 880b35cbaaa956db019d6341ebbe3bd721932dc4.nq.gz
    ├── 88a43177734e787f57fe420ac3a817ac0d85a0ed.nq.gz
    ├── 896d4be6a37a1a2493792b5fbf89681f30d6ef2b.nq.gz
    ├── 897cfc3ae24d7ea01a7680be4cb17b8a98fec495.nq.gz
    ├── 8ab1df3b44f76a9a793b81b664ffc62954fd1d4c.nq.gz
    ├── 8bb235e7b1374aadce2331c9d1577096aee7f066.nq.gz
    ├── 8c24f8e1566f68d372db623a7dbbe3eeadd5b5a0.nq.gz
    ├── 8c3c76374124d895252f67d5185ee58e7e09a96a.nq.gz
    ├── 8e71f5fdd6283f3b1453f8f524e069af2ce987ae.nq.gz
    ├── 8fcfbc620b047c76f2ed0a663bdd35c9a46613d0.nq.gz
    ├── 90223ff7619c49911d750732f105cb755d17e26f.nq.gz
    ├── 9051fd3116c5398e9798da491fc8c042b012886e.nq.gz
    ├── 9167681c5166acbef0e9d3eb83e09ec793f28cdd.nq.gz
    ├── 924a56411aa5421893107da9b6f1049004a2ad24.nq.gz
    ├── 945c51265303cdf242764bf08e9a54063f62d9a3.nq.gz
    ├── 978b75e6cbdcca895675f57b931f67ba9249d25a.nq.gz
    ├── 9902d6122c8b8de4ca7bf401dc275bfb17ff0eef.nq.gz
    ├── 9ac85fcca6a6774a3ae98a43ae9fd80f112aa5f3.nq.gz
    ├── 9b0871873898c319819d510c951600e892bc2807.nq.gz
    ├── 9b3dfc6fec2dfffbc055b5d5994fdef1e6fbf1bc.nq.gz
    ├── 9dc34e10cd47a12c4469c430ddba543766e19120.nq.gz
    ├── 9ef2056bd96f14c39b30e04a27b3de212254e33f.nq.gz
    ├── 9ef3334841057f53caac5522332e38391d3fb33b.nq.gz
    ├── 9f5bfdf118cd12d84fb3f3315a81e87de095992e.nq.gz
    ├── a02fb65b9a4b8483fb88d517fa45078fd0d26701.nq.gz
    ├── a0a563fb64178630d6d360ec9923ee7dd028c9eb.nq.gz
    ├── a1bbf87665803ddd4b378846a878fade7bd538ca.nq.gz
    ├── a2235bae525899afac93c47a37c8308e6e83d9dc.nq.gz
    ├── a29d731d889a6e3e1a0d87717663604fbc66be3b.nq.gz
    ├── a45d5799719a0bce58dddb9a3afcd4b9881ec40d.nq.gz
    ├── a46e407d64165ebdc2b101ed66b78a27ff1d6dc6.nq.gz
    ├── a62ef3e8bc0446de096c8384a0bf5c99867043b2.nq.gz
    ├── a8403ce208825b4673cb2b5e0f27b1dd8161ac06.nq.gz
    ├── a902cd8f8e6604335e59bdd1254b00fd7b47e1b7.nq.gz
    ├── a9459730d45016d4148342f72934be85c54ad468.nq.gz
    ├── a985007151d0e7b21557e2b0225394e93684ec68.nq.gz
    ├── aa1d9df06b94c76fa4c173c8a291a1deda057969.nq.gz
    ├── abd7cc603924a96db648185c4caa7acdabdf9f7a.nq.gz
    ├── abe1c2544810169705044491991c2cf8ddf884c5.nq.gz
    ├── ad847b5e4607198fb17a1d80d1183cbcf51865bd.nq.gz
    ├── ada106e7bfa65a97bcda21b6b0365e067968e28f.nq.gz
    ├── ae2f4e3d3ed90b5e0ab3723325a01f88fb8c1a1e.nq.gz
    ├── ae3d621da99e2071ff87439f8192fbc609549b30.nq.gz
    ├── ae8138ddc2700f20d8d3fb0398062044c6cf6ca6.nq.gz
    ├── aff0fd50ab16d535186bc61617fee13513b8b388.nq.gz
    └── b1ea523d4bc8c34510acaa2713453dc49085672d.nq.gz

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

[NousResearch/TextArena](https://github.com/NousResearch/TextArena)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
