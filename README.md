# Repolex Knowledge Graph of ansible-community/molecule-kubevirt

RDF knowledge graph data for [ansible-community/molecule-kubevirt](https://github.com/ansible-community/molecule-kubevirt), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-community/molecule-kubevirt
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7987e80be1ebf312f43af9c4ad5056383ba94e1a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7987e80be1ebf312f43af9c4ad5056383ba94e1a
│           └── chunk-001.nq.gz
├── blob
│   ├── 0bf81833772947e26f235bbc18465a3e20098a0b.nq.gz
│   ├── 0d283d7502e67f784c1b39be969b8c11f94e5fb9.nq.gz
│   ├── 10a1cbddadc4ce1959fa6314b599ce843437a478.nq.gz
│   ├── 111107b1b83e71de51ffe402f6580b571caa67ee.nq.gz
│   ├── 118f5482bbda54275a1d170e56724c2f1379ea2b.nq.gz
│   ├── 123df27cce2951ad3150a240deb2333bd474303c.nq.gz
│   ├── 196817bd56afbf955b64856f6602b8319329425a.nq.gz
│   ├── 1a06c16732ebdd76569c412d87479f4dd1ab0273.nq.gz
│   ├── 1e48bd7cc4400d4381bd30a2576d2a3fcda4addf.nq.gz
│   ├── 213867e3ee3fc2679b6515c83e04465835aa5e2a.nq.gz
│   ├── 21ccba71fcae7b2c2123bec58c4964e17482d08f.nq.gz
│   ├── 26eac47822ba9d57b2257333b33a7b0ef9f4e6d1.nq.gz
│   ├── 3fe8b6c03a09d087edb1d2b10ed797067e26a6eb.nq.gz
│   ├── 4a3afe9428a583e36f0f9be9f53a057aefda99d8.nq.gz
│   ├── 551d25014a6a0c30c211bea74352570a08440bb2.nq.gz
│   ├── 6b39c43e80bbb2385be4fb1cbd1aa6d8631995a5.nq.gz
│   ├── 6fed11067c1170fe6aa70edd3c793ed02f493df2.nq.gz
│   ├── 73de1e28accbb4c2c237813179b5862339f16718.nq.gz
│   ├── 77868b755aa6531d1f259cf482d6360ba5ae92b6.nq.gz
│   ├── 79044cd067d65d465136e1d68a529f32b58e0d38.nq.gz
│   ├── 79778206cdc82dd2fb2e0f7d22170b5e75b5b635.nq.gz
│   ├── 7ca9299c154f8480a6712c43a5f638044b5f56d9.nq.gz
│   ├── 7d3004ad02493c942e76da617c5a3ae82c44d581.nq.gz
│   ├── 8542cfeb22814a4c45ef42ad24c218222f17b19e.nq.gz
│   ├── 8a407d08fddb1c9a960abbe67154ee7eb5fda0f6.nq.gz
│   ├── a34e1f9037ee1cb654a86d0c48f024fa9b40d208.nq.gz
│   ├── a444debdfcf6f65fc44e4e18bbb10573e61aa5cb.nq.gz
│   ├── a6422e88ba5f419cb9f79aaabf26bdcb677d11e9.nq.gz
│   ├── aa5c2472d1c3a8b0704205dfd4386b1bd874d2bc.nq.gz
│   ├── acda2d42d0f8cc1736057703425c8f16fede5363.nq.gz
│   ├── b71fb797038edc75fa5ba93894a3c2c5dc4bc6e6.nq.gz
│   ├── bc64f5c08e6ea25b7acf48db06923dba6d8e11e9.nq.gz
│   ├── bd880bdf3847f7cfa693e33cab90ba37ab476c0c.nq.gz
│   ├── d3f8d7d0ecfff4de886ca3b30e459e98bf0e4c43.nq.gz
│   ├── dc4df77b356e706b436ba65c4367dfa486e6c0a8.nq.gz
│   ├── e5465b72c22118efd3db2a431a8678c4262d9fdf.nq.gz
│   ├── f086315b0c0f1305f09bda6ab88537b92902887b.nq.gz
│   ├── f13b5b7200ec7a8619641f93bba9df5f5ea25080.nq.gz
│   ├── f23f14867bac54bce3de2c9e93dffccdad328159.nq.gz
│   ├── f2b8d6ae0aec77941d09efa85ad09b915c605cfe.nq.gz
│   ├── f87415754c0c4355e56e97a90f8280716fa096e2.nq.gz
│   └── fecf1c843b17d073ee9b2f4c326bf5d2cd870962.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7987e80be1ebf312f43af9c4ad5056383ba94e1a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 50 files
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

[ansible-community/molecule-kubevirt](https://github.com/ansible-community/molecule-kubevirt)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
