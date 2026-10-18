# Repolex Knowledge Graph of facebookresearch/demucs

RDF knowledge graph data for [facebookresearch/demucs](https://github.com/facebookresearch/demucs), parsed by [repolex](https://repolex.ai).

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
rlex download facebookresearch/demucs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e976d93ecc3865e5757426930257e200846a520a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e976d93ecc3865e5757426930257e200846a520a
│           └── chunk-001.nq.gz
├── blob
│   ├── 03bfe3dba3c5617a31a522b84fb8fb72ce51e089.nq.gz
│   ├── 03d6dd3b0414b7e6759ff7eec8f66d70f7ce8fa6.nq.gz
│   ├── 0474d5875f0cb18f41e2236b0b8b2ea9a721713c.nq.gz
│   ├── 056183a58219d44d630c125893908af037b4aaa1.nq.gz
│   ├── 0952fcc3f57e34b3747962e9ebd6fc57aeea63fa.nq.gz
│   ├── 0aee2f71e0eb3e5c3f27075610127e3dbee1c330.nq.gz
│   ├── 0cdb553e7779dcce0ede8c1110e7b15fa3f111da.nq.gz
│   ├── 0d5f2089fa3e1a0335d93de070f6802598cd4a4d.nq.gz
│   ├── 0d61d33d14140d19aa4c66f75e068e7c5687a4de.nq.gz
│   ├── 0ea089139bfbef4a1126ab25e93c3dc380a90b46.nq.gz
│   ├── 101bee026f41306bfee2154bab1a00fc3004e352.nq.gz
│   ├── 1540f3d44fc8bbca1ce377cc80af3cd9212278be.nq.gz
│   ├── 157958559afcc1c613b59d34d398f5cb5002f426.nq.gz
│   ├── 179cf0ddd24d976a2f0f2d97dff010d9ca9d90af.nq.gz
│   ├── 1940bf01d0e23a0834baa76a9aff5087ad44faed.nq.gz
│   ├── 1cbaa82c40673263cb8a2e966f1de0d96f737576.nq.gz
│   ├── 1e7d05adf0218b9779973deda6793fff98a7772f.nq.gz
│   ├── 20079a6b5faf2d4f101031b83028cb2378d7bc0a.nq.gz
│   ├── 217654a9b36a19a9d5c20f4c2509315fc02df773.nq.gz
│   ├── 21d33fce2e096892571c8b6ed5cb39a7e6e6a1b9.nq.gz
│   ├── 2419bf3564b3aeafa48f37c5af7ba971c1a15c73.nq.gz
│   ├── 29250459b30e3127912293ea17f168e7caccba9a.nq.gz
│   ├── 294290d31d786a0fb54ff6a32d0576a5dcf3e716.nq.gz
│   ├── 2a20f9cb0012cf9c92112091ccb883275980c1d4.nq.gz
│   ├── 31b29b3c348b29cfa7120c31542bc9a16ac24405.nq.gz
│   ├── 31d9a695c1c9c05a4e451f059151be252339f118.nq.gz
│   ├── 346eb33cd0affb0647da55cb54eea53c2399f210.nq.gz
│   ├── 361bb4196569bffaf622e39dd067d802dd43b38b.nq.gz
│   ├── 367769e6862e11a63d7361256f09a3b42c0e216c.nq.gz
│   ├── 3bdb419115e9f45c57590f4904fa5d8258fb095e.nq.gz
│   ├── 47163d7946e4897155d067a5d06c86810dc9a0df.nq.gz
│   ├── 4e81a5064b86698bf322a4fe11c23451924a5fc5.nq.gz
│   ├── 51933ac9ad898690980dd85c53ff4160567dbc8c.nq.gz
│   ├── 56a465b861d7d018d0eca2779bbd392f07e411a9.nq.gz
│   ├── 5d2eaaa1eb2620a5d2147eb86361e9964fb94528.nq.gz
│   ├── 5e20ff5199e5003cf3e2228d41998e53200691de.nq.gz
│   ├── 5f7fd1e4dfb41d6524b53c76573376ad171acd33.nq.gz
│   ├── 62d447f17d52880594461108b16c9fdfa972489f.nq.gz
│   ├── 62dd235e8466a0ca28b36b3be12bc0d918ec2aae.nq.gz
│   ├── 64f235fbc92c9787ddec3484817f773b24b38da1.nq.gz
│   ├── 651a0fa536038a3e6d650f7b2bcc0b50ff7a4be9.nq.gz
│   ├── 65c5df9a022085717a73e0df8f134b71f3cebe83.nq.gz
│   ├── 668604d876880d39913ef73bcf9df4b4308a9d70.nq.gz
│   ├── 691abc2c80fc959a4381c3b716c6f21adfc61fb4.nq.gz
│   ├── 6acb9b5d4c000cce3656d0b97152c58b8b2811d9.nq.gz
│   ├── 6dab7f1225f4c96092c85e91af2cf9c4a65c44a8.nq.gz
│   ├── 711d47157a975e04a0ffb044991d2dc3cfd54b66.nq.gz
│   ├── 73e488b5b1a3b3fa4f0d487ebb3e332c0b39f571.nq.gz
│   ├── 762a7c3f9e893914d6d9b94b55f2ee89ba661f71.nq.gz
│   ├── 78eb8e0c9a51828de1dd52c82743d2983353a8e6.nq.gz
│   ├── 7bb4ee8901508d087a7ccbc48acb86f791666c36.nq.gz
│   ├── 7c80b148e1f2fc1e5bd05ef41731ffffcf756a66.nq.gz
│   ├── 7c9831602f8bfa0e0eb307abe702a16d1ea37d34.nq.gz
│   ├── 80ae49cb1d3e1894f07eafbb49f95559a9f3de33.nq.gz
│   ├── 827d2c66515e01d74f374e53438e73c1cd927f96.nq.gz
│   ├── 847bf6659acce8c31aa9535923e2fd317a05a9e6.nq.gz
│   ├── 85a007e40a73768b7fb18b36194bc7423b828c3b.nq.gz
│   ├── 87702bc87e4a32acee816e9ffa9a73e8d18404ac.nq.gz
│   ├── 96e5f54fbaa50e606aaab04fcff035de121513ca.nq.gz
│   ├── 9a2d9df5e7a74aaf11cf35268901259193211ab4.nq.gz
│   ├── 9aa7b64bb238364d0fc7781e4d5ed55ab60bcd28.nq.gz
│   ├── 9b38aeca0bbff9507bb5fd124a3b1ba0d01713b0.nq.gz
│   ├── 9ebcfd5af9ee7a0d401c0beac967f4caba2e785b.nq.gz
│   ├── a3f5993e0281be546c9691963a8343c2b2c85452.nq.gz
│   ├── a45a376fb0fcd4a3de06b6c096e62028929a2dcb.nq.gz
│   ├── a839345ee04f37c872f2382e1692453a1c51f791.nq.gz
│   ├── b259b765eb38ebde3e02ad990b4c60383d3b5338.nq.gz
│   ├── b31e3dd6587a855d411f0d97c1842bee00da6814.nq.gz
│   ├── b88a7519f23ac2f0f63fba024d31058c1b752568.nq.gz
│   ├── b99a37b09d2a7ec6f54fe087ed4147ec8c8d3ae6.nq.gz
│   ├── ba5c69c272770f5e5db3dd5fcda75b94ba523250.nq.gz
│   ├── c3ea21ed5bc35b546a9a889608234c491f335f23.nq.gz
│   ├── c4e17f16518462bf0ebcb830425e51290c17d18f.nq.gz
│   ├── c5623468ef3aced5901c23a8becad3e9e7bcb587.nq.gz
│   ├── d043f64442f24d1825dfabb3eed57ff0f843f64a.nq.gz
│   ├── d2597cb5b4196d4e723aca4fcc1be36b7ba3dff9.nq.gz
│   ├── d5102edee23dbe00c14080f9b637a6a5ad7022a5.nq.gz
│   ├── d54d56a0d403187f4add6e76e85b5346b28dcf67.nq.gz
│   ├── d5d16ea8bc419198692fc993b560c1bd3f8eb8c9.nq.gz
│   ├── d75aa2b6da04970f55397635fee22287316d4e0d.nq.gz
│   ├── da0a541084f9780be9896a4d0a27d57dd1574e79.nq.gz
│   ├── dbd858a7e8f0392ef66d1ef4166d59dc78d606b1.nq.gz
│   ├── dc1576cb49693df491d58c8813d5ebac6c8ff749.nq.gz
│   ├── dfc022f827ba1a9a7f3ebe9bee92189825b26fbc.nq.gz
│   ├── e02c0ada9a1831da8c4130bc645b663772b2de80.nq.gz
│   ├── e4de86856989046eaddf6d5f44d7aaf3e0b89377.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ebef7364ef030efce46743c711743db0a20844ba.nq.gz
│   ├── ec3a858da27de137c1c785a28dba620b1df99a5c.nq.gz
│   ├── f049d4c53173cc44e0d0755b874d108891a5bfc5.nq.gz
│   ├── f0adc467eceafdefca00a609c6c014fbd938d63a.nq.gz
│   ├── f14f4af3376097c8b0f76f48d2c91c31165ae0db.nq.gz
│   ├── f62da1dea20c1c4e1fc10a75c1d950997df9c92b.nq.gz
│   ├── f6a4305cb420aa83e2a54c8af7a7d73e96afe373.nq.gz
│   ├── fa046070be3790c000a599e1a8a02e54bf427085.nq.gz
│   ├── fa2ff45313ed2d7e0aee4f1426f3d8dc1279dfbb.nq.gz
│   ├── fb80cf5aa1cde6d68b965466cb5c3590813a0ff0.nq.gz
│   ├── fe47bcf274cbb2b28559c7aca559ea64c862d673.nq.gz
│   └── fe7e77b992b7918eba9491119d313abf5bc3eff1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e976d93ecc3865e5757426930257e200846a520a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 107 files
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

[facebookresearch/demucs](https://github.com/facebookresearch/demucs)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
