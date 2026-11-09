# Repolex Knowledge Graph of FilledStacks/flutter-tutorials

RDF knowledge graph data for [FilledStacks/flutter-tutorials](https://github.com/FilledStacks/flutter-tutorials), parsed by [repolex](https://repolex.ai).

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
rlex download FilledStacks/flutter-tutorials
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ea17632fc1b7f0d999550b05c43003d9ae5dfca6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ea17632fc1b7f0d999550b05c43003d9ae5dfca6
│           └── chunk-001.nq.gz
└── blob
    ├── 0007e2e59d758b4f39031c7a7551ba0555f78667.nq.gz
    ├── 0012359cc8574519c705031fe0c9df0ce0d2d294.nq.gz
    ├── 00be119e0806afc2646d2ddf44b12f387ef9d732.nq.gz
    ├── 0151266fe9fdd0a4a99dde85b9e28ec31ce1a193.nq.gz
    ├── 01546674b88049b3afcf7645ffc414310b54580d.nq.gz
    ├── 0205863421c75eee236cc46c4b674a4d951c1361.nq.gz
    ├── 02583d15449344c4ac5ec260300988183751e75a.nq.gz
    ├── 0259d89b144f50e2eac29ca14b333c23bd31954d.nq.gz
    ├── 026977f3a9e334b0fd1d23ac2f5f6dc38893846b.nq.gz
    ├── 028c8d383ee900b094bd2b77a46495c2b477c86b.nq.gz
    ├── 02f7bbf819e9e93750438bb66bff9ca2871186b4.nq.gz
    ├── 039e2f5208747728f5f4d78f118bb2403b90fd9b.nq.gz
    ├── 042f5f4792bb745fa20bfda1038b8ace600d51b9.nq.gz
    ├── 04530e0a4ba6d5c61b9ffc8b7f6e57ab947fd893.nq.gz
    ├── 059f9e7cf4a029451775086020cdd8f3452476c0.nq.gz
    ├── 05de5b85e3cb50b30098aad96a81bca81ba6f7c6.nq.gz
    ├── 05f2a189513e56af13c72e3301c60041e8a2d428.nq.gz
    ├── 0629356ea4d307534f780077cceaa5a295897482.nq.gz
    ├── 066a096b8ddf95f6519ec3ab9a5ae85c7e65d88f.nq.gz
    ├── 06b1f9caf35708b144dc098683afdf3755a94914.nq.gz
    ├── 07739f9c26a4ba93402ee201d2eef649d63705b7.nq.gz
    ├── 078de52434f87d1d6a697fd4be1e1297fb65ea9f.nq.gz
    ├── 08c8932d3591eb8b89666789892bb053147795a4.nq.gz
    ├── 091a970561641d1b4ec64ebc86387de6291d0ee5.nq.gz
    ├── 0a2cb0c768ddae75ebdcdc7fcbcc01d6593ffa5a.nq.gz
    ├── 0a2de2ffa820201ceb0bf7c13f611b503f2bb229.nq.gz
    ├── 0b96e2af17f8d562cc0d12a04543063e2d1e0aaf.nq.gz
    ├── 0bf4a92adf01c63916cf0d5e7315dd91a23f0087.nq.gz
    ├── 0c3ee084ccfb698624c209bac2f84341c4786454.nq.gz
    ├── 0ddb212cfd5ba01416a11b41fa903ddcc37ca1a7.nq.gz
    ├── 0de43291c583f05408b7c875e1350782bfe779a4.nq.gz
    ├── 0e4b8187cc607dd8dc075d107255377878e1af85.nq.gz
    ├── 0e4d85a64c73c2e5caa4450879772abdbdaeff94.nq.gz
    ├── 0ea18c803651d2c482390d9e5581c0a8e1fbfb82.nq.gz
    ├── 0ee1401ac06f4e4708dcf720ac27716a9dd135c1.nq.gz
    ├── 0f2bd04f24416aa6a61bfaa869047083d4846cba.nq.gz
    ├── 0fe9facff2ebaf6d576aa62fecea565efaff2730.nq.gz
    ├── 0ff78fdc72509146ecb29ab8ec62455fda7a8900.nq.gz
    ├── 106b8626756d85b71dd11df690e50ae431ce74a0.nq.gz
    ├── 1071dc6c5a092d68f9050b6c8238650f63c574f2.nq.gz
    ├── 10f6bd40df850a52a8d658f83a50fe62449e306c.nq.gz
    ├── 1164752033134bcc3d89c5fb203cf9c99fbf70f6.nq.gz
    ├── 11efa8a67e625e4a8891fbc6511578ad2563f38a.nq.gz
    ├── 12966b0e6a5162a9228dac57f4ba25684e073618.nq.gz
    ├── 12afd35e8cea5364db72697cd8f690eeb853b7b6.nq.gz
    ├── 12c7002664855fd6c42b1f090c80d4bc740599d6.nq.gz
    ├── 130d74a6fb1467d0977d6d95d456c6e525222478.nq.gz
    ├── 1331bf259a8f997860bcee9b6ec3d50d3a354282.nq.gz
    ├── 135075f61daf0431f5f76fd8badfe611847c3acc.nq.gz
    ├── 13b5078a8f7c6be3855051d2c6272348362f10f3.nq.gz
    ├── 13ceb078387b3a452b6c0964e35e49b82eb42605.nq.gz
    ├── 1778eae6d2eb0ba276c037bfa3b90f7254e2a494.nq.gz
    ├── 17bf736d7c130a349e9b0540ae23c215792fc242.nq.gz
    ├── 185d70110c9719dd93787ab6b0f28e29577a1265.nq.gz
    ├── 18cbc769bb6f26cfc7b7d187c9890d6eb099823a.nq.gz
    ├── 19dc5005ddc9d23abfaa0e539964864f8284d0ef.nq.gz
    ├── 1a2334159f4f6d2d0c1fa261d9841ad2ce7374f2.nq.gz
    ├── 1a273d4cbbac3f2a08fcb80046c295d331c09e4a.nq.gz
    ├── 1aed138b21215d79f5b7080feed5b2a099d16eb9.nq.gz
    ├── 1b723eebc2957851d80032aacbe4b7e5e158408d.nq.gz
    ├── 1b851e9722ab1cfdb42c3293b37c9a96653b73ce.nq.gz
    ├── 1c930a5942cfdd05a2212591dd03889ef598787e.nq.gz
    ├── 1cbe9ad71a9eddd4379180965addb9b00bab145b.nq.gz
    ├── 1d35c87445eb3121424465027d1eeeb4e519ee69.nq.gz
    ├── 1f07ed2c6c6b718608b293b591b938cf2860cf67.nq.gz
    ├── 1ffcd5a3db7824aba24da2bcf60706d4f3958480.nq.gz
    ├── 204b37e6e55e2e89c4aecb9d4c2ebb829129cca2.nq.gz
    ├── 22e56b9b06203eaddeffd676b18cf71dc1315afd.nq.gz
    ├── 2344fb42dfbabfbfb67354640ed1e52730e45014.nq.gz
    ├── 247b3bbb406d3c495a49a4c4bb0692858bea9a78.nq.gz
    ├── 248bdc4f89e891e912b6cb19d7dab50e5e01b5a5.nq.gz
    ├── 24f0f4b69c56a21da57d62c8d30ecb618d424dce.nq.gz
    ├── 25231b8d43af64359e23ea51147dd9652183b501.nq.gz
    ├── 257d41534d453d4a59654422a547ee8f4664daeb.nq.gz
    ├── 25952a7f3eb916d01d26302bfc77bdd997cb9a66.nq.gz
    ├── 2663d69af9a0d1008e6e4f016df22240643e83fb.nq.gz
    ├── 2667d74a56193f9bdf8bda7e989d929bbfe03d1e.nq.gz
    ├── 266fd9c74f6bb83a93de9b427dcd906ef008e703.nq.gz
    ├── 26c9bc6ae9b0db337ef6c2352beb5088ff8f97ad.nq.gz
    ├── 26d53dbd73723d7334fc9b1e36874465360de996.nq.gz
    ├── 27aa4adf5184e70301ccf74bfc672b3eabe61d35.nq.gz
    ├── 27d678681176117aafdb5783c95f8875bb209836.nq.gz
    ├── 27f74ba8ecbf2fb27656743b71e7d127193ce4a8.nq.gz
    ├── 2855fde6303f7f326c2eaa809650b79307c39fc5.nq.gz
    ├── 28f45f3e1750e33d14ab7f6066ffd67a3fe12645.nq.gz
    ├── 299ed635291d98cefb98b5088a5a016085d12e30.nq.gz
    ├── 29bfd35a2bfdd92b6e8b4ec2970f4d1eebf49357.nq.gz
    ├── 29ccb4f89e73bb0d5ce3a88e5a57e515c18ff3fe.nq.gz
    ├── 29cfb895967ad112b9a3ab88ed29aa95efe5c3b8.nq.gz
    ├── 29ed022a6d9cdb343fcf396a522fbd5867837f28.nq.gz
    ├── 2a1e9f73d8de746ee162d5303b98b26d1f8c75a0.nq.gz
    ├── 2a290c4f7429c295bee33b587dc995d1298ed652.nq.gz
    ├── 2a709b12afc559b115afa2b6aaf4cb323147e869.nq.gz
    ├── 2c9bb58d129ab3bee74dd01a6f2e3388466b5f40.nq.gz
    ├── 2cec84dfa0eff4713dc8778aad4981f58c7e7a8d.nq.gz
    ├── 2d4084260e2fc61e7b663bc088a1494bbc918e15.nq.gz
    ├── 2e1612486ef626d206cdf88b5fd523973ef4996d.nq.gz
    ├── 2e2a7f4bf6fad6dec614966841bce1782105eb93.nq.gz
    ├── 2e31d02424ed50b9e05c19b5d82500699a6edbb0.nq.gz
    ├── 2efc274d65b1702261a7b2abeef1fa289be95e37.nq.gz
    ├── 30dac4cd6cbd34db910ee90230b6601c6140930c.nq.gz
    ├── 3141dab3887de491c3c090160c0da7186e609480.nq.gz
    ├── 3148df72b8e5e334ee037bbdea2cfe89b40ddeb5.nq.gz
    ├── 31e39fe0f62bd9154e43936e89120b18feca6fac.nq.gz
    ├── 33aaae6e69b438f7661d0b333e31aca03250d53a.nq.gz
    ├── 33f0612f87b600e2de2522dec5dcc7acbf3d4c3c.nq.gz
    ├── 343791aaae4da541d80e38a7e461e22ac72e02b3.nq.gz
    ├── 3451eb0aa7dca40cad6842e6ac1b6c1f635e59d0.nq.gz
    ├── 34741b6f3c35052a375438a37aeb69f3b9937018.nq.gz
    ├── 347792c85531df2655adfd43922b8deb266e0407.nq.gz
    ├── 34fcde986aab0aae7f31fcf31b1bf31cbbaa43db.nq.gz
    ├── 35333ac246792fb94a1fad3e8156382ed0e8ba6e.nq.gz
    ├── 3660681d398100fd0e2dcffa089570eea893629d.nq.gz
    ├── 36815b2430ba291291c615aa7af3aaea16fa9ffd.nq.gz
    ├── 36a616eb8e814327fc5799eb68579a501b8e666d.nq.gz
    ├── 36ad43a55ddc0b072772005821b995ed021a3564.nq.gz
    ├── 36d387fbfba8edf999e34daf29fa4dbc3133e0f6.nq.gz
    ├── 3712976ec156e45d754108a72dcbde6270704eb2.nq.gz
    ├── 374492b3857040909f27cee25d851a1acc4b770c.nq.gz
    ├── 375f54fea530f9b3b2e8b9795c0816609672863a.nq.gz
    ├── 379da8e776780279c4ea9aef77ac16e42e00797a.nq.gz
    ├── 387f852cc7e8161ddec71931aa2f594e21721e72.nq.gz
    ├── 38a234329d4ac544faea6f3febeef030ce599b18.nq.gz
    ├── 38ca289f7c3a7167b4f1608e4a9b904a16d6527f.nq.gz
    ├── 397adab37cbf299eb7892061c4f81b559add7d3f.nq.gz
    ├── 3a9c6ff87d3b9d939e6d05656437610f145c1111.nq.gz
    ├── 3b3a7b99c401a4543ea0480ebc8610388dae57c3.nq.gz
    ├── 3b88ea3510c5d13dc4d7fb9ea4d72edeefb6f72e.nq.gz
    ├── 3bcd3854b5215bd7ee273c63f9a82f087362fabd.nq.gz
    ├── 3c4ac7db4550a5a6a604385516b1a6f40d68b04d.nq.gz
    ├── 3d2d6fbc4a87f5cca0f14beaeea19c69722418c6.nq.gz
    ├── 3d511e5d0ced270e0dfe8e19b3f4b4ca5ac76127.nq.gz
    ├── 3e1ebe1385649a279ef30fc5d13caeef41d0b053.nq.gz
    ├── 3e8555b66b44d50b78f4e4acb1400c8e291fa353.nq.gz
    ├── 3e8ec65e02ae55898a20982bae204c7af36a1ea7.nq.gz
    ├── 3ed087e4b7d4f54ae2ce8e1c568eb73d22e86099.nq.gz
    ├── 3f5b99f24435a3e6b4c424e298b79641e97f416c.nq.gz
    ├── 3f6b1248ccc5ca8e9c0236b2823708230600ad68.nq.gz
    ├── 3f91f5150fb4eeaa883f9c7776beacd6fa4a238b.nq.gz
    ├── 3fc0f5247696d6b9f5148a5141e5f045c98fdfa1.nq.gz
    ├── 40b878db5b1c97fc77049537a71bb2e249abe5dc.nq.gz
    ├── 40be47cfe02a32e032576c16a1a5c5c5750b781f.nq.gz
    ├── 40dbb3603386f74f3315dfffcb8c29e3686e6e48.nq.gz
    ├── 413babe28cc39723d8294622772c99a9500dd1b6.nq.gz
    ├── 4206873b1f767f6e41289bee2d00aeb5600c4553.nq.gz
    ├── 4289f72cf68ca9941856d25d8971638b7e003a55.nq.gz
    ├── 433ef67833e3e21d739fb84db01f133924d8c627.nq.gz
    ├── 43ad166d329ac81300e85b904b2be0f3032a22d8.nq.gz
    ├── 43cf7c88afc41d2eda9d806d65d047f55af4c776.nq.gz
    ├── 43e38db20675db5fb452252cf16da5c86d64c430.nq.gz
    ├── 43f01266562575a7eb5b4272c6f050158f179c37.nq.gz
    ├── 4524aca0a5747706be9d3244b846773cf92870d0.nq.gz
    ├── 45d3e880351edb9810d43ccbb813a792fa2ffb1f.nq.gz
    ├── 4617663735aa3e29755b9b5c43c91040b3f997b4.nq.gz
    ├── 46c58630e678ffbb58470872fd83f825cc26ab16.nq.gz
    ├── 46cf324eef23c54b33b61eaf37ba1c814488003a.nq.gz
    ├── 483fe20f66ff6816804308b16e0a2d55914b34ba.nq.gz
    ├── 48443e8be741e1dc47febb33b7ed92b374798bbc.nq.gz
    ├── 48b04eee9c58bc21be653a621c619f530123dba5.nq.gz
    ├── 4931eb8cef8f5004ab8a400453d71d04d7432ea8.nq.gz
    ├── 4986e8750fe5e7358902fbb61e7ef635606c7004.nq.gz
    ├── 49dd9b81519cd5df8dcef6ca2562faf540bc405a.nq.gz
    ├── 4a2a6e1d2bb707283491010f5b66791df672ffaf.nq.gz
    ├── 4ab6d96d675e8ff04e383be13ce059f7f5f17707.nq.gz
    ├── 4b12870efd07e8eb29608c323ec98e4ff9f1fe04.nq.gz
    ├── 4b838c31a62d5cebdf00cf5f9759ab93388599bd.nq.gz
    ├── 4baca98de5e7fe6ada0ade73b223476a0ababd0b.nq.gz
    ├── 4c09c1e238b019bf3f0cee1931fc416eb60c6da3.nq.gz
    ├── 4c20883ea8367124bc2e3e516834d9a1b815a497.nq.gz
    ├── 4c246220d147b4530aa8d339b3348f80d0f13111.nq.gz
    ├── 4d089672aab51f78eefba66d0c7ad59dbda91324.nq.gz
    ├── 4d2a97b890bf13e0dce542aed02a90df63acaa00.nq.gz
    ├── 4d6f0251ebab5b193adacef0a71168e5fe0bf458.nq.gz
    ├── 4da436d29d206d9541e37abed1ef4c96c4bef6a6.nq.gz
    ├── 4dfe1d19e0c58ce89ad7f28afcf9f84f32dc2f2d.nq.gz
    ├── 4fab7a21e8a82efda60d780211e816547ae8090c.nq.gz
    ├── 4fac7cf205ce3ce98009265b2763d0892de59098.nq.gz
    ├── 506471a1ad363feece9ea81529385b10987d85d1.nq.gz
    ├── 50f38af1e0c5351aa0e44816373a49d7f99a4b86.nq.gz
    ├── 53ef17ac4b5e1583ab813dec51e8e7ba6643518b.nq.gz
    ├── 54c9c712985f6c70c0e0a1f9b6005e2819b063ad.nq.gz
    ├── 55813afadb56e14a6679b0331067322a061ab591.nq.gz
    ├── 563872c7680aed4d9f8f7a4bc4f3c1506c2cbbc1.nq.gz
    ├── 56b9a53194c0f9bf74d462ec9c5f42c15b71f619.nq.gz
    ├── 56bfc2c4d6be0e426d957ef6df37b2b4ca09b58c.nq.gz
    ├── 56cc28afde05ff4c266d3ca568cc3f42576f80df.nq.gz
    ├── 58c46788cb4739f8c0de3f8fca9cca113e547bcb.nq.gz
    ├── 58f884e5d796333813ba3b7d8430a94604b92925.nq.gz
    ├── 58f901afe4e9e632bb0f7a54927d1bf80fa80c75.nq.gz
    ├── 5a5b8bec22fd0c8b1358d12f53b7e87755be63fe.nq.gz
    ├── 5accd22b9a33e45c008a35ae4d343efcced1200e.nq.gz
    ├── 5b2b2bd4e49953cd44f778af0459b96eeda70c6d.nq.gz
    ├── 5b8406e2ff965149a30d8f81f45e7b6d44008083.nq.gz
    ├── 5bb623fc4cf79210e4cc6534cec18b3cf39bd381.nq.gz
    ├── 5be59a14350cb0b29eeb61a989ce3189db1cb044.nq.gz
    ├── 5bed422500f5a85f7bdc675483a4cf3525103f31.nq.gz
    ├── 5ca563a43d8dc66931e2832f9d34e81e2b907093.nq.gz
    └── 5d4c38e3d2ceca6b9c031ea3c5ef4a80513fcf4a.nq.gz

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

[FilledStacks/flutter-tutorials](https://github.com/FilledStacks/flutter-tutorials)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
