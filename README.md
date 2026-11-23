# Repolex Knowledge Graph of amodm/webbrowser-rs

RDF knowledge graph data for [amodm/webbrowser-rs](https://github.com/amodm/webbrowser-rs), parsed by [repolex](https://repolex.ai).

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
rlex download amodm/webbrowser-rs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 13fdff33e967dd160581ce8ac45a8c3588e8eb59
│   │   │   └── chunk-001.nq.gz
│   │   └── dc5a47657defa9dd9dac45220c6f3e3c727b6e41
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── dc5a47657defa9dd9dac45220c6f3e3c727b6e41.nq.gz
│   └── repolex
│       └── dc5a47657defa9dd9dac45220c6f3e3c727b6e41
│           └── chunk-001.nq.gz
├── blob
│   ├── 0189f8d8fb9b8a352bc6219151e95b25a3dfb1c2.nq.gz
│   ├── 0676ead892fe44c0dbee10c04bbfa1a20e5a6363.nq.gz
│   ├── 07efb8f95f4336f1ba406c8f9b042fe97d374e67.nq.gz
│   ├── 08546cc30be40ccc359dbf6cb310b43c983dfa37.nq.gz
│   ├── 091f0ac89635c0d0545f577a94522f8a34ffefa2.nq.gz
│   ├── 097a087b9307673c30b3fe809fa65a799a26d242.nq.gz
│   ├── 0df21d02d4a150cdd8a8e12941e0119af102fd3a.nq.gz
│   ├── 156f13a58b1b0099d801baa1b4a7a311b8b38fbf.nq.gz
│   ├── 158af1258785f871312dc868d1b9daa2a705fb53.nq.gz
│   ├── 1d3e4da426d1f89d9a17e385e8af98d2e634f895.nq.gz
│   ├── 1e7caa9ea89a3016bc73f03b5e4c167711a21374.nq.gz
│   ├── 296ab922eb08a9e67bf1fb7136ffc78d56f7d367.nq.gz
│   ├── 2ba75fae442b28024248c1d38f93f5b2036861cf.nq.gz
│   ├── 2e3d852cf7f862b5af341984de7796129d127919.nq.gz
│   ├── 31abf6bcd218750c7e985483a5c6f8f97b80487d.nq.gz
│   ├── 34c363e41f9abb7ff292bfb2d82cb8dc63a8c02b.nq.gz
│   ├── 4e301317e55e8c768204d3f494112f9f7a237bb1.nq.gz
│   ├── 55b5fcc9ff85f39bad47d31680abc666e0a940b3.nq.gz
│   ├── 5a4134f587ff93f7a6acad6fe4500c919a3e03f4.nq.gz
│   ├── 5f5c076e91ae83e353dce4ddd16f5e0cd6f2c066.nq.gz
│   ├── 6239943aab35a2b4fb7a3ef93097f2057a5c5612.nq.gz
│   ├── 681b9acef6489afa248c31e7152a34ca9fadd569.nq.gz
│   ├── 72b2eb4664a6d55726e3ec1f0460c2e9e7e650f0.nq.gz
│   ├── 78c786d9fe9791b0934011929735453ce1c91e1c.nq.gz
│   ├── 8164aab1a1c25c05475853578be0b9db49947564.nq.gz
│   ├── 86966fa5e870035093fdfd62877a6ebb7cae9b7a.nq.gz
│   ├── 8a3f35c488f22f5180fb0a8fec1a203411f88eae.nq.gz
│   ├── 8b4b88f0daa3a899d5c36c6f9f49fbce1acac6b1.nq.gz
│   ├── a32799d2247cdd7d8479d9979e037ae8c32b755e.nq.gz
│   ├── a54194b460bdf47f354283682773990cf0191d0d.nq.gz
│   ├── a578885eee9792bd9ce10e2e8e7c4c8d5eb75e72.nq.gz
│   ├── a6120773afa929ca5c297f82a5a8809620cba746.nq.gz
│   ├── abfaecbf0cd3b97913649ecd22b21765d460f93e.nq.gz
│   ├── c0154361eddc46a9df44c2a755e7762ae09ce867.nq.gz
│   ├── c92ab03082926547aba3fbd4835a74ad4e995b74.nq.gz
│   ├── ca5c6780969063fbdf715d6e9bbbe4f2900f8a0e.nq.gz
│   ├── d1c2eb0291083ef664f86943c784a33e004d842d.nq.gz
│   ├── d4eaf08271561f55fb2a1256000e84091490925a.nq.gz
│   ├── d71c8df799abe9747bd1b647db730f0bd8cdd7ca.nq.gz
│   ├── dfb500e7b3b280bd6198f9434a0c0e25229e8409.nq.gz
│   ├── e4dc3b89679af097ec03cf6c9b6201e8ddd2f621.nq.gz
│   ├── eedfba4c30c72c6b838dd43c568694e8dd098637.nq.gz
│   ├── f7ab33257ac38db76a27b90569bdbf6506a3568e.nq.gz
│   ├── f8f112a2caafce7f21125dba15292ecfb35b01bc.nq.gz
│   ├── f9322b2c5599a20214925e48caf2d587d9d06d7e.nq.gz
│   ├── fae832ed1356cc4bd046c8f5124e57906c912601.nq.gz
│   └── fc7d8dfbd7869de4a899992dd7193a2621211b83.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── dc5a47657defa9dd9dac45220c6f3e3c727b6e41.nq.gz
├── filetree
│   ├── 13fdff33e967dd160581ce8ac45a8c3588e8eb59.nq.gz
│   └── dc5a47657defa9dd9dac45220c6f3e3c727b6e41.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

16 directories, 59 files
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

[amodm/webbrowser-rs](https://github.com/amodm/webbrowser-rs)

---
*Parsed on 2026-11-23 by [repolex](https://repolex.ai)*
