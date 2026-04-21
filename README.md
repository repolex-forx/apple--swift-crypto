# Repolex Knowledge Graph of apple/swift-crypto

RDF knowledge graph data for [apple/swift-crypto](https://github.com/apple/swift-crypto), parsed by [repolex](https://repolex.ai).

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
lexq download apple/swift-crypto
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bb4ba815dab96d4edc1e0b86d7b9acf9ff973a84
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── bb4ba815dab96d4edc1e0b86d7b9acf9ff973a84.nq.gz
│   └── repolex
│       └── bb4ba815dab96d4edc1e0b86d7b9acf9ff973a84
│           └── chunk-001.nq.gz
└── blob
    ├── 007421298e54437adcc04cf46e3e6209928b66d0.nq.gz
    ├── 00a0b79a4eb013cd329c37700be41c6acdf8764f.nq.gz
    ├── 00daec8db7268a98172366d37604c2dc48e11269.nq.gz
    ├── 00f82defc90602615fbaf784ba5c51acb88a7221.nq.gz
    ├── 01cb73f44f793eec1afc15078615697fbd203193.nq.gz
    ├── 01df29e66626825f75624f85cf846b3cf8fc411e.nq.gz
    ├── 0238a9ca182e04711b793c5b10651e3ab5b13788.nq.gz
    ├── 028147a4bcdf9eb0a42204b9aaadf3d65f423139.nq.gz
    ├── 02ce6bbd181a8e1e3e8e5dc7105cbab6c5f9daef.nq.gz
    ├── 02cf6d922ee0ca8d494234f5f92e4e57a54c7d45.nq.gz
    ├── 02e116ec060ae462735d4b504c492593dcd3d42a.nq.gz
    ├── 0317a9aec6f194fa43725b79b60a7eae4080ec70.nq.gz
    ├── 0334f2a4a712bd9a03e3e67dcb481bd6a796d101.nq.gz
    ├── 0353a1e11f6d56dd6d7d7d465ca9a5362efda0b6.nq.gz
    ├── 036bc06d9bbd06f9388ddfc4ab0d4e29497ab554.nq.gz
    ├── 0372aec9609f65f39407d45531b4d9302abeaa58.nq.gz
    ├── 037de26f6bb13cbafd2367e89f4092552386e5e4.nq.gz
    ├── 03a10ee1966a703b215e64e122c12720978adaaf.nq.gz
    ├── 03f336d4c27fd52da88854782725b788b677985b.nq.gz
    ├── 040d9cd7ab4d3bb5b81c6337136f7e09f240ff9b.nq.gz
    ├── 040ed854ae4f58075f26e4fdf5abc52e9ba61293.nq.gz
    ├── 04b7956862e55e0f90bb0f260edebab38c145e35.nq.gz
    ├── 04c11a26d0e7b3e95c595f9ed628fa25fcb88d71.nq.gz
    ├── 050393873b58669fc88d294c8f87eb7cfcec5546.nq.gz
    ├── 05150b49fac1dff131672800972c3d7d78954e77.nq.gz
    ├── 05526b5f7f74b3d579888e81931267f0aae3b84f.nq.gz
    ├── 056378a045e1b1beabe64b7420482c4446daf18d.nq.gz
    ├── 059eefd2bdf894fb69121f5a6d5e8e568acf3d20.nq.gz
    ├── 05b2fa3affe770728f1ab9ddb81ed56da31fcab5.nq.gz
    ├── 05ede8e07445f0bc85fe0f75c1f36bc8aa358d8a.nq.gz
    ├── 05f3aa22c8f8f6566b2f2bdc5100d0826a5dcafc.nq.gz
    ├── 0615861f70fe009483747711c123380e9df32ff8.nq.gz
    ├── 065f8ff6af1b594e48e44b93fc1c4260cad0fadf.nq.gz
    ├── 0704f0694f8b603f559af12f47a4c347e7aca155.nq.gz
    ├── 07051a67226e7e5ea1bf77632265680a42d69db2.nq.gz
    ├── 0776b8a0249ee99ac98e548953e3d18b44ca64de.nq.gz
    ├── 0778a6fc9f69833b95fd883ec6a8f826d03cbffd.nq.gz
    ├── 07b002a8343e395b678d3c4f0694d5f13b7f873c.nq.gz
    ├── 07c716975937c864315e2e52e8df14f76a0ea534.nq.gz
    ├── 07d67b4a147e6b7515276966c672483986f9f504.nq.gz
    ├── 07f49224f2559fb523b4913e08107e42382cd40e.nq.gz
    ├── 0842eadacaba5c84bed47fc9d1cc3a8aa71d69b2.nq.gz
    ├── 084a6c732df55632a792df1c28cc51a677de908b.nq.gz
    ├── 085b6c958eedd9d0171100be2ee6a53a2084d7ee.nq.gz
    ├── 0878c36af9061d2ac6cef12aeed2c02f137715b0.nq.gz
    ├── 087a13260a44dfe6c67eb1eb129682c3739da9c4.nq.gz
    ├── 0884e7d00b4d0df04893ec902748e06996902281.nq.gz
    ├── 08891d83f67181f147fc91135bf6c0016a2bea7e.nq.gz
    ├── 08a63413d6e439dd7d59c652634161475a5cb62e.nq.gz
    ├── 08b65ddcb6ac0e4c893185b54d8aeb8fcbc7d924.nq.gz
    ├── 092e8845bb6d0fa307b9af06a9a8a286b450f6ff.nq.gz
    ├── 09bfafbaec86f70cd3ccf2d11b538a7bcae288ca.nq.gz
    ├── 0a1890a7679ba11a363205e3591f34fa233f637b.nq.gz
    ├── 0acf95ac5c07dc82b0fa6c079976ad20271d9ef7.nq.gz
    ├── 0ad4c4abbdb05be0b2e49abd5f473a45c6e4b54f.nq.gz
    ├── 0bcc5ded12dc736c4aa75d76fd0a720dad222acc.nq.gz
    ├── 0be0d6b18f2f968e258abbd6862c18d8f6b2275d.nq.gz
    ├── 0bec2458db41ffaedddcd193ff185555a72ca22c.nq.gz
    ├── 0bf0ccbc85040bca89280d44f350d8d9f60d776c.nq.gz
    ├── 0c76eb2d366b13821b17697d79bad4ced95a080d.nq.gz
    ├── 0d0623c1e9f9f50adbf9112b9056be69fe04ef39.nq.gz
    ├── 0d32f4abb27c1fe2594425ff2380e536e2d6515c.nq.gz
    ├── 0d5912493d3286e31f5682ef638e432520f03151.nq.gz
    ├── 0d61efe4962fb4b5bac195af0351156eb2276832.nq.gz
    ├── 0d8ef98862b952daa0772bc443d86680bd9ab56f.nq.gz
    ├── 0d96580543ffccdc0e3c3a8c0b9b2db4d37d50cb.nq.gz
    ├── 0dbe15567eec432bc6e4b6dc179fecdfe6240827.nq.gz
    ├── 0dc4111f46d4a2c156e0f43e0b817de35513dc9d.nq.gz
    ├── 0e46873f638fc62357134cfd2be5c143e80e6e27.nq.gz
    ├── 0e570801cfb2c505a2f8e5694e4dba7d59838438.nq.gz
    ├── 0ecc61c4daece376aef04f75ecb0d64ff448ebb6.nq.gz
    ├── 0efab8de7c43635836c35fdb5f230918a09faf2e.nq.gz
    ├── 0f2d5e7e972a08524b327ba5d54014c7a13d8c35.nq.gz
    ├── 0fae0be60fcdfcc9266c40ee9a41990fcaa009e9.nq.gz
    ├── 112376e5dba8dcb892e755377f9eb94fbf61e23d.nq.gz
    ├── 118bc3882ca88449301caadf5eb10fcd2a7d754e.nq.gz
    ├── 11c9a5b617782aa2a97ccea17906e798e1f61686.nq.gz
    ├── 11fa7ec45724b5bd4ee1bbf762d0a7a6e836017a.nq.gz
    ├── 120ee218ef57ff09bdb9c9471a3278139c8d474d.nq.gz
    ├── 12acd2f425086e1f44d0ce2566805cd8432301f1.nq.gz
    ├── 12e9d195a5529196dd45ce0fe80784a08b29580e.nq.gz
    ├── 1335616bcbf678698995973c1d1929b5d2f35549.nq.gz
    ├── 13d31f0465cc9435d202001d815b6c602da85d5e.nq.gz
    ├── 140687c5761f90b4a36c5d1455b20c688143f2cc.nq.gz
    ├── 144b2e7fd65cadef75a6ebc04899eedd1bada27d.nq.gz
    ├── 14bef96ef1d713c718ec2692d21c8e2a06c999ba.nq.gz
    ├── 14d64cb8cce57db23f3fbb9b7722a28f76689f9f.nq.gz
    ├── 14e2975bc7b0ca3395b54667fe0770cbf120a7da.nq.gz
    ├── 14f85804faaea4aab11c176f72a0749db348a616.nq.gz
    ├── 1510ceabb57e4f94f3694e45141191f48152494b.nq.gz
    ├── 1513f3830bf2c97b6e1d8b6193ea1be7d6ff7eb5.nq.gz
    ├── 155175cfcd28a95a4e289641510232f84b7ed97b.nq.gz
    ├── 1569a88f33ef7bc2f15c7f8009fa1b26f341b582.nq.gz
    ├── 1589f86fde525abc7db5316dba0a83d2551c6548.nq.gz
    ├── 15b1adab5fa29d2fce81a5b324b1c8b3624f5df6.nq.gz
    ├── 167e4ccceff399d8b75f80e8862fb9d1e360e138.nq.gz
    ├── 16938f52fe8db4c49f1d8b5699f1b1ff4f384b1f.nq.gz
    ├── 17467a8543afc278145c6dbf8a71e9f07875f476.nq.gz
    ├── 175645680382f6ef2cfb071e4b8c6e3697f6f4ac.nq.gz
    ├── 179f92a7d1f9b5139421ab338f44ec2390cef1ab.nq.gz
    ├── 184dd42cbba546033ae4d2ac9e74679c069fc782.nq.gz
    ├── 190b957b7f8213ef37d3f4fde90a323fa58e6f14.nq.gz
    ├── 196f3249b7b3c611b355556f8289838a62334a06.nq.gz
    ├── 1991f2f6ca4fbf722fb4724249e14319afdc414d.nq.gz
    ├── 19a8bf43d3708e4cb194023f0d04d7bc55c474c9.nq.gz
    ├── 19b76ab515607a3bf7703522321e46d488cc27d2.nq.gz
    ├── 19da2ad47e9c1a9044a243a7e63f1d56353b46fb.nq.gz
    ├── 19f0158f2993fd9ba95898cd8831bc0ea12f2c07.nq.gz
    ├── 1a20271fd74d790798ddff1b6a589b73f60a2d5f.nq.gz
    ├── 1a3716f3716b4c5d3799b5875cb77d3e57206c07.nq.gz
    ├── 1a3ec969490739c8930c0fd5997b48fa7a851243.nq.gz
    ├── 1a577d75a3dec605d7a4d196ec57305167520aff.nq.gz
    ├── 1a5fe5375ba15a868d369a898d6cbb5094ea8314.nq.gz
    ├── 1a71db6f26cdb8adfa1afa9753c867bf99655c43.nq.gz
    ├── 1a96877dd1ea760966576d0319dd528b9f14e9dc.nq.gz
    ├── 1b560e783a2d7fe2c292541d0a7b6019fd0bd3f7.nq.gz
    ├── 1b6625f64eced15a42835acaa5e8ebad055741be.nq.gz
    ├── 1ba28018c2ecf6320d11ac08a9c2e4385a9edf01.nq.gz
    ├── 1bc0dac10db7df1fcea3cca4c53657b886950a44.nq.gz
    ├── 1be6d3cd4a66304ecfbd3fc08567217463cc90cb.nq.gz
    ├── 1be855a6e1fc06942a1c79c8e365536c9296ba92.nq.gz
    ├── 1c8e9a7e567966b9df7dbd2b511eae44d4fac800.nq.gz
    ├── 1cd182c102914ba3de3e163a5a02f357222d9c8c.nq.gz
    ├── 1d06652d9d9902d3f65294d115446a0004a49648.nq.gz
    ├── 1d6878dcefe5a8c5b34fb83416cec12bc1b7f089.nq.gz
    ├── 1d7c9a2062709cc0c5ff63f97190ba788b159043.nq.gz
    ├── 1dc00aed7850e9a57b410dd6a69aaadb63c8b08a.nq.gz
    ├── 1de320313092afe9bbd73e14a416058dff4b8533.nq.gz
    ├── 1e8c47703e09a75c87eef136e86dd2b4bbb5c160.nq.gz
    ├── 1e917fe7feeeacdf0817ec2e9c1315b41d0f78dd.nq.gz
    ├── 1ea2117457354a4607a80bebc4e27c0aaf944559.nq.gz
    ├── 1eb90bea1b63988c9618c18ff3af67bedacebb9d.nq.gz
    ├── 1ec2095ac6072f1792c404aaa192ea7da3c3d197.nq.gz
    ├── 1ec38294154299618335db9c5ff0f91a186ab3e4.nq.gz
    ├── 1f80787f76b3a455c2ef3b69c9fe3fcf3bf06ff7.nq.gz
    ├── 204233236f7a2faa7fa6856c64825515f64e005d.nq.gz
    ├── 2071a34fd0b7b20ac2345157c4cbeb42ba8b7889.nq.gz
    ├── 207a4d33ed0a4aaa3768b1b05108445c6320db4c.nq.gz
    ├── 20a540ec4137f81f4a065c0e97c3ad182a6d6db7.nq.gz
    ├── 2131b9006e53eb4e8d63333a86e749309d1ca7eb.nq.gz
    ├── 2178fffb6cf989753dc98fa82ddad3555c264d6f.nq.gz
    ├── 21825ac66886e7156320b5851dd091bea52eb0f5.nq.gz
    ├── 2184433f2184725d39d6577da8a2423b4da69207.nq.gz
    ├── 21cba29e186aa9eb019588eee4fd1688273bc093.nq.gz
    ├── 21cd68f2712e2b4d7ce2981986425e6affe3ee68.nq.gz
    ├── 21d5da6fa7a7e955131e4ae2a278fc971707fbb7.nq.gz
    ├── 21e8fca6744f6dd6c74c38168e26db5d1ada9104.nq.gz
    ├── 21fd730eea2b6d1c311617533216009798308634.nq.gz
    ├── 2204eb55289dd0a8ae00e726fd46ec240c22eacd.nq.gz
    ├── 22679acf034f15e45ecd727bec09a1334553d7d8.nq.gz
    ├── 22809c65cd2c3c439633b1af62517f7a8f492d9b.nq.gz
    ├── 22bc012a2b76dc327801bf0e7f70ce5b30831991.nq.gz
    ├── 22c9cb3e470632b5e9a21cf7660e9a7d66c3a533.nq.gz
    ├── 231c0bb463a4ae4b834dfb98468d0c6fbb654582.nq.gz
    ├── 2375912dab7d8ebded64180de19457a7af8ebc8f.nq.gz
    ├── 23766fe4005a0ec1ef5e53964c981ff434f6631d.nq.gz
    ├── 2385d916e609b2cb5df2ab2606e0f7954455e969.nq.gz
    ├── 23c78641c30dd03f35f7c0f86398daf3ba24f1ff.nq.gz
    ├── 23f815e0bebaca4f08ef29c8229c0ebba48eab1d.nq.gz
    ├── 23fdd057ae2233609f86cbb1a60a29f2371ecfb4.nq.gz
    ├── 243aaee047943f6df6b1f9c744bfd298bb59e5ad.nq.gz
    ├── 24c7860b609535cf7a9a4f292f4ad8f63df94ee0.nq.gz
    ├── 25358f9a002d2d3344a392fff4802dab9a5aa12d.nq.gz
    ├── 257b2a2607792ad4e3cc06ca69e6e6f264c651f0.nq.gz
    ├── 257d69399f46bf10378d163d76e8c0a43ef52756.nq.gz
    ├── 258237d209a65c5c3837c3cf0ac33e7570742d94.nq.gz
    ├── 25dfc3c74d3d77a38fbe3bf9783cf19864cf5eb3.nq.gz
    ├── 25e71ac4e50268c24668fa95ee76f34537732909.nq.gz
    ├── 260f4528c0d47c97fbd163242602e76a85ad8b0f.nq.gz
    ├── 2677597a10572d2c5a93fbd905e3a9bb1f3b2f8e.nq.gz
    ├── 26c4b29ddc73fed3893d81d30177a231caf3abcb.nq.gz
    ├── 26d802b93cb31c2e24ff6ac61c169fbaa0fa18ed.nq.gz
    ├── 2725676f582d7255d48eb52128cb736dcc6688e1.nq.gz
    ├── 276d820a15cd678e1d95ae3688743a15c08e14d0.nq.gz
    ├── 27aaa2396ed84235028dd245d76d4de5cacf947b.nq.gz
    ├── 27affb47da700138ad152bd8323b25f2a9e69f93.nq.gz
    ├── 27b46ec76d87c7035d7584a5f679c4a9aeeaca79.nq.gz
    ├── 27f80603613e4c8256b3a77a97e03253c459de16.nq.gz
    ├── 28336d123eb9c41a629f577a47e157570b692447.nq.gz
    ├── 288f50f29d1850ab0b9f86393c2235af32a5760a.nq.gz
    ├── 28c917bc01107c2606baf556b14fbe35b273c502.nq.gz
    ├── 28ef9f0bc6455c3e30598f9605044227a245bec2.nq.gz
    ├── 28f72d3bfbc17a2cc918b1f001ffd5b7cdba80c7.nq.gz
    ├── 297c909141fd69a529eb4541decbf0f3119d240e.nq.gz
    ├── 297eadc2af71cf98e016191d4ef19647a3e8457f.nq.gz
    ├── 29981f041185970a394c74c1e4733aa271572717.nq.gz
    ├── 299e00c1f81a820339ff387b78759d6c417821fc.nq.gz
    ├── 2a19b0f11d60a97b24c47b8e5fffd7d80370a760.nq.gz
    ├── 2a368fce9dae92c3c67c8723e2033686cb948c8a.nq.gz
    ├── 2a426d0a8dac59c385a8e70cddbfba8fc3ab3fcc.nq.gz
    ├── 2b1f6b40df02b1552f2e214319dc0602cf712672.nq.gz
    ├── 2b3693d79ba991c667af7484a11ae980d9c84d6f.nq.gz
    ├── 2b5f6a8129b16e11cb2ef2c6781dc3005510a225.nq.gz
    ├── 2b60f96daaf8dcbe775ae6f02bcc74ed70f02769.nq.gz
    ├── 2becb6f08d714faa7fde306f7d60e92424069b56.nq.gz
    ├── 2c54b18e6b3fff92f66cc08d126c08e842d20036.nq.gz
    └── 2cb3211ccfd5a2d0e4e0441be166d45df132dcb0.nq.gz

8 directories, 200 files
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

[apple/swift-crypto](https://github.com/apple/swift-crypto)

---
*Parsed on 2026-04-21 by [repolex](https://repolex.ai)*
