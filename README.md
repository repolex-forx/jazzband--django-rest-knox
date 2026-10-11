# Repolex Knowledge Graph of jazzband/django-rest-knox

RDF knowledge graph data for [jazzband/django-rest-knox](https://github.com/jazzband/django-rest-knox), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-rest-knox
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c3522713e03ff8990c16c327a125630a0c16170e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c3522713e03ff8990c16c327a125630a0c16170e
│           └── chunk-001.nq.gz
├── blob
│   ├── 001fccc27f07997478d8974117422091be0669bf.nq.gz
│   ├── 01172573dd7a33093c78c0aa0bd7938553b7888b.nq.gz
│   ├── 04c99a55caae5d51f17666f554c2c8cea0aadfc0.nq.gz
│   ├── 08a22f4272e631e27e82dc86699bb1c853a22fbe.nq.gz
│   ├── 0d72820f3e7bd8f13887bffa282f4789a9dff583.nq.gz
│   ├── 10d791913f8b3f6e2e8cff5014700aa176fce0a4.nq.gz
│   ├── 18a338361052136a953ec70dd8a08d8116173a48.nq.gz
│   ├── 197cefb7bed05c2990c6c36c1fd9195de18e852c.nq.gz
│   ├── 25e0138ae5722af4bb817c76ade2e3149c5c1d32.nq.gz
│   ├── 285222da4f7b85c9299e423ce90bb90487c8f8e0.nq.gz
│   ├── 2aa99bc1fe5bd96453842b02521d2b1303726ed4.nq.gz
│   ├── 2e6a8a9809ee09ae9b2ada76f83cb37c59e09488.nq.gz
│   ├── 2ecec2a37f25e06c372277f62cce0eed90d37284.nq.gz
│   ├── 310512e903dd08d5e0011afc555fecd22233995f.nq.gz
│   ├── 3b4733f2ca2d5cf272f745c4a71a8211f5a90703.nq.gz
│   ├── 3c644fc651388d10cb20964308b776ee1232bd7c.nq.gz
│   ├── 413df60fc64fff288a3225a1b56a32f71dd1dbad.nq.gz
│   ├── 4a5a12d2bb0ccb835af22450bfaf34a0d4d56d3a.nq.gz
│   ├── 4a674fed7cf6c52c86e3988bb2c415063a49f510.nq.gz
│   ├── 4b0f98adfc17d4026ec26b5c0f95f3336ea7af7c.nq.gz
│   ├── 539f22376787a7671ad857dc08cd6a16a4165716.nq.gz
│   ├── 5524fe430be0d41c9ea59ea82b26097476d6c44e.nq.gz
│   ├── 580be76510a7b9c4ad5b7909dfa987c1919bc5ec.nq.gz
│   ├── 59b058d55651db1b81352c31eabaa8b148ab27b2.nq.gz
│   ├── 5e117246cecb9ea7dbeb6d783af2116a0ae79618.nq.gz
│   ├── 628f8747c1424299c9c81c66790f4489284daba5.nq.gz
│   ├── 658dcbc2473795848acad09a4d84888d559d378a.nq.gz
│   ├── 70f85f09a5e7fae2d1534df9f3cff28217dca2e5.nq.gz
│   ├── 722d0e435f07fa7a9f54f7bdd6aa45cca0cd2c34.nq.gz
│   ├── 7791a82cbec66dd1778b8aa67409eb504c846b29.nq.gz
│   ├── 8124e5af1993f43975701b3f83a7f536eaf8c131.nq.gz
│   ├── 8365e1aedc0ed50e177f8a438fc82def7262aea7.nq.gz
│   ├── 85b22572af3d82865af498a3e3ab65aa95389c8b.nq.gz
│   ├── 8b3fb1d1b9f2ba11a95fc6750188a3f8f55a61b5.nq.gz
│   ├── 8bf9db7397fedd70938f29bb3d0ecfd4ed415ad9.nq.gz
│   ├── 8e81c01ff4eb12f828d4facbc38e7ba79781bd61.nq.gz
│   ├── 974e7470122c689c5ef3bf61ea3b32e3b11cd1c0.nq.gz
│   ├── 99959fb76dc1facc4ac47a7f35abed4e29039a03.nq.gz
│   ├── 9e9b075bf19e8999d41886410eef6ea022c9e8c0.nq.gz
│   ├── a187a870e444861617620e90fcb007d44e863d84.nq.gz
│   ├── a3fa51d3f521bb2aa74d69560af2c1758b2922b4.nq.gz
│   ├── afaeb55961130cb6249fd78488ce89b89563d750.nq.gz
│   ├── ba97bc96a37ec58e7b041741f8fbb88ad3460232.nq.gz
│   ├── be8b5d9c415ffa81e2d525e53fb7d269bcd39e07.nq.gz
│   ├── bf3b3bd1ad109bde475a8c8b8e53bd0d1d6b5362.nq.gz
│   ├── bfa2d96a16d650056cb921ffef579b60aa863a70.nq.gz
│   ├── c8cfda4ed8d71dabfd800a175d7b745046ccabcf.nq.gz
│   ├── cdaee9188c68765221bf48864264002b481b0fcc.nq.gz
│   ├── cfce0f821f28dd71566278814bcc28a19077f4ef.nq.gz
│   ├── e1061e27c43df547bdf932b05cc0edaf5764ccdf.nq.gz
│   ├── e27a8ac21e8db427eaa69d63b918560ce43802fc.nq.gz
│   ├── e3ac58c86586a7517f15055cabf42623b395e32e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e73a05c25bbe072a3f2242eb924ce7c4c7de9320.nq.gz
│   ├── ea3e530380bdb98a3bdf6f57636690bfa74a8a9a.nq.gz
│   ├── f24cebf977dc9a9b9b54171b73b2837f99e19e31.nq.gz
│   └── fd5a5db94789ca12d78934952d9720c627d28fcd.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c3522713e03ff8990c16c327a125630a0c16170e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 65 files
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

[jazzband/django-rest-knox](https://github.com/jazzband/django-rest-knox)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
