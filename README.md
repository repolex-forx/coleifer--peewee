# Repolex Knowledge Graph of coleifer/peewee

RDF knowledge graph data for [coleifer/peewee](https://github.com/coleifer/peewee), parsed by [repolex](https://repolex.ai).

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
rlex download coleifer/peewee
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e245a01b1f57005e7ae315736da8e6a70e65afba
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e245a01b1f57005e7ae315736da8e6a70e65afba
│           └── chunk-001.nq.gz
├── blob
│   ├── 017d82c88cf81e4a169a7a28eb9e5bc21a5c6853.nq.gz
│   ├── 026450a9224a7b945a19653e8abc9a24a9822a40.nq.gz
│   ├── 058a2647b8108bf9b81226d5600e4b1c9d6ae471.nq.gz
│   ├── 06b2c2327a8c9d1d674e824d0047b55e84eb2da5.nq.gz
│   ├── 06e2b98c618786a0f6c5ecb2967a12b607c14d63.nq.gz
│   ├── 079300a5b4ed1b5d97d1cbe9bceae5de7e2bba0f.nq.gz
│   ├── 07d89b63d7ed714c020b9c621e6f4937891f48f9.nq.gz
│   ├── 0819ca024648e5b9f8b2dc34b6f25da001f96779.nq.gz
│   ├── 0897c449aa60d5f3a6914b4b0165add8638c67d4.nq.gz
│   ├── 08c483ed12b35d11f16e8cec135b66294719c891.nq.gz
│   ├── 0c0e9f27c625cdd93ea223c849cdb3cc6e0167fd.nq.gz
│   ├── 0c77683a486562b5bfab4c8abfb13553ea3cbe75.nq.gz
│   ├── 0ee2b8fc28c5d983262e4622fc75476295b0843c.nq.gz
│   ├── 0ee8cf977b5bc753d100bb10484c2a952dbcb36f.nq.gz
│   ├── 0ef3347912f80ec41b0070df6574b863f85260b7.nq.gz
│   ├── 125f1d4a08f25ae18bb72063f6ef69ea0000d2c3.nq.gz
│   ├── 135f84c9b5c8886a6c22c3e5d930659db55dbf53.nq.gz
│   ├── 153caf4c00b8b8462a5158ffbc0e371696862986.nq.gz
│   ├── 1654477bae2127d779634dabff963937db21b1c4.nq.gz
│   ├── 18a7029612f5c57737cdcacc583a4cfb7052040b.nq.gz
│   ├── 18c720f804c6f034cdb1ee02a616cc1e271a4007.nq.gz
│   ├── 18ca65f72f1508a2dcbc10b5bac3833f826074b0.nq.gz
│   ├── 19295fb2f0da620d66e58180e444196ae8369608.nq.gz
│   ├── 1b4bf9ac75819cc27f826bc94865f9ecc629743f.nq.gz
│   ├── 1c6df309edc8fd9c5aaa21d4a7fb867dd73ba8ec.nq.gz
│   ├── 1dc7e4f85e7afae5e72ac1ae8f8e1ff606736c43.nq.gz
│   ├── 1e44599b01d88076ba66558a29bbe17907d8c451.nq.gz
│   ├── 1efada2781e55100b5ceccb157bf96ced28b7016.nq.gz
│   ├── 24866995a087285e1bc0c91bbc6f84a6655b1fa7.nq.gz
│   ├── 25697c0c30304aff2d0fd6da0d21f4a1f85a0f91.nq.gz
│   ├── 266710b6a823185b807d89e514e668c03cbe3ebe.nq.gz
│   ├── 2a429cfcccb0c437468206b7204c1f015adc7251.nq.gz
│   ├── 329e8df4642d577ba6fdfe91d327c9c9098fcdef.nq.gz
│   ├── 338146b63cefbb240a368847711bfa128783044e.nq.gz
│   ├── 34d0c21b27248e2d4f66686a5e01639f251c3a2c.nq.gz
│   ├── 379383b5879008aeb1f8f9595f7ff12ea8435fd3.nq.gz
│   ├── 380da9168340a7a11552e80cea73480fdad75f39.nq.gz
│   ├── 39a24b72fbdd5565671de2d03851af2ec765bf3e.nq.gz
│   ├── 3f499454fe12b214ca3e7eca25cf096a13936efd.nq.gz
│   ├── 3f6941e99e6de4e4f4be22f33d329b5d29718188.nq.gz
│   ├── 402abf5f64faf78e7f212c27d2aa7b01eb866b21.nq.gz
│   ├── 4158b4d9570640082741f5692b71c35b394b2519.nq.gz
│   ├── 4343d2cab3036d3714448740e875cf71b6878d0a.nq.gz
│   ├── 4526982d05284bcae42009a07f497feaac1e1bb5.nq.gz
│   ├── 48fb27e3c42609b8f1ac599249978c9bfc43c877.nq.gz
│   ├── 4a4ca865d67e86f961bc6e2ef00bffa4e34bb9ed.nq.gz
│   ├── 4c3ab9eca274af32ec9d023f6a3a96641e9cb073.nq.gz
│   ├── 4d3812f2ba3d3964b943a04c400788b83475edac.nq.gz
│   ├── 50531cc3548f8df47daa1430188223b581165a5e.nq.gz
│   ├── 513327b02425fea4e089bf91ebe35c5725b8d9f8.nq.gz
│   ├── 5535ccb4e5ba65f686bc93e9ac0e90b63743d92d.nq.gz
│   ├── 5623a33b8e55edb374fbacdfc4667d12bf89d6f1.nq.gz
│   ├── 591a899a78a2ab6bdc4157ad218de96232e5e710.nq.gz
│   ├── 5abb032d400957f8b3c65cf1ee9251d49a5a413d.nq.gz
│   ├── 60e1b61e544439932ba83a2321bdb5fc080449fc.nq.gz
│   ├── 6327112e5745f35169ab27afb60d0ec149c2b612.nq.gz
│   ├── 66b458f12e36a42c8426b55204ce37aea1988f6d.nq.gz
│   ├── 67fa00bf83801d2fa568546b982c80d27f6ef74e.nq.gz
│   ├── 6991f3299f23751f3331be6e3429ecc7f052f578.nq.gz
│   ├── 6a1f5f1e2ecd94e38a5cb91f9a3c8b605465eb0c.nq.gz
│   ├── 6afe879fcc93a977527a7ac8ca4f62af4e66915f.nq.gz
│   ├── 6b642d229a89c8debd5145e6bf824d330ac72bd7.nq.gz
│   ├── 6c483ca4fe86a80de9cfd64fa3426a2789fcc48f.nq.gz
│   ├── 6cedb847e1bb965f8b8a52260ea3617b0fe85ef9.nq.gz
│   ├── 6de3f1fabb825a21be136ec6cb5e7db5faba5078.nq.gz
│   ├── 6f31f11740aa26e583e538254d6db617713b459b.nq.gz
│   ├── 712a75fda8d987053ab17c6e3567a28940d2d9d1.nq.gz
│   ├── 71569c9e16b3531ed1767ff5e2d58b3be5f7e8ee.nq.gz
│   ├── 7496db148047b812b12923597f28b2e7e148f0f6.nq.gz
│   ├── 75ae780829f01860ba3c7282ebf01203a8b39e42.nq.gz
│   ├── 773383f999303a1b054d2d40e9cdff12f3b1c18e.nq.gz
│   ├── 7767e7feb75e391a0d7b4761c40fa4c0c330d8b4.nq.gz
│   ├── 78cf769a2f18451a7c8d995b77ebd794285157b0.nq.gz
│   ├── 7d329b1db3f0b9383f111d23fc0c945b7e957017.nq.gz
│   ├── 7e02c9d28b70a4c35024a25491f5ea8b559ce1fc.nq.gz
│   ├── 7f1897b3fdfd0df4b8fd0e6bb3663a769b0aeb05.nq.gz
│   ├── 809868a5d1c39054ae578a18f5774e7b086175c2.nq.gz
│   ├── 81155efb054519b0ae5edc9c66bdc9f74a99f935.nq.gz
│   ├── 824a306b250c005263fde0bf6b16db02cdec0bb2.nq.gz
│   ├── 858aabffb549962e3eaca0937ceae5854edd7049.nq.gz
│   ├── 87d70130c4226e44c165ddd23a9c1c60ca41c465.nq.gz
│   ├── 89e41bfd409d8f2559e9b716540b3f2f75304fc1.nq.gz
│   ├── 8a6479faaa2e17f738ac43ec6787a0b0ea9eb050.nq.gz
│   ├── 8acb98866f565936fb36b890d038f6f20dde9f18.nq.gz
│   ├── 8c54182aa5d4d1ab3c9171976b615c1dcb1dc187.nq.gz
│   ├── 8ca97b0c6c3fbddab284ffc9094abe18fcf2f852.nq.gz
│   ├── 8cc62e0965c1b3514239007ebf198aab5adb03e0.nq.gz
│   ├── 9077ae2a998320458dbd5409da0207d710159aff.nq.gz
│   ├── 917f6487b768cf6e8537436a3d16ae4fcbe8dbb3.nq.gz
│   ├── 919f9e6db7d6331116837333c3271b2a2417bed4.nq.gz
│   ├── 92ec5380b8b2b1876cb3c7ae20a066b8c31b0067.nq.gz
│   ├── 9374fcf871869159c65182573f56c09a2e3bfdbe.nq.gz
│   ├── 946becf87f9bcb748b3866c18c53457e5118c11c.nq.gz
│   ├── 962e560b9d6cb58e0c2dfa0e0b3b11a75424fc0c.nq.gz
│   ├── 9d564d35deb142cbab40bbd18b4fc984fa8dcdbc.nq.gz
│   ├── 9dffb61d463b1b99404aa4acbcba7899a7395fb1.nq.gz
│   ├── 9e312c87aa279ba6539dd4971cea8afa639d743a.nq.gz
│   ├── 9e9de6dce8ab5c727b473e170552a4a189688816.nq.gz
│   ├── 9eb1af9222db70dfa87cabc46bbfe8e488e87c50.nq.gz
│   ├── 9f4b77d2f750e9609eb1dcb514294bce0299d8ce.nq.gz
│   ├── a0efde258d4b19268008643c44c18a86ac05f67a.nq.gz
│   ├── a1a6561e6b71d52545fc5c9979627f2141610204.nq.gz
│   ├── a3f1fb628ce01c4add771f90b633f2fd30a5d736.nq.gz
│   ├── a5f505eceb24aa6814c37bb0babbf4a79daef6d3.nq.gz
│   ├── a7c1d62673251ba61a4500f11a12c02e5deebbe1.nq.gz
│   ├── aa97976b64de0d0ba2e5464d804b5c1db3c94482.nq.gz
│   ├── ab6e93a9f4d5d83d4561d10cf93b6deb36031bc2.nq.gz
│   ├── ab9a1e366652bfecea31ac2f4c6f02997712fa3a.nq.gz
│   ├── b045ee41bfb3b87f532d343d7ba7048083e32684.nq.gz
│   ├── b1188cab3af12fe29ec4e33b955f76fee56c7998.nq.gz
│   ├── b1c5920aa2e0d1450974448a7ba43a72d629a252.nq.gz
│   ├── b2494eea78f973b211d06b1a8b6a69d5814e04c6.nq.gz
│   ├── b3cced9b3105e549356418017f6ae8ab2e719bcf.nq.gz
│   ├── b44e0630fd6722519cf3fee4f872c5c80447f8dc.nq.gz
│   ├── b45216f4de7fc51345b385b94811d2a680faafab.nq.gz
│   ├── b4d6f81519bcae93aae7e503a84e32347e432378.nq.gz
│   ├── b5ca39bc1ea7d9c27dfb80b986a59acb14594468.nq.gz
│   ├── b5e6afdb088a8d7b0b7c9b4cc4e7074fa77e698b.nq.gz
│   ├── b7e095efb1b77284b65915f2fa10333c88b714b6.nq.gz
│   ├── b8c8054f76f2efe46db1688b1bdd3b9a6c1ce09f.nq.gz
│   ├── b8f5ac059da1e1bde18fd0ae8114138d3ec99f81.nq.gz
│   ├── bdda7a242c9e1e0d6d04604acea5d84aa9368394.nq.gz
│   ├── be24aae4c7bf417dc7d5d6b1936a75f7a68c6a09.nq.gz
│   ├── be4fa497302665f6cead619818887b8b16e3cf05.nq.gz
│   ├── beff60191143bd36d9f85262e24b7c8081325fcd.nq.gz
│   ├── bf6f4455b4661adb97f811c18142ff4a512dbff5.nq.gz
│   ├── c2ab7b8851087421b05ebf3ea684b3fb2a379543.nq.gz
│   ├── c315d2fc333a67c170f234c6677ebd4d3435d79c.nq.gz
│   ├── c375c32fdf2a568df1182e15e71ee3ead46c7b43.nq.gz
│   ├── c432ac0fa85a5c98e3c4f8091fc5bb59dc3c565d.nq.gz
│   ├── c752ab3ead2e7be324e5cafb5e1d53135c16af13.nq.gz
│   ├── c75d1e3954186ddd3417819b21dd805da1e8f60f.nq.gz
│   ├── c999ee5f7cc27cc6a1e9c6eacb54d94bd05fb758.nq.gz
│   ├── ca5996b6ac7530c9119e6ec722a3077aa7e31f83.nq.gz
│   ├── ce0ad1467c3eb944e6bcda6eaae4e1165171687f.nq.gz
│   ├── ceb6f6180e30bdffeaa54c8120b8cec9536875c6.nq.gz
│   ├── d2fdb25b594720179dad0cbc6ec6ae44de8bdc53.nq.gz
│   ├── d4bf2515472def842f9a30e0475865145b65d1be.nq.gz
│   ├── d7a12b9ed6438f58954c42e08a488d43a0a528be.nq.gz
│   ├── d99dd85ed8d4fb344d393f66648050260d561ad8.nq.gz
│   ├── db085e13626d9cd404b1362370922a042913875b.nq.gz
│   ├── db926055cd0ba1776deb00a92fd802c409a8fc6a.nq.gz
│   ├── dbfe9dc8bb6b645bce61391a4ea85dd917705ec2.nq.gz
│   ├── ddb35e0fe764c48f2743f4277a47f7a019f8c45c.nq.gz
│   ├── e0591a6b97303492b5fbf514e6ed8709f7499df7.nq.gz
│   ├── e0b8eeb8c86b16c274a70ca20f601e100d2d5efc.nq.gz
│   ├── e0f1b9546cce0ed3c1ef2e41e3ab00aef714496f.nq.gz
│   ├── e3e2dc739dd851f2d7d291be032e30b909e3e95f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e72815ad486dcbb6b2ad76aea4577b73262afc7c.nq.gz
│   ├── eab4fbf722a3982ce3c00145d1aecf67e830f316.nq.gz
│   ├── f064e20848fefcdfd4738d296e9abdcd72c8319e.nq.gz
│   ├── f08e45dfc917ee7d0b125722945bcfb4b434eee3.nq.gz
│   ├── f0a4e5b22f5a098d3101efb7b4533921e922a1c6.nq.gz
│   ├── f38ac1a9cc33fb6dceabf1b6a7e2fadd9ce5dbd7.nq.gz
│   ├── f3fc51f7dfd594f7dc59ac43b95dff8a69c11445.nq.gz
│   ├── f46c6fd3fae0d673fa67963e62283d66bd2c96b7.nq.gz
│   ├── f46e72d1695be2c5aa65b36fbd1781f661188e46.nq.gz
│   ├── f48ae83ebf53d938c5c08d8faa8fecc7b4a6e2eb.nq.gz
│   ├── f53f53ff4355f47766058dae9a4af9dabee8daad.nq.gz
│   ├── f6115d59e873283974043415feb2c6a6ac1a9415.nq.gz
│   ├── f68f3dd8c8b983fd4cfc56de77af38598fbd5bc8.nq.gz
│   ├── f71d895291b18b8a2a183d72d8a86207932b9ab1.nq.gz
│   ├── f793ed2d718336d94e8e2d2218f57a31b664db96.nq.gz
│   ├── fa8e572ad802b34499a41b8a853513c35ec423d5.nq.gz
│   ├── faebd6902f81b0ff3529c89c7a355e266688d50b.nq.gz
│   ├── fc3a1b525f402ae0d3aa609955c753c72df7aa5a.nq.gz
│   └── fc3c33ec7a2333bccdaa6aa6fd035140cf2ab5d8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e245a01b1f57005e7ae315736da8e6a70e65afba.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 176 files
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

[coleifer/peewee](https://github.com/coleifer/peewee)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
