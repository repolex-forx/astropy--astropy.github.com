# Repolex Knowledge Graph of astropy/astropy.github.com

RDF knowledge graph data for [astropy/astropy.github.com](https://github.com/astropy/astropy.github.com), parsed by [repolex](https://repolex.ai).

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
rlex download astropy/astropy.github.com
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── faa056f7d9293e467dd6ac96e067bb7df959b6aa
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── faa056f7d9293e467dd6ac96e067bb7df959b6aa
│           └── chunk-001.nq.gz
├── blob
│   ├── 00cc0370d2c3b0b08796eaf70a8aabbd9cc78269.nq.gz
│   ├── 019e00a269679d8ce2a68cef6a0737a17051c681.nq.gz
│   ├── 0305b23efdb6fc03fe345e292563089e0ca40bdd.nq.gz
│   ├── 04a367ba9337ac07590a15455c5fddd6b2691dd4.nq.gz
│   ├── 05d3a9dc539c14ee525b6894083b1e51317c3a38.nq.gz
│   ├── 08c0ff0122367d7da97da050f241854175a35959.nq.gz
│   ├── 090e75fc7e0bff504d90588572f90f7467dd2932.nq.gz
│   ├── 091e42b67c08e002463cea20e2bce64e00b27952.nq.gz
│   ├── 0b36f884446f3146edef0e9ff5fcf899ee08c701.nq.gz
│   ├── 0ed547f237e324767aba02304a2fae9976d47ee6.nq.gz
│   ├── 11d8167fe1894b79038a47f69c447fef6fd3550e.nq.gz
│   ├── 16d5af74063464af10044808430b468abe9ff374.nq.gz
│   ├── 189f6c08d10566df740bc247f7264591d3579c21.nq.gz
│   ├── 1c0c7bda0ea37a2ba87af352a450f3581380b185.nq.gz
│   ├── 2350a56cc21dd9c57f6b46043a7ac72150c1943f.nq.gz
│   ├── 26f4877ea2bd6cd19248cf291e8c441bc03db5c3.nq.gz
│   ├── 2b2054290f666d53d0d7f2adbe23b45eb3d4be95.nq.gz
│   ├── 2b20eae9f6cccad9cb3df2391301f2557cfa93a0.nq.gz
│   ├── 2b4c4741bdca70b0efc1958d93ba48645fb01d42.nq.gz
│   ├── 2cbf5b30c48a1a92fb095e31f23d98cdec5fe40c.nq.gz
│   ├── 310653107e9738fa0e2ba198886139488231baa0.nq.gz
│   ├── 391d19f20b839b116b6dc65c466beb8ba565045b.nq.gz
│   ├── 3a17cbef6787f0aff5becfe40c7f53f668d4a957.nq.gz
│   ├── 3a1fc48bc37f0acaf1e0d53d886271bd6167e86f.nq.gz
│   ├── 3a943d104c11881c58a7da6adddf3ce28b646f13.nq.gz
│   ├── 3bd96747946b96391a2c609fadb49693677432d7.nq.gz
│   ├── 4726b394451b8e323815f9e8b0aa5600802995f7.nq.gz
│   ├── 4ec8d6e5504dcec0e30111fc2de01f6504fdb529.nq.gz
│   ├── 4f80191a3b501464a6b4d04b06f0fe0f9523d2f9.nq.gz
│   ├── 4f9284e93b6d1ebd3be4d0cd72a3db0501f9ac6b.nq.gz
│   ├── 599fd90b7480423244998bdd05676b1a6144beef.nq.gz
│   ├── 59a8acd7cb7d5653523da3723f1fd0b2abd1acd3.nq.gz
│   ├── 5aef9f32b60a986e3f02fc29ba90cc1da95fa577.nq.gz
│   ├── 5e38618742172ad018df94ee82066bd781517735.nq.gz
│   ├── 626c64992f2274fec0f6a90cf451c93725444cfa.nq.gz
│   ├── 6b0c235992bd42858029a97cf48d4950a1438b9a.nq.gz
│   ├── 7125b632b8724f48656e33f233bbccb8f21532e8.nq.gz
│   ├── 715b085dc67f7ab1fbae7648ee56ad8d3a23f383.nq.gz
│   ├── 7658c5b1ad9fbf3ac516165a49d9a1a96751cded.nq.gz
│   ├── 78a0a5e4814868c72c22d8d93b8ff68d94fa54bf.nq.gz
│   ├── 828346426b40512212ae59d7c55b80075755b662.nq.gz
│   ├── 8a35029ae1bc171e31eb712b663b2281c99dee70.nq.gz
│   ├── 8e1e5753c9902d200a657337dbfe21bf67e590fb.nq.gz
│   ├── 92a29438df8d20d2382c142edede406533e552a3.nq.gz
│   ├── 939b2611f8023e2415e8373bc01a65922daad059.nq.gz
│   ├── 94f8b2833fa946e7d147e57751815d6199cf9989.nq.gz
│   ├── 997575012f3eb67b64e26cc7b91a9f0dec545dd0.nq.gz
│   ├── 9a173ddb3ec5c914416634453f494ceccd4730d2.nq.gz
│   ├── a041b66f5fb555146b2b9f0bd4588032947c8cf2.nq.gz
│   ├── a0e2b42436e76be682b4f577600ab3b3735e2245.nq.gz
│   ├── a36aaf2f7ea6720625839ac6e3cfbd2674f97ea3.nq.gz
│   ├── a52c65ed0192b239b5c09c6e87838953d9904d98.nq.gz
│   ├── a70f69b4539e8f32e629a7982eeb8359c3390371.nq.gz
│   ├── b374af5037758df02eec4b9daae72c14f3099b0b.nq.gz
│   ├── b559507ed23e157b5cf21ccb5b0eb7451e014cde.nq.gz
│   ├── bce10c7a413565a83c45ceb66f380709b8650690.nq.gz
│   ├── bcff0ed69dfd4de115cf4ba8e2c17c4dfb03bb7f.nq.gz
│   ├── d148061ec7d9645017f32528e51707f84c7115fc.nq.gz
│   ├── d32cef2af45f5d20879dc6e883d05bf0a720f06d.nq.gz
│   ├── dbb21c777628766a8ab3f09660f8cd08ef8b1a46.nq.gz
│   ├── dcabb08f8ffd21e0513357bf4acbe738e54e4ab8.nq.gz
│   ├── e1c2799accd720c041cc803d9befea0766393a16.nq.gz
│   ├── e3a42492742b5dee2b3fd9c32456538331100d69.nq.gz
│   ├── e3f4e70f78bda3fecdba03ebbf7773f5f50144d9.nq.gz
│   ├── e4af0e52b3ed279ac2dedfd67cac74a707d8bf8b.nq.gz
│   ├── e5893cd09678b122d4bc4b93da3d43da68814d37.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f1f116483b941ffba4c41e0ef7c3524e207917bb.nq.gz
│   ├── f1f903b0751ee8cbc186a78dbb0019b875aebc09.nq.gz
│   └── f843b5115a609038297a7c1d8ef81cb39953a134.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── faa056f7d9293e467dd6ac96e067bb7df959b6aa.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 78 files
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

[astropy/astropy.github.com](https://github.com/astropy/astropy.github.com)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
