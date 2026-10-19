# Repolex Knowledge Graph of petl-developers/petl

RDF knowledge graph data for [petl-developers/petl](https://github.com/petl-developers/petl), parsed by [repolex](https://repolex.ai).

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
rlex download petl-developers/petl
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1b9af0030e9563089f2519ef427effecd2d55a9b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1b9af0030e9563089f2519ef427effecd2d55a9b
│           └── chunk-001.nq.gz
└── blob
    ├── 01117ff29d97178ae5be2a7e9b1bdfe8b31986bd.nq.gz
    ├── 029723e486037bc00c73cb8c8720e06610b8defc.nq.gz
    ├── 02cb04f8c840d1e86e8910a79cba3f0b49143a48.nq.gz
    ├── 042639186330162f433a5ffa34b7acb5fbd907ad.nq.gz
    ├── 04a24093bde6f2fe19a48ec6bce93b6181c884e2.nq.gz
    ├── 04e4d9a1892769385baeb769d18d8fc12346d171.nq.gz
    ├── 06002d21e524ddd8b9f36d7c859e440c2bd5afde.nq.gz
    ├── 063f2cf4711e1961671ec19b580b72cae87046e4.nq.gz
    ├── 072b6416ee5a2800c8605f6e79f45e3d13c35407.nq.gz
    ├── 07cba9bfba36c6133b0ea9fcc40ce7b40463c27d.nq.gz
    ├── 09e9c88b091169bdeebc31865f65dd9c3ace02b8.nq.gz
    ├── 0a0656364c48a408785d766838e62e6f9e48eac4.nq.gz
    ├── 0ad1cedb1525300e1f3b8594c627cb4c7362ec93.nq.gz
    ├── 0ba94e70a59e174114fbbcc01d3dd00d64f47efc.nq.gz
    ├── 0dc48a8dc6204a47cb5c904b3ee6438fc8e10df5.nq.gz
    ├── 0f0f5da5660b47fffe0965b05530dd2611dbf1f3.nq.gz
    ├── 105dea8d2dfb0cfe4e19b0840db350d97042d7d9.nq.gz
    ├── 109b962144f2eb41769a1e414d09842768cf4783.nq.gz
    ├── 118ca0a2c58714ba914fb2a53a65ce4c79b501bc.nq.gz
    ├── 12fee4787ba3be61db9a78ef3f40a361f479f0af.nq.gz
    ├── 140fdbe08a2d383cc141686afbad43af818b9238.nq.gz
    ├── 14e8c444b4c1f410e6cb0bd9a3bef184447fa63c.nq.gz
    ├── 151fe3afbbdf7e8f1c9edfb1a3c72f0e821bc363.nq.gz
    ├── 1591c1789b15a3044a90db7148a26a5b84bc8672.nq.gz
    ├── 1b4909f5ecb8d87cb90360cabb60ce66993ac1d4.nq.gz
    ├── 1bd36535b4801163d4b552658f17942545c5eb29.nq.gz
    ├── 1c089fd7cc8ce58f4ddcfab4a5a1ae3101ed7b46.nq.gz
    ├── 211b8d3dcb12f29cc3e490716f2a4027186aa25d.nq.gz
    ├── 2133883b81d5e8f31736c596eb54b4db3b15a098.nq.gz
    ├── 21b0a6a04066aeba4d4a5bb988058d8a36f7da8e.nq.gz
    ├── 21fea19bf4954f044fcbe9aec44cea87db9e4fe3.nq.gz
    ├── 224fbbc6c81b25409ed6a762b7bbb40a1bda9274.nq.gz
    ├── 230a51f55bba21129b9a80b91e69e7ae841cfcb9.nq.gz
    ├── 23dbf1b9b97b29e0ce8189ab307fbce92f9b8893.nq.gz
    ├── 25186a98f9df6221f7c8ebe041cd947107f2cd4c.nq.gz
    ├── 256def62326eb1fb89b7915f71ba3504380f9c79.nq.gz
    ├── 25f0ba978a512bdb38eee6d9224db1e094c1fd36.nq.gz
    ├── 261a742362970da6efbccd2780e4cd6889e04cc5.nq.gz
    ├── 262ca92d023cc120865e6f9f04dc037e554d1a93.nq.gz
    ├── 281cf3e8df19f1f68c2300809f147240f3c0c1aa.nq.gz
    ├── 284b2d27032bee13670b314edad7e0da4d8fba3b.nq.gz
    ├── 29f9f3ae4dbca8e1082bc9e15c192f46c858dece.nq.gz
    ├── 2a043565b2e4d11425eb9db2eeb2a7b978d5405e.nq.gz
    ├── 2c27cab953e860c4a438aebdce275087c6b891bb.nq.gz
    ├── 2cec7e2fbf27c0957e794aea90f77e915cc4ff2c.nq.gz
    ├── 2ef84605e9fe0d7bfd13cfa02a2aa938db1518b1.nq.gz
    ├── 30141f5840effc2ed4a455515d8fb17539a9dc54.nq.gz
    ├── 30c8e80778c83f254e6303e416f5996233da8576.nq.gz
    ├── 3107b5d31c4812bbc13475fa6bc2bd9aa1060fd1.nq.gz
    ├── 317183c940d45d85560a557303074232b4c8c0c0.nq.gz
    ├── 31ecb054130f850e9b64b57a4e706f7a8f384676.nq.gz
    ├── 3278aab42dd417bd308fe022b4cec112f9581d74.nq.gz
    ├── 32c6f132d994984216960967d43c66a3ee9a4ab4.nq.gz
    ├── 36ac63443269f5ce11e1e7b9ec4c8ce122fc9349.nq.gz
    ├── 384ec7c70ed21547c63b57cee4a5a69128a964de.nq.gz
    ├── 3870ae1f0f0e07ae7270cb083b2a191aa4539f08.nq.gz
    ├── 387f7dea2202a6134a1e55827cf60ed3fc840b86.nq.gz
    ├── 388349f0a312f68c1785456c35129ec88e1d5e03.nq.gz
    ├── 3a44e2241dd65b2c558f51da8f63dedbad4a1db5.nq.gz
    ├── 3c7ce9c74ffd2db7c28ccb6d1755ecdf162d88c7.nq.gz
    ├── 3dea3a5cad4705c057749b79164ad35c9d189217.nq.gz
    ├── 3e298201423d2fd7b50636a45807a4eaff84de17.nq.gz
    ├── 3e6e089e226d93689c9cb8ec209c0f49d9421135.nq.gz
    ├── 40a9610c7159e0700ee0a864e4005a5e830c2d8e.nq.gz
    ├── 43b1e6126441aebd9e2d6d7f3ee69568b762c2f5.nq.gz
    ├── 440f9003e8cf60f76514de9617c16fd9d62b713b.nq.gz
    ├── 47a673ef77c7a90b6abcbbb14af9dc45247a476b.nq.gz
    ├── 47da046c9c8b52444aa9b89a5d1ccf62a1f30c88.nq.gz
    ├── 4815a15bb277f9af45325f3100d8cdebcf040444.nq.gz
    ├── 4835ced8ce13bfe28c274f6998bd6cbdcc5d2c1b.nq.gz
    ├── 4a94ff7534d6ef3e8cca5eb4ea3c240482d7b8f0.nq.gz
    ├── 4b612160bd55775396912a2cba725b0ac3960afe.nq.gz
    ├── 4bfd2219dee1f726f29ab33d92d3ae344ce69e6f.nq.gz
    ├── 4cbf2296128aaca67fb094bedc47299dc1206efa.nq.gz
    ├── 4eaaf53ebcece5bec48ff252cff25d57187b11a8.nq.gz
    ├── 4f4cad8993a085c23d05aa0c0eebe740f99d7d1e.nq.gz
    ├── 50c855f4d733b090d8cb2b7f15729ee76fde5c4d.nq.gz
    ├── 51082d0c416e2177eed264624b37e26d6f309910.nq.gz
    ├── 513b781ff834a9f49bfa71ec598d76ddf9b8f9e1.nq.gz
    ├── 538f58892885944e328997417e9af28d11958085.nq.gz
    ├── 53fe1ac4139abd3d3da6d153b5acb8803ec25aef.nq.gz
    ├── 54aaa47f9ae3f722c11c00d474ec4b6d603e5302.nq.gz
    ├── 5549795f11dcd1d44977221ae0712e2266ec9df2.nq.gz
    ├── 557afd5026aa3f78f03d7631c7e327fcb74907b1.nq.gz
    ├── 560c96c68d000a08a4c84d3b2e75c9bc4229911e.nq.gz
    ├── 56502a06f95beeed1bc1cb2ebfdcae9ed8ebbab3.nq.gz
    ├── 594a9ad39d3e8a6f114cd8e329dcf4affdadc8e5.nq.gz
    ├── 5a02c1f8660f5234310a7bc79240d602d1eda3ff.nq.gz
    ├── 5ba9551f59c5c5efda7a6a4f388185e961ebd4cb.nq.gz
    ├── 5db34b30e8a3333ae1e14e86b2368166e1cbe9c0.nq.gz
    ├── 5de74c11d0f39b86fcb8a72ad395d5b87e103c1a.nq.gz
    ├── 5e2701cc6a16c573b1776354aad8528dcc6f1db6.nq.gz
    ├── 62136cbc40c92984d7793faaab2288c892a4dca8.nq.gz
    ├── 6418dcf59a857d90144d06c443edf0f471bd32de.nq.gz
    ├── 65035416fb403e64d6a30c0cb9016e3aa73dd7b5.nq.gz
    ├── 659d6ffa1499365244e60463597f13e61084341a.nq.gz
    ├── 6721a854623da6cbd62c63d9331ea27190207e48.nq.gz
    ├── 67448f5bd0e54b97b2f4caab51ccc56334da7293.nq.gz
    ├── 678ae5c4c83dc8f59ef509d6ff4d1d37b15c1b32.nq.gz
    ├── 67ff17b93784c1b5c6e143ea0d99473f5c962333.nq.gz
    ├── 68b6c37b8cc65e5f1c21e1c18972b71d6dfbcd22.nq.gz
    ├── 6d7f5f3dfbba648fd37ab7ddf7798d2c38153308.nq.gz
    ├── 6eb4cc8db0ad0d56ed4ed671208f8bea4ae67bc5.nq.gz
    ├── 70d921300f39679a8c26880376dae797d5fe5dfd.nq.gz
    ├── 715630e6fcd7353eb90539091718c6b63d3f5eb1.nq.gz
    ├── 72e08594c577bc38b36893935227b2636b84e877.nq.gz
    ├── 73fd09b5a8cc8264d290997d67c736c3a31ac0d9.nq.gz
    ├── 7485abf9c20bd26bfb37b8bf08dfe9193af8c7a1.nq.gz
    ├── 7507ce723cb64a68ce061564dbfbdaf74bdc271a.nq.gz
    ├── 7553e095664ff0cb509b35273b8bf8921bbe98b3.nq.gz
    ├── 77489dac376dedc76c5b4b51efb42fe92de9c011.nq.gz
    ├── 783cc03b8e6eb0a71997feb0cdfc0ca0c8c2d948.nq.gz
    ├── 7a97a90e2c1c9f6c015171fd3fee3d87088e09ee.nq.gz
    ├── 7c4f42083aec7bf7156ae4ad20cec036d987697d.nq.gz
    ├── 7c82bf81c7482aeb3a0b269c813c7e30320d03fb.nq.gz
    ├── 7d6db41da36ee69fd3076022cfa1889ff35a7107.nq.gz
    ├── 7d722f790ff3b4e3d5a9f724bb5b00bc1b1c9d8c.nq.gz
    ├── 80b609a0ffb459ed9bbc11908600e674424e4d99.nq.gz
    ├── 81bdf4c2b5af5f38ce19def376fb089bf22571ff.nq.gz
    ├── 81fc646ad0142e78f3dcdcae2dd9495f98242450.nq.gz
    ├── 8376c3c21b15afe35b0d3b30f444a17f485bbd47.nq.gz
    ├── 838c827b48d5de15f849f14476d77be514b76474.nq.gz
    ├── 8451f1f8f1d7e1979ade3c3f6a2ef40b11791df0.nq.gz
    ├── 84d275263799bf611da836d395dfb0073ac24485.nq.gz
    ├── 880b8d0fe1c2a5cecbf9f1879af9f54804d17f50.nq.gz
    ├── 8935dc2477919149b7d1006a9fe203d5484d38a9.nq.gz
    ├── 8b040370f9f3cfa1f3ebea0d2279870b8edc43ac.nq.gz
    ├── 8b6559fa5d4bb9bd416a1c32cdc48ac8de5c5410.nq.gz
    ├── 8b8e9ed34db49530d9004ab14efb536b915ce9bb.nq.gz
    ├── 8d6b565affc30c7777dbf09538cfa9d94ecdad3b.nq.gz
    ├── 900f846dd22196f67ce1d69de8cc162219294821.nq.gz
    ├── 90a31ca84126e2addd356c01a72a5fa0bf7252f4.nq.gz
    ├── 9505ebb0b4f811ecb7a013bcc89049655f8ae335.nq.gz
    ├── 95288eeb07d4de6b5b3bc364518775232033fe95.nq.gz
    ├── 954265461ed82c275d8404d6ce23d6eb933b6e11.nq.gz
    ├── 95ebb32876880c3decd0a5466afb76d0a8c4e03b.nq.gz
    ├── 963bf9d69f3a8db04c8de107c6a6a282e03b837f.nq.gz
    ├── 96b9b866e56d50ea129ca854fd418a030aac5437.nq.gz
    ├── 97c980f98f50438d332fedde8bbeb95fdccdf874.nq.gz
    ├── 98f7c3a923f36fec9044190df18b5d68bdc03c55.nq.gz
    ├── 992b7ab3d1d35087fd72acfe60932f4210600c54.nq.gz
    ├── 99588adce07536adc203948da8d6bf2902e89c34.nq.gz
    ├── 995bdd4cffdc49749428b95a4dcdab2e8f7a8c56.nq.gz
    ├── 9ba000f3e3d4153affe4774edfac17f47c7e3d8e.nq.gz
    ├── 9c8293d6d908217ac0388c980178b3eec292c5c7.nq.gz
    ├── 9ce25aae27ada7dab0a91b6934b53aea04cfdf35.nq.gz
    ├── 9d58034180bb033451c9ec069ece070c98404a7c.nq.gz
    ├── 9ede039734f1f186ac587ae2d5d50761011fa9da.nq.gz
    ├── 9fac479603dc11b9b2db450f584c41ab0a8a5c17.nq.gz
    ├── a05b6b454250838282e4215dbbebee5f8bbdc271.nq.gz
    ├── a089258d37280fae7295ed58bbbd3b368b7b1008.nq.gz
    ├── a1bf00195205c7e9165cd4704e81ab55cab9d56e.nq.gz
    ├── a1c570a9a54ee9d719e305e5df68c6efb6fd7013.nq.gz
    ├── a307fd558ca90b8103ffcc838e1ca77c164c2e09.nq.gz
    ├── a32c9cdd33bb2bc428f084befc1116e472c83802.nq.gz
    ├── a4c349c49a34adb90da6ef2e065d1594f0057751.nq.gz
    ├── a64ab6fc702eb5cf24ff96ae3f1111e3d86751c6.nq.gz
    ├── a6bcea5dada2f403195e673ec93b21d0b923f5f3.nq.gz
    ├── a7751dfa172b4888da128a8890d90158c3631f10.nq.gz
    ├── a7b8a6b791028daf23a917c1bf82df0977c08a60.nq.gz
    ├── a921f7dd039c95a0d7a74697ec30b40076db097f.nq.gz
    ├── aad597b18e9e3fac75c9500b548f80195f297e6a.nq.gz
    ├── ab9fc019bd6a19c90f087c7a8aa4d05dee2ba9dc.nq.gz
    ├── ac71e0ce0418ab2bfe20dfc36282739baf6557ee.nq.gz
    ├── ac8eab09c3b9ca2c06f17974ba3eb0b67e2bc37d.nq.gz
    ├── ae5ed0ad5a4a8f79a43de981ba8cfb59e695e694.nq.gz
    ├── b0941e68ee988c8f7cd13547bd49ca1a86afc0b3.nq.gz
    ├── b09be7f0825a0adb3618f4663edfc42f326bed2d.nq.gz
    ├── b34a98cb100c6b19dfc5991f231dd9908471b3fc.nq.gz
    ├── b58c2a6f9cf4b65e50eee6fb19632c14f5f1ed04.nq.gz
    ├── b66fc4ee6ee86ef2a84a9842bfeaaffa505c4561.nq.gz
    ├── b7b788dc466ff5aa3e7900c30f2d4b44f602b79d.nq.gz
    ├── ba78b0c1806496376998b3acfd7192c11935efbe.nq.gz
    ├── bb13c6d73f76c6970b72113fed02aa2a1db3f5bc.nq.gz
    ├── bb1e93ec60089fe0637adb4bf059dc5f96dcec26.nq.gz
    ├── bb8f3c17c3d65d75633949794de26d4f400d30d5.nq.gz
    ├── be1897941848aed907d8d5e748a8d975f45b3c31.nq.gz
    ├── befc61f9e7eb89028b0a8e2221a784d18d224e08.nq.gz
    ├── c17fa20c828f0fa44d1daf09ad024d29e5440bd1.nq.gz
    ├── c2bb2efd64a88da7c0d3b155e8b076902f1d4abb.nq.gz
    ├── c654ff91644553494cd0ef3ea3cd9ee55dcec41e.nq.gz
    ├── c84ccd0bc5cfd747eb2ed4f035db154b5a357424.nq.gz
    ├── ca8b8b9a35168aae115909170174657d361b1fe0.nq.gz
    ├── caa22a58fb4e8b497eb4d970b54699c08e1b4378.nq.gz
    ├── cce71515b94228a82c327dd85f69af5ca9508c23.nq.gz
    ├── cd8a114263c958566eae628f65326137c6366676.nq.gz
    ├── cda051a454ea6d85bd458bea56eea4d32cbc637a.nq.gz
    ├── cdcfd0c7a75665b572e74045e08746282ab6df01.nq.gz
    ├── ceae18a70a00c88d812923fa52c4488ebeb06454.nq.gz
    ├── cf14e9eb259b79bb24ef3923c609703bdf6a23da.nq.gz
    ├── cf5103e97d5d5b0afe3e68103e8d28d689810805.nq.gz
    ├── cfe88121e723cb9e606aba43e88964d9ecdc297a.nq.gz
    ├── d2b52f15fb31ca3a2a9f31be6173ed4b1392c8d1.nq.gz
    ├── d3790d8045ecfe265f8608719e14695b6d86ee91.nq.gz
    ├── d4c536a96ac18c20995be46ba13cec551465f44c.nq.gz
    ├── d6f0284ef837ce6269ef0bee0847c14014cc5720.nq.gz
    ├── d71415816496908b8fbbb91b427995e3f25be4ac.nq.gz
    └── d75bc6e89771a4f6a7d8b3b7d2936a5d8c6f8d4c.nq.gz

7 directories, 200 files
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

[petl-developers/petl](https://github.com/petl-developers/petl)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
