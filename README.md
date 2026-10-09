# Repolex Knowledge Graph of modelcontextprotocol/quickstart-resources

RDF knowledge graph data for [modelcontextprotocol/quickstart-resources](https://github.com/modelcontextprotocol/quickstart-resources), parsed by [repolex](https://repolex.ai).

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
rlex download modelcontextprotocol/quickstart-resources
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2912bb30785c7702a2f9abfab783e9140aa7246b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2912bb30785c7702a2f9abfab783e9140aa7246b
│           └── chunk-001.nq.gz
├── blob
│   ├── 0ab6cd7325d22509d356b8f3a73ee5f935495628.nq.gz
│   ├── 1833b1d4ecf9731d472c621dda62b8ab2b82d1e0.nq.gz
│   ├── 18be39f116b7811a631c04f2471c041277fe622c.nq.gz
│   ├── 1c61a98d686ef9d64bf44f349daef20dd9cf63f4.nq.gz
│   ├── 207e88c7927566c626f8421135ca7c89dc11b8f1.nq.gz
│   ├── 22d5761df56edb3a0a92b200926ba7cafaeded62.nq.gz
│   ├── 245fc29610f79a3a6461331d5f580681e129ea77.nq.gz
│   ├── 26302b178a3eba68bacb77dd085e06bb646e062a.nq.gz
│   ├── 28ae21e39205ccb2c2230c222b1d20e85211208d.nq.gz
│   ├── 3ddccab88cebbcfeefaebda75864dfb7eed0ba12.nq.gz
│   ├── 4219e6369724a85f17ef50298ffaa7b25c85440e.nq.gz
│   ├── 43bac93c628f51221790b28e908f62e62dbddf3a.nq.gz
│   ├── 4431a360e32e2d14bd34411e97734c6784b977a3.nq.gz
│   ├── 4646c193dd7af1b9b994a734037993e7bb8d65a2.nq.gz
│   ├── 4969cb18359dd70963e76306aea16d0d30017b5b.nq.gz
│   ├── 4a93985763241755401a10678395303de4e720ba.nq.gz
│   ├── 4b6f4d1a6819a6e28c979b9e3a05f0c9b0664fe0.nq.gz
│   ├── 4ce27274bba30c9097cf361710f0c85adfa18869.nq.gz
│   ├── 4d4e7735f25873f353a04e0f25de771276d82193.nq.gz
│   ├── 54fc7e207781f6dcd469eb702a973bd302a37c7f.nq.gz
│   ├── 5b8e4185496f0007760555dafdf37ee76807e02e.nq.gz
│   ├── 5cf29715dd84cc99010ed3c47b14b0b19e69c74a.nq.gz
│   ├── 5e796308b4bda903a81f7d0fb6cdcf578b7a9d3f.nq.gz
│   ├── 691602f9e62d78c1a21446155c16052e931b3527.nq.gz
│   ├── 6a3e6f9674a654873ce6edf28205a17c805d37ee.nq.gz
│   ├── 6cdd761a006c6773ee933323e59454a0c27d8d68.nq.gz
│   ├── 6d9a96f843407d01f7cf05396c369ca289edc2d5.nq.gz
│   ├── 72def02d4c3912e17bf5a4b5443a7518ceb7239a.nq.gz
│   ├── 732e426a3623b94c943d6f915d77bae9031e2776.nq.gz
│   ├── 7437ef33fbc048f15406704325cb55a7d53cbd0c.nq.gz
│   ├── 758911153a64495bc87607680d8d57ab2999d989.nq.gz
│   ├── 801f4da0b9de8f852f0630f05cf2421f34973117.nq.gz
│   ├── 80435c5cdd3b50cfc9f3017b7ac15e51c63fd03c.nq.gz
│   ├── 80a79e625b3f1ce70b9c5134a7537822c6d22463.nq.gz
│   ├── 82b2b375072e9aa6a95b039db30838a87b439755.nq.gz
│   ├── 83a81faf93a8c4f69d76e21c63e1e9eccc1b57d5.nq.gz
│   ├── 84ef0e4978982e66e4f273c57537051312dba6da.nq.gz
│   ├── 8560c3c0348657497b2544ae06360f539c9e1b85.nq.gz
│   ├── 88017db09b3c83c745d748b12c43f6c8109180a7.nq.gz
│   ├── 8b3e12580738e80ab7a020f758ae22a848a8febb.nq.gz
│   ├── 8fc5a87482c3bb98ddc5f55f1e036994d0a6233b.nq.gz
│   ├── 935274df3b62ae5d036654639c14f2b29ba50f6f.nq.gz
│   ├── a003a53c6e861fe2afcf2679cf57178970a5f3e6.nq.gz
│   ├── a52b095080831d0797f9d68ad9957e83fdc38faf.nq.gz
│   ├── a6dec1cbf1a8305dcb075771eca45aa29cca21ef.nq.gz
│   ├── aeede7fa32711273e44319ab9ac7b2a43df58310.nq.gz
│   ├── b4bacaf3bdde0806d1c3013ee505da1256526539.nq.gz
│   ├── b6b477058e71bc8d4dbc8f450ee493eafc798043.nq.gz
│   ├── b9599636bbe214dc725a32ad3bf3a2b62dacdb15.nq.gz
│   ├── c30aa4bb0338d5580d487e2f71459d035e81ece7.nq.gz
│   ├── c36b3424865a877a331957c7c7b9ff29096677d3.nq.gz
│   ├── c8cfe3959183f8e9a50f83f54cd723f2dc9c252d.nq.gz
│   ├── c911f6d1f2c5166d299fcf8204d0a28c43ae5347.nq.gz
│   ├── d0430342dd4df070e1471e1b8420035fc59bd01f.nq.gz
│   ├── d93742163028f52805ffc7c446f9b4b3eaf9d0d7.nq.gz
│   ├── dec24fd1872d88f89b7de7af12ab6654be60eddd.nq.gz
│   ├── e2c734f6ac2a2a7e15d1c64511dcfae4463584ea.nq.gz
│   ├── e61119ae240bfc74f5ff9f1bf67c36dd559ea2fd.nq.gz
│   ├── ef064b72b38678a11642563ec7d438569a0163f9.nq.gz
│   ├── efe6f54bd3dd7c2131ede0fd298a74f6062caebe.nq.gz
│   ├── f14d81be00fc389f6302fcee1439275f7ec69f79.nq.gz
│   ├── fa2133d66cbc524e8a4fe5f0110041a25b928a2a.nq.gz
│   ├── faa78cee645c1a3655b42fa2ca99d02055a314e1.nq.gz
│   └── fff5cbe0831c3d8ff44c27a5d34cb089f1928e07.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2912bb30785c7702a2f9abfab783e9140aa7246b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 72 files
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

[modelcontextprotocol/quickstart-resources](https://github.com/modelcontextprotocol/quickstart-resources)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
