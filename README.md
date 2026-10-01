# Repolex Knowledge Graph of block/schemabot

RDF knowledge graph data for [block/schemabot](https://github.com/block/schemabot), parsed by [repolex](https://repolex.ai).

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
rlex download block/schemabot
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c48f53a70e207b527d383e8e08709db858246e5e
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   ├── lsp
│   │   └── c48f53a70e207b527d383e8e08709db858246e5e.nq.gz
│   └── repolex
│       └── c48f53a70e207b527d383e8e08709db858246e5e
│           └── chunk-001.nq.gz
└── blob
    ├── 003cc1bc84a5877d9246059d17ea7df1594d7ccc.nq.gz
    ├── 009c2fb0dfc8f503e9a8510cf7f2b314466ed92b.nq.gz
    ├── 00c083a9a12a946d62f0ac53c9fef2d5089ddbe5.nq.gz
    ├── 017a54e341e583c489c7a99e1715362c9379f220.nq.gz
    ├── 0181760497db1c085671830eb852cbfadecb7a26.nq.gz
    ├── 01923f625c87182efee6dac9f49f0aaf5de78259.nq.gz
    ├── 02361eb4373a005f165dbb9e1a3893461cd0a87a.nq.gz
    ├── 024eb7c7fabad31bb31056f456e780c72e8c9190.nq.gz
    ├── 038bc626b05429b6d897962039f5b91d53286f5c.nq.gz
    ├── 03ceb33120b3c27aa213dc50922de625ba16e01b.nq.gz
    ├── 05bca5f5677d1992c76f9d48ef25250ce7d8b011.nq.gz
    ├── 066b28a3f4a0acf9406b4485d030bbd63a6166a9.nq.gz
    ├── 07d59f0b9b0047a25ec8c2f4fbbab8423744616f.nq.gz
    ├── 0861480de8060455693eb3c3609cf02fabc8cd23.nq.gz
    ├── 0906d314474bcaaf2cacb0d3f71c34d9a4a728f3.nq.gz
    ├── 099c1f124408181d589d183d48aa526e12d68ce2.nq.gz
    ├── 09f5779f78da6c6fd227d291fdd4c2af4a992e8a.nq.gz
    ├── 0a3c86601120df712ce2183d6a03705503e231bc.nq.gz
    ├── 0a734b1ec3ae315c5e0fccdfe54be233a4fb626b.nq.gz
    ├── 0b0eb7884cced750ac26e45b507be6298dcba797.nq.gz
    ├── 0c2feeb4833b134206cfedd47f764e70cae2c47e.nq.gz
    ├── 0db2f2ee436a48c548aeadd661bafc6846fd70ae.nq.gz
    ├── 0db33c5766efc67a0f772a5ec9d1f6ce987697f3.nq.gz
    ├── 0eb2f8969212dbac72b608b9024e7e4fea24d89f.nq.gz
    ├── 0f2e78dc8cf51041c28f66b096c95538ecca2ee9.nq.gz
    ├── 0f48038e65d89b1be25d178df5eea69381c4e630.nq.gz
    ├── 0f4d9d10b81424eda1194165855804e76aa30451.nq.gz
    ├── 100e0292dcade7a76e7785b9d58fb03ed8e006e4.nq.gz
    ├── 10a2235b1da119d318ba21eb5e5867b2121ae553.nq.gz
    ├── 10b372a29dda4076eeaa1eec959540c63c9f463a.nq.gz
    ├── 1208c3d7b3902194cfc2329c286a42e50b9c9f0f.nq.gz
    ├── 12300b5b08366f03d6a9caf25cd258a1e29639d2.nq.gz
    ├── 123cb111a91e92d1b8c86b7400bce6e8840411d0.nq.gz
    ├── 12571620f97bda0090ed77aa734af82d7ab46994.nq.gz
    ├── 1290f372a1261d48b003f22f61289c2270d0896d.nq.gz
    ├── 13f4daedd28726b7454041288e58e4733faf79af.nq.gz
    ├── 140497940d896a2b915bddffac6b27cfa22a0df4.nq.gz
    ├── 14607bceea21be9d09fbaf1b9992b57a7fb4b2fc.nq.gz
    ├── 156454b0a957a858a9da64d7fbcc3413ea42a644.nq.gz
    ├── 157f3aaa198b18258e7d9acd34ef463dda289f12.nq.gz
    ├── 161d747aff34048e9f00e104a29fb16f167eaf97.nq.gz
    ├── 1666bed7b4e4871d26f8f5b2ca12f3ec9cef777c.nq.gz
    ├── 17141638ce7197cb629f62fad8b80a2be31c6484.nq.gz
    ├── 17b16c2b27cb6b0153a3a4a4f626afeaf2420a98.nq.gz
    ├── 18c775346482f7c1bc17ae60c9bec6f754617a6d.nq.gz
    ├── 19a5d2db8a0e95a81973cf953039945ab53261fd.nq.gz
    ├── 19df06a1a0cacf71a0b3b4333c8aeec67ad48b22.nq.gz
    ├── 1a12642211c9518cce6ee52cd44e462123f1234b.nq.gz
    ├── 1aa8debdc772e9b62b59ee5b20ff0e09f371e009.nq.gz
    ├── 1ae153f386d78a1ee5b99adcfb78224bcdae9d92.nq.gz
    ├── 1b4d148176dceaad87aa5aa133ede39e6fe87360.nq.gz
    ├── 1bce4214a0b21fb5b600b4b6891cd183558590eb.nq.gz
    ├── 1cabb0d9a09add88322621a10e715380fbad7921.nq.gz
    ├── 1cbf23e83ceb0fa3c36cb9d3623a5add80c0b8c9.nq.gz
    ├── 1dff9206f091748674aa377035842de7cb545186.nq.gz
    ├── 1e81a16c5ab2d2bfc074595ce49f52d0eff520fd.nq.gz
    ├── 1eff8be40d0f1c7832a5374fdb1e336438b41687.nq.gz
    ├── 1f9a69fb3ff3aa33152f87c81360794115d9b2be.nq.gz
    ├── 209b64dae060151337e90edeeac48273a5807536.nq.gz
    ├── 20e3b27d986a0fb37cf5f8ff361e77f9f3d96df4.nq.gz
    ├── 20f58654d993dbdccce74e3d8e5389fbfe40d9b8.nq.gz
    ├── 21b98c6f3a8cec36b655ca4d9f0c95beac5a4156.nq.gz
    ├── 220581d74929da1ba7bc41d62f070b9e4a15effc.nq.gz
    ├── 224bab3f3424b12b08e923c715887c0d78380e4b.nq.gz
    ├── 2295c6712e84003be060b55064f3a96c98b5e37d.nq.gz
    ├── 22fd7e8c6f72a903c0ece87bc17372a4977b74ca.nq.gz
    ├── 230f6c25f5b35b3526417c53272b19eb8ef81a9b.nq.gz
    ├── 235bc3a778965a39e91834957ca8b207040f1a3a.nq.gz
    ├── 2365b1b83637efaf2a20b229f558c170d0a643ac.nq.gz
    ├── 23d49328ffe79f3e2d55ce84dd3748d5515f43fa.nq.gz
    ├── 24aeb935c36a866216c096421267f21d7b0f9bfa.nq.gz
    ├── 24f080703824cdb1f9e058a0cbbd1d8d12c2c1ff.nq.gz
    ├── 2595644d1e8df3b4690d4bb80b3ec4c2cc3e15e2.nq.gz
    ├── 25ec74706883b3d0c81554ba7ab701d99dff07f8.nq.gz
    ├── 27173249c3ab99fce85b8bc3017faa8ad8f76ac1.nq.gz
    ├── 27402afc49e0341737aef55cf06aa1f2e9dca2a7.nq.gz
    ├── 278fed50f93cdebf9dc0f67688116fe42aae7692.nq.gz
    ├── 27ba025f673ec4d8b56edcd4e20d4049036e5270.nq.gz
    ├── 291406f651c59ff77eae1eb890a03a0ce578bec2.nq.gz
    ├── 29cbde456ae19ab3f76090d6ac57fb32a2965619.nq.gz
    ├── 2a871dda253a113bf9526a9d2f79b1af138c7407.nq.gz
    ├── 2ae1cd7fb21528b4d96582a63bbf941406b979d3.nq.gz
    ├── 2b434fcbb72e2748af77d602d52fc77087177e81.nq.gz
    ├── 2ba1fce78e8bcdde3acc3998876db5319eae336d.nq.gz
    ├── 2c5276a872be9264df857c8be000fb621bd66af2.nq.gz
    ├── 2e033c97dd92cc7b904c27863585343e808866ca.nq.gz
    ├── 2e151195ce5c224a0fd71238d3e69cc33c900a98.nq.gz
    ├── 2e3d06ef1aebd84cd99d1837e779cd3b2733f9cd.nq.gz
    ├── 2ec9447e1e0c1dd89c27808d092b3ece53fa12e6.nq.gz
    ├── 2f30cd2f6603bc37a2c5d6228dae7982d51eddd3.nq.gz
    ├── 3010c7f37a412750e8ffc3e53870b9fffd3c84d9.nq.gz
    ├── 31650d11d758f17fd85aaf726c97b5de88ea5560.nq.gz
    ├── 31ae5aa1508b6d5072c13f6813f5d55079489c28.nq.gz
    ├── 31f9f2a7f3819c23506aabd24ec8aa2aaf4790da.nq.gz
    ├── 34df3f59e21c142af3531d060e300b4047ae99c4.nq.gz
    ├── 34ee9c47ed56a8ac49e8d471839b7a185e5ccde5.nq.gz
    ├── 353928195072b41195295be48a53330c22411428.nq.gz
    ├── 37c54e6663d8ef7345c718eab8bf15eb39fb6523.nq.gz
    ├── 37f806b11d1b7ed5a356aaa4aae6deabcba0a084.nq.gz
    ├── 38b3e77a5d9bcaabcc4e723656fd336e4625bb8e.nq.gz
    ├── 3953386f5644d9fc4ecbaec54fce96c174ad9eff.nq.gz
    ├── 3959e43199e39ff60738dccd72ab6666185ffb87.nq.gz
    ├── 3a12cd9caffcce7ad5ed6cdf83d5cc5a82dccec8.nq.gz
    ├── 3bcf8df333e6daa1658a3638d41155a9805c352c.nq.gz
    ├── 3bd23ab455477cd2a6e815eebb85d68c2510bd72.nq.gz
    ├── 3bd40783be5138e3d90ba888f2f1c7066bf603e0.nq.gz
    ├── 3bf56e12f5ad4e20cdeb1da66e9ccec810e0b427.nq.gz
    ├── 3c5823bdcfb65951f740e43f30aefaf1591aa566.nq.gz
    ├── 3c6a909ea46fb059ccc310c4d5c12facf07ef4af.nq.gz
    ├── 3d1cbf3a0378572b5b9ade742d2a4c434c57c96c.nq.gz
    ├── 3d5a5298750835eccfb6503284a793bede18a300.nq.gz
    ├── 3d7bfc9df9891e22844103d906d9a55645759ea1.nq.gz
    ├── 3d9595e91324b2fe2ef3b2de9f88d817b92f0716.nq.gz
    ├── 3d97cbdb5204594db0f208e6a0b61a26e1df798b.nq.gz
    ├── 3f2324ad6092d00a638bde3d73414ee84d2a93ea.nq.gz
    ├── 4062a9e9f924ad0c41ae80350a538a830040ea58.nq.gz
    ├── 40a35786ec38ce350dea06480c9c0449893a894f.nq.gz
    ├── 40c4dc04f617dc9c9eddafe0ab3835ea6f4067db.nq.gz
    ├── 40f5257d948a88f5aba49761d2d30b8ca107b85d.nq.gz
    ├── 41c0b5bc381a4748812dac2713480e5353a63d95.nq.gz
    ├── 424eb04151e78b48edec1c9d961126b8511ab5b7.nq.gz
    ├── 431b69dc4df21e585aa87057d9bdeb843f8f944c.nq.gz
    ├── 43d7f70799a870fe3a9641ff394a84b5962365ba.nq.gz
    ├── 4406700661d80893855676ba15d9f1cbacd03f58.nq.gz
    ├── 442691dc81af981e9e351f5293c2073622190b44.nq.gz
    ├── 446598c84e7f47e43de11c8f09087add152c10b2.nq.gz
    ├── 446e311399a6094c2da6c5840ef8eb36262acd90.nq.gz
    ├── 44ccc4bb9b620098fc5c1e59d80a99150a9d9900.nq.gz
    ├── 44d5f18bdb706f47309723c4ce2899296dbc6937.nq.gz
    ├── 451889fa2b9bc8e20a18af669c6d18df52950982.nq.gz
    ├── 453e5f1098d0bc552b5b1043b82ff326d131bc95.nq.gz
    ├── 45aa2ed7e5f38f9a9e0672aa2bf0f000a9950046.nq.gz
    ├── 45dc6b697b4292d055d605a765f076b1f6aaaf43.nq.gz
    ├── 45f4c9d1c59ac81f394b2b92df4218748abcd958.nq.gz
    ├── 467948e8064ce96fd93369d31325a624fc27c4eb.nq.gz
    ├── 473af3837896797f39837ff077d695068d1e6911.nq.gz
    ├── 47e298b96b9fc2c0402435c45c7ff8b00f04f00f.nq.gz
    ├── 48573256aaa3b503402243390bbafd3813dd7c47.nq.gz
    ├── 48d2459802b8a081ebe74acfc4eba6ec99977d5f.nq.gz
    ├── 4a0340319c415e8d63418a2da987bb7b4f498e2c.nq.gz
    ├── 4a415df109aba887898856c2381ccac7ed208617.nq.gz
    ├── 4bd80a344973340a382bc3c2bfab521612431b84.nq.gz
    ├── 4c1565ac6adac562db7baf2ddfa4fe74ddd3f570.nq.gz
    ├── 4db7fba1ad92cadce56cd7efd696a320d599e8dc.nq.gz
    ├── 4dbe66c7bd65bed1d1602544eb657c2d61c8c475.nq.gz
    ├── 4dd05522ce66ea2b508d8398b2bb5c7d020ce87d.nq.gz
    ├── 4e522e5edec05906cf9c1dfc21798ef8ef558bd8.nq.gz
    ├── 4f4c5c6748c04b3d1294c76c00ca9fda2f96262d.nq.gz
    ├── 506879001b6a8796c48061dd239c91654fa97a77.nq.gz
    ├── 50e3400dfb503ce5ea81ac758aea2c7de356652a.nq.gz
    ├── 513cfab907b0bf0b251bbb68e262854dd2ab45e5.nq.gz
    ├── 52c25d6399d0bf602ed615d849d9aa20e9d1df4d.nq.gz
    ├── 5369605154b682b1437c8600f7acf9018849387b.nq.gz
    ├── 5387e2db612113ed40b59123a98ebb65e18b1274.nq.gz
    ├── 5418eb9e3d26fbd13d4f38ad406cce47ac86e7b2.nq.gz
    ├── 54d0a87cd0b0203aa970209598fbb5654b7b4ae3.nq.gz
    ├── 55308138e0329c45331b8e1049660303daea0887.nq.gz
    ├── 56922fb341c8b8e9b6f98ee835af4fc982bf90cb.nq.gz
    ├── 56a50d25c0ae354dfe64358ad9291901442bddf5.nq.gz
    ├── 56b1f570b61a4ec0904a2f645ae2d1f1290384e6.nq.gz
    ├── 56c214aec6478fce0fa9182e3a09ebb5a6b119ed.nq.gz
    ├── 56ca20b0bd6782fec46347c333af338f9e6f1699.nq.gz
    ├── 56d98eebed2476fa764060b6812e1defd7731e3d.nq.gz
    ├── 578e9cfaac7eb9d52b28e3848d722b3c8f14d2c9.nq.gz
    ├── 57fb45eb9dcfe0fbc8f7154c7b6e67b09e010f51.nq.gz
    ├── 589b1c142a0337cbc9f2096c0773ab86c9c5872a.nq.gz
    ├── 58f7c85b34530a11758bd018e92a28eb312b273e.nq.gz
    ├── 59c07fb8e27e3d90c9330fd0e2f8563882a5990c.nq.gz
    ├── 5bf0172061819ea6a0a16ea0641fd12af945261f.nq.gz
    ├── 5c17d495f3847ff85680be9a5c6f72841992ddff.nq.gz
    ├── 5c628657663f4dba02280ff11a36b45806aa32c5.nq.gz
    ├── 5d5b1ec7b7583a4eac3558e5e23dd29d6ecbd66b.nq.gz
    ├── 5d73613a270af010e3957b8e4948e9268e24d5ab.nq.gz
    ├── 5da48fab08b7bc1e7b8bc8753b4c01a1a9960bc6.nq.gz
    ├── 5de95433dfebfd7d12a86aace497880a3316d581.nq.gz
    ├── 5e2ff2ae54d2d3e1e6877cc208fd927e0c16ba9d.nq.gz
    ├── 5f4b6452adfc98f490ec6c7bf422f795db9b192e.nq.gz
    ├── 5fc40df68cd644dc913763bf00003879ddb9e604.nq.gz
    ├── 608afcf33198c7fcd7056d0c0398d1234624465f.nq.gz
    ├── 60c1457ff2e58f9d231e831a72226198e847b517.nq.gz
    ├── 6131be69e50fdb0e4f6642ab80725a05312e9cf9.nq.gz
    ├── 635fc50bb6caf81b1388fee0d9d399149ee9ecd7.nq.gz
    ├── 6459c88c6dbdac42f686cd1ceff36ff4e87031ff.nq.gz
    ├── 64aa9cc639be0ea9017c58b79857f7019fd61d8a.nq.gz
    ├── 64ae85be72c1c1879808544f9951f5a633f0d5b7.nq.gz
    ├── 656994f05a7dd6e3ab6d22d2c41b39fc4af2bc68.nq.gz
    ├── 664273065bfd3a55936c35e6af2f061061bb62b1.nq.gz
    ├── 6726f17528c9ee7785923c7f8a8d02702a807911.nq.gz
    ├── 6771f82925d7fcf0923f475b712dc06b34114c96.nq.gz
    ├── 67f2892cdc93b12c32f4d9f5dd359bf0e4476914.nq.gz
    ├── 6854c8fda0a3d2aef1295c8893d6c65546a77102.nq.gz
    ├── 6965e6a2b938459089c5697e69b2d67be7eabccc.nq.gz
    ├── 69a21c39c76c3044513981f284ea80f382c961ac.nq.gz
    ├── 69c59c9d35be1bc7f52b8c620df012175327386a.nq.gz
    ├── 6a89e891717c091a2d59b3391d79e13133c67ef1.nq.gz
    └── 6ac82229431ea7eec908d6be626cc240b28b7659.nq.gz

8 directories, 200 files
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

[block/schemabot](https://github.com/block/schemabot)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
