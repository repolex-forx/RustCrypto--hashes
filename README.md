# Repolex Knowledge Graph of RustCrypto/hashes

RDF knowledge graph data for [RustCrypto/hashes](https://github.com/RustCrypto/hashes), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download RustCrypto/hashes
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 26facec5f38b0e3eaf8f945c2f89981f61dda386
│   │   │   └── chunk-001.nq.gz
│   │   ├── 8af25eee87dc09af19013afe9723599d2d9f5d9c
│   │   │   └── chunk-001.nq.gz
│   │   └── b5051e5a5e7dc86a6c27c1ec7a390744ebcfb97a
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 26facec5f38b0e3eaf8f945c2f89981f61dda386.nq.gz
│   │   └── b5051e5a5e7dc86a6c27c1ec7a390744ebcfb97a.nq.gz
│   └── repolex
│       └── 26facec5f38b0e3eaf8f945c2f89981f61dda386
│           └── chunk-001.nq.gz
└── blob
    ├── 003eeb41c05931fb8704af4e5ab6b565174e5654.nq.gz
    ├── 0074e2a2230ba0892ca784fd15d21d0ca3fc8b34.nq.gz
    ├── 00fe6fcd918bc93c653db5161c5cb9e175444766.nq.gz
    ├── 0146f801bbc8b316b3c5dd517b17e8a3c211c803.nq.gz
    ├── 01ff1777044c9e5865ae26d47e21456b88796975.nq.gz
    ├── 0227deecd11b1ffd0914abb73fc470d6688f2747.nq.gz
    ├── 0228c1266644cae522c856da135633c5591560ea.nq.gz
    ├── 027da3aa26215a26fa7299aaab3b9cc7c2b10fdb.nq.gz
    ├── 028c38aa3e2fa0a4192d344bf8b417eea9ae8a37.nq.gz
    ├── 02b9fa36e97bc8c083f7ca718bb25869a29f7ed6.nq.gz
    ├── 02f1093ecd889d405034ba4ebbd93e1ba9679ef7.nq.gz
    ├── 03947f64c3682f8dd04e5e0359042a116b546ca6.nq.gz
    ├── 03cd576191ff080f86adaf3573fa550d0e6a2542.nq.gz
    ├── 043262805538a91cc6651b994892d2e4d5544cdd.nq.gz
    ├── 0490fcbc4cead9a30543af26f9f4ee751676c545.nq.gz
    ├── 04dee4854b522d6a42193cdaff03a94caa8e84a4.nq.gz
    ├── 057991cb7fc8088077578ad89ead82cf04327f3b.nq.gz
    ├── 05fac74f3d8d7922d55ffca20aca471b8aaf4aff.nq.gz
    ├── 06633982e8cd1c343498dc4f38ceb2ee48b1e22c.nq.gz
    ├── 07e61cb32a0aa371dbef971a7517de3f6cc86699.nq.gz
    ├── 08335f758f8ed56372666de0ea03028cbd1dbd57.nq.gz
    ├── 0869eed8113492d8033673fbbc4297bec4ea01e7.nq.gz
    ├── 089120085008d32909f5273105fff881a55a53d4.nq.gz
    ├── 0896f613055474ca4f2bc51af6a71ba99ec22457.nq.gz
    ├── 08ec16099a17be09159d96e26c184ea79befec9c.nq.gz
    ├── 09de6a1d1c9d231a84530efeb2629ac8ee565c50.nq.gz
    ├── 0a21abf5725374ea3137931b5814913e01284927.nq.gz
    ├── 0b189becf944e865524bf7b1fdb80553da51fac2.nq.gz
    ├── 0b82922331e46d7c8700a7e645d5610bab771b42.nq.gz
    ├── 0c2d45c7681e2cf0865e14e9fe8de9ecfbc1db55.nq.gz
    ├── 0c50497199aa2212aec023b83ebb86778d90309a.nq.gz
    ├── 0c606d3dc818374ec7b435bdbdc200c224f02bdb.nq.gz
    ├── 0ca4fb48fd9c33a3c2f99c0a47c05e61456aa01c.nq.gz
    ├── 0cd648f76b488a00f8fa6bf50b3120c7e1d8464b.nq.gz
    ├── 0d9615b08fc029300f066cddf49d14dc777a15c3.nq.gz
    ├── 0d9e10daded4a2220a425596158198e35affaacc.nq.gz
    ├── 0f049b864e53481477b56dcb383180a7e1f61479.nq.gz
    ├── 0f1b2bf1f83a34944785b6f4c5646686451a277c.nq.gz
    ├── 0f26a5da6c874298be5efad7dd3c3d4023832487.nq.gz
    ├── 0f32fc224ddaecc158454e65e02e821479c83d96.nq.gz
    ├── 0f8ac73f9d5a0966aa320ef131e1577c3a23ec27.nq.gz
    ├── 0fa8305344b8e49de1cdd6415d47b49d5ecc8893.nq.gz
    ├── 0ff48acbc22c4e634321396e3ca470ce7bc229a1.nq.gz
    ├── 100a823ccb7dbbd84ed100ce827e9d03ea044c3c.nq.gz
    ├── 103837957171c9e47eccf77351817c56e753e0d6.nq.gz
    ├── 10570b05cdcacd26b335b2b3af5891e8e6b013eb.nq.gz
    ├── 1067c423604c3301a0a5b038984af611ce74e455.nq.gz
    ├── 108f3f1088010fb35767d046b2812b9e3b456601.nq.gz
    ├── 10b25f6349e994a83a5e8fa90fda32a5d65c17df.nq.gz
    ├── 10d4796767012fcb97462213f394acc2e1a47d03.nq.gz
    ├── 113a7460a58753fe460fda4674b37127cbddda7c.nq.gz
    ├── 1140491119fe7f00b0e44d507bdbcc796b2b9470.nq.gz
    ├── 11d191686916a833cbedf1eef8deab793e45c2ce.nq.gz
    ├── 11efee4f88ea7ba29b4fd09337ec1f59ed087456.nq.gz
    ├── 122de3971d024919c9e66e1ceeb0aadda7e06ac5.nq.gz
    ├── 12635130f98cf24cae3b95e65c2e965752c185fc.nq.gz
    ├── 1290d4bedee483cf49db7379d56040ebcab68909.nq.gz
    ├── 1381d7f5c254e4af41a1329e86a088ad8a0e3a83.nq.gz
    ├── 1384e2c8967d24ae6e6c587a2ce313014f04551f.nq.gz
    ├── 143ff244cfb355eabe6b8260bbfb3a3a49d6ca65.nq.gz
    ├── 149e1ec17ffea81e5b7a0cff74bbb62b8e6dafe7.nq.gz
    ├── 14deae77c0f1a962258cbc74cfb65c1de6b42858.nq.gz
    ├── 14f8d76d1d9d8a6ef7b323ff2af5a310c9337674.nq.gz
    ├── 160291528a707bf1d7e2acef652291af3b798258.nq.gz
    ├── 16053c40f3ff637a0c73f2343e1ddb9e44ba8bab.nq.gz
    ├── 167a27d1165d9f6833411e2c94343dce72582cff.nq.gz
    ├── 16a3d6f6f2feba76acdb65ffc2ef340f8ca5c42a.nq.gz
    ├── 1705d414cfc570f59fdadfc3c773c02eac1e6ad6.nq.gz
    ├── 179ec3236b10ff02fe8fa90ff2c893e78cf2f0bc.nq.gz
    ├── 187d4b1bb971b9bb69974b3e8a654aed80ce7490.nq.gz
    ├── 19156f410656aaee29cf0fd13d9f3914ea32be60.nq.gz
    ├── 1921782840c562b8e4097c32197f74af08a75bb3.nq.gz
    ├── 19e3611c99ad56b0d793e3663b571df16dcdcde3.nq.gz
    ├── 1ab4d78539457601bffe1378cb4bc6c27144bdcd.nq.gz
    ├── 1ac867918fc36ec66e7d359d5a5f49301da523d4.nq.gz
    ├── 1b09961fa36c437f7568b08de41d3f03cdb37ba0.nq.gz
    ├── 1b597ffd901e74ae8332f531d31f41ee395a5c6a.nq.gz
    ├── 1b600a9450bb3cb29e9c5ccd5a09a3b9f8e3ebe7.nq.gz
    ├── 1b6257940551d213aecc78e68727e921d6d463e1.nq.gz
    ├── 1bb31ed4d2c0127e17a46750780462fa26758b02.nq.gz
    ├── 1cae786b4c555ec1dbea7e3a250285f4137ae477.nq.gz
    ├── 1d04a59176c77169cff04e3385fa5d25fe2426ac.nq.gz
    ├── 1d1c80dd5d41aac04751873708a0d44c6281c695.nq.gz
    ├── 1d61e4774c8ade75773483507da14b2ceb38e12a.nq.gz
    ├── 1d8353c6bc4b5a8012fa669a26654d47ab5ca5ef.nq.gz
    ├── 1dd1bd21e01169b386e05841949c6c0927b528f2.nq.gz
    ├── 1dfba8772414f1be289bab02aca0f194c63a636d.nq.gz
    ├── 1e18def83cc45400deaea5e1196f69437d3d28de.nq.gz
    ├── 1eb321535426d86a4cbc411c0a9dfa7749663d3e.nq.gz
    ├── 1eccd7df253154cb25bc3545eb7edd52a84765e2.nq.gz
    ├── 1f1d17cc748dee18ff7e96451dda756de5dc8d42.nq.gz
    ├── 20a1926bd5bbb8edfb3f8f20185b741a11b8f1ea.nq.gz
    ├── 213d9233493923b533b0a9810f2629e413e2e7e3.nq.gz
    ├── 214d845bb8a9310c99ae58968a077fcfd5761fc6.nq.gz
    ├── 216f74fdfc00c79deb341e92c67be90853d7eeba.nq.gz
    ├── 21984f530f553d0a49298b4858456c84e9876113.nq.gz
    ├── 21e6deadc01f90ae56af82d8f8d23d8430dfe583.nq.gz
    ├── 2248d95f4e44531f44ad2e6161c3885fb2577665.nq.gz
    ├── 22d8e7890c697e83da28bbc58ded5bee5cd7fd07.nq.gz
    ├── 22f2ca3a6c008f65ef3eb0af3f3864401b4dac92.nq.gz
    ├── 2329694829d0e6b416bac075deb72be6319bca54.nq.gz
    ├── 2380f633bb8c3f7073a712f50d91bb012f69c37d.nq.gz
    ├── 24ade82aa74d099bf6b5123793d4556d1a70ef54.nq.gz
    ├── 24ce9ee34a8655f5cad718c8a4c4cdbf1ea2e588.nq.gz
    ├── 24e95b69d774d8c016aed957f982a78a1713bd02.nq.gz
    ├── 2509429442ac211eaccbc0e8a62dd247f0fed1a1.nq.gz
    ├── 2654c2bb50c378dda499c724712b4c95f0cc20a2.nq.gz
    ├── 2742a664ef45b6ad143dd8cc5d25139597b34e57.nq.gz
    ├── 27862f8568452b139441e4d3a1ce15391f49eef2.nq.gz
    ├── 27c4abbec35b5997c62694d14e2c8783ca2b7c7f.nq.gz
    ├── 27c77b19215db99691c646b3116ad2ffe397d279.nq.gz
    ├── 27ec65e410fde5a6aac288a794dcab6b6725c123.nq.gz
    ├── 2858e8ae1607987fd957009bcfdea61479a6ce3b.nq.gz
    ├── 294d5c30aee667884f4b62dfce753c17697048e8.nq.gz
    ├── 29ddf67c64632a264bc240ab52f10f139e104685.nq.gz
    ├── 2a198e488d0561e2bf253d922a979b174eb0614c.nq.gz
    ├── 2a804b396a77406396b015eee6a3ac04f63e7954.nq.gz
    ├── 2ad3f5ed2249ee462a6add1291426d7efc5c32c5.nq.gz
    ├── 2b6c59abaa8537d517b06bf4ee5b4d5659a25610.nq.gz
    ├── 2b9a1400c4bad3de0bf97076e37dbf1c9aa49644.nq.gz
    ├── 2c404cbe21f828148429d11e79ddaf1e21c1b04e.nq.gz
    ├── 2c4d2d50301aa00166706cdf7e33cfc2f006e977.nq.gz
    ├── 2c504e309b46e0e885199c2aeb8c1012395645d3.nq.gz
    ├── 2c7653ae8e9033eb6e2ee4f467197d0705b1487a.nq.gz
    ├── 2d57688f9b83a9f8a4fcf2d424336c5a957d3359.nq.gz
    ├── 2dc5e15e282b276ee6965fc157ce98d88846a8d6.nq.gz
    ├── 2deca402fbcf6e905c7151381c85ff0e44a519cf.nq.gz
    ├── 2e2781c4c3196766d33308741b343f1e8cf7fb2d.nq.gz
    ├── 2e28b05d0396e3bb16db51fe2b756e452ded7028.nq.gz
    ├── 2e5c755d4a90d77a383d8d80f7221b574177a863.nq.gz
    ├── 2eb8250d71120fb57db07cdeef8b7e6ebf6e1c2c.nq.gz
    ├── 2ec54977ee845a3b7126aae39df9c82b0bf1b43b.nq.gz
    ├── 2f6664b4367c4c19aea0555d91bab0e05616eac3.nq.gz
    ├── 2ff4e474ea51d57863973d3b3dd86deebc14e027.nq.gz
    ├── 304f783bae957032b5cb2a26b012b60007dae52e.nq.gz
    ├── 308d4d5f0ae3c69fbf04b9c86fd9974c37c24fcd.nq.gz
    ├── 31f1fb8046d1932a6d3db63c77a2febf8e659b60.nq.gz
    ├── 3211131c75591e34b480d720e9c32d7682b2dca3.nq.gz
    ├── 326570d37fbedae7d6ff84cb3784f2f2f7779dd8.nq.gz
    ├── 32bc75fcac9ae18461bcd25be68645e3f52b6457.nq.gz
    ├── 339b73e54197e85f99db271021d260e588a90426.nq.gz
    ├── 343ec6d9cead4861c5262f836df3c919a8683f09.nq.gz
    ├── 345e7cff28af718471f159eb42cc41689416ca9c.nq.gz
    ├── 34856a314892979e11c160726c7fc87c23187742.nq.gz
    ├── 34e6f153b64544774e9c0339e3e6d4d128db10ae.nq.gz
    ├── 350f945879ecd876ce39face0b0e14d69023353a.nq.gz
    ├── 363dda755e313c50bfab44b9b63b9fed5aca79e2.nq.gz
    ├── 36b99b673964bfabb3361625d2fec1d2fbb85797.nq.gz
    ├── 37ad56a55470a0eac6684a4a38cd8f088b60663f.nq.gz
    ├── 380a97488b4a48c3977fce7ffeda426566797565.nq.gz
    ├── 380aad8cdff0c4b8a2954601c48a3e8ab32d58b8.nq.gz
    ├── 388c48eedb1cacb776080049e73834778a8da4d7.nq.gz
    ├── 389a125787f3625171cc47f1bc005d3003b493d6.nq.gz
    ├── 38aca3404d25d82a4186d5a046af544f3d0e344e.nq.gz
    ├── 38d928722aa78f7492898a6ba9d7486f4a0b1a21.nq.gz
    ├── 38ec37d67a9f904a44863a71f29ae0fee934df2e.nq.gz
    ├── 390c10a07d27cf028007fa39f8ab603614e0379d.nq.gz
    ├── 3910629f862ff5a4041c8aa049d4d16eed495389.nq.gz
    ├── 393c26be4571e73474829a01ff0b525588eadb2f.nq.gz
    ├── 393d0acebd1cb819b00a8d382444ace7f9a79bd6.nq.gz
    ├── 39dfb6c2df1f02ada8d116bccf93febeda1046f4.nq.gz
    ├── 3a4111937e6090e27f9dd0802612415b736d683f.nq.gz
    ├── 3aefbff65b6019240ed0d7c274f20c53fbd8b9f7.nq.gz
    ├── 3af97a6549fa66bbf869178b08bf56aeb31451b0.nq.gz
    ├── 3b271bd549ed5341ef09e3f8c44484604e0f5011.nq.gz
    ├── 3bbd8523e91d8c84c472a42d5a6eb0ab567f1873.nq.gz
    ├── 3bc290b542b09af5fb463f82ec73470186ce4205.nq.gz
    ├── 3c3ab8facce9063c162fadfbfec7e768f92f9cfb.nq.gz
    ├── 3cae19e5da88acca5f600c5a743c380d02c41abe.nq.gz
    ├── 3d334f71c165b9be7e387237400362eee8595178.nq.gz
    ├── 3d5186167b8164d9abb2a26f204be792aab18145.nq.gz
    ├── 3d7cd6a74bcea677655e03ec4b8b93cbc1f8efd8.nq.gz
    ├── 3d99cb173a7be0e4250c1af61645fdd69d7f8288.nq.gz
    ├── 3dcbf4062ffacea0ba464d5db01ac460a36c1844.nq.gz
    ├── 3ddb0a1973bbb278d9d7183a0caae3b05d187d16.nq.gz
    ├── 3de2dff70da6fe7db0a4c7acbd9b458beaa1aa80.nq.gz
    ├── 3df32e738e890973a93d477e6ad96bcf0c133269.nq.gz
    ├── 3e4229ec646383b7868b28a8ec8d400702485f18.nq.gz
    ├── 3e9aa1f31d2380db697ed7ce3af7d198f07b67e0.nq.gz
    ├── 3f6d643839fe7be82b7bbe1a2c74a08e7b748468.nq.gz
    ├── 402f3f31870b14e719084a1c9c64cf0ee085ddd5.nq.gz
    ├── 403073d8388c8e898aa65823fe5d54b4e4c5c2c5.nq.gz
    ├── 41197d1197b9975bf7057890960f2580073b3019.nq.gz
    ├── 413c74c63ad8b1beda484691492c3a48506b2a87.nq.gz
    ├── 4177898c973a45894be60246e0cdbb91357cc8ff.nq.gz
    ├── 41da3e0cb103ea3dbaf07db602caaadafee4931c.nq.gz
    ├── 41e814e8d248380e3457cde0a05ad3d6c8695fb4.nq.gz
    ├── 4222b2787d0273459b64556c59b61f740c3a842f.nq.gz
    ├── 4257b4f1f60b22ecdeab1a4c45593ed0d8dcff87.nq.gz
    ├── 42678d3c8be5ef7275229d102113df1db4b4d686.nq.gz
    ├── 430d6b5fb9c79dd71b526d5181f692e8bbad4297.nq.gz
    ├── 4316e96f1d22feeca1062a99209b738358b9f205.nq.gz
    ├── 438ecff677e0b3c807224ddd42cef8ad00a8f238.nq.gz
    └── 440682ea77e8a734248280c7bc9e61e9c9ee9387.nq.gz

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

## Source repository

[RustCrypto/hashes](https://github.com/RustCrypto/hashes)

---
*Parsed on 2026-05-10 by [repolex](https://repolex.ai)*
