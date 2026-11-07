# Repolex Knowledge Graph of ansible-collections/community.proxysql

RDF knowledge graph data for [ansible-collections/community.proxysql](https://github.com/ansible-collections/community.proxysql), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/community.proxysql
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4513f9d657e15182c42e404ef755875819bbbe33
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4513f9d657e15182c42e404ef755875819bbbe33
│           └── chunk-001.nq.gz
└── blob
    ├── 003a06aa32ac1fbbf312ef555aedffa2937381aa.nq.gz
    ├── 0153512eb97c5923fa9a66440607171e4e4848b3.nq.gz
    ├── 03e35bb5d6febad386b7c3464d4945ab2fb6df68.nq.gz
    ├── 03f759dcc6e3e8bb74787f38ca2356fff3920ca7.nq.gz
    ├── 070e15bb0ea49c68f595ff46e5786db1ab2cade1.nq.gz
    ├── 0758fd2749b25c447c7ef133ef90ab1e1b013542.nq.gz
    ├── 07f52352f413dccf8c29acf364361b7a90e78fe3.nq.gz
    ├── 0a58aa930b256646cf59646a342d160e331922e0.nq.gz
    ├── 0cb5ae1ecb562dbeb44f807286eaa4da7c9a7746.nq.gz
    ├── 0eaba208a5ac1be21345e832fd898830a7aecd41.nq.gz
    ├── 0fc4ca8fd1b6f00a3bf9f216c0ec3ea9bff3ff35.nq.gz
    ├── 13104752665d51322d59498bd4b1f911b1975f6a.nq.gz
    ├── 132bc3567603d89830df5afc0d97ff93b2c81e2a.nq.gz
    ├── 1354c3b51f432cbff495a99da94398a527749022.nq.gz
    ├── 142ad5436e777ba38767f483bb0e5450473919af.nq.gz
    ├── 14967fd6804e61640852687cb725e90131dc19d1.nq.gz
    ├── 15086d5892faab7088929c2e2e6d84ea90a64736.nq.gz
    ├── 152ebff84d3136686c70a49e895ef199908ef198.nq.gz
    ├── 15335cbb295afd88194f10cb1e16a596d7b7d04f.nq.gz
    ├── 16a9bb7ba7343cccaeae827bb73376178388c9be.nq.gz
    ├── 17aac721d1cd73e94c5048eb863b41e442fdcbb4.nq.gz
    ├── 17b8f2cb7a7958c6a584f55c596109328f1f68ed.nq.gz
    ├── 188d0d0bb4efe0483001534791ce9c15f0e94ca7.nq.gz
    ├── 19da9918112783e4cd909e42502a588e8f354987.nq.gz
    ├── 1a9142998650852c22740a2859f9e5d190d29267.nq.gz
    ├── 1a97cfa82ad0609d3d1c90332241716f9472cc25.nq.gz
    ├── 1b2c6342eeae2ed4fc9f24bee1245b87b64339b0.nq.gz
    ├── 1c0f84d65f6dce09345838102c3c7b790fc61a6b.nq.gz
    ├── 1e7ade0d1b4cabf1352a110758ea9f91bbed0fcd.nq.gz
    ├── 1fb5879258f3a1c334472205a8f9f1f6c4367397.nq.gz
    ├── 2023b8da85e2b0871a4a5063a04bb9808b5da679.nq.gz
    ├── 210f48b66b27de6d27156fd741c0362b5b896a4e.nq.gz
    ├── 21b9025fbcfeea549f2e272b1b4350aefa74ed7d.nq.gz
    ├── 24d1ef18e153097fe9f860d4a1c1c318ba3e91c3.nq.gz
    ├── 25a93c32c7998a37e607a9b142717d362ea0dd0c.nq.gz
    ├── 28c60c7a1eaebfef0193952d49815915d0b75b53.nq.gz
    ├── 2988b1afffea5dd94ef8629a2a4e65c5e28103f1.nq.gz
    ├── 2bc42d42451cf347ffdc55d9246b6a73e6dc5deb.nq.gz
    ├── 2c2dfa97a239ba2af52a6c63466a4bac51db4322.nq.gz
    ├── 2c79084f36f38e0ad8166b4a8eefbe09bd755302.nq.gz
    ├── 2e283ec726385bb8c76672966965f99eb0bf1d9e.nq.gz
    ├── 2ee3c9fa9b21eade729afb639808ce15cfbbf6b2.nq.gz
    ├── 314d63076f370d0a71fb2464805de51bb7a12d69.nq.gz
    ├── 32c6b4f0719de80178990a1a698f6640150a8c3d.nq.gz
    ├── 32f27910a6d5e911f4e52c23adba61103fce981a.nq.gz
    ├── 3377cba9a795e6be279dffbcc47dc81bf54f82eb.nq.gz
    ├── 33ad6e84a6190ae9a6d57af3b1050ef2d3d80b1c.nq.gz
    ├── 33d76d23aa72adf73aa50220454a0c9ae6ea7310.nq.gz
    ├── 35ff5507bc4d38704c623c177849b9f3ad2cfb8b.nq.gz
    ├── 3688fc0e28fdc579b429165fa0aa17628e912a0b.nq.gz
    ├── 38ddb798294189c659726f243c17c375d5d82ec1.nq.gz
    ├── 396ab83668f781219f8d14667b59c073a61e291e.nq.gz
    ├── 39a45523b328ed8df7a64bf73dd10b817ce1e2ea.nq.gz
    ├── 3a3a4efcd68102aa0175874e3767562f74042d22.nq.gz
    ├── 3cfc800522decd9e291452330b4e8b1879e5c0cb.nq.gz
    ├── 3dd3af43968d6036cee7cf65a46e585f89f92ede.nq.gz
    ├── 3eef3fe50209b57dc5c6b21e78727be35d58fbb2.nq.gz
    ├── 3f233b7f52c66e2483af90e4a2dc10a57224f2ab.nq.gz
    ├── 3fdd1d26fd1fac7fb5cb10ff92b1cc0e6c1d2f6d.nq.gz
    ├── 428982b4c760e227b751d317d2596bb021995f26.nq.gz
    ├── 42fff02716183d7b1e4a14c4ebf7f435b25fa6a0.nq.gz
    ├── 43542d8922cea740c4f36e31eb65855aa148a4f6.nq.gz
    ├── 4458ff4e4969caf1ebffe4740446f799bb7760fb.nq.gz
    ├── 4581e4ddb64f4cd73fea126a64a0f0b72f3aa1d2.nq.gz
    ├── 466a7c6b4da0c53c7da8b741b845b2712f5bd70f.nq.gz
    ├── 4881b82dc1003cc6123a390a739b807d352ee4e5.nq.gz
    ├── 48b4f269b4a0bdc4d62ed21c7f5603721fd31425.nq.gz
    ├── 499167e99bb50b35f9fc368adacb58bdee339f02.nq.gz
    ├── 4b958cf06784ce281bf12a4dc27e866989154002.nq.gz
    ├── 4cc47fd0c7a9beec19d5a3e46eb7d48d2bf76b3d.nq.gz
    ├── 4cd1d0979ad00e8dab168682bce8b3aa9cab4a8e.nq.gz
    ├── 4e381d458dfe58c01b870144194ca7ff9caa6dbd.nq.gz
    ├── 51d2248274af1aaffff6c4b7df15045956b85039.nq.gz
    ├── 53a04fa01e8b1d4bb25bdbf7cbe1e3b8c3a645fa.nq.gz
    ├── 5515ab45138d992638c1e1992e2b7cbdd7fba083.nq.gz
    ├── 555ac5de2b30cbfce7b4cdaa8d62eef44868bdb2.nq.gz
    ├── 568d72e9a73a878a2cdc7a8abbe7c5b4731177df.nq.gz
    ├── 57f85821934c3f5c7f386d634eddc4af914759e7.nq.gz
    ├── 58c576b5ed345b5650368957a1ead739e7b24241.nq.gz
    ├── 592931076337d0b509543d0f08c3e29190dc3e2c.nq.gz
    ├── 59449b17e0943b751482975f31757fb3384d9591.nq.gz
    ├── 5a1a6dac8b142bcec8ee4a8a06cb3ec05068fdc8.nq.gz
    ├── 5a36f7fbd93420fe66a27d691a0757e6987e0c6a.nq.gz
    ├── 5a66ee0687c4e366ae55d64355b5dfe0cfa6e49c.nq.gz
    ├── 5a77333eef7849682f9a134546a2e662b4470021.nq.gz
    ├── 5b94bd8b3fb270227115e0178d77a076a1e1640f.nq.gz
    ├── 5bd6e361022abef0b083db4bd274fd8ac252c2f7.nq.gz
    ├── 5c5e6a4cd7311b95efaf62807497602b2a6ade1e.nq.gz
    ├── 5cc42b1b985bb674e7ae2b325fccb0ab660be083.nq.gz
    ├── 5d341b981e405bfe318a235661ee392ed835b0f1.nq.gz
    ├── 5ea2dee2d0a5bede6ce5af061f217ed8b2d41b90.nq.gz
    ├── 5f6a05462cbd1bbae993e3f4cb86eb4f76b5d2eb.nq.gz
    ├── 6499f12f0bb3858b72ffd9242e0ab1092296754d.nq.gz
    ├── 64d9dacdaa407650f326a8b9e12970f009e5ab6d.nq.gz
    ├── 64e3c167a1aea778b4cedec3195e83c98a950caf.nq.gz
    ├── 6541cf7cf0727c4d67993100c4d2224c736da0a6.nq.gz
    ├── 662cb23522ce5212f28f09ecf3f5808cc8ac6d7e.nq.gz
    ├── 666a1171271ca3b6373153a214324a04fb061897.nq.gz
    ├── 6700a7e8556de793b7b86f91ead9f3d0601e5ffd.nq.gz
    ├── 68241ac776241e1722449eb379e53871058c5eee.nq.gz
    ├── 6b5bcab6807f1ea6c90acf2c34198effb18d00f5.nq.gz
    ├── 6ca346e4f55020438b031903a2ba949da414cadb.nq.gz
    ├── 6ca46f0c4157f4f382a7f782b4e7cefaa7d5861b.nq.gz
    ├── 6d9bfff199bda5b49c4f8d57543dfc892d680ec0.nq.gz
    ├── 6e3601df43fc2c356b2cae3f683c7f9a8283b5e6.nq.gz
    ├── 72b7ecdf69013b2877c6f276b377ef2748161fa6.nq.gz
    ├── 73977f6356e24691a0895df3de4ed2a2c874fedd.nq.gz
    ├── 740e2753a3c3ce4c6b27e11ef5c158f7ca6fa959.nq.gz
    ├── 753c044db2b7d435141bcfaf4435d924d9e21b5f.nq.gz
    ├── 75f5a5687229ef54d9585c8f4b2a2a83fdaa6302.nq.gz
    ├── 7638b914bec996312d4301d6809de6c616864268.nq.gz
    ├── 7676ddf9b3429f4ae91702e872c63ad55a71179e.nq.gz
    ├── 76fb000f6676f1c3ce807233245087a2d71fb760.nq.gz
    ├── 775e83d0acfc24111cbb74d74edb7f2a77dee62b.nq.gz
    ├── 7a5d75c9e8964a41ef733e1330e81c1b87530d00.nq.gz
    ├── 7b63832f0fbabad6db8148aa67556b04b0f38f08.nq.gz
    ├── 7c22188b3fc0b65401c9312e41c3f8c8a2848477.nq.gz
    ├── 7c54302fb408ce4a458788cbaed111e8a7607500.nq.gz
    ├── 7c80653d659767d803f1034057cb6f68bbdcf4f2.nq.gz
    ├── 7d16b246c30cf6fbf9fa8468adf530c9ebc8ba99.nq.gz
    ├── 7fc2cfdc963bed83a0fc84177aaa9432e714286c.nq.gz
    ├── 8055135fede0c98f0d2513a9cc21762416bc4147.nq.gz
    ├── 80c6d3e24651c772e665cd5e8ad5556a0e4cd2be.nq.gz
    ├── 80f38e2f0caa2cef3730b316e2cf6bee86b4ce65.nq.gz
    ├── 811ab7e95ede9b861b0eabfafad34cdada81cc0e.nq.gz
    ├── 81941708f7cd8ad33f0b736bc704fc204800cce8.nq.gz
    ├── 81977c04a4937f83c4a7dd64a3baac4abf7ae0c1.nq.gz
    ├── 81c22815bff0060e952ba2d95f005b811b5ac334.nq.gz
    ├── 82ce0d330d3973ac87c28ab5a24da9b3d0497107.nq.gz
    ├── 82d7be6f2a5b20c8166b542067395588a0f81fe6.nq.gz
    ├── 8412c18c88638e9e7632654f5f743cf6aed0ac01.nq.gz
    ├── 85c904ff63a9af1e676b28b8cfb561f7ac0820b9.nq.gz
    ├── 879e99c52349f6d01ae9bd3c03785da66328f234.nq.gz
    ├── 8896c5990bdfb881a315f76d956b68d096e426ee.nq.gz
    ├── 8a0d4911182de1cf2d5fc38fcfaff175d11020f6.nq.gz
    ├── 8b068296fa3229a09ed49f26fd0f192502f5e500.nq.gz
    ├── 91cafbb771bfe2a6e04ccff764d184be8e074e5b.nq.gz
    ├── 92070168d1f73ef5bb7d5c323d4204d3277cc82e.nq.gz
    ├── 9229c5ccfc4182170d7395e556a9285168a02843.nq.gz
    ├── 951801b11f58c34fd776479d364e9e4462bc3c4c.nq.gz
    ├── 966b6cd394008b7c045982bc0e31ccf2a0de5563.nq.gz
    ├── 96a847ddac81bd13a5223bdb698bd84032f0ac13.nq.gz
    ├── 96b5952c7c04552f7d6b28ba1cb213c3e1ceacbd.nq.gz
    ├── 96e5133f8eccba4f6e2ccee7a2af4e41ef766aaf.nq.gz
    ├── 975516c54c31be92d61445bb236b9f7a9607832c.nq.gz
    ├── 9996041ed8c5de33bd480b0d4bada4a40c41a90c.nq.gz
    ├── 9c1e053b49f0dc1b6ac6143db93903981daa0c76.nq.gz
    ├── 9c3fa05df88860f63dd2afde3840bb84e4f4b765.nq.gz
    ├── 9d9423f428ef7d9f9bc6f19d13a39294a5db7117.nq.gz
    ├── 9dccf7ef174657345b77b37626c52cdc0390117f.nq.gz
    ├── 9dee8f05213b44e86dadb6d151a5483e759890e3.nq.gz
    ├── 9ea04053f9bfc6470b98e3ab47d9e63e9f5ecb85.nq.gz
    ├── 9fad0d343c07aa82e21752481014bb870092c693.nq.gz
    ├── a0270865d6c82e055536e43dff81d6b65de052e5.nq.gz
    ├── a1395541ea840837d373f3cc9a6e2b3f21745a3c.nq.gz
    ├── a180706b69a6fb48c058fd078b923107177d1def.nq.gz
    ├── a1c94f6741076b6aacb86bd79af89b8a18f1a48e.nq.gz
    ├── a2001540c160f144a27a2701e0481404a268df87.nq.gz
    ├── a28e4f45c0c0b40d2edb21d343283126f2294811.nq.gz
    ├── a5b0a8c47b6046bf87739c2d98382c4fd14d94bb.nq.gz
    ├── a6088b1513daf093d1db7890347eea35bc4e0091.nq.gz
    ├── a6e11b2b6166b2910a64cd1ec1d97d4c2261b839.nq.gz
    ├── a81b7119a7141d23a50d5bcc82144c5860b2b32a.nq.gz
    ├── ab421218cb6f89bba06b136e152de785b5a759bf.nq.gz
    ├── ac8a64dc24f1a9f73ca7abccca9ac757b7563d67.nq.gz
    ├── ae8267e4684a3ec30733c4ba3164bd289bd54795.nq.gz
    ├── aeb5d9415b0d73dba33f81f4e894d9d7a890011a.nq.gz
    ├── b084e123d4937f02d5d44a10e57fe20e9b6ae43d.nq.gz
    ├── b08c935817d07b7a862ff077c44b02070c4b879e.nq.gz
    ├── b1e21523edbd4ab90f68b2b081dd3d303e33bbdb.nq.gz
    ├── b397957167a51a06bc423c6bc24897a8580ecc10.nq.gz
    ├── b3aa230a93274ad2b80a2a78d0a15376586ffc95.nq.gz
    ├── b4026a1ee7c0e7f679b2cdf55576d599cc0a2768.nq.gz
    ├── b4d02a0ca051e1eddf7a5d1a0673ebc203b5b5d4.nq.gz
    ├── b59b6617c38431f846e4ed5db9f0408ed83b70ce.nq.gz
    ├── b63cd3fdfb7305b23baaba4134c0096a4b8c965d.nq.gz
    ├── b72d4f6752d4b1a063d25c2496545403169b4f17.nq.gz
    ├── b7510e2e78feb3061dcbfef3c4c0264bf9d754d2.nq.gz
    ├── b8dae32918137a672f13f13e5da41143ea1fdfbf.nq.gz
    ├── b9a2fb2fbc6ad2760c6b765d980d62c517c453a2.nq.gz
    ├── ba3a42aac051b980371838710a5e43b1ddfa6e6e.nq.gz
    ├── bb5b9d64871b3d7bf61597abc121c206707ea1c6.nq.gz
    ├── bbb5de4d5434eb83c0618c9a91aecf9e7d8dd7ed.nq.gz
    ├── bd4f78739efe6b5982c66cf23e605472e4e52d5d.nq.gz
    ├── bdd7a754e5c3430d47e64c5db9726b2635ed5bff.nq.gz
    ├── bee5184befc1216fce08b396b3ae7d00d5d5ddad.nq.gz
    ├── bf2ba7deacb94cc8441a701a1c0b8905ce1dc453.nq.gz
    ├── c0efe577fad5e3c70d08fc55eeec8eb2bf45016d.nq.gz
    ├── c1578891d9a2f2d57d938563452943530c651f4e.nq.gz
    ├── c54a28270146edffaadd14d8cfa01a536ad2938b.nq.gz
    ├── c5d4ddcfe254d1fd0c3cd778bd6199b8a7ed0b5d.nq.gz
    ├── c6b2668cfcf28827879020f59082f2cca07e5852.nq.gz
    ├── c779026665f6bcfec32cbd348af66abc02504d4b.nq.gz
    ├── c7de0c43ed61a6d3943181c18965a94bb9862b07.nq.gz
    ├── c872c8e3166b7442f2a05570e2a234db85f6690d.nq.gz
    ├── c96fea7ff7a8310094fe7f7d37df87782fe335cb.nq.gz
    ├── ca8ee1460909c07ddcedd88449e38dbd92ef32ee.nq.gz
    └── cb1b5669c4c8f072ef304d8156ab87884f55cb6a.nq.gz

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

[ansible-collections/community.proxysql](https://github.com/ansible-collections/community.proxysql)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
