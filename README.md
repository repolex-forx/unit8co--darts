# Repolex Knowledge Graph of unit8co/darts

RDF knowledge graph data for [unit8co/darts](https://github.com/unit8co/darts), parsed by [repolex](https://repolex.ai).

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
rlex download unit8co/darts
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dcdde2414f07f13b3bbb095428d9c6cc41492588
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── dcdde2414f07f13b3bbb095428d9c6cc41492588
│           └── chunk-001.nq.gz
└── blob
    ├── 004fca5ad124272922c949c025d3cfe166203917.nq.gz
    ├── 016dc82ec7cd3f25cc9918a5f84c434981b621f8.nq.gz
    ├── 01e05c61f44c4265833531f787b442d581f48aec.nq.gz
    ├── 022b84144a13532f40383d9c8549d43cad760648.nq.gz
    ├── 02f646d49fed764298f4719e7f7ee2ef4844d2b2.nq.gz
    ├── 03f2d40ca011c51c864bef3112e24006be2a773e.nq.gz
    ├── 04347c7dac1b24318b55c43138100e5d346c6d44.nq.gz
    ├── 060c3164a8dec39bd71de9e6e2e8bc1c4636ea54.nq.gz
    ├── 0693962c45dead3c38be054d676992feee5bc34d.nq.gz
    ├── 075f7f83ea583f5d609a30ac7025682baaa49663.nq.gz
    ├── 0d0e344c1e22b7af916d51b84b829e858816d0bb.nq.gz
    ├── 0e5c7214dd3f05ec58229acbd8a30300a00cc88c.nq.gz
    ├── 0e92b972c0b4ef904c832f652a86cf6c3e53644e.nq.gz
    ├── 0ef8c7884ee4297c7063c51592931845a3307127.nq.gz
    ├── 0f32290ae6660b98f0ee49b879717b4d366b92f3.nq.gz
    ├── 0f3cb64c8ff2a9a7a7a0f12073cff2b1ca70a94a.nq.gz
    ├── 1107c51d9b60944e4b3bd7f4a8d52927f92b8f5e.nq.gz
    ├── 1126227e19a49257801c0680c84fb0d8c0dbb098.nq.gz
    ├── 118cedfdaadacd241648a40fb8dedfff07063b72.nq.gz
    ├── 11c69845cad9cc3d335d58d6b4d8cb11f2dca20a.nq.gz
    ├── 123b1f96c19d397eccee244be1f5dbe96a506084.nq.gz
    ├── 12c2f17901e6d0f89fd564d4426cb4881883309b.nq.gz
    ├── 138978febd0aeb39464527327e1822efbd01f6f2.nq.gz
    ├── 1477837371558c487da42226e17128ea7fdecdc8.nq.gz
    ├── 14a54dc5bd22763c013176a79385171aa05b8568.nq.gz
    ├── 163a24416e408ed5f5789daa1c2eaacad0833542.nq.gz
    ├── 168f483387535a300249632cc887bdd9699dbd2d.nq.gz
    ├── 17d22449d0e71caa57a8218c9e27a45c025621b3.nq.gz
    ├── 18094ebe3df252a9cbb7739a0bf78ef9c6708308.nq.gz
    ├── 19bbdf495e290d714001d2ef92ab3277dcc31b14.nq.gz
    ├── 19c055b3c8485db776ce2ac92c68f21921aae9f1.nq.gz
    ├── 19e83b865266a8cdf3d5ff70d9f14cf6fb4860a3.nq.gz
    ├── 1a8934f6e18e31f5376a23d101e79f9f05715240.nq.gz
    ├── 1af9e261642a740d89e661fd4b70dbe82db8035d.nq.gz
    ├── 1b433d4b440f08d00f884756d88a48ead74f4598.nq.gz
    ├── 1be6eee494cf52d3768958232e5ad284f0e92eb6.nq.gz
    ├── 1c92fc4f62e0d3013d6afa4ab14a71990ac3c09a.nq.gz
    ├── 1d83261169b71d6f47b0a1c70661596db31ee4a8.nq.gz
    ├── 1fda14cdb12e398994f55069e38355325ad7c49a.nq.gz
    ├── 203c98e715b7ad919e3fa1725a085ef73e8687ae.nq.gz
    ├── 204fee7210792831044f2b45bdc81d6e4cf7269d.nq.gz
    ├── 20aa96f359083b6b6018aaa7d6e724e774d6ff9d.nq.gz
    ├── 21c2dcb390c80183670171b02cd79ac0af967731.nq.gz
    ├── 224ac83ea2610fcd2cfdb574a5c9c20f54050dd0.nq.gz
    ├── 224c276bf4b57f095a6ae0f04b2210814f19af6e.nq.gz
    ├── 22b15aae2e2842310d1c48db3b8e542f47d7d925.nq.gz
    ├── 231cf764c7c1e3ce8b1282dda8db7077885ad99c.nq.gz
    ├── 237589a64228a9bf9f065be1e7e88689745225d3.nq.gz
    ├── 23a8e85834d0f810fc340f752cb5ff7bfa5976a9.nq.gz
    ├── 25082e5488733c1e2353d9041d78d62bb781f880.nq.gz
    ├── 25e84bf3a06ba58701cb46bcfc9c64bbdcafc80b.nq.gz
    ├── 274a273beae0c39db368259984a6d6659a0caa7a.nq.gz
    ├── 27a8bf63adcfa60ebe0cca062a93fec2072d37ba.nq.gz
    ├── 27cf9342d96dc86666ab5ddecc418dd00272f1ba.nq.gz
    ├── 280100547a31957c8aefaa65e7a0a13091086d47.nq.gz
    ├── 2810a3cfe232d3b32c0711688bcbc045e0d13d09.nq.gz
    ├── 2891d0f314e9a6d163cd020642251fa94501fa81.nq.gz
    ├── 29149c328765a090e126b2f04f93608ffdb9f762.nq.gz
    ├── 2932ee5b90eed2c050fc65c1bb45f13852f84407.nq.gz
    ├── 2949f6d9dac3f084aafac50f60cab2a850bba2ba.nq.gz
    ├── 2a2583f3518938cc1199eba738cc579ed591a9a5.nq.gz
    ├── 2b1afd97ec84747a9760f3f27b8657f480808fc7.nq.gz
    ├── 2b48ef3468225f06f82e53e6cbc33536906a9946.nq.gz
    ├── 2be72fe20be051094ef648a38d7349bea4ee24c5.nq.gz
    ├── 2c19d7e725d3bcfeaf6e8a24e1f358d0655bc0e2.nq.gz
    ├── 2c905f7688b74139893629f9aec504b6cf22129a.nq.gz
    ├── 2dd9e9d62b537abe42659109424d74c87e864a2f.nq.gz
    ├── 2e5a484b4158e46804712027b5c0061b5e78ff18.nq.gz
    ├── 2f0518afff0f04a2884665545381c3ed38b2d82b.nq.gz
    ├── 2f56162d4073343fd1d9a1f712c5b26252613c28.nq.gz
    ├── 2f9dcaf6139d0ce2f6078f15e9df9fb4a21992cc.nq.gz
    ├── 3021c5ea68bd42de4e044ab3c2745d81703d9db0.nq.gz
    ├── 314100abe08c0c42d92cd9bf36642a3bb5a8d0c8.nq.gz
    ├── 3164c4e32396237a70f8584207a20db2cf04a8f8.nq.gz
    ├── 31d8c69685d9c5cc6ef5e6cd70976e69f6a84b67.nq.gz
    ├── 338938e780a3278a37474e089b9bc045583dad01.nq.gz
    ├── 33906b1282ac850128e7b1404d6aa73ac22a508c.nq.gz
    ├── 3391a1f398832e6589470ef6b16975feb3704133.nq.gz
    ├── 349652d5b558d04cb5916ab113781d8f965e8ae5.nq.gz
    ├── 34fdbe1fa1f987b9a61ddeca61b4b497f38e0fa0.nq.gz
    ├── 351a7c9af285268bc402901c6a2bda3834559aec.nq.gz
    ├── 363415718b95f4a5f6b0e07d4ecc482d8b005ce2.nq.gz
    ├── 366dc591304c54c8a9a3aab4b1bc2c3ce54f6b41.nq.gz
    ├── 36ca8d5296c9c79c6d89ef97b64f46b164c753ed.nq.gz
    ├── 36ea642b9eb1ec57a8a27fdc4870546d5af68ea4.nq.gz
    ├── 37315109bf465c65bd6e286445687e1b60b4c2fd.nq.gz
    ├── 383c8672fd820c0883650cb303ad887d71675176.nq.gz
    ├── 385ff0e74858c598d5b59f92ece689436ec02a10.nq.gz
    ├── 38b98cf41571203c80c0512232da51428a47aa9a.nq.gz
    ├── 38d9a15858db1a279f1356fb8e04bfe65fd30763.nq.gz
    ├── 3a316ea5a853a02e2e9c23fcf61eff8bfddd8ed5.nq.gz
    ├── 3acc31fb54c23d4e4a09290549a8b43b2a1faa5d.nq.gz
    ├── 3af1e5e06563868f08db599a7d4ddd8f6b1af2ed.nq.gz
    ├── 3b3250c088b4bf471134196c1844d7b022c4930c.nq.gz
    ├── 3bd6a0ce7f6c76660b60a6169980591d989c2dd1.nq.gz
    ├── 3c853efd6e93da3c6d0ae158edc3587b79cce9d6.nq.gz
    ├── 3d37e3cc3ab357b804b7ccd3314084fd28823371.nq.gz
    ├── 3d653e411363048b55a86bf03d036b310bd04deb.nq.gz
    ├── 3d70f026c03998228d3f3aeade97dc39fcd6596b.nq.gz
    ├── 3ed56c428f10215bf8cc076153c850b645ff7047.nq.gz
    ├── 3f1535cf6ed44c9bfcee1cd61ee80d372e79e3f9.nq.gz
    ├── 4010e49480008b73da523cdcbf63895f135e60a0.nq.gz
    ├── 40e681c81ef9b1e44af26115dde2e7e99051bce5.nq.gz
    ├── 41e37e02b5a6e77494cd18cbdbbcb20aeb2cf158.nq.gz
    ├── 41fe02bb1330021a9a4e76e6175efa5671be4750.nq.gz
    ├── 44b0c1dc9939e5cbd8edce3d58f28c84cdbab06a.nq.gz
    ├── 45a4d735c1a5b6bac0091e3c978c77e3e65c7f67.nq.gz
    ├── 46e83f92c746f743046f173d11fc7b6eaede02a4.nq.gz
    ├── 48047b230133ca20403f5b2866db4a54f1edf07a.nq.gz
    ├── 483629b843fef947bac5651c5b9665cc70be520c.nq.gz
    ├── 49063876a94abfd6e5ae1cdb00f8f20f036589ec.nq.gz
    ├── 4992a421b2016b641be5d9467adf379b8b7e344c.nq.gz
    ├── 4a11fa626fd67746aafaa9e8ada8a705ebcbaf5e.nq.gz
    ├── 4a90c130c91413d3d8cbb5f8a220c3b156c2985d.nq.gz
    ├── 4aadc1b7521b07efc34b163b33b287e7fcb93dff.nq.gz
    ├── 4acb62715ce9300d6e6b2bbb7bd4bf4166959938.nq.gz
    ├── 4aea387e9c7d60796b26a314a6c453ac80d1b6e0.nq.gz
    ├── 4b11c74b7929be4993db1cbb62e9f123e317b91a.nq.gz
    ├── 4b39ec7b11f1d4aa097f9b0e17c32497ea15a623.nq.gz
    ├── 4b6e36c52d82d971cd86f1eb819160fccd465164.nq.gz
    ├── 4b875b9ac9152675a38df565f6e8a8cbe6368a1b.nq.gz
    ├── 4bcdb6dad2bf70d02a12d64c06731109b2c4c568.nq.gz
    ├── 4ca6f084063bb033212fb4f4f6a87ad63fb564fc.nq.gz
    ├── 4e1415ccbd85344ce427b466f08b852635a6e887.nq.gz
    ├── 4eea9701bc95fbdd97524267ed6b4362214d69b2.nq.gz
    ├── 4f3beacf344dbf33a3a772badb6c2a26afc4f0f4.nq.gz
    ├── 4fd1240054347212af02c97fe40feb30fb65598c.nq.gz
    ├── 4fd9c9660d584fc4c49290d3ed6293d267019031.nq.gz
    ├── 500f87c65bec60c0915e8af6f424460808860ab6.nq.gz
    ├── 5026c4fb85291a79b5f22583ae3b126040731c18.nq.gz
    ├── 508574ad488fe502fd698a8cf330f9441c659bba.nq.gz
    ├── 516ac732af1f438635476996cd7627bf27533a95.nq.gz
    ├── 52ea742d97707bb296ffc85b1258ba2186759583.nq.gz
    ├── 533f4d95cb74c837b01c8826001a69cfe54c89e1.nq.gz
    ├── 53a4df6f20d182f87ac9598a99f1838a0bfcb2c7.nq.gz
    ├── 546b12e0e9bacf9380f92d07adfe501148add70e.nq.gz
    ├── 54bbef3e5936648c357bf1fdb70ba262c9f638ab.nq.gz
    ├── 5562c51114e9b491d4e1149e8722f2cb005bd401.nq.gz
    ├── 55d6464932224863211884493baecd35a7908481.nq.gz
    ├── 55fc041c4b493639f86de7630f44c3c99faa5cb4.nq.gz
    ├── 575d3010f2d1138bb133dbcc6e2b4db564609a10.nq.gz
    ├── 579e6a552126858da8c2ca3fe8eda23e5cf3c0e1.nq.gz
    ├── 57d5621a38103f6b35fdc39bb8001c6a9a177642.nq.gz
    ├── 5812c6e8c1948e9e8e0c3a82d29aead5cb952514.nq.gz
    ├── 586c1a7258975077fae6ff3bbcf58817901f1af8.nq.gz
    ├── 58e3917ad4c532435d102c00f9507fea5c146d6e.nq.gz
    ├── 59234ea01edd4f87f345e5eb465596ca212b256f.nq.gz
    ├── 5a3461c96a236c6d4e358407279b9faec11f5664.nq.gz
    ├── 5a4b217b62c2b9ed1e6946905bbaa1b3bc6e5a98.nq.gz
    ├── 5aae3ae4846fb8b7e9741e80b44e8c36708e2ed2.nq.gz
    ├── 5afc380d88d226931e87d683218abb0b9e137f39.nq.gz
    ├── 5b252a8e740ad5a58a92aa8ce81954ff0cb514e9.nq.gz
    ├── 5b7a124378d154d8631a1e488ccc45581ebba20d.nq.gz
    ├── 5c34cbab26096df58f4dbdfdd913940f0768dc59.nq.gz
    ├── 5c5ce2fc2ae311d60262c841d599c72b67e61747.nq.gz
    ├── 5da4e71db3de182919db8e8f41006c90f7121d27.nq.gz
    ├── 5e6d7580cfd648bbd0886725aaf52c63816bd727.nq.gz
    ├── 5eab4a67c7b944a9ad5778580df31437c38cfc3c.nq.gz
    ├── 5ed84593f4f69c195552fe95ce2f5018ebfcc23f.nq.gz
    ├── 5f0854f491168348b0c9cb1c9185d0593214ca73.nq.gz
    ├── 5ff544ca81f83c7c6368500c3f8f9a854c975c0f.nq.gz
    ├── 6057ba7bc9cde0a5b879da923f5348f1178e3d29.nq.gz
    ├── 622e5a67879dd13fd8a855989c2b0a3085c91b07.nq.gz
    ├── 624b4010ce7636765ed362e404cd30276fcc4186.nq.gz
    ├── 64274c4f12eb388363fb8da41e6bafbf0b3e8c14.nq.gz
    ├── 6513ce9b09165d638dcde9ed107e66815f54277a.nq.gz
    ├── 652e7410e904cdca257070c18c571944e16029fc.nq.gz
    ├── 66d6c5fe4dae8d43806513f96d82d4173b5ea247.nq.gz
    ├── 66ddce81fc5798c46d9a76c8d9456320192678f3.nq.gz
    ├── 674f97e4a43f3d674a06e63cf500d285a0f4c328.nq.gz
    ├── 684c454d3442edbeefebb73b149303194d256acb.nq.gz
    ├── 6900600889bae6f7d3803cc68afd53c931d3bc5c.nq.gz
    ├── 69ae3abce5a79db3bb7529a9d2020355708932cf.nq.gz
    ├── 6bce145ba58feef88ec0b003061f524e52a21319.nq.gz
    ├── 6ca1aea6132ec2a5b8413f664e9c7b557ec79f39.nq.gz
    ├── 6d1bd084cde3e6fc3e048b63041871a9e6e04219.nq.gz
    ├── 6d6c3477d4fc83bfd9fe2553d0f118a5b416e330.nq.gz
    ├── 6dc99b1b8fd819fbef5590475d1b6c4275d12608.nq.gz
    ├── 6f267ccb4902ff9d37e15cdc96ae70f4219e8925.nq.gz
    ├── 6f352f04d7f8b6b24a92c46620feae17a9868708.nq.gz
    ├── 6fd3df74d96ebc1c47d3c7fbfcaeb4c460a52696.nq.gz
    ├── 7010e34bc9d666af697c6dbc74f4011a3a46f23e.nq.gz
    ├── 70f3a230c5ddda9898593b3457c2db7001771a25.nq.gz
    ├── 71afbe6b719129ed80bfa4c08878d4e03bcbc294.nq.gz
    ├── 71e9b66d47b2f9706b264e09eb3e21dedecf4732.nq.gz
    ├── 7348267dec681cb4ea9eccf4e89398d6c839d654.nq.gz
    ├── 73d3d9ae59fcd87fad4ca4cfe8fc304be16c675b.nq.gz
    ├── 7458a97fc4a4427105993a8eb64c53c57e398499.nq.gz
    ├── 74c6dfbced2170c583a1e52f5204f5392468b9e2.nq.gz
    ├── 750638d41aa591fa99bff70c1e244fd8ef8d7594.nq.gz
    ├── 75410b9ac0abaedd45e1e741e4647c714705f72b.nq.gz
    ├── 75b93ebdc62f18392273463f2b0d0c72449b3ea8.nq.gz
    ├── 7667e0bb668c1443c7735180b40783755c0efad7.nq.gz
    ├── 76c5f5064741a9785431ab67614c68f089af66be.nq.gz
    ├── 7710f20028bccbcc1a2ddddf4125daa876a45455.nq.gz
    ├── 774e83314a38077b381b86e1122c62708dda003e.nq.gz
    ├── 77c0747395b5bff3361b4b1719578a720184a002.nq.gz
    └── 77ca93f69943dd442a758ebb8d80e573b069516d.nq.gz

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

[unit8co/darts](https://github.com/unit8co/darts)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
