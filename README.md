# Repolex Knowledge Graph of jupyter-server/kernel_gateway

RDF knowledge graph data for [jupyter-server/kernel_gateway](https://github.com/jupyter-server/kernel_gateway), parsed by [repolex](https://repolex.ai).

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
rlex download jupyter-server/kernel_gateway
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8c483ff06e6b88a579137b5045d3b90c2826b8b0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8c483ff06e6b88a579137b5045d3b90c2826b8b0
│           └── chunk-001.nq.gz
├── blob
│   ├── 00211087567df66b709b045a87f84abd3d1a9442.nq.gz
│   ├── 051b1aa10f2d98b84bcad697d9509187963237c3.nq.gz
│   ├── 10d8abd4ea9405b9397e495a38a1853cc50f560d.nq.gz
│   ├── 120fcc8fcce47d9ee0d0440a56948906edccb1b3.nq.gz
│   ├── 15314bee67fbd218291f107361686e949f5a834f.nq.gz
│   ├── 158172c4cc7eec6e038b39da81ed267a3d7cd5ac.nq.gz
│   ├── 1a1eb06147aab3e4ae901ed35fadb10b5fb6275f.nq.gz
│   ├── 1a5b5032750245bb7a2fd707d2335fdc0f9ab005.nq.gz
│   ├── 1ad4f4417c345044913616c8c2d4a31c941e50f5.nq.gz
│   ├── 1b7234ca214bdbe3c7d361f6a701ab2f7e16a3fb.nq.gz
│   ├── 1dbe9b82d0839c99d7c93d9b7e8000557de18be5.nq.gz
│   ├── 251ef9c3022c4de20aca9ec5dfb2cc741f675dd3.nq.gz
│   ├── 2ca460150bce6e3b88fae9653d4954fca08c6949.nq.gz
│   ├── 2e9b460e2d384ce2cfe9270d66ea12e0667ee5c4.nq.gz
│   ├── 2f0208daeea4b851179a692692971a322c863a61.nq.gz
│   ├── 3309c306b40a636fdca1cd267118d98df815db23.nq.gz
│   ├── 3370c6c36ecec36a999bce45c8ca0d9607fdd1de.nq.gz
│   ├── 33b53e072fac48bd7431c61353ddd0f1ee87fdc3.nq.gz
│   ├── 3682fc79f5ac6f0613a24a2e7fb2165184a77020.nq.gz
│   ├── 396330bb9729d2ec595617aef79fb28600d86bd7.nq.gz
│   ├── 3b108d34ee498e10c0eda4b5e59589ebbb76ac9d.nq.gz
│   ├── 3d90e41fea6692235dfc7bc3a4910de8fca4bd64.nq.gz
│   ├── 456cf53ff4816e320664aa60fc9e519636e85939.nq.gz
│   ├── 4c5b6599919b805ebbb12480b729db32ec46d972.nq.gz
│   ├── 4c706fdd8586278123e0f1da690a8959adbb2417.nq.gz
│   ├── 4cad8ba011610ff2cd01d7b10f43bcf95ad44e78.nq.gz
│   ├── 4cce7e904eb9a73d09fc3a95cf94e0c6d6ed5eee.nq.gz
│   ├── 514ff0d1b8b93f773ca7e0427d874423472bcbea.nq.gz
│   ├── 528c70c7b90cac8380acfd05fad2c3088c52fcc1.nq.gz
│   ├── 5295e776b63d7adfab3ddad99962cc6f81968909.nq.gz
│   ├── 594a8fa8369e93aea280c972fec68501c454f5c4.nq.gz
│   ├── 5bf500ba12f47aa20bb160286e8a07c5e8586342.nq.gz
│   ├── 5c61ed7e310502f5e977cf034348fe5037838854.nq.gz
│   ├── 5fb6c580b5c88f93b37299d03810df54fcffa4b9.nq.gz
│   ├── 606849326a4002007fd42060b51e69a19c18675c.nq.gz
│   ├── 60af4c5f16741c7c2fe17cdd9718ae5f6d56d8a4.nq.gz
│   ├── 6bd90a77606e5ca8491f34b2c29d75e847387ccc.nq.gz
│   ├── 6e1b5a78c7e05c3a7f2f46a83d3fe6c235a1d62e.nq.gz
│   ├── 6e7acef92f3d12d532a519175726939128332387.nq.gz
│   ├── 6f58e5447ebe686a105487cdbcdcc0919a63e209.nq.gz
│   ├── 715e6bc7178b150ae3dc84427a260bd3086eea17.nq.gz
│   ├── 75432d5f8f7de66b985f77497f2a4bcdf7b81107.nq.gz
│   ├── 783fdfb34f4a94e480c2c58194a46434fad3a886.nq.gz
│   ├── 7cea53deea23a7d11287e4214b9944b866b67b55.nq.gz
│   ├── 834ba9a0bf9faece197762fb58f404db94c7cf89.nq.gz
│   ├── 8640c7ebe0a84cbbbaa102e73fdcd8b34c750048.nq.gz
│   ├── 87003e20fb007a318cb723225b1445bfad28c473.nq.gz
│   ├── 8758cccefbf849a2335fcef7de060b6c156ae0e3.nq.gz
│   ├── 8a650b53ad9c3c5cfad418152eed52eae7c8a52e.nq.gz
│   ├── 8e88a2637c9b4d1f225a4f9ec7c2791a5173f142.nq.gz
│   ├── 9071e954c61310dcb7436c58a106af702bc47a0f.nq.gz
│   ├── 92985dc50ab9f2265934a25088c9ccf213f042bf.nq.gz
│   ├── 94f8f0881ce8d400ea0a405bea5b912ec96c6c8a.nq.gz
│   ├── 95b8c563266f834e826e787c51d9bdbdf86fc0a1.nq.gz
│   ├── 9739cddda5837b6af73b88f1113f2fc69909f3c7.nq.gz
│   ├── 983483fc6387c6f473249de941d0b0e1a5021c6c.nq.gz
│   ├── 9f21370696d628ae4ae7ed37273f69c7ea419fb1.nq.gz
│   ├── 9fe4cb2814168ead557813a8d53399f8ff90b462.nq.gz
│   ├── a011861bda342f599e53e25c5fb8d5e0d0a882a6.nq.gz
│   ├── a3ba92ceafb948de8d3314faedcee321cee78550.nq.gz
│   ├── a87c0ebdd12b5e3876aba72eb58e80f733f5942b.nq.gz
│   ├── a98ca1bfddef5a7bb43d7d7e27222690733050dd.nq.gz
│   ├── bab382d7eda7814539ace4015acba558bf0dc68d.nq.gz
│   ├── bdde0a987e4ecbdd499c57c321858733be915c4e.nq.gz
│   ├── bf11435f8e2f946547852be8323e3dd69708b6b5.nq.gz
│   ├── c1463008fe10057d5339c9611053564131449401.nq.gz
│   ├── c2dc7e10207ba5e44931f76cf8d2764da441efdf.nq.gz
│   ├── c4477c154d66a3e0a29e596b2914f0c1fe8ca62e.nq.gz
│   ├── cc0e8ef51fb2917657c470a9f68d782b95bb3a40.nq.gz
│   ├── cf7522f5895f331f786e23d4e77125841c6af6e6.nq.gz
│   ├── d889f274de8228845f9aa47c442acba5e6007f2c.nq.gz
│   ├── da7a01bec030d35a6deb15bf62f5a1b6a76c117b.nq.gz
│   ├── e509f6f9847a86d51fb3d3a3a716d6f8f5f9eb54.nq.gz
│   ├── e519ba8bda6af8cdf854e12a77e393a7de19239d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eaa74e4f5d3ce122eb82f9570366468c52531452.nq.gz
│   ├── ee0c07949e5b2c75a9bbf2d81fe254b7b4392a7e.nq.gz
│   ├── ef63b7bb3e27a6230366f248f5ae1650e07c3a6f.nq.gz
│   ├── f53f1d0eace67383bdf918a4e472c6dc4116e02d.nq.gz
│   └── f6a42617947116db4562178f2d69716e5f69d2b7.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8c483ff06e6b88a579137b5045d3b90c2826b8b0.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 88 files
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

[jupyter-server/kernel_gateway](https://github.com/jupyter-server/kernel_gateway)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
