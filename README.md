# Repolex Knowledge Graph of aio-libs/aiocouchdb

RDF knowledge graph data for [aio-libs/aiocouchdb](https://github.com/aio-libs/aiocouchdb), parsed by [repolex](https://repolex.ai).

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
rlex download aio-libs/aiocouchdb
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 84a08cc339c430175c069b894b3e27b034f45b12
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 84a08cc339c430175c069b894b3e27b034f45b12
│           └── chunk-001.nq.gz
├── blob
│   ├── 11032aaf203f455a339326a11bf3530f5bf896f9.nq.gz
│   ├── 1ac007b88a1711a298acb1fc83742bd5f7a1dc25.nq.gz
│   ├── 1db063a28ec98efc8812f1502264eea05e478cdc.nq.gz
│   ├── 229533e904c5bc435d14d33b4793cdb69644fc93.nq.gz
│   ├── 2453cd26c844813311a5547fef750ff91d91d61b.nq.gz
│   ├── 2bbf7ebc8ccfd06f4ea57caa0b001bb999c48654.nq.gz
│   ├── 302d870fbac0fc033f55595dbe35b977609711e4.nq.gz
│   ├── 33cd77bdf0336c66437d132a10b6fe603e62d859.nq.gz
│   ├── 34ece40b6386943e961d750502c9ce1b55f6e444.nq.gz
│   ├── 3958c3eedca322618a9d26396390f1c79852e9d9.nq.gz
│   ├── 44bb1311a964a84386f75f232f4bfaadf08a8e63.nq.gz
│   ├── 4635668bd435b876d22d77e01e08c5d49d250403.nq.gz
│   ├── 4638e4aa53e32b2e7914e32f47b025e0c638c266.nq.gz
│   ├── 4756c91d1824a7b3d0ddbe508f8648d0faf8e6b3.nq.gz
│   ├── 47e1afbfd6c0281372f38502df684f1263c2eedb.nq.gz
│   ├── 4ad2a8ea73f150e8eda3dfa42c500eb595dc6bb4.nq.gz
│   ├── 4e1fe9e3eaa87e462ad8302902c1b8067b966535.nq.gz
│   ├── 62587d2a55c08545fd37599c7e01bc85fc19f957.nq.gz
│   ├── 626cf427f0de45c739e91b1657e8383921ad617f.nq.gz
│   ├── 68a8e9c20bed20f19123eaaa6263d6d355c615a7.nq.gz
│   ├── 7286e35446f7c3b0cf6a7474b01a6b36cf359df7.nq.gz
│   ├── 73071a582f220e75679659c256b2a8184e50d7d9.nq.gz
│   ├── 7b101ee7410e79487e40fc780bdf7e148c13e87d.nq.gz
│   ├── 86204d6a51d7e862185a03be47b24b1426cb467d.nq.gz
│   ├── 896d7fcec759cdc1241bab2f4a7fc546b39e3e60.nq.gz
│   ├── 8d7536032d8c73b37ae40b1ff5eef761cd3d8d4b.nq.gz
│   ├── 8f30d123a05e8b2a05e5938e3c07e3b0df3b46bb.nq.gz
│   ├── 91e9439ec4388a5d74a2b850725df55be922075d.nq.gz
│   ├── 9263cb6c04bf507a9b8feb1c1aa0a658634bc7b9.nq.gz
│   ├── 95c2f981c1e8d487daff0351e44a4eb725e37fca.nq.gz
│   ├── 9c3e694c9e7666ef68974be4af929459eea80b50.nq.gz
│   ├── 9f6596b554333a64e849da7a73db07912de3ee2c.nq.gz
│   ├── a25bf22115a89bd329631839b58154b889773e75.nq.gz
│   ├── a48d823ad0ff163074a0fce58bd7a6fe667fc59e.nq.gz
│   ├── a9ac36e20211959c9365d2c8466dcfb9f23ce869.nq.gz
│   ├── af701062441ab9b8961a5f115ec57916be3e319c.nq.gz
│   ├── b1e3093134dcd4dbad56a2c54f42383ae4564c43.nq.gz
│   ├── bba194710fcfa219a8c02ec85b739f2c99543cb4.nq.gz
│   ├── c08af6421b11d5f4eee0710524bd07cdecb8ef87.nq.gz
│   ├── c413ded5f92b8828fc0ec2118b8b331e9c5c54cc.nq.gz
│   ├── c4c302fd0ff72fd7e97a4dae0d84d379dbefc2ca.nq.gz
│   ├── c8375931da1cf7f6b3f44b6cee59ad24380539d0.nq.gz
│   ├── ceb9605e3c84f45de682a0b474824d7bdf51e09f.nq.gz
│   ├── d58504918c5dc1b3f9ca03f7b99e484d876e94e8.nq.gz
│   ├── d86a854ef4cfe60a0e0b71c1dee9c482354d8295.nq.gz
│   ├── e65c990e214a4d3c25f2c3b17cecbbc4d9e3f835.nq.gz
│   ├── f0325c205d239a96f2831c9ebefd882625bed35b.nq.gz
│   ├── f73f4c6de4904ec08741f4a5c038a506eb9a06a5.nq.gz
│   ├── fc44f9db97364472ac5f3b3f19acb5b2457ce32e.nq.gz
│   ├── fe65518372da7582415eb8111e20e2edf66dfc82.nq.gz
│   └── fecf4d1bd21a5c6074983fec3bbf7ccb62bafb6b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 84a08cc339c430175c069b894b3e27b034f45b12.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 59 files
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

[aio-libs/aiocouchdb](https://github.com/aio-libs/aiocouchdb)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
