# Repolex Knowledge Graph of PrefectHQ/prefect-operator

RDF knowledge graph data for [PrefectHQ/prefect-operator](https://github.com/PrefectHQ/prefect-operator), parsed by [repolex](https://repolex.ai).

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
rlex download PrefectHQ/prefect-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a8ab74c3ff32f59605d6748829568b367cea9b71
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a8ab74c3ff32f59605d6748829568b367cea9b71
│           └── chunk-001.nq.gz
├── blob
│   ├── 014311af118a2e024381a04862fcb1c41fb3595e.nq.gz
│   ├── 02faad4d7c61d4a3d27d3edbc510f14d5b909449.nq.gz
│   ├── 0691e97330e06deebc9e8a362309221b10af1736.nq.gz
│   ├── 0897eaa372882329f64890a02862370c2ef72ee0.nq.gz
│   ├── 13a8f94ae0878916cc6817534576da2b226afe55.nq.gz
│   ├── 14ee8ae37b29cdf9cd908e8043c687bbbc04e9a6.nq.gz
│   ├── 15c11bacac55bd039e7bfbd118b33548816ebea9.nq.gz
│   ├── 194d360c96e7c76f9eda006caf994c05601a9ac5.nq.gz
│   ├── 1978155de53fe13f08a2935a54d5fee0ab27d527.nq.gz
│   ├── 1cf135252e79bcd0107d8c4390d1a38f912ac63b.nq.gz
│   ├── 1d8dce310378305a5fb1add501840aab1d7c5f0d.nq.gz
│   ├── 1dd9549b544d14b1abb83f4122abb5a3c9236fcd.nq.gz
│   ├── 209bfa638e9953c067a584a7720e1fb98f056ccf.nq.gz
│   ├── 2378005f3872d2d877fbbe5da7875d490b3425e4.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 26da0374577898996d09d2e68351b569c7fc42e4.nq.gz
│   ├── 2ba2aaeb14d02cefabcb6ba65d814edb48e6d44d.nq.gz
│   ├── 2d0a5c4c8049a48212b32f071988ad0b55070243.nq.gz
│   ├── 2e5d2211ecf7ce5199223fca02932119d985a4ad.nq.gz
│   ├── 2eb203cea8e2df87310d9de5789bad8c6392e229.nq.gz
│   ├── 2f62f44de6edf8ed56ca1775dbeed5543d4a4156.nq.gz
│   ├── 30f6b3d48365fe67156e06d5d999e02a15dcbcd8.nq.gz
│   ├── 3356c4adcbe50113cb0e89d91f6dce8a2cb1db16.nq.gz
│   ├── 37d50a54acf447373ff1b3879192f353555b80c3.nq.gz
│   ├── 397acb5b820bf5cce675ef60975633e0525bc7aa.nq.gz
│   ├── 3cd369fdabeab987be1de99faad1fe5ac23f4d1b.nq.gz
│   ├── 3e82356cb0f5b2c975536d2110ce810a07f73031.nq.gz
│   ├── 3f16d1582e77d182d32fcea5f83c00b1be96c68a.nq.gz
│   ├── 40b11b4f0a37f8127d071fe955a5d93bee45d404.nq.gz
│   ├── 412f2e531769663f9a4b5393a1eceff00156426e.nq.gz
│   ├── 415e26f8a702e092ca4fc8baffadf286d3748e17.nq.gz
│   ├── 43ba990f08cd32ff57786f123534fcf43211bf79.nq.gz
│   ├── 44142be32b21f21890c2e299849e64aebba8f1ca.nq.gz
│   ├── 448f899d1ac6843198c10a99d9f7fb624522c6f6.nq.gz
│   ├── 4495a26f4524428f52072c9111bfab0a5e716bbc.nq.gz
│   ├── 45f54e340a1fdd63c510f0066dc5557e210967b1.nq.gz
│   ├── 46009f0e7a08f4643c734cc93cfa09541999f26c.nq.gz
│   ├── 47dc3e3d863cfb5727b87d785d09abf9743c0a72.nq.gz
│   ├── 48d533ea191456c386ef17ca467390f27059b90f.nq.gz
│   ├── 4af62a8e146c62a0fc521190cf914a97e4c9ae99.nq.gz
│   ├── 4dfe454b72cf4caf65bf0dea440d7462332ee882.nq.gz
│   ├── 52ae17887ae8f6fbd094d29c7aaab460b303c6c6.nq.gz
│   ├── 558f2923ce38b16d1e12dbbc5b9a58be0e20e1f8.nq.gz
│   ├── 56678a8d1c0b73745d97deaf6b466eb1e227fa7f.nq.gz
│   ├── 57a14f55efccaa76e43525f560b239ed7c04de84.nq.gz
│   ├── 586050fe275e330810380fa550c0689c25941a76.nq.gz
│   ├── 5a0753c68be617a104e19aac7bdde4d2795c3181.nq.gz
│   ├── 5ad02da780d0c27f46a8e06175c62687bd5d94e6.nq.gz
│   ├── 5b2a9e4546e4e4587cd783a14fa9fc8f9936a8cf.nq.gz
│   ├── 5b9052bb86c025195a2a2bb4dec5e7034ab0ca50.nq.gz
│   ├── 6510b3840c29b8ed469f3510daba0fffd320cb1a.nq.gz
│   ├── 6605c561ba2d643b4751c31f29ce709996930608.nq.gz
│   ├── 6b15af31a60f67fbf796f0d1140aaed39c896181.nq.gz
│   ├── 6b29295b89a6024d58296c526ca24bf9a008fb92.nq.gz
│   ├── 6c77026a0d114d59f708bff01ba3bdef862860f6.nq.gz
│   ├── 6c8be8073074e30747531551c3ef617381fa0f18.nq.gz
│   ├── 6df8dcaee276081951a6e7bcde5c47922c70d88e.nq.gz
│   ├── 73c4e22275ac9646c340a777638ed773d0cf3018.nq.gz
│   ├── 7492045e889497d2717736c66b03982697d0f64d.nq.gz
│   ├── 76e7689fcaf95f358d9f49d2f30d5a49c2a87426.nq.gz
│   ├── 77378f21714385612c0f3100a926b5d4710b3780.nq.gz
│   ├── 792e71d3341451487e1bbda7bc16675ba0d60bfb.nq.gz
│   ├── 7992b42bbdf7f649839a3138f45283b5ced87a99.nq.gz
│   ├── 7af24f1267371fdc6537c12489958bbce5956fd6.nq.gz
│   ├── 7c1e6ac09085217e5e39d60be406d17093837c8f.nq.gz
│   ├── 7dc7334abe5ce22ac98ae0f3633463d67af2979b.nq.gz
│   ├── 7e14fee95f77e63d975f9a80b57f93a78b1b9056.nq.gz
│   ├── 7f3f79616b885fd670e8564571268bcbd49b88fc.nq.gz
│   ├── 802a504318cd9f06292b9c72202ad33c52460e1e.nq.gz
│   ├── 806462b9c4f1f36f023fdfb79264c52bcb66de34.nq.gz
│   ├── 812d6c1832eac3130017d7abf508d74cec22a659.nq.gz
│   ├── 8236e58073398ec37f4db81ad0f5f119ff04de59.nq.gz
│   ├── 839d1afab6cb8f4222a6938fb8a7c576a5f8c367.nq.gz
│   ├── 8448ca9a7c8c820ce7389eef41a4007187dbc0ec.nq.gz
│   ├── 847bc9652ab2c56b5d7c18b1a57f5c25532e8857.nq.gz
│   ├── 8683b4a1cbdccfcf4b4334026988bb9534132624.nq.gz
│   ├── 87da08a60dbaa261c7cdea05ee196765d9defca6.nq.gz
│   ├── 8a6876fa18f6caa53d6f864c6889c928014e53e6.nq.gz
│   ├── 8a92b522b07f83962a08ad7e342f212305c83e2e.nq.gz
│   ├── 8cd7598dd3ba6c742d1479444a3fd8e158bef08e.nq.gz
│   ├── 90a43d19a80f83b7fe944afd92e11c853b50c0c2.nq.gz
│   ├── 91e173310f4cbc9d5f675c4c8fc040b9f4b5dc82.nq.gz
│   ├── 92fc1b75b557eb1c5778ead5a4672d3124b32c7f.nq.gz
│   ├── 981b85588eb39c5cf29d7cceb4509939f364b33b.nq.gz
│   ├── 989d5d6932a3588c280ba58742dbc18a46e12cc4.nq.gz
│   ├── 98d86ea018fb8dccf5ae12f7520971483a18c0f4.nq.gz
│   ├── 995df246b3e0459b217a2c90975f57ae01b6f42a.nq.gz
│   ├── 9cb8730325e1cbbc2969c3a0a3892749bef2e32d.nq.gz
│   ├── 9cb8d7714c5bf384e76307399b9df81e5883a2f9.nq.gz
│   ├── a0b12164e67d602f6bcdcd372576fff33d0bfc48.nq.gz
│   ├── a194ddf58c675d629f8373ddb0e8b5c53860aee4.nq.gz
│   ├── a3069da46a8b1768267f4c1a20e415b894f4a827.nq.gz
│   ├── a3103d55ff7fdabb44ac08eedd93152a085d1583.nq.gz
│   ├── a349ff8846f57bd639dac17e5e38b13a661ed3a2.nq.gz
│   ├── a3aab7af70cd8a107975af478bf654d0ca540384.nq.gz
│   ├── a55dd384b902ce1b880ed23909d21b730d8afe95.nq.gz
│   ├── a9ae5fb91da58f20241c8f0fc6e52e1e34fc01e7.nq.gz
│   ├── aa5c61d0a824ecd72f2b7991f7bc7971cd64267a.nq.gz
│   ├── aa870b2ff2d2fd101061597781a0c8f2dc1137a5.nq.gz
│   ├── aa954ca7a839157be96ce1758bdefc16f644de4f.nq.gz
│   ├── aab65ab098dc09f624ef1fc69a1eaf0cde531867.nq.gz
│   ├── ab8368453b4964af55e6c82594bc2a4276a9d547.nq.gz
│   ├── b2412aa179b268c7c5cac6e2c2440e3079c171da.nq.gz
│   ├── b4e97fec2aeedaffa5b951393f0cb2fe92438868.nq.gz
│   ├── b6e8a5e38b5f998387e892900357c3c06f7c440b.nq.gz
│   ├── b902c02791e1924400e71cacc2f01d126259e9b2.nq.gz
│   ├── b93697f17c61a42a1992c1da1bfad263812ebb5b.nq.gz
│   ├── bc581021022f1888cd56c551cf0ea4a7d8bd4a4f.nq.gz
│   ├── bd5ca7bbf7dcb32a2ccba67dfb626b2ddbcdf979.nq.gz
│   ├── bf6ab01a7105eddb574aa71cee2f99d0276d042a.nq.gz
│   ├── c04a7259b8b0eed7f0bc9e44f956e3992f83f2c7.nq.gz
│   ├── c2e19e5954ffab56c7f15d8ccef72aea9776f45f.nq.gz
│   ├── c75b28c94b65aaf1cc2512072369d2ff3a44d6b3.nq.gz
│   ├── c87a3b6edc685596d79e06bcde6e66a73e8ffe6c.nq.gz
│   ├── cabae06c19f32c45c2cd892613270d53ba85844a.nq.gz
│   ├── cb77613a8b7542695cbbaeb6ae1d601f5fe0f8d3.nq.gz
│   ├── d18d3d3ea4d9ca727ac0a98244b0798ea70f56d8.nq.gz
│   ├── d32e9fe94000205afb28b82b04181ea212331d64.nq.gz
│   ├── d3f1f33ccb3df7c2fc6d64815c8d3bda8ffa0842.nq.gz
│   ├── d5f31cd6c86ea22de0dd4aec07a0d7bf05c921d1.nq.gz
│   ├── d9ca18e7711828ef1bd503faa0fd1e584ef479eb.nq.gz
│   ├── da1ba693cbf8570c221d83be21cbdeb88bd99293.nq.gz
│   ├── dbafe63802a313aed6956b5ef54219c57f66997a.nq.gz
│   ├── de4418a2ad6427cd865ca0be2209fe0f3cc88606.nq.gz
│   ├── ded6939fe536afd5a37b5af7bde4b424c9cdbc18.nq.gz
│   ├── e0023959ba4e136ecdb8d5c786e61d51f29e76c9.nq.gz
│   ├── e3a27c59847b2703d9900702971ac26119bec866.nq.gz
│   ├── e408a0ebd35d3672db96a14fc77890256d98a1c5.nq.gz
│   ├── e4ca26053f126e2a3fd815544d57a5257d269347.nq.gz
│   ├── e5e217d26210bece3f97579f3e18690c319b2a49.nq.gz
│   ├── e6d33d79d0371e545f26c05a5ca2e0fc89c77cab.nq.gz
│   ├── e803840bc4636605f0a333aabb401c4a06a5af20.nq.gz
│   ├── eaae597ed4bcd044951d984c5681908c1bcde53a.nq.gz
│   ├── eb78c1dd0197693e6ba416a610499465d965a186.nq.gz
│   ├── eddd674c34720f7b13675dca7fea385ca66e9d41.nq.gz
│   ├── eecf880b7fd3dea3b3fcacc99585679e4a0e0200.nq.gz
│   ├── f0c13194444163d1cba5c67d9e79231a62bc8f44.nq.gz
│   ├── f2f796bf9955d8a918f782658a05f63fdbe6ce16.nq.gz
│   ├── f32d2038c15556ca021e2ceeaffd97086d364022.nq.gz
│   ├── f376b7143f2539fe5df7a6d33a0af7854ffd94aa.nq.gz
│   ├── f4d2e1ce923ca35c942d0f65d180ec2b80965d7f.nq.gz
│   ├── f66d5bd8fe864f976fe227c22cfe7f978af08b58.nq.gz
│   ├── f7b895eda9186d1df9be951ce840ccb8419328e0.nq.gz
│   ├── f83b344b0318cfc9377d99adf96d99f832eff698.nq.gz
│   ├── faf3cda97b2314a85b785201d6f31cc6187265f9.nq.gz
│   ├── fd21509a31b7e1a5cec817425e1bbfcc1f738a9e.nq.gz
│   └── ff6068643f3b83e5cac28af216d0be8ad3429075.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a8ab74c3ff32f59605d6748829568b367cea9b71.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 155 files
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

[PrefectHQ/prefect-operator](https://github.com/PrefectHQ/prefect-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
