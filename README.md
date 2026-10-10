# Repolex Knowledge Graph of tox-dev/platformdirs

RDF knowledge graph data for [tox-dev/platformdirs](https://github.com/tox-dev/platformdirs), parsed by [repolex](https://repolex.ai).

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
rlex download tox-dev/platformdirs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b3174fdd4e80c83d72cf723fd2a7bb6cb54cbd5f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b3174fdd4e80c83d72cf723fd2a7bb6cb54cbd5f
│           └── chunk-001.nq.gz
├── blob
│   ├── 0a145e6efc0e62ea23fc0f9f9ac8774ea6099313.nq.gz
│   ├── 0c5a16bdc894cd5d82dd38701b8fb601f240948e.nq.gz
│   ├── 22303d2b12c51c8b4b0454a6b4b71d2add943bc4.nq.gz
│   ├── 224b84eb7e977f78931831a9bccaf475f5a793df.nq.gz
│   ├── 291f478090a0b98c6f10bce3ec842aed613e0be3.nq.gz
│   ├── 2f63e50b69a1da9328085f550645803d15e096de.nq.gz
│   ├── 31d2678cdb3fae4f1dc44fdcfd615cdc61fd7efe.nq.gz
│   ├── 3bbcfc54f6e462a814e8f06b8962fa82c2e1829c.nq.gz
│   ├── 4683247f77b91c27c8ba7c713f7e59a5b6f7d2f3.nq.gz
│   ├── 49c0cf584ebb7a5c1f1538d5195029d50862f210.nq.gz
│   ├── 4e98c32b098769a22fe65fd4a0faf2cb807d553d.nq.gz
│   ├── 54c0c08bf329f0ab9819d7aebdd102ac855f6e7d.nq.gz
│   ├── 5ea3973fb8014102f519bf8ad21f547560ace276.nq.gz
│   ├── 5f89818f9e63c2f6829c7706c57f223cdb5bbd38.nq.gz
│   ├── 605d5983d4594de0ab3738c9cf897b9b3a294ba1.nq.gz
│   ├── 62eb5075fc71566a9c97a5e23d02b7c64d9360c5.nq.gz
│   ├── 66e05dca76f0c48afcc73f6c541b38af4cbfd1a2.nq.gz
│   ├── 6a0dee2dcf15a00507c6f38c4298fc7a92aabe58.nq.gz
│   ├── 6f685f3e9d1754c580849cfc060f4c4a56c5423d.nq.gz
│   ├── 7130527f15a9eaa9fc24e3395ef086b947c00013.nq.gz
│   ├── 75a1779a65d68603073fe77b3abfec80b1108021.nq.gz
│   ├── 763c90f2eb45146f1bf04e4c3fbb44f9c5a40cb9.nq.gz
│   ├── 792a1d94f684153707af0789f7fe48adedf10630.nq.gz
│   ├── 84f75c677ff34eae0517277c88167b0ef0db1642.nq.gz
│   ├── 8a646005dd33d1e069882f14b79e654381b100cf.nq.gz
│   ├── 96cc6a44f09a16dec53fb8ec47b4bcb6b389ab76.nq.gz
│   ├── 98481b71212460bbfa9225f49a6ce76934e7a255.nq.gz
│   ├── 98890fe25145eb90f89bdccdf1098ff99161b2b1.nq.gz
│   ├── 9c2d014db2839265941905d61471a4a5ef0c2e9c.nq.gz
│   ├── 9d0781aaa71ef1207c97ece3523a96e1ceb0bfe5.nq.gz
│   ├── 9db7fadd747df328611ad5bfd24d6d978b9badb8.nq.gz
│   ├── a06182c808126ef3d2068fe389145c1b8c444c39.nq.gz
│   ├── a6350e6fa2bb6ca829d096c4131983a084e7b062.nq.gz
│   ├── a767418eadeef9bac14eaaba7545925855323cc2.nq.gz
│   ├── b5c57521eec0b8c1ae0992bb6d93c1aacbde2eac.nq.gz
│   ├── c1729032517d01d3cc8caa5cb18fc0a241175ff3.nq.gz
│   ├── c93bd221b2e819e7bda9723969200d078662b839.nq.gz
│   ├── d034f293a2296bbbb8b65052c286a7ae899237bc.nq.gz
│   ├── d94a1c95ebe72602dc762b696fe4833f94c6d944.nq.gz
│   ├── dabda041ce47f74e44e8bffd3ae46c488168c396.nq.gz
│   ├── dfb844943d3fddfd00c31013f12bf26b7ed387bd.nq.gz
│   ├── e32d078c067090fd3e5584a17e9c9c8ebc6d1b7c.nq.gz
│   ├── e587f94397f6ab0e8ffc08b2d5c4a2879182926f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea70b5ac5b40b8baabf42ee3b5d8c9f1b8d2575c.nq.gz
│   ├── ecca6799d5e91aed4a8f17e8b0ce8d7b521358d8.nq.gz
│   ├── f09e831ae35d79a16b9504cc2d9af307912bc295.nq.gz
│   ├── f2bd595b089d464f557da01c4bf6491c5d8bf433.nq.gz
│   ├── f35fed9191b1142ddaada8a96de4a9461c5d796c.nq.gz
│   ├── f43c18c05d9a52effe8018f30c977e858cc9b31f.nq.gz
│   ├── fa4a9d424e4ef07d2752da001af101c43a680493.nq.gz
│   ├── fd0ac0ee545a88d558d45312f966e93d7115299e.nq.gz
│   └── ff2e83ccc697b46a9253e3407cbfa479e6ee0e08.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b3174fdd4e80c83d72cf723fd2a7bb6cb54cbd5f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 61 files
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

[tox-dev/platformdirs](https://github.com/tox-dev/platformdirs)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
