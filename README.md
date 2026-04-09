# Repolex Knowledge Graph of django/asgiref

RDF knowledge graph data for [django/asgiref](https://github.com/django/asgiref), parsed by [repolex](https://repolex.ai).

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
lexq download django/asgiref
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d97a7339524c89798c510de6c142b663fe40400c
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── d97a7339524c89798c510de6c142b663fe40400c.nq.gz
│   └── repolex
│       └── d97a7339524c89798c510de6c142b663fe40400c
│           └── chunk-001.nq.gz
├── blob
│   ├── 01e6caabd26f8288acb15b7904a9e868defb9dbe.nq.gz
│   ├── 131ea4305daa2dcccddbf58e5702de49aa5508e5.nq.gz
│   ├── 1bf398ea22a070a3c4fd326955bd9564887eff0e.nq.gz
│   ├── 20908f884d345a6783cd0055086ea709372127e0.nq.gz
│   ├── 27accce08defdda1ad8339e6f1790ce0b1df361d.nq.gz
│   ├── 28c9d40e97ae67d230d7ecde7de020a14e5f1c47.nq.gz
│   ├── 2a427f9762986a9ad5f38cbd4d80bba736337fa2.nq.gz
│   ├── 3417b28e80049a401a26f79b43e53f05a39866b6.nq.gz
│   ├── 368aed59bfdc3dc7234093493d7f6cb92364f39c.nq.gz
│   ├── 3a2a63e6ec527bf244a549c7471e76feaeaac353.nq.gz
│   ├── 4164683f8a4f24a5dfa296feae0d8279b33e367a.nq.gz
│   ├── 4199ce65e9940a94cba305c3acad4b794ed5e7a5.nq.gz
│   ├── 46f160aae2ba3f8fa26ea6fc74254f35889c6646.nq.gz
│   ├── 4aa8c4fe070fdfa3cc9b354a9eae33fe7d2cbd03.nq.gz
│   ├── 4e24f6601f78647238ed8aba6fc12dd5b8eb6c7b.nq.gz
│   ├── 595a2b3bb89fa00309c103a9a713be763ed0d46e.nq.gz
│   ├── 5c8b0d9155aaf2da3b99166d8ed667f1d01624fe.nq.gz
│   ├── 5f4f225dd282aa7e4361ec3c2750bbbaaed8ab1f.nq.gz
│   ├── 61d42bb92ca8429752c78d45497b925e8eb8cf08.nq.gz
│   ├── 6293cbd7f2316f1460bad45473adcf54953cd542.nq.gz
│   ├── 6822ccc64ecbdf0bfd317423230c9b25fbe82708.nq.gz
│   ├── 77e57e8909c2f3f01ea141292f637d985d384c72.nq.gz
│   ├── 7a863e31a6a5d0abbc4f7346d42fa1c374362ce8.nq.gz
│   ├── 7b0e3245637e2c34a9f2faf3b6f3f24b9e8dc265.nq.gz
│   ├── 82133027c9eb6dd3ff20c82704ecf25650e474f5.nq.gz
│   ├── 845313a81dd0896e7e84e267514b0bba5ce0cde8.nq.gz
│   ├── 8d8a9bdcf5c39c2601df68995f5278120a2a34e2.nq.gz
│   ├── 9c710e13da6b8e2db4fdf863d6d266298ad70a29.nq.gz
│   ├── 9e8cafdbbcb21701a0e61213ba61931f48989415.nq.gz
│   ├── aec5bf9cf9344ebbc02786896340bab7a6a21db9.nq.gz
│   ├── aff1c2f1083e7260bb047fda53f1d99b8d9fd831.nq.gz
│   ├── b66e56ed74c93510aa1b10ebaf87010c8260725c.nq.gz
│   ├── c24fdaa3fe3bbdf2594ac55af54f012b8da152b1.nq.gz
│   ├── c299bced31730f95a67ad8b0979dc6388aa1d94d.nq.gz
│   ├── d256327a831b750e489ab84f717c6d9409d1a4c6.nq.gz
│   ├── d6ccee58778eab8b4d131486ce682b27cde898c4.nq.gz
│   ├── dab6a75e9eee65b2b4059c95b728ba50d9f3954e.nq.gz
│   ├── db0315d6e7c2105325b37ea2e564dcaa5b8c221a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e733c8e55f81f1132c681d2dffd463e4cc3c51aa.nq.gz
│   ├── e7cb44927646763aeeb63fc30209db92abb50d3b.nq.gz
│   ├── eb1152714e00dccf232cfda3a6b2fd4445631489.nq.gz
│   ├── ee4c69c05e7555b96542c9f5a213fe24921a1cab.nq.gz
│   ├── ef0a43141d65f60b6306a9d278244ef86e5aeb4e.nq.gz
│   ├── f8aad448c1769984048f53734c69577c1097ef00.nq.gz
│   ├── f981e8e61e5a23942683102a900d3940676948b5.nq.gz
│   └── fd5381d0d9a0a3ebc0bccb798059d42ede75d038.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── d97a7339524c89798c510de6c142b663fe40400c.nq.gz
├── filetree
│   └── d97a7339524c89798c510de6c142b663fe40400c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 57 files
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

[django/asgiref](https://github.com/django/asgiref)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
