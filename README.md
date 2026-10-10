# Repolex Knowledge Graph of pydantic/pydantic-extra-types

RDF knowledge graph data for [pydantic/pydantic-extra-types](https://github.com/pydantic/pydantic-extra-types), parsed by [repolex](https://repolex.ai).

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
rlex download pydantic/pydantic-extra-types
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 27cca0ebf575fc99a21a249e66197f4f84069211
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 27cca0ebf575fc99a21a249e66197f4f84069211
│           └── chunk-001.nq.gz
├── blob
│   ├── 0011d9203c3b4bca901affa939808c33614f5117.nq.gz
│   ├── 00699708a7a5cd935a5bfd2734118b8ec4b5201c.nq.gz
│   ├── 039b3740a0d603879a3d9ffa07c55cf1d2c63448.nq.gz
│   ├── 04a26fda00ab384d5ee49c3559984c8daba594d5.nq.gz
│   ├── 04b418e36cc9673e42c774ad3e7d897b6a474d9a.nq.gz
│   ├── 05732d5b6a409425d2d5e146992ae9eb36006e49.nq.gz
│   ├── 0982fc451f23f044753eb89272c0159a5a5588f0.nq.gz
│   ├── 13bb85a022b33a656864c82970967599098a43df.nq.gz
│   ├── 1991953b71f134123cf61521a69e14bb32e266f2.nq.gz
│   ├── 1baccb1ba8ccf472ecf458539652d284a338a4c8.nq.gz
│   ├── 1e963ba233ede77b129cb8e7690ca51737527541.nq.gz
│   ├── 24bf222ec77d019ce1084649d5c621af98064826.nq.gz
│   ├── 26092e50492201085e57bda13b8f6d95f932d26f.nq.gz
│   ├── 2a5af8ed23e85ae2df478211597f5bf00af11440.nq.gz
│   ├── 2b5886406d1312b19a1437d310b19509a091b072.nq.gz
│   ├── 2c21f131408609485f0ec8278e97041cca7f8103.nq.gz
│   ├── 307d6c41909c8a406b32baf77db498e3ba40835d.nq.gz
│   ├── 3815feb98e0bc9921d46fae0112e40e4dc727935.nq.gz
│   ├── 38d6e10ef1b00645ddd1f83afb990b9730c02599.nq.gz
│   ├── 3a7085244a00d48f8fc474ada905faa4003b03c9.nq.gz
│   ├── 3bd99975f0f2b654ab7e17fdcdc1b03168ec37cf.nq.gz
│   ├── 3fb861b11f90276cf74aca65a4c4bbd1782df211.nq.gz
│   ├── 4656f4daf027c5f3f8600126778ed55c52fe4530.nq.gz
│   ├── 47dd08b3e860559b2aa72611617698df44d331b2.nq.gz
│   ├── 4a7086d9e446f6985ec7e2c6c748a186362b3da7.nq.gz
│   ├── 4c725a5576b43aa1eb9cded165c37759b19af3cc.nq.gz
│   ├── 50391206e5bd1916b47d5b99edb6dbca91fd67a5.nq.gz
│   ├── 50efe48ff94739a3b137698039240ba72fed4af2.nq.gz
│   ├── 52cda3f79775738bf06ad8049b234806dadfd71d.nq.gz
│   ├── 53689d32e2b1e98e93defd97cefbe984cf1d3e3c.nq.gz
│   ├── 555d0325323b061bdcc51c82a233e7d45eca3d5c.nq.gz
│   ├── 5704ac399f85fb6446cc4107503bd7d8a17c6cc4.nq.gz
│   ├── 57d2f7f8f03b671e0744510b4c2f9d0b4956a3bd.nq.gz
│   ├── 5deeb02ba97b2733b3fb5c9c7b153be7850501f3.nq.gz
│   ├── 5e4d6a203078b27fdfaf4e3f81ae08daa5c0d50b.nq.gz
│   ├── 5eb66fb682a67f9dc164650c8fd2d8431bb1bc47.nq.gz
│   ├── 6550b665ca3f7f1411f34b65cb2f2e99e729c4bf.nq.gz
│   ├── 6c37226d785389cf519396c984de0576e479d2d6.nq.gz
│   ├── 73d65cad2e342bceb72b32d8796da5c9ce7800ad.nq.gz
│   ├── 74e515a62d7afb2004e63d3d15af53f758aab882.nq.gz
│   ├── 7c5cb6ffeef085f81920c4c83ac6d0f93dc968b9.nq.gz
│   ├── 87390304dd9b01c47abcad70f3e61f8d0db85090.nq.gz
│   ├── 87f11867f6c28575c873fac57acd0d38c441366e.nq.gz
│   ├── 890c060ac42d5bd06977828c6c3770027ae94376.nq.gz
│   ├── 8ffdfde1487303f0811829bde9e7536344ea0aba.nq.gz
│   ├── 92183a0bb73dc58f56d7bc9e49f81a50e9ea9da5.nq.gz
│   ├── 9950bd2276feee8049094401cc16c0694e367c57.nq.gz
│   ├── a0ae2a285505b4146816ac599d5324597f226433.nq.gz
│   ├── a38870be188ff4aebdbe1ee60fb82fbe719fe139.nq.gz
│   ├── acc2360bce06f3a334bdf35ff233abdbc05edda6.nq.gz
│   ├── b05c5fb1e22f2c012e1c1591d0ebfbdd103aa178.nq.gz
│   ├── b7474b0465c068617821386d7888dde7ba7edb6c.nq.gz
│   ├── ba78f0b4801e328a9fbabe656c08047bd32556fc.nq.gz
│   ├── bddbd873f9fcce047e87dd9d0c430f7a3471de2d.nq.gz
│   ├── bff606762897e2c70a2e3ab05845a90a2179f0b1.nq.gz
│   ├── c2a5e0fce0ae1f2c386e3b8938855adb3a02dca9.nq.gz
│   ├── c3906dcb303af170d90deaf0ab7f164f6a0bbc7c.nq.gz
│   ├── c3b27bb51379eff3be1ef331f21c31872b499046.nq.gz
│   ├── c53c88e0a0244e8a9e640805efd94103fd148bba.nq.gz
│   ├── c636b0e727f55804cefaf491633299eedc185212.nq.gz
│   ├── c70c2350b0299fbfa9d08978fb5733571fe76588.nq.gz
│   ├── cad0f4e0c50c9650e3d5bc464054f90df5949d16.nq.gz
│   ├── cb4b8df319fac2acb17764e20eb421250c61b0c1.nq.gz
│   ├── cbf36bc743d7ec1d58821aabc57e266b25b5d04d.nq.gz
│   ├── d18c1a75f51e79dfe34dda3825ce5a1a60c3093f.nq.gz
│   ├── d35b8fb98a275ee6e55dfa08fee8415f3682a7c3.nq.gz
│   ├── d50d94d7acb68bfc8021d9911a84fe9cb4c1e98c.nq.gz
│   ├── d70ae69919c1995c63e37da98a5ecb1f081dff1b.nq.gz
│   ├── dbb574ae74e0afd634461c10fdf153b45553e487.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6f52844f2f31c584d2ecb1a63a4bfdca93be3ab.nq.gz
│   ├── e9813eda4e19e989e2894cab76a9cd135eafe299.nq.gz
│   ├── ef3ad538c4670bfb18397d8c7b87a5fc2cd0d0f1.nq.gz
│   ├── efcca01b100f479ddef04c77bc3fcdde5367a9a1.nq.gz
│   ├── f3175c43fd9881f7d12e6d60344e222e67b31fc1.nq.gz
│   ├── f64690f1c4db150e330b720a1a53c77f0123687b.nq.gz
│   ├── ffc17d90b3df48d350f99ab32b61b1d0ac4fb0f3.nq.gz
│   └── ffe2f3bdf5fc211cb3b4149ee191d28a62698fce.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 27cca0ebf575fc99a21a249e66197f4f84069211.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 86 files
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

[pydantic/pydantic-extra-types](https://github.com/pydantic/pydantic-extra-types)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
