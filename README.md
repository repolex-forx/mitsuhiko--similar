# Repolex Knowledge Graph of mitsuhiko/similar

RDF knowledge graph data for [mitsuhiko/similar](https://github.com/mitsuhiko/similar), parsed by [repolex](https://repolex.ai).

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
rlex download mitsuhiko/similar
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 96993d92851eff9a484ea157614de30f80dfdc73
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 96993d92851eff9a484ea157614de30f80dfdc73
│           └── chunk-001.nq.gz
├── blob
│   ├── 028bd3282bc504e17b5a33f69e56de5f5b72084f.nq.gz
│   ├── 040fe978be780b0e31b085b952732ecbae1fdb38.nq.gz
│   ├── 051c596598c0d938dd92ca17e7ef12996dcaa1bf.nq.gz
│   ├── 08200f8b7d3d0dba5358ec3447763021426d7246.nq.gz
│   ├── 08c258f590cfc5edcd0ef0b104c1bf21d5bbed33.nq.gz
│   ├── 10ed169c3dd4cd6674b4373296f18834017a16ae.nq.gz
│   ├── 13013267b76702425bd5d49431258ee86c33f84a.nq.gz
│   ├── 13418a6f403f5469cc106c51986f20582d1e75a4.nq.gz
│   ├── 1590316915a92ca16d485e2685a4ce7d51075679.nq.gz
│   ├── 15a0a132d60a81862176950879c8e4d4081dc8fd.nq.gz
│   ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
│   ├── 1a90327ec5293321b92e632abfa094bb0c20d3c5.nq.gz
│   ├── 21334601e14f3229b1d85b7f9091213371b425ee.nq.gz
│   ├── 2197a59d47c28e6f8b839d38fa9321dddac3161c.nq.gz
│   ├── 22bcc6cb31814cb2bc4115aaa6d0ea40579ba308.nq.gz
│   ├── 23d11f2d3b412cd90b67efb3d935ed262611aca8.nq.gz
│   ├── 298a505a4e862aff931e6c9e05c75bd086979314.nq.gz
│   ├── 2c976c4e634040c0aad144418604bd9c0cc61d60.nq.gz
│   ├── 2fab1c294511308425372bc0c68288f5e0b2e39e.nq.gz
│   ├── 3389ed79e0a89f98103be07654be78397834abb7.nq.gz
│   ├── 38cca884e999231451f418ccfcee5900da00cdff.nq.gz
│   ├── 38f537b7b41c8939680ba03cc3b5a012e15ac2c1.nq.gz
│   ├── 3d8eb9c9107ccd59bd2e58aebf7a943e073346a3.nq.gz
│   ├── 3ebd78a11c126e4e3d2b1ebfe7352a4b53f46311.nq.gz
│   ├── 407f4157b0bb73d897abbf75c2527325934e42fc.nq.gz
│   ├── 428ed2278a7bdab37c7c393d9c733fe1ce945cc3.nq.gz
│   ├── 432916d5eee717b569c13137579c4015f9350cab.nq.gz
│   ├── 44ab829aaf7af902e762873b982bd881739020e3.nq.gz
│   ├── 45bbd4641c80db2d542eedbac94a1978a7b9377b.nq.gz
│   ├── 465a6c20d71d952cdb9a0b16c67ef402d0d16a45.nq.gz
│   ├── 469a1fc8124586531af42ff46d32784f290f297f.nq.gz
│   ├── 4972822f1346b3c87586de1f781fc489ba830f74.nq.gz
│   ├── 4b898a64679b264e4f28d3043c5ff3e044520e7d.nq.gz
│   ├── 4b9511b414288cdd1d2b34306396c51965675d67.nq.gz
│   ├── 4bb626dc26fcfe2cd345c865baef817cc5fea0ce.nq.gz
│   ├── 4d88801a15b0a7ee24ca6ce942de028de066b082.nq.gz
│   ├── 5345b0b9aef35897d977651dbb3e5bfba1fd4d64.nq.gz
│   ├── 5b4bd8291c9fc4d9fb1c22d51a4f22fc6101d026.nq.gz
│   ├── 5b735ef1dde1798d7b3db73e893b74de52925771.nq.gz
│   ├── 61a73eb094d72776420562fb9e78ec4222a0425b.nq.gz
│   ├── 639a8d3b1c55cc26a1150d28af8e629d2f1b08e7.nq.gz
│   ├── 6a75f261b174445965d815444121c35884117115.nq.gz
│   ├── 701106701293c99ef755b1e24374b63e4ae6cc1d.nq.gz
│   ├── 71a35abadef2d708274952e92546f457dc89cdd2.nq.gz
│   ├── 7354123a9a8e9a5902325a7930671b08c8995606.nq.gz
│   ├── 757cc4f70757fbb56e4491957231e944743d4780.nq.gz
│   ├── 77e5afa6da6d5dc42d24b00c0019a07e2361a510.nq.gz
│   ├── 77f409a69cf586352d7a74630634a8c1102069e7.nq.gz
│   ├── 796bcfe26ef9f4431f8c7e3ebfc93696090fbf95.nq.gz
│   ├── 7b47c03aec3ae9ed7e0bc814803e218608f37c8f.nq.gz
│   ├── 7d588a2125788e1f7e04ff088028a519c9a165da.nq.gz
│   ├── 7fd217d3e61ac3000fb3fc82fcff72a2cde9ac28.nq.gz
│   ├── 81236f29a597c4c32cd3e8290b761ee79f010aa5.nq.gz
│   ├── 832362406cd9a09215646b016b02beefb2146b0f.nq.gz
│   ├── 84d9c2008adc5d307998d25e43dbbee057f26dba.nq.gz
│   ├── 8903c140694cb9059106a75ce9d951614c7194f6.nq.gz
│   ├── 8b02419c5d63ec195b9db2125749cfca6b582af2.nq.gz
│   ├── 8fea9d9af1832bc0f734733c8832181a2bdab4f3.nq.gz
│   ├── 9030adb895ff1d55ccce6467b5a95e120b658716.nq.gz
│   ├── 90b97a994b968a67c3896c7443556fe951ea1368.nq.gz
│   ├── 9232c8d261fff3c21a1d37e04fe4cd8b1e038fe7.nq.gz
│   ├── 98a58183552f3449b880a367634a505374d8b20e.nq.gz
│   ├── 9a5d92221b0a57d432054823495047c7608c4ff5.nq.gz
│   ├── 9ed25ae4c49e268f1a856b56dc646928c094dc49.nq.gz
│   ├── a14aa48bc1238fc1862acb7e3235810c08860805.nq.gz
│   ├── a21ec8c9d47ff1d5dbfde8da3382996fdd5703d3.nq.gz
│   ├── a3915a84e2d3fc4bfbd58b511a855037f1e03ab7.nq.gz
│   ├── a3fb829e91d8b1ae371eabc3efe4782f545d46eb.nq.gz
│   ├── a4a19e36262fc20edce8a96140862215736c1569.nq.gz
│   ├── a67027e19f9d8d0f38f1d41f82c53bb00fb036e0.nq.gz
│   ├── a74fe941bb0103d1906f0ba2fdd93790010d1a2a.nq.gz
│   ├── a8ae335a2157465fd266d06d9a83bcc7b6c7a5e5.nq.gz
│   ├── a9682d90c792855c47d83c13e8a65fb97bccd700.nq.gz
│   ├── aa3556d40f43816234083ddc18d81c37f80d6677.nq.gz
│   ├── af5b027cbe1401ba6ff808df2c79540e04a7417e.nq.gz
│   ├── b18177949f0fc5599b095439a4e54de8e3141db2.nq.gz
│   ├── b32f29ac7bc0522839906cda83730797931a8ee9.nq.gz
│   ├── b50f26b111d9c2d3838b3a0086ce811259d72dcc.nq.gz
│   ├── b952ef1ca1de5af8f2f2600b200a9f51782912f3.nq.gz
│   ├── bfa537cb5ecc0f62bf857e5942587d67b4e03d6d.nq.gz
│   ├── c3f9e2bd7cb3a359f5e697a8f32bd0d94f89667f.nq.gz
│   ├── c66450c4ef20c031e359b50a63dc18d148186a5d.nq.gz
│   ├── c855308d9b02c0d405274102aa79c76e2c6595a6.nq.gz
│   ├── c9b64c539f029ce00c31cf8a57618afc3ee64540.nq.gz
│   ├── cce4066edcefbc56172fc4bdc82db001c55cea42.nq.gz
│   ├── cdb09028d04c0ab059837a35e2fec30f0a5c9b54.nq.gz
│   ├── d0046498817404287555e2c09740fa8b3e037333.nq.gz
│   ├── d181b2828afcac1d5811a81c3d6ec924ceec3ef6.nq.gz
│   ├── d2e6eaa4deb9c1b9a92dbc2e41e8231a4490266e.nq.gz
│   ├── d43706ded0b07abf2ce73fb23873363e6f65e009.nq.gz
│   ├── d6ece59eccb2a7749cfbdb7fcf3a4bbc600aa186.nq.gz
│   ├── d9fe981d37373b30438087b5811e3cc12e30a73d.nq.gz
│   ├── da88b76aca66b558352f9a034b3796ff3dd1d175.nq.gz
│   ├── dd9745a7ee08ee288e1279648c16844df41baa54.nq.gz
│   ├── e3cc9553f42a5728234a7cbf81a2a9a31ab6ae6a.nq.gz
│   ├── ebe283a0308ccf9128936cfec1efd742b1aa056e.nq.gz
│   ├── ef8b611bbf4bdeb2b14ef4a1112e5ed8bbe8140f.nq.gz
│   ├── f18725919e04dcb6e41b129dbe754ad8d912218b.nq.gz
│   ├── f8651d1b5a54bdfd9852f57f4c12159c7a01be29.nq.gz
│   ├── f972cca8ac868408590c010fabf88c56ac85ef2c.nq.gz
│   ├── fbea3c2bf51a9dd15464ea83694e26b8c545798b.nq.gz
│   └── fd4abccc60433f59c5ce324cfb1ccf8b0f99ac08.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 96993d92851eff9a484ea157614de30f80dfdc73.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 110 files
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

[mitsuhiko/similar](https://github.com/mitsuhiko/similar)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
