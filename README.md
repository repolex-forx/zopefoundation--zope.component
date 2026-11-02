# Repolex Knowledge Graph of zopefoundation/zope.component

RDF knowledge graph data for [zopefoundation/zope.component](https://github.com/zopefoundation/zope.component), parsed by [repolex](https://repolex.ai).

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
rlex download zopefoundation/zope.component
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bb12836f35b40f427fc313a0bc033816c30d890d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── bb12836f35b40f427fc313a0bc033816c30d890d
│           └── chunk-001.nq.gz
├── blob
│   ├── 05c45ae98f262f03bd58a2c78ed0f576942f68b8.nq.gz
│   ├── 0b80a0e80b54c6ee5d5edd673a7904f6e5039d38.nq.gz
│   ├── 0bf91dde600ba7f92c6879a82c6c84ec2028357e.nq.gz
│   ├── 0fd240629cbcf3c0975bd53fcd2de3ee7686dbde.nq.gz
│   ├── 1295045f38d721ba7f6ade9f7321e45d9c7e84db.nq.gz
│   ├── 14b101e2313553b645b52d9bf89442ee5af4f47c.nq.gz
│   ├── 15251acfbaf4028d7e96d2950d6031dfb74fef54.nq.gz
│   ├── 1828f4eb68c9857a3152c8e6239054a5e5300380.nq.gz
│   ├── 1a947f108addbcad52359bfb349bff529de4418a.nq.gz
│   ├── 1d3be06a28cc3b0723c8d09a05a8ff63bd433d90.nq.gz
│   ├── 1e26bacb8fc5924e52ab9773b0e4d1d39f1c18eb.nq.gz
│   ├── 1f37b096e61c8a26c224add4a7e36d80e5f7bb92.nq.gz
│   ├── 23a7e0dd1b139db92bbe0250170b0822a06b2d98.nq.gz
│   ├── 2596a596db536ea35996d5d7cabb3da57d8bb7d0.nq.gz
│   ├── 28a172c167eac1aa96759ccd1df35c70f34b91e0.nq.gz
│   ├── 33459b583c644ce048a44fd495809b6139abde4c.nq.gz
│   ├── 338d1a8d6aad4e313623b85541d93326575a990d.nq.gz
│   ├── 382e69bf7141a1cc17ae2d8521a2be3160dd0232.nq.gz
│   ├── 3915bc4767f27deb56ac0e21a199560c91f65900.nq.gz
│   ├── 3fe697aa2e48480f1f20ed49c459a361fcbcaa5e.nq.gz
│   ├── 4db983eb3e0c3ddd17d41304c4561db68452c7bc.nq.gz
│   ├── 504b11bc96ec0d0a24f961899b3e8f97d1003f19.nq.gz
│   ├── 56fecdb72a75c4118ba880431beb7a936ff2cef0.nq.gz
│   ├── 5719927d2a179e0e8fd778fa51e7e2522788af02.nq.gz
│   ├── 5c8651a5321b0dad3b1ffe9ba1468608b27255cd.nq.gz
│   ├── 609929df89fca2968a9662f5bfb1a9630296c076.nq.gz
│   ├── 62ee4f322eed30cabbaf3f79360306a9c415befa.nq.gz
│   ├── 64897991dc1118738d7bf55779b72344538ff050.nq.gz
│   ├── 654018fb00bd159190edbc155ca72aca2219e3cf.nq.gz
│   ├── 66fecd4ee92532f401f02fb5fa676ab15faf0f1e.nq.gz
│   ├── 6ab72a980e64f085b450013944db9958ecd2b6a2.nq.gz
│   ├── 6bcd7864a6587ea973730a547b9530e53c5a5277.nq.gz
│   ├── 70f2ba7b707499345070852959ec2a1b88e694d1.nq.gz
│   ├── 74e0ab8ada9157850fcadd9ae0d524f8af996ae9.nq.gz
│   ├── 7756d9128686df76506d196d74785733ae209ae3.nq.gz
│   ├── 78616264e09265cd6a39a085504cd70fddce56c4.nq.gz
│   ├── 79859e06010bf4967c5b4b044afea6ef39742938.nq.gz
│   ├── 79eb209eb31002a37a9f54d1e7775de321015315.nq.gz
│   ├── 7a0779fd44b44f05abd56f5bf1693f3ce16c3649.nq.gz
│   ├── 7a2d93189777fb09ee19849cba6e6ca17e010dd1.nq.gz
│   ├── 7b776999a68af06ff270dda1da72d81ffdb1a5c7.nq.gz
│   ├── 7c4d888e52e025c0cdb11eeea7fc5ff0ea717ee1.nq.gz
│   ├── 7e6ae6bca31dc92756640628ac29c6b630c5bb8b.nq.gz
│   ├── 801edeeab4d25ab8d128d2b9217959fbf305c468.nq.gz
│   ├── 892fe105e91f5cf4b315447db649a8927c3498e6.nq.gz
│   ├── 89dcd3a9a0ca3fb31f8c4bc9c5ee2711f49f3daa.nq.gz
│   ├── 8a1cde635fcfe005cc4438d504940505395236a7.nq.gz
│   ├── 8d5a39e2c3d50b5faf532a780dc9d0c0de2e21fe.nq.gz
│   ├── 8de5b193b47c501af297bda60219e7557a165180.nq.gz
│   ├── 8e4542922987304b1615147334de5d37b704e98c.nq.gz
│   ├── 8f88c53733783e3191ececb8923b05eafcfdd509.nq.gz
│   ├── 912ce755139caa681b5cd70d0876b834893af07e.nq.gz
│   ├── 94667d55d4d697adec279288aaf5c80147792678.nq.gz
│   ├── 9669189787e015021ecc0d990fed022a51aad523.nq.gz
│   ├── 9b7fee0649595e070b5638d43bbd401a051f7aaa.nq.gz
│   ├── 9bddfd6401c08f600f473af603303cb9119ae5ad.nq.gz
│   ├── 9f55c35caa1b3a4036a85d48c6c0ec2a498c0ead.nq.gz
│   ├── a92be276e3949bc381a2fdb1a2729516be75daf5.nq.gz
│   ├── abf7a867508538e54b6505cdef162812b13b76f9.nq.gz
│   ├── adf70e40761e1701f9b63680ad09874372115d9e.nq.gz
│   ├── b732fb88cbfeed3025b3265a5f4dad6e0084d72d.nq.gz
│   ├── bc48e4c267d891f9a14f6fce834daaf87c7415f0.nq.gz
│   ├── c161c851f886ca693c8b1d2a6bc34c5f1e246739.nq.gz
│   ├── c32039a568c1fc3cc332382cbd2f469d57d48a58.nq.gz
│   ├── c50985a65794bd74cb0d5d609308e61e6d1e6941.nq.gz
│   ├── ca517f4eb0cec1c691c0c2b54cd5eb85e906f11b.nq.gz
│   ├── cbc4e17e232fec5cd97a9d2caf8ec7b3489c2ceb.nq.gz
│   ├── d75f5a979d6a6c4c7fe1e174ee00930bedcd0737.nq.gz
│   ├── d9e113ec685b92b018297dd2f200341d1fba01f9.nq.gz
│   ├── da0804f654f58d44f408b6be5c6416c21dc80605.nq.gz
│   ├── e1f9ad7b3b48377bfbfaa1b380c384ddea24060f.nq.gz
│   ├── e23c3c47b24eeb63c07946a4de72b7f3bff2c66e.nq.gz
│   ├── e3579011e1a5792ed2adb52fe79f1ac001b9c3bf.nq.gz
│   ├── e40b0c3c531059cc15c0d94a5a12c1d8ce9b59aa.nq.gz
│   ├── e4b867329e05886a4818f86b117fca2102bc84bf.nq.gz
│   ├── e5029b57fd580deeddd3ef804a1bb65943fe80ca.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7a203a8cd5bea20fc05768d5d969d3272fe14e4.nq.gz
│   ├── ec7f59671f3037299f9ff52fea9a487f5c972211.nq.gz
│   ├── f4df78aefb930e469027bc883139347a9509a7a9.nq.gz
│   ├── f528f1725dc8246ab836f363fd6e7aaa7c82b59a.nq.gz
│   ├── f5e19b411ded932c8b5f8ec18a5840189139647c.nq.gz
│   ├── f81cabf053fb4487bb3496afbc276556076bc3f2.nq.gz
│   ├── fb0723f76cdc900c8ebf3de68b17a87f96a9c6e5.nq.gz
│   ├── fd0decd2543b779a51eabb9818c22efbc498c5db.nq.gz
│   └── ff456f7114e93405b599802333dd359116d78184.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── bb12836f35b40f427fc313a0bc033816c30d890d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 94 files
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

[zopefoundation/zope.component](https://github.com/zopefoundation/zope.component)

---
*Parsed on 2026-11-02 by [repolex](https://repolex.ai)*
