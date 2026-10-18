# Repolex Knowledge Graph of thombashi/pytablewriter

RDF knowledge graph data for [thombashi/pytablewriter](https://github.com/thombashi/pytablewriter), parsed by [repolex](https://repolex.ai).

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
rlex download thombashi/pytablewriter
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1943fe63c5f70567f32ad4cae6a58ec219f58b95
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1943fe63c5f70567f32ad4cae6a58ec219f58b95
│           └── chunk-001.nq.gz
└── blob
    ├── 0013b79468acfb72a195a7b36ae6278936870349.nq.gz
    ├── 0114d286316e08de8259b22129c2946fa8b836fa.nq.gz
    ├── 017c1639f9a0466616eb70503fdb5e710d969279.nq.gz
    ├── 0244a1cc7e8912800038b7ac6dc64513227029d0.nq.gz
    ├── 02a03708b243979b7ff42b0956cce3ec8489df79.nq.gz
    ├── 02e5b5d8b32f4c59a496955a7cfc5ac26b56b08f.nq.gz
    ├── 03027d18e7b658203cdb470cad427ac8d80fd420.nq.gz
    ├── 042eec251389691fdb939c2e50d8711554fab0fd.nq.gz
    ├── 05e0216db75187cd64dc8124e1a374e26cc827d2.nq.gz
    ├── 0701ccdf2e5123b7b13d666f848d8171d6a0757e.nq.gz
    ├── 0a5cb2d03bf9e7ae3a6e66bc8303738e4a078f4a.nq.gz
    ├── 0bf6ee5d1656497a354c1720c229a0fc18a47392.nq.gz
    ├── 0cecc632155a6f54a89a1caeb98df2e478add308.nq.gz
    ├── 0d359cc12febbda7851d37585fb15c8f30b9f7b0.nq.gz
    ├── 0d45b37ad6419c3dd9c381e79fcb1beaa3a16b62.nq.gz
    ├── 0e116a1ae13fda44995680c1400ac3b794da2047.nq.gz
    ├── 10d570fb0b02bf1f7436019fcbc71876c0578d3e.nq.gz
    ├── 1118079705ad52a15572e997098d4f6fbd6551aa.nq.gz
    ├── 1119e5aa27fd6556d7379e8a90c467707f3bc0ca.nq.gz
    ├── 15b07e9ed1ede41b1fbea5e3e9757348919104a2.nq.gz
    ├── 1613721072682180ae8ca8e247067d2906279ee4.nq.gz
    ├── 1677be060c018d14ed8e46db8263ed2f52bc2030.nq.gz
    ├── 167ede94d565d111c24cf10799d2b7bf991244b2.nq.gz
    ├── 16ba98e1f9f1b0b0d40642ff0ed1293b7a964024.nq.gz
    ├── 16e050bebfe1a05ee3e5b63f89eff1626905daec.nq.gz
    ├── 17721bff7c450c0e34af23f9f89e895280967fe2.nq.gz
    ├── 17763a9a6cbd5cdfdaa456e253ea2ff18b1a53ac.nq.gz
    ├── 17a3ecfd8f2b2110fe910fa05473d2fbe1bd450c.nq.gz
    ├── 17bd500bb252f6fccbd9cad794d6cce781fd4278.nq.gz
    ├── 1803c66c4af5d16d12d7ffb04d6fd993b2076182.nq.gz
    ├── 1ba085a994824371598841f51cf1ee5559baf717.nq.gz
    ├── 1c5c80d7e026ef55b4d36e288fa2a96895607f84.nq.gz
    ├── 1ca847804a495c14ebbc16858dc25fb1984eb74d.nq.gz
    ├── 1de427a45ad4986de92d71eea6a657aceb095766.nq.gz
    ├── 1e2de6663f41894a69d0af8cb772aece96867161.nq.gz
    ├── 201748ced3731bcfc04bf685ac3e141d633908e4.nq.gz
    ├── 220a4c1bab808244b1fe2c877cf3d41a973fdb6f.nq.gz
    ├── 251b8ce3b10d3e3f0cad9a45e262134a40e4e8ee.nq.gz
    ├── 256c3d6cac1afe19ab1d8887d66fd0a8a2d4b4e2.nq.gz
    ├── 2599002a876ae5b4aff57a8a3c914f3317d8b59b.nq.gz
    ├── 275347305c2a563ee8df04501ac96a3b9a2dc8b2.nq.gz
    ├── 2786cbe335d1a1d8bd3bd7fdaa794ec977332e6f.nq.gz
    ├── 279ab316c7367fe18d509299392259c55b4f60f3.nq.gz
    ├── 27d8be206260a891136fcae04940a212f7014a50.nq.gz
    ├── 285f3e2ce185fca0f1356eb3f7f300bf366be402.nq.gz
    ├── 299364b8695698fa23ba5460f576bf037744c34c.nq.gz
    ├── 2a8d70441a2dd20e4184eda5ab80bc4a5d116960.nq.gz
    ├── 2a96d50faf7d2e20773dbaa66bb67f6eafe2a86d.nq.gz
    ├── 2b58471618df929e8e0526f7a78ff1f42640358d.nq.gz
    ├── 2da8105a09934a89d8014a8019b2ff4d6fe19eda.nq.gz
    ├── 2f5827ba8c5b3a080f3be1df6619d13ba364575c.nq.gz
    ├── 2ff1e6850c5821e24803734d5445ee80f09de8d3.nq.gz
    ├── 306b4bb72410602fd0f23ec274cf60683f9497c5.nq.gz
    ├── 325be5c2e4395d0898fc7d9b3b43acf011ec48b7.nq.gz
    ├── 35a2aceaa510e4c43f5563adde6280389343d560.nq.gz
    ├── 35ea4d496a4100421c797292cdbe8dbdf92ba9de.nq.gz
    ├── 3742416fce9d48332e755b67aefb6b1ff6699db1.nq.gz
    ├── 393478de76283f0389194ac2dbe525b8f6603770.nq.gz
    ├── 3d4359a697cb48a58759526cddc0bc07f1e0c6a5.nq.gz
    ├── 3e3c2f9d5e2bc9c160cda612c58f5fb61df672d0.nq.gz
    ├── 41ab4d390168fa5c04e35b967423e3d34bbc1b5e.nq.gz
    ├── 42027b3e421d3dfae62e4e60dc402a35d5e0b3c9.nq.gz
    ├── 435b503122ef3b34c27d473f14bb7bb753128727.nq.gz
    ├── 446ad40c79a90d0d2f1550e955849188a473b9df.nq.gz
    ├── 46d73c96d94031a6bc5d6d079d066c4ed16de1ca.nq.gz
    ├── 4921a960c420fc7d0737d05cc7b0cb3bca4c753d.nq.gz
    ├── 49222563cda582f7e04276284437766c814d4e13.nq.gz
    ├── 498e7280b914f781d501fb44df98420b1830c9fe.nq.gz
    ├── 4a743b4743c5545af7978e44573673a5b38b633f.nq.gz
    ├── 4aae9cf992bf1ef244c8d913d6a2791825dda9b2.nq.gz
    ├── 4aefbaf4ad68a941287badb7b340709613f83eaf.nq.gz
    ├── 4af0dfa82d100e869c754f05fad39c73ec1d9c82.nq.gz
    ├── 4b437f548c2abccfde15d4f92bd459908acc7ecf.nq.gz
    ├── 4b48ed472a7eba939bfc35b3d0d894a8c30f79ef.nq.gz
    ├── 4b6cdb3440792891f83db5f1b4bc86bd89fe5e2a.nq.gz
    ├── 4d0aad595527160317b4315a0492a2a2d5715abc.nq.gz
    ├── 4df5b5128dc9a7bbe4c753e2d231e80cd2221198.nq.gz
    ├── 4e4f84b6c29037306cdb56e03e6c0172ed95719c.nq.gz
    ├── 4f0ee125197f44a9959457a1fe01245163aed649.nq.gz
    ├── 4f2ac9cfbe47fcc869a6853fa7a0209a66b58d80.nq.gz
    ├── 505a810c0912225ac726c09e4ee9d28d191bf937.nq.gz
    ├── 513cc30b2b68a88569804e2b934a65a906778669.nq.gz
    ├── 52a2c622ecb276a49e8227bc0172c58481f232f7.nq.gz
    ├── 535556ab69e6538f2c26252ec757cdfdd92e4186.nq.gz
    ├── 543f1c5c7d960e13329ff32aca92ed1c21dc11a7.nq.gz
    ├── 54b3da2588e26f94db4221226081e10226e21e76.nq.gz
    ├── 55276d62148a85031d00fc7d4a8d85a94d256b88.nq.gz
    ├── 579fefe4183b303b09b714051def401bda16ff01.nq.gz
    ├── 596aa7e4e9606df28cca95a16e15599835090382.nq.gz
    ├── 59b7f28be427476790fc00c73967172ac39a9b20.nq.gz
    ├── 5adab579347056c06d93a61999d4c6c854e5904d.nq.gz
    ├── 5c2067af0ee422c548e38ecc6ed1a838282661ec.nq.gz
    ├── 5ce6ed998070927fc5a25b4780a62c19c7c72fb6.nq.gz
    ├── 5dcee68fff85e0f5a2a2e601676be069189cfed4.nq.gz
    ├── 5e089d8e1f17fed2703d852a0b92421030c112b7.nq.gz
    ├── 5e4ca4e7ab98b5caaecb0fb4787b1a0ddc9d8ab2.nq.gz
    ├── 5eaba4e7194296e514a9f7cab6aa4acaa652dc8d.nq.gz
    ├── 5f8aecf10d65fe6fba2816b3ad6a35f748254972.nq.gz
    ├── 600a6cb11105de1a29a57f62169d98413297eaf1.nq.gz
    ├── 6074fe826ba587d56b79c8ce784a1727af3d10f5.nq.gz
    ├── 608ce2a92f5d0f02a6b2c150715693be59f177f8.nq.gz
    ├── 609501c8c5930a400204046b9dfa63a8132e9086.nq.gz
    ├── 61637f3d62e874bbe17f6bab28bec54247669b3a.nq.gz
    ├── 616c3ddc9b2e8c4c4cbcfc7e39297bf0a61c9d4c.nq.gz
    ├── 628f241c32f42f8dbd2634cd034fca39d9771839.nq.gz
    ├── 6544322b16ab0d41d4ca8934f052fef979088eba.nq.gz
    ├── 6601b35bbc3011a79ebf5ce314a931cfb7953345.nq.gz
    ├── 674ebc78d5f71c90cc5aafb9e45de6a20f255d32.nq.gz
    ├── 67f352bbbf24a5a259db456053837e69555e6cb8.nq.gz
    ├── 68c0edceff17773ac679199fda13bb89a7ab9b27.nq.gz
    ├── 69e394b39c6c6ef8b9f5b00b082178da53a4af84.nq.gz
    ├── 69f53c139101dc79b879f65e89a014edf63adcb8.nq.gz
    ├── 6aa94c9b26179da3f8cea4b1d7e22278b05f769f.nq.gz
    ├── 6ab3124970f858328122021844ec410fd3b231c4.nq.gz
    ├── 6ab47b285f6973a6132b5eb1b0912c2a38089d75.nq.gz
    ├── 6af3bc7dfd0df4f6603291b3d45d21e2b49601f4.nq.gz
    ├── 6aff473e74c89f7154ca8473619bb367a5c95172.nq.gz
    ├── 6b155ef90f4691b9396deda0155d1245a0bd52b3.nq.gz
    ├── 6cf7bb3b016a55bfe93276adad972d655e28d308.nq.gz
    ├── 6d63ae84388155685809922a05038e951e7bf1b8.nq.gz
    ├── 6d81e362766416cd574ae79a2ac6758895eaf0bd.nq.gz
    ├── 6d91451752cb2a9b5a6967559957ced597647935.nq.gz
    ├── 6dbe57a51ba0b7a2820b5fa834a0842b9a2d084d.nq.gz
    ├── 6e365725bc7d4accb22dacbe3d2597d80c9e5f75.nq.gz
    ├── 6ecafc1a877b4fb4ebeefe1c9f6edb3bf568a524.nq.gz
    ├── 6f6bd54589732ed712c2f9e391b65b16c8aaec32.nq.gz
    ├── 71a22ee8678f48a93be297636b78521b903276c5.nq.gz
    ├── 71bb14a3252a4d4fcc3f2b65844a6a70f24a7a91.nq.gz
    ├── 7298285793390057f3cc2fd633342c12c9b4aad2.nq.gz
    ├── 7686c90066e3a6eae7f6811c1dda131bde2f1158.nq.gz
    ├── 77203ea9ead92a316d96114872ae681f5c8e3a73.nq.gz
    ├── 77576b58fed19cb7283200cf1392242f57b12aa0.nq.gz
    ├── 781de1a6d04f9a8fc683af800640e9d763e7d133.nq.gz
    ├── 79831cd412b4750c54d2fed6e8cd0c5bd3101cf3.nq.gz
    ├── 7a23b9102747e300142f088cb4b62de3c68f768d.nq.gz
    ├── 7a4ae97af1595720fea614cd2b60d35a01db9b4a.nq.gz
    ├── 7b580191a02897cc969273b75c59c914afb37411.nq.gz
    ├── 7b9b4f190b833cccf3a50e86d9d95e6d6f081a96.nq.gz
    ├── 7c939dcbb0f57f40094c8996af64817de786c531.nq.gz
    ├── 7fbef6dcafe217fe252735ae8a009173cae34acb.nq.gz
    ├── 8216472feeaf76b9ee0cdd981faaa6b7debdd9dc.nq.gz
    ├── 82cc2fc03d2d254122a22461ac62b795adaed161.nq.gz
    ├── 832338be80fbb2895138edef1d3f425aece02fa8.nq.gz
    ├── 8533ff8309c9969335d046da42046b0df071fdd5.nq.gz
    ├── 85ce31086eaf98602c4e6dfae54fb2844b606f02.nq.gz
    ├── 8659bea4e54a73c04ed278f542820acb5512f240.nq.gz
    ├── 875b263cec9f757c6c4d081c64d01cb22409718b.nq.gz
    ├── 87d7ca1cf87d1b5f010ced8dbf8d2c9e4e366599.nq.gz
    ├── 8a3469ac49478ef32a780d396330684d1d8cc1e9.nq.gz
    ├── 8cd7ba2fb72f9aa5d4e72b140fa869ffb971c858.nq.gz
    ├── 8d673f7854911f65f3d6708e7b86ae576c6604ae.nq.gz
    ├── 8dc9ad0e9638336da4296ce825c3fc4fb0f622c9.nq.gz
    ├── 8e9876d2f3bb7e40a71cf331dc9903a0fa09a017.nq.gz
    ├── 8fe51e4e5e214ef66091794f3442409c82358d50.nq.gz
    ├── 90365cf53991b07d53dfaec647c6d6c6adc53ed8.nq.gz
    ├── 916abd9bc8c14d05bd14327b72c7be5bdbf36d3c.nq.gz
    ├── 92f19a6987292be2d262639be77914ccfd34ece2.nq.gz
    ├── 939b410a4aa8821f554f288bbfefa5e1fa0dddf9.nq.gz
    ├── 94a8fe1878b0718bcf82023e226db2db68cf7272.nq.gz
    ├── 9501db2ade006136b5d9abb0642b81cd7d78e6e4.nq.gz
    ├── 951ae5096236616fbf57cfd42523f9cfc7733289.nq.gz
    ├── 955a454b5fe0dbcba783213b011a5df47d311ac4.nq.gz
    ├── 959d65df1a812b8896f3c5108983dab509bb5455.nq.gz
    ├── 9c76d3c5c1b750cfcf7aeb179832481b966cd394.nq.gz
    ├── 9e26679ae5f7ca791c56425bf910cf667a8b28c0.nq.gz
    ├── 9f855d7c1e081d475eec6abc4b7e7b08c7e5c56b.nq.gz
    ├── a0256a32308d7b2c885d04f885ef46936c0bbeb7.nq.gz
    ├── a11cc6c02a106aa3f14a238ac32ea2536d7925cf.nq.gz
    ├── a4c7796facdd54a093506d320b9c32b41a2ddfbc.nq.gz
    ├── a5175dc063d6eb311fddfbb380a7613ffae99bdc.nq.gz
    ├── a6dfc420f6491e724909559720931cd6f07fe333.nq.gz
    ├── a82d5fc54fefc622eda751e2a0bb96246cadc939.nq.gz
    ├── aa2dd1eca865351aecccd18ff85dd2c1b129235a.nq.gz
    ├── ad729621b234d20c7f7eac14b69ea763247ff156.nq.gz
    ├── adf34e498b31912da529f77ed908074c32e6428b.nq.gz
    ├── b58969c7445e234dc897d74595c88e8f81a8247c.nq.gz
    ├── b6122c10ee96dbba0a2b43585333a26855152420.nq.gz
    ├── b63538e431e6e4436f7e49fc6a98e692f904dda5.nq.gz
    ├── b7a1fadad3f847b13bcd20c437930bf680446642.nq.gz
    ├── b838d796e9dd8fcc7e2a15732e30d04bbfb1058c.nq.gz
    ├── b88295a802a7fb15715eb3a1f1463cd99ec293bc.nq.gz
    ├── b885df363d3fb294bb8d05642677986132c5790a.nq.gz
    ├── b9be0d7cb522126882e5d0f0197028f3ae1fdaaf.nq.gz
    ├── bb21e0c2d849a759e3419340e8c6877dd84547b5.nq.gz
    ├── bdebe4458c3fe2b3b9df8f0fea53351b44258a3a.nq.gz
    ├── be19b33bf5a8bd8259c0d8eff1bbf0fc521a2204.nq.gz
    ├── be4accd8044d9bbfff9aad0feaa1be2cb61244bd.nq.gz
    ├── be87fa3f34f26bd6a49433a0d0eb61c61c2fe62d.nq.gz
    ├── beef46dbccf661f796184a6c6ab92567987822df.nq.gz
    ├── c03e73f1a431b551a12fbb6a33001e5ca9cd11cc.nq.gz
    ├── c078ef34bb38548a0dc25bba2d9963d18df6758c.nq.gz
    ├── c172ae3ded35fa66c66989c215e7fc73c01e08fd.nq.gz
    ├── c32c3737bc19314a0e0d95cc7ab5c488496348b3.nq.gz
    ├── c32f6159b6f713997356270530422c09e43a02d6.nq.gz
    ├── c4315b9677af01a88790a924c3d4d45563f6c8b9.nq.gz
    ├── c4a6bb93241b40892e297868fa374aca652777de.nq.gz
    ├── c5b93bd0c9208d85743253c858a85f83bc696306.nq.gz
    └── c5b9acad094451b7dead5d57c1a84aec0ef0aeab.nq.gz

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

[thombashi/pytablewriter](https://github.com/thombashi/pytablewriter)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
