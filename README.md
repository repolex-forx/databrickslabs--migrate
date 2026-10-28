# Repolex Knowledge Graph of databrickslabs/migrate

RDF knowledge graph data for [databrickslabs/migrate](https://github.com/databrickslabs/migrate), parsed by [repolex](https://repolex.ai).

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
rlex download databrickslabs/migrate
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6dc7bce355dcecb52610e3309b8f44545104cb74
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6dc7bce355dcecb52610e3309b8f44545104cb74
│           └── chunk-001.nq.gz
├── blob
│   ├── 03216e00dbf33a1b6114be2025308aa62194fa5f.nq.gz
│   ├── 062c24bafc2ba699535ca2996b16b58760816825.nq.gz
│   ├── 07a07abf5765f04c256280c059662dfb2ad4582f.nq.gz
│   ├── 08b1c1fc68c17f534f817e9838acb1eed9c705cd.nq.gz
│   ├── 0a29fed25fb90138a94b5bcf23e56a4b07966d30.nq.gz
│   ├── 0d4dace315d39f8286a3f3e1aabbe4deb6c4af64.nq.gz
│   ├── 0ebd254547691f0764b2c3d9dda0172ed54626c2.nq.gz
│   ├── 1191706f8b5b70d6f44c2f76a1ba0e3253b0a2ee.nq.gz
│   ├── 136e4091d11510e7a3a8fea603dd9d3676b847b7.nq.gz
│   ├── 17712c0d86907af2d0a067c2c686f13c105dd3c4.nq.gz
│   ├── 1a3dd406dd5aca138e645b0bd6886ee215be4172.nq.gz
│   ├── 1e13434fe34f35087fec5df9389f908fb487bf77.nq.gz
│   ├── 1e9052954d056aafdc292fb769998165b8a0a157.nq.gz
│   ├── 2440888b5d3978bfa4bbb3c7831ea4b50ee41ccb.nq.gz
│   ├── 25369f0c318a4694f4c83986a928e0c272927342.nq.gz
│   ├── 2c8c252f38ae7994d73e92253697699a2d3b5fb8.nq.gz
│   ├── 2e0cceae8f6afad245661d2accacfcd47995f9f3.nq.gz
│   ├── 2e65969f8120cc768c75debe42d8cae9def3fa11.nq.gz
│   ├── 2fed27484e32ffb5f057112fdfbbca5184d8c61c.nq.gz
│   ├── 30ee7aa18818cd2208b336f8f019050d9e8516bb.nq.gz
│   ├── 31ed9b30bbf9e215085370197d6f44a211b85fad.nq.gz
│   ├── 37356a04820fbcc15778b577aea5ec7e4d9eeec5.nq.gz
│   ├── 378a1b8f3c4e9f1b4905bdb5c73fa39af03dbb94.nq.gz
│   ├── 3980b7f11bc35af5e0527ccbfcadbf81d66cb3ca.nq.gz
│   ├── 3a7c07e6f1cc578ad6f6e267b56242e15e2c8fa8.nq.gz
│   ├── 3ee6bc1a50ec996285ee752621a8f18954609622.nq.gz
│   ├── 401448bfa29d96cdc42c56630536ee8b66a6e32a.nq.gz
│   ├── 40b9a2abc58f04022f480552339603756cb59b98.nq.gz
│   ├── 412d8aecd86c6af272525cfe1f4f2c18c2ed25e3.nq.gz
│   ├── 42ff52e01e831e8effafced91a68f98425f58f3b.nq.gz
│   ├── 45df3365952ee98952f7f0842370a7a01fe6f78d.nq.gz
│   ├── 49ac607196829fab6f38a6d9f24eb194dc5f49f9.nq.gz
│   ├── 4a1f205d5dc9352351565e219339a0f6eccff5f5.nq.gz
│   ├── 4b7d8cbaacc6db8d68b7a406dea886e2696342a4.nq.gz
│   ├── 4d0c3e224ea65017de6a61ae721b1168e1dfefdd.nq.gz
│   ├── 51699a2033f5cc6430e69183233727630be1a1fe.nq.gz
│   ├── 531e9e20f99a09583dec1a359d14c9ff28a4f46e.nq.gz
│   ├── 5619ec2596580b24aa5ceb34016975d04b11394b.nq.gz
│   ├── 593b10eff7e377fbd4c90282f417dc435be9bd0b.nq.gz
│   ├── 59f835d981a54ee02aeeb23f81f89fe4f4bdb8b1.nq.gz
│   ├── 5a6f4c18189613b27bba7119c9dbab787dea615a.nq.gz
│   ├── 61cc61b2f3d960a3ebd3a7d46c9622b54b3c0e1d.nq.gz
│   ├── 6281646483eecd40af24b371e7e135c83f774428.nq.gz
│   ├── 636815b7b6df87ff0a08ca5f63b31991c49114e5.nq.gz
│   ├── 66d0422a1227964e867f78d635f9e1f7a858e7e8.nq.gz
│   ├── 677c1c6130ecf888ef236b4647f8b1a20a94d8e0.nq.gz
│   ├── 697bcaf277f4323f413d556216948c34be18a77f.nq.gz
│   ├── 6a62b897715328b54056c2386bb77eaebabeef95.nq.gz
│   ├── 6a7199b66cdd4b4e73ec9bb03046decd24f217e5.nq.gz
│   ├── 6ad6a2030b604b3aee14782b89d5e8422612b985.nq.gz
│   ├── 6d40cfb19492e68f4439c911d5ee0a352d2cd644.nq.gz
│   ├── 6f2134ab062c2ea1f46dd9e9c8efc74545209b9b.nq.gz
│   ├── 7202836da375f47d87d944259c099d0d8fbac1ac.nq.gz
│   ├── 781f376fe2b13b9b74e13dca815cbdcf509327bd.nq.gz
│   ├── 7923753f7549ecb66c1658f6150fa6518337a453.nq.gz
│   ├── 7b6e3206ed9ef8c0e807cfd21090842591dd2d18.nq.gz
│   ├── 7f30aa0c345840c6e75d3349058aeeb6c4d85471.nq.gz
│   ├── 82ec510e2c0c6c87d8254a15e75aaa9e252de540.nq.gz
│   ├── 8a0d12ec1ef76539b18658148af57f25b78c67f3.nq.gz
│   ├── 948447a0a9a99d86038e54c8632b125424eac72c.nq.gz
│   ├── 94f5fb1ead0c0904a6ccd49540f76b316d339a93.nq.gz
│   ├── 96f856e0634a03e64107c473c39c295e9e43997b.nq.gz
│   ├── a2ff9f792440c79566eab0b5707db356878e5778.nq.gz
│   ├── a7a0751798d2b5d62055f61e1d549ba7c7d05661.nq.gz
│   ├── a7a9076c63934ff44fd9b904e82e3093624092f3.nq.gz
│   ├── acf3b62a7b29bb7a8a4d3dad348cdeb7ee9eb136.nq.gz
│   ├── af3db7827755478fbb4feb4b4e8603990584eddb.nq.gz
│   ├── b18e37c6f0116ed4764e797ad8f84d6747aa0ef7.nq.gz
│   ├── b31af38163b63783b55f0274418b874a6abb8b97.nq.gz
│   ├── b3f521e1dd9dc46ca405daaae5ddfe971248209d.nq.gz
│   ├── b5df330cca614a8135a2790393e497417764136d.nq.gz
│   ├── b7eb84729b7a4d2d252daccf7469667deaa515ee.nq.gz
│   ├── b92b54c0c749bb3537ea3b64b766fb6ecfb13792.nq.gz
│   ├── b95fc0981ed5ed9e8d2287ef00acda7080273096.nq.gz
│   ├── b9f59952a1f8e77a264ae96bb3d413a49e9d8b13.nq.gz
│   ├── bb981d0410cad178962c20cfdbf2c81851f6e428.nq.gz
│   ├── bc65ef198d8819aa225776858ddbbdb840f6b9c8.nq.gz
│   ├── bdf878fc51de9dc1eff800b1569b4585d68cdd58.nq.gz
│   ├── be45dffa1f6a13958716d8aaa261b3379ac5ec3f.nq.gz
│   ├── c0fae056e20123028aa2b7060d0575c49f2bfa8d.nq.gz
│   ├── c4bfe00627dd3930ae66e6894e11880d8822b806.nq.gz
│   ├── cee1510d4385b510ded8a2fd106fa2d10ad4f10e.nq.gz
│   ├── cf99da2cb9b9041e39c5ffeb9aec87b741dd7f52.nq.gz
│   ├── d206ab0efa9b7d6e34bc2a5f4f2771f639401ede.nq.gz
│   ├── d72c8e8305556effd10e5386e2330be37fa465fb.nq.gz
│   ├── d76dd0ccb45b82c40b65d23cae7fdb79cec87e27.nq.gz
│   ├── da0f2e65f166fc3eb096add5e90c788189d84a4c.nq.gz
│   ├── dc05741959540080949eca862cfbba923d78054f.nq.gz
│   ├── dcfacff0140805885004fcdf0cdd3cd27bbee727.nq.gz
│   ├── dd8f844136954a32feb872793be0281097eb395f.nq.gz
│   ├── dfae1fb15f81a9fb9897835ded15a2aaa07a1421.nq.gz
│   ├── e2054c51055dc592ee2dafc04a89e58f94e3df24.nq.gz
│   ├── e26023c58585b188c86cb83f56a6c3934948a22c.nq.gz
│   ├── e32f919ab5a032cc06d2de50961a4a45b2419a22.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6ab94b650abda77fc8670fdc7a320f5983129b6.nq.gz
│   ├── e6ad312b3f2cf9771fceec7c45fa9e112f5b33eb.nq.gz
│   ├── ecde5d28a5c9a5f0de9a16bb26839df35f96bf96.nq.gz
│   ├── ee22675a79e75374b9c3872aace88f7bb1d97533.nq.gz
│   ├── f00b8ca4c512c7340af238f6aac1a65926cf01d6.nq.gz
│   ├── f0edae0247b7e8b75aa323eed9ba04b4c887e1f1.nq.gz
│   ├── f401ce997971d2752ef3bcebd42cbe8d16ba6275.nq.gz
│   ├── f5456c32b2d2971e1779c5322d16da0f1d5ed581.nq.gz
│   ├── f6099c0cbba2e5ac54cc0ea52f96039d113360ca.nq.gz
│   ├── fb092b2cfdaf1e024e065ba9d34d2ae81001e5a9.nq.gz
│   ├── fbcad968f542a2f9a58712413c498c6bf03a9f8c.nq.gz
│   └── ffd61ccee3a2a84cd96c1ed8fa5bb7cb27590066.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6dc7bce355dcecb52610e3309b8f44545104cb74.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 115 files
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

[databrickslabs/migrate](https://github.com/databrickslabs/migrate)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
