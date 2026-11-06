# Repolex Knowledge Graph of sphinx-contrib/exceltable

RDF knowledge graph data for [sphinx-contrib/exceltable](https://github.com/sphinx-contrib/exceltable), parsed by [repolex](https://repolex.ai).

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
rlex download sphinx-contrib/exceltable
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d8c05cf49a0a43bb1ca868ce0a395a00314c02d6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d8c05cf49a0a43bb1ca868ce0a395a00314c02d6
│           └── chunk-001.nq.gz
├── blob
│   ├── 03c56efcf4b0120742f07ca42ac3d0ebbaf4d182.nq.gz
│   ├── 05cfe4670f392f82e0bc9c5d7b1e23e96464d00b.nq.gz
│   ├── 0dbd51121512d7aef0a9f7bd3041a812e2ccf8f8.nq.gz
│   ├── 1688ba5c70cf9acd7ca53f27ec4d9534185bf93a.nq.gz
│   ├── 1fc91d736d20c40c8281222cc4fd5e51bcc1fd64.nq.gz
│   ├── 20fcd67aab0141ad5fb6da0296c59a6b6fb8270b.nq.gz
│   ├── 2341d41c54fb3b91596e2b25ce0b031b55587309.nq.gz
│   ├── 251498d7560a454a45f1ec6762350e8191eac85f.nq.gz
│   ├── 2e1b43a16a092c8037af9f05ce6f08d4efe71b83.nq.gz
│   ├── 2fe051d2d5c6548410ecbc7a456a5363d9a4b7cf.nq.gz
│   ├── 3b00adc5b13d86757e598ada2081642a66836d50.nq.gz
│   ├── 3f481dfd401dbf845acec213a24e5f2042cabaff.nq.gz
│   ├── 45dd5f5b51e10661a6b6699e050c4ab23d721804.nq.gz
│   ├── 497ffa47026602239ef86f25c262a93ca8bc9071.nq.gz
│   ├── 4b9742e4469763489ad04045e1acb94ec8ba41e3.nq.gz
│   ├── 52b93ceb9ef655980bed5a80fb1ed15404a2d73e.nq.gz
│   ├── 56d56f10892bbcc3e885222aa0d3ba5b160bdc29.nq.gz
│   ├── 5c8e7ba2f3639e138f4a4041dd9d2da294971b6a.nq.gz
│   ├── 62ac3342a593efb196169a4c139b581781f30b99.nq.gz
│   ├── 707639e77346164ee506b31a2827dcb1ea797905.nq.gz
│   ├── 7ab9f7deec7f4d55dc9dddf77f4c63367f7f49a8.nq.gz
│   ├── 7b3d83d96cb2b47cecbcc66856aca7cfebc146b5.nq.gz
│   ├── 80e211d23454390e2f7ce88dcd0aecc62ad1ee1f.nq.gz
│   ├── 87b085d1428d76101f6b0210624001fe0cc0bb84.nq.gz
│   ├── 9052adb0f536335571f60d5c86a476977e4cb2d5.nq.gz
│   ├── 94b9636520e2246f9396a117b8565b6add71117a.nq.gz
│   ├── 954237b9b9f2b248bb1397a15c055c0af1cad03e.nq.gz
│   ├── 9578a8cc7a26e3137f0bcfdba9120c5ffe8e46ae.nq.gz
│   ├── 98b915782e7fdbdc06e8bcf86e1d2f9d7a2db059.nq.gz
│   ├── a0381ca86600d4931a669719b47406fc9b2f7557.nq.gz
│   ├── a58ce175e9c6148c83c772b037a6ce96b3caaeb5.nq.gz
│   ├── bfa4205f13be8df999093731fdefbe849b4894d4.nq.gz
│   ├── c6d0eb81233f47eb8b311e5d995a207dad1f4973.nq.gz
│   ├── cfe729890af48882f12a8d29e8861ab38f1999cf.nq.gz
│   ├── d00562b5a8c697eb71ed07831791d4a11d07b52b.nq.gz
│   ├── d058c79da8bd3d75d03fd09ffee66734174d1db8.nq.gz
│   ├── d261436d2ec9826f3733f3fa61c6df0eab60a7e7.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── edc38d56a0c01712facda2a2c3d7434b212d6232.nq.gz
│   ├── f05b93456cd6e40a29feaa94ee7a8d354e1cf316.nq.gz
│   └── f109a231803c13b2b99d067b5e81bcbcbd7eb2c9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d8c05cf49a0a43bb1ca868ce0a395a00314c02d6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 49 files
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

[sphinx-contrib/exceltable](https://github.com/sphinx-contrib/exceltable)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
