# Repolex Knowledge Graph of canonical/loki-k8s-operator

RDF knowledge graph data for [canonical/loki-k8s-operator](https://github.com/canonical/loki-k8s-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/loki-k8s-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b26f896394b0ed6ad965e0f80a54e99a875429a8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b26f896394b0ed6ad965e0f80a54e99a875429a8
│           └── chunk-001.nq.gz
├── blob
│   ├── 0177dc1ef517805f8120637ac38120cf47fe86b4.nq.gz
│   ├── 02c6c55dba1c1d55b720405f91aad141b4ccd501.nq.gz
│   ├── 08512ee4ef52d4a5d5d1cb187501c7c18458cc89.nq.gz
│   ├── 08f49b9c2a8089e41f6846b4236f4b0e4a6c5c7c.nq.gz
│   ├── 0bf6589cbe253cb80c2aae7664639e480d3c3056.nq.gz
│   ├── 1292005e596ab8039dabaebc2dd199f3ece58a16.nq.gz
│   ├── 14cd592e0466bfdd79dcf2003f3bf9310308a98a.nq.gz
│   ├── 1527248b125dabe30867ea3750b2a727c6797536.nq.gz
│   ├── 1a5f0e77f4c103012fb323e34faeae62c1132c58.nq.gz
│   ├── 1ad595885b24c0eed96a78209e3f5316adb7dda2.nq.gz
│   ├── 1b8c68cd511494b07f9d88e9f11de701928a3cbf.nq.gz
│   ├── 1bb45e9085b56696c3b53307f0da6268b4b3d16a.nq.gz
│   ├── 219793a0aa948e6766e7ef5ea130682b05755c83.nq.gz
│   ├── 22656a1d214698937065cc85298dedf3829af6aa.nq.gz
│   ├── 25e1bc38fcf04afade43855e65899f3aad90ce96.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2853b36eaf062a785bc9ff7a74d1b44a4c62a52c.nq.gz
│   ├── 2a354b5bcae3a417d6cf131ce8b83c75c99ba423.nq.gz
│   ├── 2c3f0e5ed7915b3800370e2f37f7661e29df6742.nq.gz
│   ├── 2cd611a4ac82ee5df24793d3c200db880aff5ad6.nq.gz
│   ├── 2da63974dd293dd81265f89a687da435ac7f1df5.nq.gz
│   ├── 32185cb3e9d6867d17136bfa0ea786040f0f51df.nq.gz
│   ├── 32ad9d1b1d6da74d4b9424ce046273ffa80d9f5c.nq.gz
│   ├── 379d021483c1640834e62ec9de493a89d9360455.nq.gz
│   ├── 381f20d3a2a09e06232936d56772d3f5ef2c208a.nq.gz
│   ├── 387ac6a47738bcce3f686ea6d43178ab2197e414.nq.gz
│   ├── 3bbe8669a505e133c13c6d0a1cd5e9447a8eacf6.nq.gz
│   ├── 42703039e7a42761690ceed10cd3c746e5b621df.nq.gz
│   ├── 470c376fd9ebb2d77cd2e992ac8cc42250938765.nq.gz
│   ├── 498308b47da2680e26de1a7ccd8d1c4743d92bf9.nq.gz
│   ├── 4a6ed466d158b72ca4f19089305f1a2d4234902e.nq.gz
│   ├── 4e15ae4e548d9dda44c0af260e33060614abfc94.nq.gz
│   ├── 4ff601f564007c76c90f10907806dbf046dc5a64.nq.gz
│   ├── 535ac293032b8af15936c205b66f1834f9da4b64.nq.gz
│   ├── 561edb27c02467943721d47d78c9501bf68bf757.nq.gz
│   ├── 56aa846b2201586134525758b7a98d83b0dcfc4f.nq.gz
│   ├── 5dcced9b0a5fe23646bcd8be4ebb1fb9dfc6ffaf.nq.gz
│   ├── 5fadc225ebceebd76699f611daa6aa402a08c2f6.nq.gz
│   ├── 60f42418ffe81e3b4ce423a128a56122020de605.nq.gz
│   ├── 6529018230d905782e567630986cf15c86cf441b.nq.gz
│   ├── 652c7d218edf2dc1dcf39f46f745b352c2172801.nq.gz
│   ├── 6ccd559eabeae93e4d23215fa450130fa9b37ace.nq.gz
│   ├── 6ef8072bd4d3355948e31555aef24c560c0f4a72.nq.gz
│   ├── 6f94cded4fec60283aa42d48789f2f779e32bb9a.nq.gz
│   ├── 789092469ab08072616be5349eaf11158822645b.nq.gz
│   ├── 794cd985f295eacb4907f214314891c36a094824.nq.gz
│   ├── 79c9aee489568428287267423d4e4629255a716d.nq.gz
│   ├── 7e91190a496364569f3a5366dedd5d63be68dc34.nq.gz
│   ├── 813c275b31ad1a626343478398d270963c49e7c1.nq.gz
│   ├── 83590cbd9150c73fa71607571d290b71458c9bf0.nq.gz
│   ├── 888c85583f72dc67ed997c9868566452e70cf898.nq.gz
│   ├── 88ff1492be46a0699eeca8676d36750066c2ac8c.nq.gz
│   ├── 8bac1fe1243099c1b29d8f5c820fe40efbb86d71.nq.gz
│   ├── 8c83d77e260753d405abb2ac0580ee37bb02d18d.nq.gz
│   ├── 8ef84fcd43f3b7a46768c31b20f36cab48ffdfe0.nq.gz
│   ├── 901f14351bdce339c3fcc6c3b3112c94e4fecb2f.nq.gz
│   ├── 901f9a938de6c666711ac74043e51bc2cdf5e4c4.nq.gz
│   ├── 9539a27327a90e3c17cc7bb7ee34501e49227d97.nq.gz
│   ├── 975c7e116672043ee80160f2f39eb69f18c9fae8.nq.gz
│   ├── 98a86e9d270dee81aaf94e542c8c181f5c3c27b7.nq.gz
│   ├── 98f9c97a9c0eca2bf2426f69b883b6a647d475e4.nq.gz
│   ├── 9a2876d8337406f3d39032b8905a158d8498da07.nq.gz
│   ├── 9d1045cc70dde437bcfaef19527240469a8dd081.nq.gz
│   ├── 9e38210007ec3806af1eaee1459c345544578cd8.nq.gz
│   ├── 9ec7d9686d5edec8f23213006478efd049481af5.nq.gz
│   ├── a028fd911073a514c7a7d373425b0142633ecbf4.nq.gz
│   ├── a065dd53af21d8bf4ad1af1644959f5fc734fe23.nq.gz
│   ├── a3a16c749b498eeb25265ebf2e0395fc28c3b0cd.nq.gz
│   ├── a4beca7fb162f4c55f5b457aa75d2aa03cab44f2.nq.gz
│   ├── a62a03710d67d75241d393fc71d65472519ab374.nq.gz
│   ├── a6720ddae548ca02f636e702b1a9d35ced98cc79.nq.gz
│   ├── a7820058a363d3c910dafbe34fcdaffff7aef8fb.nq.gz
│   ├── ac0cb43e4dfea8a0c68e1674feaf8a3dafb0cea5.nq.gz
│   ├── ad60b546623c02340f4e7eb19bf83031a47b2ea1.nq.gz
│   ├── aff29f890a081dacb874528f6aa2e9edde9c581c.nq.gz
│   ├── b083af2590b2d359a3ec9f22fbf1db67d4cc59f0.nq.gz
│   ├── b1e92931d28bd6c43d8d55eea51c53cd467dd144.nq.gz
│   ├── b2301deef14b1a66774d507c1fde1dffd37ded0e.nq.gz
│   ├── b2348b9fbfdc4eb154566c80f844510446be1d02.nq.gz
│   ├── b26710e23924dc2ae8f44435e0466cd3bac20797.nq.gz
│   ├── b415af0a8109afa614fe12d8c9d83e095c752d50.nq.gz
│   ├── b98a2badce49a166100ce020e0ef2dfa54c4e188.nq.gz
│   ├── ba43b897a676bd126fb05ef7f8b17ce34ea0daec.nq.gz
│   ├── bb718f288e5b26e40c94c0b91c4717afbd89334c.nq.gz
│   ├── bc6a02c945fa01fa126e8e600077df0ca77f16f0.nq.gz
│   ├── bcefbeedb0b1c140461d4ce21bc04b4f180581ac.nq.gz
│   ├── c18e45f0c377a843a30dba6b8d20c582b1f28839.nq.gz
│   ├── c21f1bb8950accb8d9f9ebf27dd3db2186c8c974.nq.gz
│   ├── c38ebe2f4961714d3459e7993dba896f5dd3b169.nq.gz
│   ├── c4714568bca342aab1e2e0992f7e79bf719e32dc.nq.gz
│   ├── c4f2c3687506829875fbbf1e787d5883849e7728.nq.gz
│   ├── c5d20da1d985e515ed427928f3fe266c5c685e1d.nq.gz
│   ├── c6fc49f9fc7971f3b0b20befe47fe3267c3d9572.nq.gz
│   ├── c7f7558b7f5cda06804923010dcde901538ba656.nq.gz
│   ├── c7f9fdda32db80652782b2e188f8f2186feda942.nq.gz
│   ├── c9302eb500a5df81cdbc72cf132060b657939a55.nq.gz
│   ├── c9d8042514241024876f0f829a5b2749bd8495bf.nq.gz
│   ├── cc8cb4070ebcf18fee69655277ed42aaa2651131.nq.gz
│   ├── cc98d25f7ed435a2fff6d5c042b6a598299a778b.nq.gz
│   ├── cff5cb9b80374e5213ce4d6cebae6a99c9fb6949.nq.gz
│   ├── d08d02cdf015b5c89fe48ee4bbf16e7886204049.nq.gz
│   ├── d094c9e2a4c7fe5c3192d41d02d27d711c1eb9f7.nq.gz
│   ├── d25729588b7ddd229cb0756c0b098ea3709a7a6e.nq.gz
│   ├── d35df0b92bcef0c67532bab64d131d60a43b1ce2.nq.gz
│   ├── d3ed02fcdbaecbe70c51d1ab02b077542455944e.nq.gz
│   ├── d6407c6b67d1e0ac8bc899b8caf3debec64472db.nq.gz
│   ├── dae3d8c5c145446bcb003017c89db09b57a1dd1e.nq.gz
│   ├── db63a72540e78e7750e027706736757524143a14.nq.gz
│   ├── dbac89ddc543fadf5dd0370d9878e6d63e61e25c.nq.gz
│   ├── de535d0f97c5fd103dfccb173b400b7e71461bd6.nq.gz
│   ├── e1d958767944f9d44edd5058fd4579b8a358a409.nq.gz
│   ├── e4549632d0d6f53d43e769a86bdef203da86ea97.nq.gz
│   ├── e458cfa5c42cd364083d52c84a5179250e8a4491.nq.gz
│   ├── e4f316e68af7e8777f0d051f3f94430a55518c7b.nq.gz
│   ├── e4f90af8b67be575b7252f52c6e4fff460733277.nq.gz
│   ├── e68e93ff709f28fcb5fc9bdae2cb6acc220b6637.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ecb349a1af1dc67dfde169b35e2877ef738246ec.nq.gz
│   ├── f35143eb2ace2ec8c395b78e06459ca40e03caad.nq.gz
│   ├── f4456b9c6407aca77bdb5304def925e9fae6b06c.nq.gz
│   ├── f46a96d437684329e742d0e015a8fae55da86ceb.nq.gz
│   ├── f4aa9e929f7e6bdca6242a2545014480968600ec.nq.gz
│   ├── fbc823f1d7f4bab4356af7253c86f9403a5c4a51.nq.gz
│   └── ffddc99280c1e7360a8cde6e6dd6f87823a06ba1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b26f896394b0ed6ad965e0f80a54e99a875429a8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 132 files
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

[canonical/loki-k8s-operator](https://github.com/canonical/loki-k8s-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
