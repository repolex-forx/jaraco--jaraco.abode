# Repolex Knowledge Graph of jaraco/jaraco.abode

RDF knowledge graph data for [jaraco/jaraco.abode](https://github.com/jaraco/jaraco.abode), parsed by [repolex](https://repolex.ai).

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
rlex download jaraco/jaraco.abode
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9dab1fa53f390f73295c7128097f0eb27440da16
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9dab1fa53f390f73295c7128097f0eb27440da16
│           └── chunk-001.nq.gz
├── blob
│   ├── 05289714d140dceb30381af8b456ee4c9914e56f.nq.gz
│   ├── 054dea47fe1fde870e5dc3c76d4fa39366e41005.nq.gz
│   ├── 07f3474a28bc6b628b70a558aeb9d6d1b1ae3fdb.nq.gz
│   ├── 090af2ee83ce54b84f3c506e6e7b2f06a0358f50.nq.gz
│   ├── 0c014326e5d5b553b82f3dc3cbe5ccfbfa0f3889.nq.gz
│   ├── 0cd242a2a00a900002aaa3d3c96fcb6de9bd9058.nq.gz
│   ├── 0ed2dfe37a37df641a95ffc6819b3e9344045e08.nq.gz
│   ├── 113890f7be32a0af39b90ce28430d99700425f7e.nq.gz
│   ├── 127fa2e0924766ccd32c5e81e13b64cd81dee853.nq.gz
│   ├── 14ad65336fa8fe7e38bcb3864db5fe7e5ccb7e64.nq.gz
│   ├── 17df8307f47a829ad6acc2f936e68d6419b4e2c5.nq.gz
│   ├── 1869933ec2f499dad2ff415ce821d6bb7d040347.nq.gz
│   ├── 1adf2fb300720cfd31db555261015cf4a9244707.nq.gz
│   ├── 1f2aa7533b0423a8eb943f6f4ec02498e39581a0.nq.gz
│   ├── 1fee46cb627afaebb2b6b3e7327d4b996bf97fe9.nq.gz
│   ├── 20178ba4da891456d840b0605a35890f37d18687.nq.gz
│   ├── 2026dca20e94c9a6cc53c7504f9fd81276075343.nq.gz
│   ├── 206beae3f24bc8ed747b91bebd36510edf21f19c.nq.gz
│   ├── 240329c3604d8ead4c10aa8c88352caa8e4ce7b2.nq.gz
│   ├── 2a4342a69d23bada013bdcf8236c1c3268845a75.nq.gz
│   ├── 2e3f4dd791a6372b427d618eb0baa8c4dc58e5f0.nq.gz
│   ├── 304196f81e11a168c9894f966e4a617ebf4ed53c.nq.gz
│   ├── 30ad1cf7f92b758c6b8f342d4db97819f1eb644e.nq.gz
│   ├── 30e1f36b4ade54aa5c9c4b2b0b4c261a80bc0f42.nq.gz
│   ├── 32b81a528c34c9c46c0266e775623158c61a8ca5.nq.gz
│   ├── 388e973a3751a90bbf9d849a6ba4a9b879f78460.nq.gz
│   ├── 3b2f8048017a18a86bfb7cdd3a802bc2517b5332.nq.gz
│   ├── 3c58567cef0a04a0ab1e5ec8f50ad16259648cd9.nq.gz
│   ├── 3e4e455ea85dd422deaf2ff0ab7af79900de8340.nq.gz
│   ├── 3e7f35df0a6f4ffc4ad6ed0fed1efd9ef255ab10.nq.gz
│   ├── 434e05966e0f3e335bb17f6ff70d9868b18f9826.nq.gz
│   ├── 464e0d6eeda988953efd83ae5f437721cf96aa26.nq.gz
│   ├── 47a464f6d4ed869cc8e5f2e63bbd62a3011dfa24.nq.gz
│   ├── 49e0345e07823860aa4106f23fdf9a7f988675d9.nq.gz
│   ├── 4b9e1d852cb29b88b006352b7216c25210a43765.nq.gz
│   ├── 4df4a19745b9691b9d6cbef18e98c9ad0b70eaf7.nq.gz
│   ├── 51289ac0c3f835bda9e754d0f884b5372bb27342.nq.gz
│   ├── 54122bd6fb34d4bee46d84821bf8656af21137c7.nq.gz
│   ├── 54c9000ec94341dd65c2053251b85b124017b9b5.nq.gz
│   ├── 54cc8303b22089e12053e552d4e6cb852a865b8a.nq.gz
│   ├── 577e87a793a20e413f7321f4f17ec1eba2ea1962.nq.gz
│   ├── 581d1d9a63213528b486ba667ab98deb1541d3af.nq.gz
│   ├── 5bdc232005af9be104a00437ae9bc64417a4c1cc.nq.gz
│   ├── 5c05f9e27d57a4b7a3c3a9fdfecf8cddb8be499f.nq.gz
│   ├── 605f007c2ef5454ecc221225e470450df14f268c.nq.gz
│   ├── 64c7da6cbac643ae60f3216ba8f72a4fb75b5eb1.nq.gz
│   ├── 6b4ae410b5b0d9022b1fb616311d579f07464174.nq.gz
│   ├── 6f27d7077a1c1f7446e164bac74f60e9930b1f6e.nq.gz
│   ├── 700235be57c1b2872455c0be5333f59cf568e252.nq.gz
│   ├── 724370638fc188317bbc7dc868f1a571995fd796.nq.gz
│   ├── 777c6d51d50e8664bdec4fc8198faf07117d4e8a.nq.gz
│   ├── 77a5015398cfa463f1b66fa077e21f4f6300b542.nq.gz
│   ├── 787d345d0a84b3dedc2389e18a66f9d5dbd5f1bf.nq.gz
│   ├── 7d030a2f62aad084847004c30646c5851b95082f.nq.gz
│   ├── 7e1eaa4e15e86da09e3f69d847ffa9d3a7e87a02.nq.gz
│   ├── 7fa0a23ba1c41b48b6f9324b19cfdc47ecdf8380.nq.gz
│   ├── 812ea6d3a611ebd4f22bf273fe8eb87aa21b85dd.nq.gz
│   ├── 81a0a8ba58d2b9f9a73eb073643e04bed0df9d3d.nq.gz
│   ├── 8cad0fb4f1645dedc38925d299d2920dbff947fd.nq.gz
│   ├── 8dde1e68966dcc3b06c313885264e43f9a45d960.nq.gz
│   ├── 8fa5845ca976e1e3bfd42b55eb00c064abc8b4d5.nq.gz
│   ├── 8fca1fad1f860f5df3f783d53643482dd732e1a4.nq.gz
│   ├── 95c3e3d86a31bed1ff4710c3b560f924bde94ab4.nq.gz
│   ├── 9960a56c5147ee3cebf0274b624698c900fdd26f.nq.gz
│   ├── 99c5f8e33986e128e405d2a8ae598aef658ac0d3.nq.gz
│   ├── 9a0f3bce1395ae3819030b822e5d9076c85068ea.nq.gz
│   ├── 9a5e231a467736ecf22aefe28a6e27ade3365bd7.nq.gz
│   ├── 9d54026f5fc5156af73056bf573b443bac049ab0.nq.gz
│   ├── 9daea2d4ffeb9a5239ad896f01a23aa9469d771a.nq.gz
│   ├── 9ed3f8269886b7fe521f22759a14266baa81c700.nq.gz
│   ├── a98784e2b01649dd3ce825cd12609b5318f8dd6a.nq.gz
│   ├── aed174ca182ebc9e350711cc3f445b1d50eef792.nq.gz
│   ├── b237b986e559bed302635dc5a4e89b1f32e64c55.nq.gz
│   ├── b41b3e29c272c1665c0b82ffff3f07555840d0a4.nq.gz
│   ├── b608b322ba73794e6a53baf6df3ac581e6e77af9.nq.gz
│   ├── b63a0f827d4b1bd794cffa3cf37661b344dbe511.nq.gz
│   ├── ba8395ace93892d17b031ed54535f8a38d9e346e.nq.gz
│   ├── bba6e1aaf05dc6c21c5b7818c0477b4cfa41b42c.nq.gz
│   ├── bc6ced2660f36173070de9e567418beea28c1b58.nq.gz
│   ├── c54e388de25f346d987719312fd48cd85eecb557.nq.gz
│   ├── c721832cb0ffdee7a313a80b84602eeb3453c5b9.nq.gz
│   ├── d70ea14c73447531ea7fd7afad83e266d7f937f8.nq.gz
│   ├── d7cc9434f17aa899b86c9079d2b4170e8245d337.nq.gz
│   ├── d7e30f0716ce51c61366e998b9d196e1bdcf1c64.nq.gz
│   ├── de33e723d2ae14a3f55dc47c132c505d4d5d18c0.nq.gz
│   ├── e2b717a411007ea59c1f128545c86d909b6a9428.nq.gz
│   ├── e69801836eff01ae3e03a69ed8de2c4945ac15b7.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f166c1607440939433a8f56ad240964b612db18a.nq.gz
│   ├── f173f2d174191a699c8aedda5a65a8dba203acb8.nq.gz
│   ├── f3cfb762cafc44581dbfb1d27be8e28ffb000371.nq.gz
│   ├── f4c2212055b38b533e9c3d4552498c43ccec64df.nq.gz
│   ├── f9c5662f54cf2244209b1df9b4d0bd7d6babfdfa.nq.gz
│   └── fb251ee34e62faa63fe2849a2762e6e48fad5b7e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9dab1fa53f390f73295c7128097f0eb27440da16.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 102 files
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

[jaraco/jaraco.abode](https://github.com/jaraco/jaraco.abode)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
