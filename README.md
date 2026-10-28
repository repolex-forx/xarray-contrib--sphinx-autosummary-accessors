# Repolex Knowledge Graph of xarray-contrib/sphinx-autosummary-accessors

RDF knowledge graph data for [xarray-contrib/sphinx-autosummary-accessors](https://github.com/xarray-contrib/sphinx-autosummary-accessors), parsed by [repolex](https://repolex.ai).

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
rlex download xarray-contrib/sphinx-autosummary-accessors
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 80a489796411ea1d68041f8fe39e33420a09f1a4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 80a489796411ea1d68041f8fe39e33420a09f1a4
│           └── chunk-001.nq.gz
├── blob
│   ├── 00182d684725aa5843fc8504e1b5e6163117fc07.nq.gz
│   ├── 0fa6800c23d5fb9eb7da69dba7e7a2fa90f75baf.nq.gz
│   ├── 109f296f220b2a136175e91884d8a36e685afd1d.nq.gz
│   ├── 114aa602b2414ba492b5d792776bbe834eacf2b4.nq.gz
│   ├── 1b7a69beef583a3ca37005655d7445ad08420770.nq.gz
│   ├── 1f851360768556c52338d516bf62173fa83239da.nq.gz
│   ├── 1fd1729545b7970bf4c2bbabdfd31258760ac2b5.nq.gz
│   ├── 21ab6017be740d1ad9fab76292afd142976ef1b4.nq.gz
│   ├── 350bdc11e3109bd9972926abc1f7a5413171f9b9.nq.gz
│   ├── 37064666a51bfe6ac6068a30f7922723a0c87e8f.nq.gz
│   ├── 40b8a78813013e07dd1a23ce4058f693860a1f95.nq.gz
│   ├── 40f577ca2c2d1d671d1ebc763cb8bb39710ad74f.nq.gz
│   ├── 41296ef2352edb844c6ae2ef99db5813ed5560fd.nq.gz
│   ├── 4ba745cd6fdba69b81e890030cc8be682e8610ca.nq.gz
│   ├── 5b0ad2e797f69849c8f35b0f39014c8e37d3cdb7.nq.gz
│   ├── 5f89818f9e63c2f6829c7706c57f223cdb5bbd38.nq.gz
│   ├── 6bae2bce8300fc1c18a3e8aeef416ca2c9e3f659.nq.gz
│   ├── 739dca2ecf5d6aba25133c0f7277f38eb86b05dc.nq.gz
│   ├── 76954a5a339ab03a07bce28961715f047771160d.nq.gz
│   ├── 78d05a58bf994f3bf5b474a17584d29a093b66db.nq.gz
│   ├── 7a3301814f5f4d690e8ec55a9d1a73316aaecb19.nq.gz
│   ├── 997504b465e8f8c409ebee298542e7e0b8e84d94.nq.gz
│   ├── 9ef7a294f4c711ce84cfe415fb9bad1b273ea8d8.nq.gz
│   ├── 9f239b768b7aa3b3b121276e004b9a688058f1e4.nq.gz
│   ├── a8397512809745fecd3b23118328fa53e566c97d.nq.gz
│   ├── a961a94d84af1aa7f4ab4050ff3f9f2e21cb4db0.nq.gz
│   ├── aba4cc9a34935837825b964862881fff2de2d9a2.nq.gz
│   ├── aefbba6ef1bbcde2a537265e6ea4542944ff4a9c.nq.gz
│   ├── afdc4dfeac1f79a88eae960ad1671f89f99febb0.nq.gz
│   ├── b5ad65d6a736f945beb1bc1d04ef0ed973c8a04e.nq.gz
│   ├── bd77b6e16bb9949fa021a9b43fc42a785594282c.nq.gz
│   ├── bfa118b32d0b1a5047806a8dc2218974fe230509.nq.gz
│   ├── c873dfec74683da773ef0a23234de054898d1b70.nq.gz
│   ├── e225150ef36f92ffd5e124b099a26fdaf085956e.nq.gz
│   ├── e241cb9966f5818d63e6bd46622a7e17f789b601.nq.gz
│   ├── e865676f4bf781d32c56dcc309499ebeecb0a9c7.nq.gz
│   ├── e9625a6a89a145937c13c665056764cdd4a59956.nq.gz
│   ├── e9f7e5f0f242a8a74cf7e89a63878a4ac95d727d.nq.gz
│   ├── ea1ff0708edabed749a95c0017672f14942ec0a2.nq.gz
│   ├── ecaa4740681eee1c066f0d246ecefb7091e2b4ea.nq.gz
│   ├── ef5c180169c3b930d9f33bb8208e37fc415940cc.nq.gz
│   ├── f72199c427835ea33f08991c4a074ee36104bc30.nq.gz
│   └── f7a51d87c9421f85a534b438ac417a481a7bcdfa.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 80a489796411ea1d68041f8fe39e33420a09f1a4.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 51 files
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

[xarray-contrib/sphinx-autosummary-accessors](https://github.com/xarray-contrib/sphinx-autosummary-accessors)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
