# Repolex Knowledge Graph of python-humanize/humanize

RDF knowledge graph data for [python-humanize/humanize](https://github.com/python-humanize/humanize), parsed by [repolex](https://repolex.ai).

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
rlex download python-humanize/humanize
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 785e5dcc0d0308ad0dff3f6cc0faa7085ad0375b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 785e5dcc0d0308ad0dff3f6cc0faa7085ad0375b
│           └── chunk-001.nq.gz
├── blob
│   ├── 026df970a06848741409690cb901bb5e8c4ba8a7.nq.gz
│   ├── 063affe05071511ff99f84ef9f2e785387471c7b.nq.gz
│   ├── 0bf73de5c8e94217d143aed483635eedbe6b7e07.nq.gz
│   ├── 11d0ab3c748682646987a1faa11d83de547da643.nq.gz
│   ├── 13c8dd8ba7c9c801b9218d7039f3f52f6dfaa5f6.nq.gz
│   ├── 14778ed0d0a4f72286f832a07d0dc23a9f9ff5dd.nq.gz
│   ├── 15dc4fbeae3360474f3b8c508900d8bb137cf73e.nq.gz
│   ├── 168cfd095ea4585dd8daee363a4433861512727f.nq.gz
│   ├── 1954918000d5af7284346a799d9ebc2c3d361a3e.nq.gz
│   ├── 1b883da593ef663911c6e26eb812cce8b1d5ebd8.nq.gz
│   ├── 1f882cc02e19f7a4427711dbc0c99480c18cfe8c.nq.gz
│   ├── 207bac43d62eac98fbd78b12996436a2de8f6960.nq.gz
│   ├── 21eba354134be2da0ebdc87107047e68ef521209.nq.gz
│   ├── 2396030351eba1e7c6a246db1569624121dbbcee.nq.gz
│   ├── 24c52378a9075717557920b039805c35e61749a6.nq.gz
│   ├── 25b4684fedd3f2389e3404c49afdfb4549323a02.nq.gz
│   ├── 270978532593be9fe66bff9d8cbe97c459e2659e.nq.gz
│   ├── 2744e25d5831606bc56d159097cdb2f72df0901d.nq.gz
│   ├── 2aaf9d8533518d09d5026cff611bec0c723fed19.nq.gz
│   ├── 2e37f36b089fd107950602fcddd0767c9a4a370d.nq.gz
│   ├── 36e8ab73a78f3028c668d9fe3da9d5de9d4aeb34.nq.gz
│   ├── 3d09ae9364bef8d48e6594fc795d41b5a77f4fbd.nq.gz
│   ├── 3e4dcdf8dd55e2631ef352bb4ba00737282c5b18.nq.gz
│   ├── 412897614462fcc8b6238c2510ebac707137f90b.nq.gz
│   ├── 4f54bc466a303acc40bab90c79f75a55fb74e0ab.nq.gz
│   ├── 4fc1d3265f10aeeb4695e492709f35c8d384120e.nq.gz
│   ├── 4fe4a0058ca3bd37a3d99248aa8ee638b20c14ef.nq.gz
│   ├── 515f29fc38000576c0b0d43a2851abe508f2ac70.nq.gz
│   ├── 529c354324a8e89420e1644a67ac51700a42c1d9.nq.gz
│   ├── 52a5356a9d9f3694a3ba0fef272abaa496e90de0.nq.gz
│   ├── 52d718d669c6c547834857ed9f902d6d656e7d66.nq.gz
│   ├── 5e547766df9d90b5f156fcc0ffe3d21f6e2b9e21.nq.gz
│   ├── 5fb12fa6b905ecb6d45a0f4af78b25b1d2f04a42.nq.gz
│   ├── 63817fecd79d5d325013fef541f9074c7973342a.nq.gz
│   ├── 645751b9fbb3a41d1a32924ca58cd73887fac24a.nq.gz
│   ├── 661c289e69686ca1498ade60bed7df3a126d930f.nq.gz
│   ├── 683fe3cedb724295f242ee7611eae0418bfcb10a.nq.gz
│   ├── 6933449763cdf8c7432997d3c1aede6bbf75f00f.nq.gz
│   ├── 69909cba69f453eb5c70d9e00c3e8de58c086db1.nq.gz
│   ├── 6b3194211b488c8af1f6fb22f47e12ef3cc4c850.nq.gz
│   ├── 70cc6786eaef74ce90453ae55413d46c31281250.nq.gz
│   ├── 74487a66a43cd297205d560f83668cd65fa03a81.nq.gz
│   ├── 7534b02a3dc4f448f411cac40eaf5248372b33a1.nq.gz
│   ├── 7827900faf0f54379944541152f0a60492294cc1.nq.gz
│   ├── 78c8399663de9f2e15938fd395dfc141fcbbaecb.nq.gz
│   ├── 7a191afd66728c440e5997cab0e8fcbcd0f6f38f.nq.gz
│   ├── 7c4a28eb73a73764bef7563e05867285b046e8ea.nq.gz
│   ├── 7fa46eca88a55ac7e19390cf15f0990552b3c4a0.nq.gz
│   ├── 83bf7f1a8c1d98b3aef3c0e7794ac1ff03098cb0.nq.gz
│   ├── 842815ced9a6b0a8ad131187c3a958d5a6a46913.nq.gz
│   ├── 881e24b4aa8373476b1b0982286b9611390d0948.nq.gz
│   ├── 887a3fc56dfd44171fc1a5d397e23b78c8e9b595.nq.gz
│   ├── 8dffa640135eb0e5243574549f4a3a3502a7e2e4.nq.gz
│   ├── 8fa6aa6e31620b3347779be7b5f98f718e0b4b84.nq.gz
│   ├── 9197a76dd165ba62fa2c8f188a2275a532fe47f7.nq.gz
│   ├── 91ac5e38782df9e933188a869e9816d17c3cc84e.nq.gz
│   ├── 92d59256710ac300d795bf59f35c903f8ff9a4a5.nq.gz
│   ├── 97ca9dc345beed107f05d82416c5d9e3c4f424d7.nq.gz
│   ├── 9b3c1b77a45dfc252a996992a757d914eda21908.nq.gz
│   ├── 9d3236aa6620be0c6fc1499a06aeff3b6d0d7896.nq.gz
│   ├── 9f3cf50065f3fcb4fabe4dce77cfa38f3db994cb.nq.gz
│   ├── 9f688bd8f6b0b202c19a13eb52e27b0aeea8f2c8.nq.gz
│   ├── a1ac7ac777aa2805711d3baf4caeb51f1aee8dff.nq.gz
│   ├── aa4bcd7fe46398dc6748009bc4404839d4ef085a.nq.gz
│   ├── aea79300af6450a7290e19834eb6825967f528f0.nq.gz
│   ├── c00d5b4ac152601297886b4c6313d28cf5e2782a.nq.gz
│   ├── c200dd0124c2d61838cc807ba088ecbddec38f78.nq.gz
│   ├── c380c76bc857a566bbe6278068ac6559d1c175ca.nq.gz
│   ├── c4544895fd191339b65b165c2c14aa38476cd9a6.nq.gz
│   ├── cac5bab58c957d0b6e7b4f19eb35aa4febe9c90b.nq.gz
│   ├── cbfece7c66949ced9b57163afa17bb66882e597a.nq.gz
│   ├── d640ef4d9441d502b895f1974eb06f85ae7fb529.nq.gz
│   ├── d65f32c87551fa8cf81c80bf043a831d5bd3fbeb.nq.gz
│   ├── db73501cc15c93387129c1e3488a166fc2e96fb8.nq.gz
│   ├── dc32068080b38d01fdff6a9cc728ef882538737e.nq.gz
│   ├── dec527367dfacdfff97c3088248537165d7c1db7.nq.gz
│   ├── ded2ede16399241be446d0a28176c10813859cb7.nq.gz
│   ├── e0687959f9e19e8bee8783424885bca65477fa28.nq.gz
│   ├── e14dec698c2f1aec48e800fd1f92211ba3c9777d.nq.gz
│   ├── e2c3ae03dd18ee022b5197fb3bf5a03022964689.nq.gz
│   ├── e61dc452b8a47cc016c04c951719d3fb6adeb97e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6f08499ecd0e46c78107237c728d98921f96d62.nq.gz
│   ├── e9a4220e1c6545f9ce754df5c492c9c6fe8710c2.nq.gz
│   ├── eab0e081d186403c9caad912781dbc25e258e9e8.nq.gz
│   ├── f1822c7de66bd6f065e4647dfbd294a76e9b138a.nq.gz
│   ├── f368d519ecf711e2218fb9acc39dd39307fe9b7b.nq.gz
│   └── f7bbc622761813cdeebe71a70e62f4473c0a7133.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 785e5dcc0d0308ad0dff3f6cc0faa7085ad0375b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 96 files
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

[python-humanize/humanize](https://github.com/python-humanize/humanize)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
