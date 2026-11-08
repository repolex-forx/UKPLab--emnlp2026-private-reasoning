# Repolex Knowledge Graph of UKPLab/emnlp2026-private-reasoning

RDF knowledge graph data for [UKPLab/emnlp2026-private-reasoning](https://github.com/UKPLab/emnlp2026-private-reasoning), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/emnlp2026-private-reasoning
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 09c42f9f0e8946f6cf538218b1cd287d469bcf14
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 09c42f9f0e8946f6cf538218b1cd287d469bcf14
│           └── chunk-001.nq.gz
├── blob
│   ├── 04980c426daeeded57bf87f676a31356b4a4c398.nq.gz
│   ├── 088985ef34919cdd46136c090a66377d6f45adca.nq.gz
│   ├── 09a8e82c58c867ed7748a4cd10a3e3cd95189c8a.nq.gz
│   ├── 0c61e3cdbf2fc7db91e079946f2c1fe5bec6742c.nq.gz
│   ├── 117e8e90e3217b71fd047b332a7f43ce895e02de.nq.gz
│   ├── 11cabde4687a7378ee4b85ed93cca7c6d3cb63d4.nq.gz
│   ├── 14411fd93d699377c6e17280cabaf9a39d67dbdc.nq.gz
│   ├── 1d7a981140e01013d488ee4ef5cbbf210ec49b7f.nq.gz
│   ├── 229edba242bb190698662cdce6bdacde9f0769fe.nq.gz
│   ├── 23ae7b36c473acb4152b4cb2be06b5f09f70dfdc.nq.gz
│   ├── 286b856c813d57f73fb65ed106c893a3b976130e.nq.gz
│   ├── 308890f1fce6c89621bc618a28453d6b53c9fda9.nq.gz
│   ├── 33cfd1b819f7bc4e8f237d0ec4c88e7c9b342e7a.nq.gz
│   ├── 3e0603159f2ea33b6ddd6c822a901f7a986a829f.nq.gz
│   ├── 4431fcc0f58f79be923a227e953f0bb62990c454.nq.gz
│   ├── 4582be9ba62fe57b9c47f54302a259a53f6d65b3.nq.gz
│   ├── 45d1a860bb59150e34bd9ac6a655143779761b6f.nq.gz
│   ├── 4c609044c6726a723e98f1f67f7abda04d51959a.nq.gz
│   ├── 52ccf65cad468529aa3c4d765c07eb2d0e4dba42.nq.gz
│   ├── 548ec0b03a75504de91ae1ed145455aaf08efb57.nq.gz
│   ├── 63587f7f9314ad4ce2e97715bc16afe0e96bec25.nq.gz
│   ├── 663377f20a3565e1bb01c2b4a83805020aedfd6c.nq.gz
│   ├── 7550ff5c800851f6de2d845dc6433fa1f7abc35a.nq.gz
│   ├── 76281355faaaefffdcba364ee648d4dbb4b2cb76.nq.gz
│   ├── 76967b8eb09765accbd3ee8110f51707856c7577.nq.gz
│   ├── 810be465d0c7c8343f2b8de8a2ac6c03d6a3d221.nq.gz
│   ├── 848c68ba570fa04bf438bf453d96c323f934156f.nq.gz
│   ├── 85530a645a3b5d395d5fd6c8c7f16a7950a5144d.nq.gz
│   ├── 87feaaaa69d4e5b46aa7b22ddf85b85334888dd7.nq.gz
│   ├── 8871abfdc9c3745a372d1b55952f4d24481e3ea0.nq.gz
│   ├── 8b14d41f730e3642c5986d15e956bb8af5134367.nq.gz
│   ├── 8f3387b3bc8dbe47725fabf8887e75fc56243f16.nq.gz
│   ├── 967e71efda9f1b42d0614735b34c1f03b3a7244a.nq.gz
│   ├── 96a83287c0ccb915ed29918c9c84a39d3bdaf892.nq.gz
│   ├── 9b3703a912d40f58fb0fb57d20742e53d9fe7671.nq.gz
│   ├── 9d90ce7e89eaea81cd293db94dd534f3caf15e79.nq.gz
│   ├── a59417c59c2407917b9da7df812b039e8d5f4647.nq.gz
│   ├── a64fd87cd0cea52f3a59b4f242957c06c1c26cdc.nq.gz
│   ├── a70d291241eea483a3e2ca58d7c779b17cc164b8.nq.gz
│   ├── a7c5919ed7126032527f3e71fc4a1c8e624bcaa5.nq.gz
│   ├── aea29664a4bd0ac51505ce6a1c532de31d7cfc69.nq.gz
│   ├── b22445df9ad776f9a1a96898ce786c2924582f13.nq.gz
│   ├── b3899f4c6629819a805d6a59fb1505fad2d482ae.nq.gz
│   ├── b5e7be85d593dbb51224a4a0cc095e3e6f2a3ee4.nq.gz
│   ├── ba767517ccd9cabd586501e4b1e5fa65ca212e63.nq.gz
│   ├── bc25d18eea5e1097697eb2d0ee9a6d58d1c1e81b.nq.gz
│   ├── c08a79032592be8f5e7318991b0242323389469d.nq.gz
│   ├── c4559011e814c2a731c474fb6a88afcc6ea7ea7e.nq.gz
│   ├── c6718de5c5ae59d2c22141a147f5afba41af9cbb.nq.gz
│   ├── c6f17cc6a887ec28ad06b828b545332d5a3393d1.nq.gz
│   ├── cbeff4611e923cdb6ca9c0e787ab4e166437553e.nq.gz
│   ├── cddd2811cf81aa50cff186020871a27cb017ba5d.nq.gz
│   ├── d1a847a3af2e7d8618550ef846f66af5c9a6759a.nq.gz
│   ├── d62fc66df4b9acdd5381753fde4173a5775b1ddf.nq.gz
│   ├── dfbd476a6f0f5a8be07e42d2e0614ecaebaacda0.nq.gz
│   ├── e0b4f313b8ebafc04cf4904fe265dbcb70ea108a.nq.gz
│   ├── e28e523e3e89d91a241b0189a91271971b55f1d2.nq.gz
│   ├── e9a1bcb0292bca7b6fa322bd3edc5f4fb0729181.nq.gz
│   ├── ecd05e1ce7dc46025914252a34db785fb2ebc8aa.nq.gz
│   ├── ece8275e6000239255cefc7a07ab5cf8e8727f45.nq.gz
│   ├── ed3a9d377ba3c30e6eb8b2a35e08e8dc814a0725.nq.gz
│   ├── f1c5f6e3a113fe70b25ccdbcaa71df91c14c54c0.nq.gz
│   ├── f637fbc990f3cce215b9ca403a928e0a7f367e7d.nq.gz
│   ├── f6428dec8aaf2d6cf689ecd610c2e07dd6955814.nq.gz
│   └── f6d1a5f8fa297c2b655e2d72c7c115ef4bdc32dd.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 09c42f9f0e8946f6cf538218b1cd287d469bcf14.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 71 files
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

[UKPLab/emnlp2026-private-reasoning](https://github.com/UKPLab/emnlp2026-private-reasoning)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
