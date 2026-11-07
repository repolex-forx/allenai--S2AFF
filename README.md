# Repolex Knowledge Graph of allenai/S2AFF

RDF knowledge graph data for [allenai/S2AFF](https://github.com/allenai/S2AFF), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/S2AFF
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 87dce9fdcb1cf2ec7dfc28559c823eca70e5b39a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 87dce9fdcb1cf2ec7dfc28559c823eca70e5b39a
│           └── chunk-001.nq.gz
├── blob
│   ├── 016a86dab0b3db6c6c0f95d817c72781ff8c4d8f.nq.gz
│   ├── 02199f6427e207fc0e65700e68bcbbe669b47f21.nq.gz
│   ├── 03ef9fdcca90a269bdec4d0aff2663f8046c3ca0.nq.gz
│   ├── 06ddba6394e5611dc22358c8ca25a686a992edd6.nq.gz
│   ├── 0d589d3e6b059d530b807c2359bc3a65672f1e9c.nq.gz
│   ├── 0e7fe4f6712694c167c2144da7e19af770da9b57.nq.gz
│   ├── 183c7d095f83df3cf49fc8e75fcab9040109c061.nq.gz
│   ├── 231698a51a729b6d8c3751a21c3045909c8fee40.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 28ce36e1da142b5c95e57fd6e0baba3eb8b8dd08.nq.gz
│   ├── 29376fcc2c00693658d957bb43a0b519b5275598.nq.gz
│   ├── 2dcdc8cf804433a985263ec18abd513cf6030368.nq.gz
│   ├── 2dd2804664ed047909dbb7ddb2b0ba08b4a42c64.nq.gz
│   ├── 3101c761b4df13c0726797e71ec0beb38f5811ca.nq.gz
│   ├── 38cd63b1f41fc7ba5350383b142d2bae6afa263a.nq.gz
│   ├── 39d7291a002b65238d0fa793894c51e8c26e105d.nq.gz
│   ├── 3bf8b517c42593b139af55b54611684b12190816.nq.gz
│   ├── 4258204262567d8ab8933a1a841fc799520f2503.nq.gz
│   ├── 500140693ab83931ba717618efe7ab8b049f8a69.nq.gz
│   ├── 504390a5f12205d94b6222f0df8ac7f92ae6eb64.nq.gz
│   ├── 50f7dd97d77d1a4410fa43d7b74407dbbee4ba9f.nq.gz
│   ├── 523d4898e815eaff4d5a0b16eefb5a0a6835b0bf.nq.gz
│   ├── 5a16ecbf33d18147a37351d5913af6acdf226b25.nq.gz
│   ├── 5f5ce24111ca89a7eb74e1c11e729e168a4bebe8.nq.gz
│   ├── 60e1bac56652435a0aeee716132c25a94d364530.nq.gz
│   ├── 67d4281a794871d3ff6639d9147aaa4cba1c9031.nq.gz
│   ├── 6942dee6642f944a94041551dbb9f4f611ce23ea.nq.gz
│   ├── 6a532316295377d0b586b022701e5207ded42e3d.nq.gz
│   ├── 701e85cda82a0fc93ba1c348ed8039cda282ede7.nq.gz
│   ├── 79bdbc9bc4fba7da786592e52cd0d0bc3ac9e6cd.nq.gz
│   ├── 7eedfa48a6af3c340031b51087f18f0a07b8ae4a.nq.gz
│   ├── 805a8654e95d2d90af95f6789bf2538eb7efeecd.nq.gz
│   ├── 8160decf00b946a2984c053fba5f99d8b99b664d.nq.gz
│   ├── 85166e395bd2cc2778c2f55428f74731abe44bcd.nq.gz
│   ├── 8719fc2e6c2191462745ec072a996c13fe6fe6c8.nq.gz
│   ├── 970530cabee030d153edb152241471c59b8c67ff.nq.gz
│   ├── 9e5a73d1be4a486d6e543a187769c4d65e2747c3.nq.gz
│   ├── 9e865795859258446cb0542e3c82eeb18a0169e0.nq.gz
│   ├── a0b24d67992dcf9b5ead3a9933d83bae2126d9bc.nq.gz
│   ├── a38395e5fbc6a7a35931c2c9e5388545fcd8b303.nq.gz
│   ├── a4661995d980508598e4af96080850fcd905bd1a.nq.gz
│   ├── a69d4377532075c06841913e8425882a768b3867.nq.gz
│   ├── ace835f193811299dcf0831fc269f88f02f77c76.nq.gz
│   ├── afbcea955d13c5deacf78db0ec4b4a71ac9f9a9b.nq.gz
│   ├── b5a9c336e56e85fd8aba8f4988926c8d4bf1e929.nq.gz
│   ├── ba64bcf392f2923d62ecbb0561b9034f4d31b15c.nq.gz
│   ├── c4205dbba295a6511c0a2b0aee44cf7e0cfab2d6.nq.gz
│   ├── c5182076497101184cf62d10e4ad044803ebf483.nq.gz
│   ├── cb44f1a55a89d9152d00b918997e92b4b7965011.nq.gz
│   ├── cf0f1841b0c32895582025ab7ab67ff48752fc1c.nq.gz
│   ├── cf3f515306478e2f1feb61b4cbf18f0ee41d8605.nq.gz
│   ├── cfcf475c44a967d13bc57c3ba3b67680f65269bd.nq.gz
│   ├── dabd8fbb691b7425fc7c9558008b76651693d6e1.nq.gz
│   ├── dc49602b88eafe034105559eb5513c998ee77eb0.nq.gz
│   ├── dd0882a73f6f875a391d954c9ac360e4f55cf74d.nq.gz
│   ├── e2c291fad7a7e0ec1191ded9316a3c55785190d9.nq.gz
│   ├── e2e32bd106096c4f3b8a8fa052577ca6b9a6c075.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e888d06d2a7601bac2fae37a0bdca16120e0229f.nq.gz
│   ├── e94c8ad6353ebb3afed71840b352f9bdef0fd8a0.nq.gz
│   ├── ea482b921d8fb4e68981dcf41abff65c00c4d796.nq.gz
│   ├── ea664b576b6b17e987fbf095577e29feb1b7328f.nq.gz
│   └── f08711d423bc678c586cf0b721ea8435de5682ef.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 87dce9fdcb1cf2ec7dfc28559c823eca70e5b39a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 71 files
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

[allenai/S2AFF](https://github.com/allenai/S2AFF)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
