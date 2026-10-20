# Repolex Knowledge Graph of hynek/stamina

RDF knowledge graph data for [hynek/stamina](https://github.com/hynek/stamina), parsed by [repolex](https://repolex.ai).

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
rlex download hynek/stamina
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5c13c8e0b4bc5faa54914115a8c796934ba6da9d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5c13c8e0b4bc5faa54914115a8c796934ba6da9d
│           └── chunk-001.nq.gz
├── blob
│   ├── 057262b1bf99fb4b228fa07524df1aebc58c0046.nq.gz
│   ├── 0f670a6a6cb2c374b8f439a804bf5cc8392bd3b7.nq.gz
│   ├── 1075a14f09e8928a12745e8c721389789fd618f5.nq.gz
│   ├── 12e9a167b2b59d5725c84db68382bf4b981c668d.nq.gz
│   ├── 257c7bda36780f3955f7a9a879fea9511cf45f88.nq.gz
│   ├── 281b43a5848141247106969ae003153eea32d7c0.nq.gz
│   ├── 2d9f703203d638e64888e4a684d61313fb11bae5.nq.gz
│   ├── 3150ae58b9d717a8fdb95aa9f4783806637be41a.nq.gz
│   ├── 365f1eb4d0f87b67e81cf9d897a9219a31943fb7.nq.gz
│   ├── 3750aeea77b9d374345d81c1184d54e9465f10e0.nq.gz
│   ├── 39332f3ddaa65f96ce5e1329745dc6b870f585b5.nq.gz
│   ├── 3b8dc5b22e18fa7290f7470f7eea58b11efbc2bd.nq.gz
│   ├── 44ff2593831714b54302a2ab81bcee027f3c7a0b.nq.gz
│   ├── 54cce20a91b27063cbc04beb07e293f774829ac8.nq.gz
│   ├── 54f2f7a85b26c0715e9880d7e2fbb94405e11135.nq.gz
│   ├── 5d06ddcfefac3b343c5dca8c8e657e59fcc71d28.nq.gz
│   ├── 69faf7b010f169142debf76eebdb5265b4fcfc13.nq.gz
│   ├── 6de85b19ec127c3a63b35e5dab30d2b5a941cb0f.nq.gz
│   ├── 73cc4f6a8e1c278dbc1a240810b6f531df81cf39.nq.gz
│   ├── 7754c56ab4e0bf8509ea375ad2909c6924a045e4.nq.gz
│   ├── 7c5100942aae489ca04d07d2c69a4d8f6f8470fe.nq.gz
│   ├── 7ecca4dcc21f256ba37a4955dd34e522b3d90b8f.nq.gz
│   ├── 7f0c1d30a688f376587f20b8bae8cfc6f5dc1746.nq.gz
│   ├── 80539083a342f94f92563c76fbcd0a1b77e4ad30.nq.gz
│   ├── 84b053195912b487673b642783ec84de7db046fe.nq.gz
│   ├── 8c09813f56035f3578845d13d5dac1fcdd6fe756.nq.gz
│   ├── 8c63cf0bb29ddd780e95c3f0d2e759b852ecde10.nq.gz
│   ├── 8cf38517a0875a50c97abdb6916e90302926a13c.nq.gz
│   ├── 9018a2247be8bb00570a54186a87f54b002aa946.nq.gz
│   ├── 914586542af7d4c1d2c9a64435020d73e1183339.nq.gz
│   ├── 93a848f9688291c7b2172cf99f133675225ad282.nq.gz
│   ├── 961f5289ef1cfdc7336186724bc45fb5d2179eb4.nq.gz
│   ├── 970cf915d64fbbfbbd560c7c0eb8e77e056d72e7.nq.gz
│   ├── 9dd356894341760ac2bf199b3961779744bc0565.nq.gz
│   ├── a19f24ef9655d4ac9845cec090565422c3835a9a.nq.gz
│   ├── a1ccc32587fc45d81aeeed04956aa8e53287a924.nq.gz
│   ├── a4f4cfc1a58de98dd5678df29356bdbb6d254a14.nq.gz
│   ├── a7d9743ea26ddc83bdc70c9f386c7af4f01c2ec8.nq.gz
│   ├── a94cb2f8c249bf0b4dfc46a28f3008ab0b9e1b1c.nq.gz
│   ├── b3f2c762d40cda20ef2115538861af4b327fb939.nq.gz
│   ├── bafd4b0a880ba54a08f53f50718a84da6c3aa1eb.nq.gz
│   ├── bb36be28b18398092bcd9f8c0d21381bfd3d0735.nq.gz
│   ├── cd46bd07565aa2cf3aab3580363284ba2fac0458.nq.gz
│   ├── cf676c579e49554975ff79292c886c7497140095.nq.gz
│   ├── d1988675bdba84c9941e4a2c798022a91242c1b1.nq.gz
│   ├── d344bf4715aa1ae3d925e7cbcbc27d339a11e4a9.nq.gz
│   ├── d4563f12ae9ed2e021fe7f5cadb335ec6732196c.nq.gz
│   ├── d9d3feca49b9a0edc34dc4cc61aa1dd85b232329.nq.gz
│   ├── da6b2ce6fd62bf6c588c480602f906bf4a1fbddd.nq.gz
│   ├── e01bb064457ed405b0e08f04205d9a4fa69fd3aa.nq.gz
│   ├── e2ab3d1059aeafb2341ab828db022ab3054de13c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb0e5d33c7a1c8b66290134642a133001e087d40.nq.gz
│   ├── efa02895e76dfd493a5ab5651036602d67a5e96b.nq.gz
│   ├── f514cc396abc9b0494449ca1cad12126e8ae8e99.nq.gz
│   ├── f94a09a8355082e0d43a6c8ba3ff82c899663c89.nq.gz
│   └── fe832349894dadf416f1f8d6435b67ab0174a690.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5c13c8e0b4bc5faa54914115a8c796934ba6da9d.nq.gz
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

[hynek/stamina](https://github.com/hynek/stamina)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
