# Repolex Knowledge Graph of celery/case

RDF knowledge graph data for [celery/case](https://github.com/celery/case), parsed by [repolex](https://repolex.ai).

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
rlex download celery/case
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e0ba875515c693fb79f8f212e5d35b140ec79505
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e0ba875515c693fb79f8f212e5d35b140ec79505
│           └── chunk-001.nq.gz
├── blob
│   ├── 15dc8e484123eff84c2d5b576559c689d2946634.nq.gz
│   ├── 17375c75b631e5dae0f9e51a3e0db35a8b2325b0.nq.gz
│   ├── 19f9d622962e3f3c6a6221c3bf0029ed433db84a.nq.gz
│   ├── 1a28a5c69fc456fb47a18a963e90740697c45bae.nq.gz
│   ├── 1a4fd77823a5329092d7f2a1e0070e3d17db1d11.nq.gz
│   ├── 1c1489c8d3a036c3af4a5aa57ff600d57f3e447c.nq.gz
│   ├── 2178b95607f0769ff76ad76986a4c3c1718ca951.nq.gz
│   ├── 22f35029f75f33ece4b2dc96624c5347497480ed.nq.gz
│   ├── 22fb1f902a9f8dced0c3180ed0187471396cbf8b.nq.gz
│   ├── 2c38e5da0a7685d1b6dba700d0ed2e43eeac4937.nq.gz
│   ├── 38b5bf1d62a2b5ee1d4ddd420a18e115766fe108.nq.gz
│   ├── 3a472bc836c30415445def35bc58338a1cbe38c5.nq.gz
│   ├── 3f05628255a9939606ed7426e91be18d07581d23.nq.gz
│   ├── 47ac00ddc337f8b32df3e026d235028ed4f400cf.nq.gz
│   ├── 50303e8c143c8b70d8e0e27ee04a960034c1712d.nq.gz
│   ├── 540601e5a4db0f2d9fcdee83424251afd69c296e.nq.gz
│   ├── 582316ac954fa6a90be37301607d4bb08580d1d5.nq.gz
│   ├── 5b20da335b1980be7deed652749d4959d650f59b.nq.gz
│   ├── 7331c33c184516dad0a32138b1e05687e4d8e176.nq.gz
│   ├── 75e0746cd50b95c12d0fcdc0f387f7bf77f76610.nq.gz
│   ├── 81bd60d37e0f0631d101594e8af3a865157b71de.nq.gz
│   ├── 85fbf0ecfa3bc578cef96110ab86c9a7d547e052.nq.gz
│   ├── 8677155029ca200cfa6bbab09f2fda1e33940e3c.nq.gz
│   ├── 8825377c32ce58c37ebc8689343a757bc115aefc.nq.gz
│   ├── 9def65e4b112296f5170874b629126b87de5b1bc.nq.gz
│   ├── 9fc3610f07586ec124608aa40090cd95bb7b8e7d.nq.gz
│   ├── a096a8cf906e6ccfd727cdb4105ab9618e942f94.nq.gz
│   ├── a56bc45da123e67c5c3fe68c2de26c41050dbd26.nq.gz
│   ├── a75aa4e2866fbb962847b820983d264b108d9a7c.nq.gz
│   ├── a76466cfe65ae5a7c894fc7a679f6333d20b4a24.nq.gz
│   ├── b5b2e4c1785d343e113f1209c49b6a99b3f1becc.nq.gz
│   ├── b7a16d39d2abe41a210e0d0bd7bc9cc3e8532502.nq.gz
│   ├── b997ff948789a15d55270e6364588b2740a005bf.nq.gz
│   ├── cecec31f47aab6fa722306dd7f801e61c5b97cd0.nq.gz
│   ├── d88576ed6a82d17429396dbdcac9f07ffb4ff12d.nq.gz
│   ├── da7087f682c9cf0adca6177b873ecc00ef8bcf14.nq.gz
│   ├── dc04fcad14fa1c856e5b844fdb411a04070bf3c2.nq.gz
│   ├── dc9901d75ebe6b6d3b7ff43539df03209accbe39.nq.gz
│   ├── de972a4fac4e74cbb0202aae70c5582bd09d021e.nq.gz
│   ├── dff00a14cf61bdab6fd248015e5c741ad9fbef55.nq.gz
│   ├── e5fa3a849e3c2979b1bda3a0d29b9ebbd4ec6243.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea955ff9ca72ea67d6627b4c06c26c6c42e101c2.nq.gz
│   ├── ef39a5dfe7fb80671fddde5d14e4c28a25fe1119.nq.gz
│   ├── f27a61a6a6679480db897c5b362a942e4597d7f7.nq.gz
│   ├── f28f749ade9ee555d890580d130dbd32cd0c486e.nq.gz
│   ├── f6e75b5b31ec274d7dd2378a9ee5d703fcec77ff.nq.gz
│   ├── f83c6c130e043ef8c5a37d52e8f7e6ab9d931293.nq.gz
│   ├── f9881529d2dc92a9aee72452fd272d0071cf8d2b.nq.gz
│   ├── fa8d306b79a33491f09b8eb50c60d15f96cdf93e.nq.gz
│   └── fc901858029bdef0d0e01528e07fcd98c52d3edb.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e0ba875515c693fb79f8f212e5d35b140ec79505.nq.gz
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

[celery/case](https://github.com/celery/case)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
