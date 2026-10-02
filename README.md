# Repolex Knowledge Graph of block/bazel-gradle-plugin

RDF knowledge graph data for [block/bazel-gradle-plugin](https://github.com/block/bazel-gradle-plugin), parsed by [repolex](https://repolex.ai).

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
rlex download block/bazel-gradle-plugin
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 87a2632b1621daa1ce6066754e28f9bb1dd46a73
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 87a2632b1621daa1ce6066754e28f9bb1dd46a73.nq.gz
│   └── repolex
│       └── 87a2632b1621daa1ce6066754e28f9bb1dd46a73
│           └── chunk-001.nq.gz
├── blob
│   ├── 0367d2331a2cbfb3dadb43da08affe106a235c28.nq.gz
│   ├── 08756ec9c245c0b9299273f7d223917886a6613b.nq.gz
│   ├── 1385fa56cd3e602b176528d29285c3a6a3d3de85.nq.gz
│   ├── 198d94cecc946b6cb643a1e0b514a54f6da73580.nq.gz
│   ├── 1f516fc72c2be1249acd4c16e8a67dadc35f383e.nq.gz
│   ├── 216ae89f255cd4657d7e842017b7c666ee9a9366.nq.gz
│   ├── 23407dd36c9309aa6fe895d487fec1a3e77a06a9.nq.gz
│   ├── 246bcc9197882ad6b5550e2513bd3d456fec5442.nq.gz
│   ├── 24827916ddc1948961969f4ede5bafedfbae9627.nq.gz
│   ├── 24a59763f5b2c91b64250a782b40d364330fb6e4.nq.gz
│   ├── 24ba7738d59ce77dd906864511ed84ecd1735ce2.nq.gz
│   ├── 24c2304ef34b6fcc931adc0eced7571dcfde1ff3.nq.gz
│   ├── 25e953ff62af363df5f353cb01504982a9fe0883.nq.gz
│   ├── 26bc609e6a7527fb5533635d00df1374d3c8010b.nq.gz
│   ├── 2bf50aaf17a6f89855dce48afd4e6cbb554047d6.nq.gz
│   ├── 2d796de17403faf4920cf1f2975f5f08a2e48982.nq.gz
│   ├── 2f3aac5a5aba6f4257b9fd0b8e40ce2637cf2e24.nq.gz
│   ├── 31e5ac095e870a46e9a5af88a076288f371ad008.nq.gz
│   ├── 357521325a4fec30988cbaa5e84110d6c356117e.nq.gz
│   ├── 3716e3472a639b56f6132610e28cb4c31a62354d.nq.gz
│   ├── 383f4511d444516caed0fd113ee8a2b640cd2290.nq.gz
│   ├── 3afa2e89f38e15bbd6a8ace4198f2ba2acd8c74c.nq.gz
│   ├── 3c6fa5d1bc55d378429c0fe158cbd593bfa6e526.nq.gz
│   ├── 40e3491765be77079461ebaada46add68d06c467.nq.gz
│   ├── 417edd8fa19db17edfdc1037b6d600ddb7ab3aaa.nq.gz
│   ├── 44f83f857648afe2fc789aad4c0280b2231243e7.nq.gz
│   ├── 49873cec759269f85260fb6acaf7fba3d4529839.nq.gz
│   ├── 4a19f3c0d1e0746c958c7b4368cc4b6ffeb15b99.nq.gz
│   ├── 4af31ce02769e5a3322b425c1c3c9dc99f0ddd77.nq.gz
│   ├── 4af3958eedafeccc3669161f3cd8bbe443dfa0f6.nq.gz
│   ├── 4c3c2260eb6d5ed5093a7fe38ea7395a5d6a4b74.nq.gz
│   ├── 4d93d28d70ad4432476ddc24b92ca0e20538351c.nq.gz
│   ├── 527df16ed281e8cd1800fd4be364356f59c62586.nq.gz
│   ├── 57621b537432592b46ff89d5c89a77e7ee50c38a.nq.gz
│   ├── 588ddcae119a7edf663a16d0956c2a07e6f42df4.nq.gz
│   ├── 5d9c831c70784d0c8d6384a38b2000c546df80e2.nq.gz
│   ├── 6224cc691a33bec315851aafdbf140e7b77f4553.nq.gz
│   ├── 62ab3052e88877cad6e3900d10b95e22cf8f8af6.nq.gz
│   ├── 632a4db94e159d0b13de49dd3e60efe75f31b56c.nq.gz
│   ├── 64924f8dfb63bcf2b173c914c00800c356bbf0ce.nq.gz
│   ├── 6cd40279b37c8e3b28a4728f53b0cb3b541f444c.nq.gz
│   ├── 772239ab466c7c8f0e67c561527369dae57611f4.nq.gz
│   ├── 7e371b1aac0c4e544dd61699ca4e584e6d4e99c3.nq.gz
│   ├── 84954b01189b2d99bf718fb1980c918abd127998.nq.gz
│   ├── 85c5017c2aab13b581422befcdae3ad087ad5c64.nq.gz
│   ├── 87acaadba3d3a97cd17d084637a6cdd94caf2167.nq.gz
│   ├── 891bfedbdb197ef6931a214c7cc2938b453e9681.nq.gz
│   ├── 8a4cc7571f7f82921a403a0de6cb7e66ec113c08.nq.gz
│   ├── 8afd5b4d09b535c0d50c918f72c86919922325be.nq.gz
│   ├── 8ca4e0b11028400f355a33da23fdb8b9e0d9a3db.nq.gz
│   ├── 8ebe0d00b95fc0ab5848ab09e162cbe65760bfc1.nq.gz
│   ├── 933515fea7c9fb7cbd963ef08676af53aa36cb64.nq.gz
│   ├── 946073ed7ae42631c53788c86bf3c613f406fbd8.nq.gz
│   ├── 9c964ac8e877bfa127c1cd1f5dbd75173520fce8.nq.gz
│   ├── 9d86a432af1e8d228ce04d3052d36d17e2b5090f.nq.gz
│   ├── a1341761ed1f8477e4e4282eac7119e856d87a37.nq.gz
│   ├── a9b7dc4d3a4acd1fa88325913caf6856b09c3d16.nq.gz
│   ├── aa6ce1537836d3d925fa457bbd0b03ebf8fcb1b7.nq.gz
│   ├── aad3fa6ea8fb5e95d17aaa7df625006411e40ad5.nq.gz
│   ├── ac5f64e247f6d2bc08cf4587d75ebe329a94e6a8.nq.gz
│   ├── ac6726d4d65323b6c1c7feacfc0e71559c491a5f.nq.gz
│   ├── add5848f7b8fd9f18489a0ee24c842e687e8397e.nq.gz
│   ├── b3c7985d8f72c443c439c1e203c625a51a8d1267.nq.gz
│   ├── b5d404c25de55f4709569fba67e961e26f1c2281.nq.gz
│   ├── bfe7943e93218fc2ded11234c4aa7424fe31c49e.nq.gz
│   ├── c40cce6f585b47d77fc10663428feb8ee91f631d.nq.gz
│   ├── cc17d794d8718ff258b63659cd8931a1cb004e08.nq.gz
│   ├── ce63e9ec0057020debbcaca30905d5e852f71107.nq.gz
│   ├── d1bda875df8984fd893e5434340223048f966c35.nq.gz
│   ├── d2c7e1f5f19ade66c71a82739b7a3a933f1c4322.nq.gz
│   ├── d7c6b7218cee5aac5fe1e9a4e10d82d8579c401d.nq.gz
│   ├── d8f0a0f04b6dcd3ca1e568c559bdf362442d90b1.nq.gz
│   ├── da72d593f08873a52e9da488faaa2ce7d8d5ec30.nq.gz
│   ├── da7d60918d11592982bb9848f1f361570654ec3a.nq.gz
│   ├── dbde5705bd945c32efee43e046d3e9e9b0f065ac.nq.gz
│   ├── dc14c9438caaed651974822d88761c64646c0261.nq.gz
│   ├── dca2f46e04236d2ae7cf8ad65fed676b2cd33ab7.nq.gz
│   ├── defd06593a701bf60f9b566e15cee9d9e13036bb.nq.gz
│   ├── e074e9a502981ed971215ef1b99b60c1fc8ae19c.nq.gz
│   ├── e148492de849ef6955d4b64da0e60a8d9ce0c2a5.nq.gz
│   ├── e3a9a9ae6559306f6f6984b4e0c452dd5fdc1c79.nq.gz
│   ├── e47f5b09c40233ed0cc8f8ca94dd8b392207a4a9.nq.gz
│   ├── e5cac51978b4d10d6ec8637e3a7458bcf68f68d7.nq.gz
│   ├── e721d9bba9f8162c3ea58263bbd0e17467d9a918.nq.gz
│   ├── e889550ba4cbc92a720527042e5f6e7a303bfcbc.nq.gz
│   ├── eccd0eddf50656a70e4721163ccdf3de47c9602f.nq.gz
│   ├── eddd8924568cbfc3cf9495250c7a696e9160ee04.nq.gz
│   ├── ee3b0d61ba975d332fe0f51064154d38ac2d9c8b.nq.gz
│   ├── f0af14acb8d1c7b72b24f474f4c6915f244d56a8.nq.gz
│   ├── f258270c5948256f3e1128c8f54e624693011822.nq.gz
│   ├── f3759058b8ad2717fcd6fc177918e2f0611aa144.nq.gz
│   ├── f6ba3d40757db5cd0f4505d43aae60e80b313cf3.nq.gz
│   ├── f78ed4e6e33b01b7d2281d03beda2faef60e4d7b.nq.gz
│   ├── f8e1be84aafeeec4e18fa526f2fe8ad35b0c01a2.nq.gz
│   ├── fe08caa4c5bcac9db202015f46013210002afabf.nq.gz
│   └── fe28214d3352b0ed40820a4999317694c8b1ef57.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 87a2632b1621daa1ce6066754e28f9bb1dd46a73.nq.gz
├── issue
│   └── issue.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 104 files
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

[block/bazel-gradle-plugin](https://github.com/block/bazel-gradle-plugin)

---
*Parsed on 2026-10-02 by [repolex](https://repolex.ai)*
