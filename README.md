# Repolex Knowledge Graph of encode/django-vanilla-views

RDF knowledge graph data for [encode/django-vanilla-views](https://github.com/encode/django-vanilla-views), parsed by [repolex](https://repolex.ai).

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
rlex download encode/django-vanilla-views
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8329c902a50aed0f49c1c27d7bf615f3a3d704e9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8329c902a50aed0f49c1c27d7bf615f3a3d704e9
│           └── chunk-001.nq.gz
├── blob
│   ├── 01f5a86138a0069e6cb7833d556b9f005953828b.nq.gz
│   ├── 03f74020ef62ae4501266b58cb73057ab30bb07d.nq.gz
│   ├── 0837a22fafef238e9d4f1fb39b9da5bb028eb1d3.nq.gz
│   ├── 0ce059464645a68e2b6dd93e63420b6312e9da9f.nq.gz
│   ├── 11cf1cc5d6421927a991ecb1b9ce847219a2a851.nq.gz
│   ├── 2605e3768e2bab92ef0550d452036472e9a6a210.nq.gz
│   ├── 38035d488563b12bfa4b2374c75883e82ce3220e.nq.gz
│   ├── 392886a0abb8bf96cd0f6ad316b87469f1b471e1.nq.gz
│   ├── 3a057058e48d73de1b49b6cd8f0e6a8d99a78e13.nq.gz
│   ├── 3bf6484a29d8da269f9bc874b25493a45fae3bae.nq.gz
│   ├── 4c5a81f03a8f13053225910231206caf926184cf.nq.gz
│   ├── 50bb0d7ce4adf1a6bbcf4138168d9330ae737505.nq.gz
│   ├── 566ca6046c2041b80974a8b14d01fbe7ba700090.nq.gz
│   ├── 5bec56a1cbf0dbdff4d9fac0cdeb0931ed536dcd.nq.gz
│   ├── 6831603dc1e665aba65fdd11273575aa99cc26b6.nq.gz
│   ├── 6a79eb7610fb98936924c05bdfd2c9441f285b8b.nq.gz
│   ├── 6e8566bcc88977adc8785c77c26d0e37f99480c8.nq.gz
│   ├── 7b7401f9dabb1225198f4b9ec9242ee831e457e6.nq.gz
│   ├── 7c41490413bc4a2369c9fc1e5c9e7b247c3ff019.nq.gz
│   ├── 807bb727b708a55de43f5547d7d16fa38a91786f.nq.gz
│   ├── 819d7039641eb50c8a1717812a9b6ee73566521d.nq.gz
│   ├── 827405437ed9179fc8218916ad9390a81d4e80ec.nq.gz
│   ├── 86d452de617bb2a93f58c996f5ebc73e1c1a48e5.nq.gz
│   ├── 878c3ed5c196539c4e2da35b7787ab08e98b9cca.nq.gz
│   ├── 8ed5e7d91c3ad5ead8e5cc49a629a7c47a75b744.nq.gz
│   ├── 917892ad576c782eee7ea81d56ef571717046d63.nq.gz
│   ├── 9259d26dca9111efc3ec6011c2e926e86afa95fc.nq.gz
│   ├── 9b88c2f8dd5f06c0e5e3855e3b20895f87b1eb0a.nq.gz
│   ├── 9fa6f766fc8af2c816697c45d4e0e26c0875a02f.nq.gz
│   ├── a5c41045e456b1e1ca723465092ae6170974d42a.nq.gz
│   ├── a6d2d47033e545f3673ccdfc88c3377eace7e03c.nq.gz
│   ├── a9969993201f9cee63cf9f49217646347297b643.nq.gz
│   ├── aaa3a42506ae2a90aa236a26b47c59cfd9756ca4.nq.gz
│   ├── b6475131193f72a5f8b131f5ce9ca0438632d960.nq.gz
│   ├── b8f59a0cf70438b8377d674947333147c60861c1.nq.gz
│   ├── b9956433dd71dc7aa4120ca1cfa6f58959d7dae4.nq.gz
│   ├── ba6b1cbc6d538e49a31b3c4393eac4a437526f60.nq.gz
│   ├── bfb0536038e80b57b41c4cd48b9746415cb818cb.nq.gz
│   ├── c2a4585bd0aa5709db3cddf3faf05f666aa70c19.nq.gz
│   ├── c9126d210e2bf63a0c737cbaa612dbed19c218d7.nq.gz
│   ├── c92a53124e031c41e8c22f208a5bf4e25200fffb.nq.gz
│   ├── cb58213047db0c8137da794eb19ac6ada7683920.nq.gz
│   ├── cdbfbe94f061bf274d83ce58f97107743cc6944d.nq.gz
│   ├── cf01f0644d4d306da70b2475edfaef79edd1ac17.nq.gz
│   ├── d468f7045eec585f39c98da3d820ae95719e77a7.nq.gz
│   ├── dfb252d43bc1d96b1ef0f904a58a0f708ebd1519.nq.gz
│   ├── e505d9e3b21c0b9501db1303a21a8224d35e8389.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9e88efbf0e66e2598093c48e05d66a93f1f355d.nq.gz
│   ├── eaf17fd8cca1b1004bb9158edcead2a91eaac5ee.nq.gz
│   ├── ec1dd318167bc1dca86b5bd77ff17cc6ebb759c8.nq.gz
│   ├── eef5ad7e6a07676b3919146d583d1c190bf1e163.nq.gz
│   └── f55aabe003277ff479c9e8e7c86c9bb029a604c1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8329c902a50aed0f49c1c27d7bf615f3a3d704e9.nq.gz
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

[encode/django-vanilla-views](https://github.com/encode/django-vanilla-views)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
