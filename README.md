# Repolex Knowledge Graph of rust-cli/env_logger

RDF knowledge graph data for [rust-cli/env_logger](https://github.com/rust-cli/env_logger), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download rust-cli/env_logger
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 41320bf391e3d62cc0171f83403c6d684686ac98
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 41320bf391e3d62cc0171f83403c6d684686ac98.nq.gz
│   └── repolex
│       └── 41320bf391e3d62cc0171f83403c6d684686ac98
│           └── chunk-001.nq.gz
├── blob
│   ├── 097058d397487628d152424cf93d86fdde89e536.nq.gz
│   ├── 0b350882a7b9b47bf523a1911c5c9a05f81d8691.nq.gz
│   ├── 0f907a61862f21f4d99891035f60df03c6d1cc09.nq.gz
│   ├── 1cd601d0a3affae83854be02a0afdec3b7a9ec4d.nq.gz
│   ├── 1d4c5dc66f4e229b407587965d09da9816e06eac.nq.gz
│   ├── 1d4fd850696ddf8d3d0b9e3387d47cb7cf8c66e4.nq.gz
│   ├── 1ecfcc8445ad60895fea3da1a5bd4d1eda8cbfdf.nq.gz
│   ├── 1fff5c96b49da8d885a42169ce4bafb0ac4b87e5.nq.gz
│   ├── 2394b1892ddc0252ed640e2a6114bf64a4cc63fb.nq.gz
│   ├── 25ceca0553fa065ad6471d4a3d195a45c0c05e2e.nq.gz
│   ├── 27bf59a884cdc6948c686a9eb9b3f0fe99691c95.nq.gz
│   ├── 398dab7024838241343ae022b03dc0ff020f3ac8.nq.gz
│   ├── 4211ae3842810ba7207dfc2148a5354e28276bda.nq.gz
│   ├── 4a6a1abdd612113aea698f0f51e28cb675ea8ead.nq.gz
│   ├── 4c4e1fcf5c3185033bf5e1d5c56e3177679d2794.nq.gz
│   ├── 4c83870825b175289e12b044b613625e0ca60246.nq.gz
│   ├── 54c1af4fdeeaa2216f16b340dc57cd30a8c41123.nq.gz
│   ├── 57e6054408b268b1d6f04101d8cc26e86b705f08.nq.gz
│   ├── 5c197a9ca53742ce9256b6e965a51117a2729fde.nq.gz
│   ├── 60bcf7a8eec08fe4490ad266b44520f48bbbcf68.nq.gz
│   ├── 61e9255c6414da502a136cb2ec427a8c72ac7052.nq.gz
│   ├── 6876c0791df289ef68af07fdc5598038cf8bedce.nq.gz
│   ├── 724305b4b124b5c162bbce67c9816a0f5fa86dc4.nq.gz
│   ├── 7446e08ea367f652b2aec4ebeb3723d71ca18d8c.nq.gz
│   ├── 76b92e769beebbf0c3a446d7d6fa8272b7ba2450.nq.gz
│   ├── 7770bf1c4a3f02ccab0564c267d783acd381227d.nq.gz
│   ├── 7a0d26d23d28a2bb0cfc3d92f59eba601eb97044.nq.gz
│   ├── 7da006c98fed38a8dd9a719b21aeacfd7bf8c229.nq.gz
│   ├── 80b9aaa3ed259b5da5a809ffb1fb3381daf9ad8a.nq.gz
│   ├── 81a1ef41ff8089f57ad4c1c107acd2394776ab26.nq.gz
│   ├── 8f71f43fee3f78649d238238cbde51e6d7055c82.nq.gz
│   ├── 9138a8e3fc824971be7888ef3eaa8074095cd94d.nq.gz
│   ├── 9809ab3f879edf210d3db78d4b122c09798617b7.nq.gz
│   ├── 9af2a6e2f852e4581d97ac5c6c0398d6f42e4a51.nq.gz
│   ├── 9e5164fbbede1f2dfa97df4741138a47d16518a3.nq.gz
│   ├── 9eae1fa988ccdf4b809cc560282f77f970bd85f8.nq.gz
│   ├── a1220ffeee3e366c2b207eadbbd3cf11a8a5fab2.nq.gz
│   ├── a2d01088b6ce55e837a6d193943580f978fb2d2e.nq.gz
│   ├── a505dc1c59522c23574b8fde893088a32edc18dc.nq.gz
│   ├── a6bab88e8b46518fecc9938ac8735c5831aa867b.nq.gz
│   ├── b2cfbdc7b0b4653afd753a7b07a036dd62e94a67.nq.gz
│   ├── b575b9298f38c89074bece7653c4ce4b4391cce6.nq.gz
│   ├── b8ed48e2388a8f84d2b87fd9b6a0e8b9fa539f16.nq.gz
│   ├── b9e6258d6adbdcb3824d035c38d6ab6dec0aa5f1.nq.gz
│   ├── bfc6a5c6b390c95dea58e41db6c3f813fe909ae6.nq.gz
│   ├── c24fef2842c768551badf60ccd3103e84119be9d.nq.gz
│   ├── cbb7daeca90ddae04f0af80df8df77c2df6ec4d0.nq.gz
│   ├── cc1fefc3b51896c4f83c75763ca9a55776dcdb53.nq.gz
│   ├── cc937797a6211af408c5018a1c3099b4567548c6.nq.gz
│   ├── cf4c1bfb053c86eeb9a1dcf27051f14bdee9f5ec.nq.gz
│   ├── d66367ac4cae6d90806c8312b99771645dcad718.nq.gz
│   ├── d72d44bcd291134ab8062abc1da46e14d5800e1f.nq.gz
│   ├── e70fb7535a16d43b05d169d88bf2ef06f5ca213f.nq.gz
│   ├── eb5a316cbd195d26e3f768c7dd8e1b47299e17f8.nq.gz
│   ├── ef1a54ace2671a5aab8e6b7578b917f7e5a33df3.nq.gz
│   └── f2661eea9a76a7a7e07640b2aa483b77995a3bab.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 41320bf391e3d62cc0171f83403c6d684686ac98.nq.gz
├── filetree
│   └── 41320bf391e3d62cc0171f83403c6d684686ac98.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 66 files
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

## Source repository

[rust-cli/env_logger](https://github.com/rust-cli/env_logger)

---
*Parsed on 2026-04-23 by [repolex](https://repolex.ai)*
