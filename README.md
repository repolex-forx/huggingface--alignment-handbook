# Repolex Knowledge Graph of huggingface/alignment-handbook

RDF knowledge graph data for [huggingface/alignment-handbook](https://github.com/huggingface/alignment-handbook), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/alignment-handbook
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 53c11c328684f965162f41ff93185bb9e0448263
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 53c11c328684f965162f41ff93185bb9e0448263
│           └── chunk-001.nq.gz
├── blob
│   ├── 07df54c76ba5033c5bd242549b378b3c57e4073a.nq.gz
│   ├── 0836e21343a92a49d2b323dc5942b518225f365a.nq.gz
│   ├── 1445d93c085f3d90a89be70f7900949a76098d24.nq.gz
│   ├── 15f7bdd7916ac5fca2274ad5d1239bafe0f0f5a2.nq.gz
│   ├── 167f1863b80389dc7c84cda9f94cd409d5236713.nq.gz
│   ├── 18cd6942f690f6e6d9e913c3ee2708443fe72ca7.nq.gz
│   ├── 21ab374fb90b1d8d667dd64a70a75715712f670a.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 267a7d90b03092f0722b216c085ab8633193b2f8.nq.gz
│   ├── 276a0b66d446276e62b9c13ecb7b3f05ef1953b7.nq.gz
│   ├── 2ec911682c8681e5fbd4b2c1d75d0c46d13bbe3f.nq.gz
│   ├── 43cb5abe25fd8de601ab29ca96ad9639502a76ed.nq.gz
│   ├── 46189468f05045ade03ac68984b2e9fb85b9f1e2.nq.gz
│   ├── 467fe236dbb6622d12280851bf05a30f72d0f3a8.nq.gz
│   ├── 4809f89970eb5a7b491b6bdba1d5bbc83c554ef7.nq.gz
│   ├── 48f7c31e43e497feb436ff82c8527189da61d7a5.nq.gz
│   ├── 4f0557131aa2c1bded4cb4cfdc1cc58a3b25765b.nq.gz
│   ├── 5204194a22d61677b2de5bee1899353ba938667e.nq.gz
│   ├── 5a9f6603fe6a675b052f05bcfe4ec8c330fdb281.nq.gz
│   ├── 5ddb059c014e98c055e7932565c6f69e14299ef9.nq.gz
│   ├── 5eb55b2185bd65b70b466b9104cec105aab0c9e9.nq.gz
│   ├── 6384fca88c3e0aa630389e2c2c5591d04cccd5cc.nq.gz
│   ├── 681fd36fca9693fc8177e8c607f39881ee300b3e.nq.gz
│   ├── 6ad6e47bd2bfda00e13f37ecbf3f2e1019e38c7c.nq.gz
│   ├── 6c44a86c636ef1a3e034ef44af188c3f3a90214e.nq.gz
│   ├── 7259bd3521db14f554aa48a936dbafbfaab0e01a.nq.gz
│   ├── 7679a7d1cdfef64866c445e7f8cec2ce4b686546.nq.gz
│   ├── 78c9b77ff151348efc76433d85554b62668a7d50.nq.gz
│   ├── 7f97256f23ba97b8caad052b011c4c674c8e5d22.nq.gz
│   ├── 80dbc6411f6f431eaa39f08fe592fbb15689dff5.nq.gz
│   ├── 84619ad54867ff7e11606a5e549601ab491968f1.nq.gz
│   ├── 8b3285c1a2a509f96412707e0ac01e7f29a67e63.nq.gz
│   ├── 8c6c7e97db6f3bb1b8f119ca98b035519d11d429.nq.gz
│   ├── 8d3bb314f0d129a2a37f39d7aa840351f321e22e.nq.gz
│   ├── 90e9973dc9938b38aaf939f52b10f9c773691c15.nq.gz
│   ├── 993c9a0498c695f5e71f1ced79dcf3d24ea2d4e0.nq.gz
│   ├── 9faecabfa3bb4d1b14a0e19e14bde8fe281211d3.nq.gz
│   ├── a1146bfe78725918584c889749fbb5415db2fca5.nq.gz
│   ├── a125db775cfe62d765e38f761b957823bd30043b.nq.gz
│   ├── a33a349b8b06de4719f2b4b5aa812d0d4e20642c.nq.gz
│   ├── b816e688d09535d437c5be58139ebcda3ac96b39.nq.gz
│   ├── b8285f99a1dee1146a67cbca65c07fb97fac868b.nq.gz
│   ├── b8e7feb545f47fc5936ac16381e35d9989a3968c.nq.gz
│   ├── bea42f305927363dd7085d033e055e2fbe96b5d8.nq.gz
│   ├── bebae849dca259a68baf1c106a1e7623f9d5cd1c.nq.gz
│   ├── befc757b51a800cb156853ff7700a9f2605973a0.nq.gz
│   ├── c0b06298df7f5c05715c9bdd9b21413ce8685187.nq.gz
│   ├── c2ee645befd5933b618f5f9912609acc5fab1445.nq.gz
│   ├── cc0fa3374866d3320aa76df9245ecba92ebd0db3.nq.gz
│   ├── cfaba96e83e3a3f847fb7e2ddbfbfc5a472f8417.nq.gz
│   ├── d02511bb9ed31aff3380c03d07529824e9739aee.nq.gz
│   ├── d23d1d1ce42800efee2c737d1fbfd1bfa58e2809.nq.gz
│   ├── e2e4d2cb71b3aa6b9b686ee7c4bcae3560422a1e.nq.gz
│   ├── e3df56d36cffa4a0d53c598d8f67a89c1b81dd7a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8f15baab95b60b96ec86564913d197e8d898e23.nq.gz
│   ├── ee050527311c24af816bee854914c9f1ef59ddba.nq.gz
│   ├── ee6554333e6757f8f8a8e5cba0bff8c31354000b.nq.gz
│   ├── fa56b2b1eef429043adc238a29340b7284978cf1.nq.gz
│   └── fee01a445aae8b55a7f5fa4f48a3ded068286d1e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 53c11c328684f965162f41ff93185bb9e0448263.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 68 files
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

[huggingface/alignment-handbook](https://github.com/huggingface/alignment-handbook)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
