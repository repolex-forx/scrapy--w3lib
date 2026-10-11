# Repolex Knowledge Graph of scrapy/w3lib

RDF knowledge graph data for [scrapy/w3lib](https://github.com/scrapy/w3lib), parsed by [repolex](https://repolex.ai).

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
rlex download scrapy/w3lib
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ade4b62e55da45a8e5ead6ed21dcdedd018b9672
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ade4b62e55da45a8e5ead6ed21dcdedd018b9672
│           └── chunk-001.nq.gz
├── blob
│   ├── 0477cc33756fc403a427673c450176d58b3bdcb8.nq.gz
│   ├── 0e5e08940d74876c79b2dc7e8e945555df507b39.nq.gz
│   ├── 1363efa802e3fc0bdcda8460603098726e94d93f.nq.gz
│   ├── 213dfe299067ae1c4711c344390099adfad132d6.nq.gz
│   ├── 22900fb0ecce0e3548d9964199e6604fa22af0a0.nq.gz
│   ├── 2feaafb4ef59593a45437d040960e146ebc18dc7.nq.gz
│   ├── 363e3f46288a59077f2c76fb7f09beeec967e27a.nq.gz
│   ├── 42853797c6ab427fccdefcf5ccbe378131f437fe.nq.gz
│   ├── 437e21d26bd39d65704a852fed8a644c21db525a.nq.gz
│   ├── 460adaf63fbd34f1f3cbfdce991b919d21dc09e5.nq.gz
│   ├── 46db37b1bf6a1b0003509687f463f40ab7333ef9.nq.gz
│   ├── 4b554c7b5b128331253a892a32b6110fe8c5a273.nq.gz
│   ├── 4c423d04e1385ed6d449bcf5f31f4588a84e5655.nq.gz
│   ├── 502554ff695b24d407eb0abb0f0c098f55cb9334.nq.gz
│   ├── 564cf77690f284be1fb26d8cc2dae26ef05e1994.nq.gz
│   ├── 56e4db48ccd8cd9ac1f4ec473f410a6824f05bbd.nq.gz
│   ├── 5f3d193adcf09fc1b0617134f2735b25ddcb6486.nq.gz
│   ├── 62925a87e54d3ff3891ef96c46f72bf05842d05b.nq.gz
│   ├── 688daec9fd0b4a1391bd1503521c3430dbc90453.nq.gz
│   ├── 6dc3315418b541fdbc597c18a0d9e71ea3cd74e6.nq.gz
│   ├── 7c390b622b08af3b7d9ce80ddecc103f7f913bbd.nq.gz
│   ├── 8044a2574deb6530cf23b8fccb7a08aad889c2f2.nq.gz
│   ├── 8c248c7bede28d6a40a64d8eea9d38b00de20591.nq.gz
│   ├── 8f1838972ed7bb42afdd92a704af934ad2d175a1.nq.gz
│   ├── 9b060367580219cfc45fba0dddb268026f0e5027.nq.gz
│   ├── 9e868d6cd92a6868c59fbab365229fe9e0f8f74f.nq.gz
│   ├── a69c2e7203a77f81b30bf692696ae2a4ac977631.nq.gz
│   ├── ac39a569d3639108e3eaae0b533b007fffb37226.nq.gz
│   ├── ad5e4e806b9142679828efabf92bb3d338dd1911.nq.gz
│   ├── b16ea48ee780ffe55d33361949a8881d802913fa.nq.gz
│   ├── b3d0b64f2ee9f14802f40d00700030e295efcb09.nq.gz
│   ├── b5bf38a1d78b2ebb483eedce817512d5b82e79ac.nq.gz
│   ├── c00e116bf40494f82e5231d47adc3f87cea1e813.nq.gz
│   ├── c41e6b805e2a9e43f70ca8356e49c2d9a3730fe4.nq.gz
│   ├── d5dcc36c6e000ccd1aa355d721646250b752ab37.nq.gz
│   ├── d70aaa1ff747f27077f5df101b1262c6fb4570f8.nq.gz
│   ├── d75e24686003d604d3d5047baaee9cb2e6a54823.nq.gz
│   ├── dcf3761ffe309fcd4d3c75d318ca53759a4c13b4.nq.gz
│   ├── e55e2354c8978e15ccae404a827651d882c6951e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eab216a03aa96abbf764e5aada01cfaf0ac51b1b.nq.gz
│   ├── eb1fd20fc6390e279f54ce500d86228e9d3e3a86.nq.gz
│   ├── f18437eb6fb2502c42eccf5c801ec89fdc8dc726.nq.gz
│   ├── f18f9aeeac4cbcc937ce23e75eefe4e1c452a4b6.nq.gz
│   ├── f4c3b8fad83abae1b6a194406cb2e40d2c684dad.nq.gz
│   ├── fb35696e0900843f64bb5d240a6424544cb425af.nq.gz
│   ├── fc3023953520f8a93ec19d04fd82714fbcdcb271.nq.gz
│   └── ffbc6da79579002b54f466944959b376ea2ed09a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ade4b62e55da45a8e5ead6ed21dcdedd018b9672.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 56 files
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

[scrapy/w3lib](https://github.com/scrapy/w3lib)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
