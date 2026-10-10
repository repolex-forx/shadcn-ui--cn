# Repolex Knowledge Graph of shadcn-ui/cn

RDF knowledge graph data for [shadcn-ui/cn](https://github.com/shadcn-ui/cn), parsed by [repolex](https://repolex.ai).

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
rlex download shadcn-ui/cn
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c71bd53a351d99dca12f0808ea7e1c7134ec4945
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c71bd53a351d99dca12f0808ea7e1c7134ec4945
│           └── chunk-001.nq.gz
├── blob
│   ├── 00cb5159f9b69c23a3144e6f6ad9e0a307f0888f.nq.gz
│   ├── 020fcf7b88da806c7c3618e7fb49a6f208f36e58.nq.gz
│   ├── 02b3865ce350fd9d529c0c1769b6856ef4d24507.nq.gz
│   ├── 030e898d77623aeb6e3f26dd5ef6aff5ffc0dde9.nq.gz
│   ├── 03fc7ae6f835a7bbc173897a5c96004d4ae80376.nq.gz
│   ├── 08029de9b0990c30e1cdbcb3e2f9cb5333146af9.nq.gz
│   ├── 08539a157d15f25173ef5e527e245b1d9d954913.nq.gz
│   ├── 08a70f26dfee792ffd29629d532a2135705b2a80.nq.gz
│   ├── 091902a4ca79a5e5837a7970ece56700c9be715a.nq.gz
│   ├── 097626c33b3c5de266b2feeb9e37e9a8981d0c7c.nq.gz
│   ├── 0a1f24569d662962cca1cd90cf9f900a3a3cce30.nq.gz
│   ├── 0a83c89143413a0554d30222bd611d3218206904.nq.gz
│   ├── 0ba62067b3a364c129cfe8c0588ae9a9659021ee.nq.gz
│   ├── 111d4729b107e2f9c36c46fb8707b72b6f55f2ae.nq.gz
│   ├── 1529f0f5582aefceee29dfd223e30cec6e152a26.nq.gz
│   ├── 16ae6082c1d2b9aec1ec1c1bbb15d7db8a78e3b4.nq.gz
│   ├── 1b44bf31601159fd7a50c07b41540698493bc85c.nq.gz
│   ├── 1db23dd10e5c9d4a803d9259f4fcc3fba43fe290.nq.gz
│   ├── 1f7147ca7b7b56a186837fdf3eb641dbaf808278.nq.gz
│   ├── 212d32412f4c9dd73575d14a8da96af28684295f.nq.gz
│   ├── 21f40aaec1ac66040cc793604c00fe1883d83350.nq.gz
│   ├── 24eff2cb0371de5c3ee839aa9f793a1a29691f9d.nq.gz
│   ├── 26fd9208b20eecf394efc20fb6d210df305117d5.nq.gz
│   ├── 28115c75d15a4a777486c9d980eeb4ad45d2d685.nq.gz
│   ├── 2e07d56bf1bb8dbc87c4a1edfaa04efb9cc18aea.nq.gz
│   ├── 3195a0d56175d9c3dab5c4ab006fa7fdfa9df40e.nq.gz
│   ├── 3400d95b408e3d91794369d63295c0cf354e2dcd.nq.gz
│   ├── 361a59319d6866ba50467663bc2fb7866bf4e677.nq.gz
│   ├── 39903381b4409dc91271314ba0f6ddc0b0115090.nq.gz
│   ├── 3a52ea7a2539aef9e21dc21f2709bd81e3e966bc.nq.gz
│   ├── 3b351a4dbb952a3c118027803ee864fa9374be9b.nq.gz
│   ├── 3e535e231a3026da589c52fe7ccebddba01e1543.nq.gz
│   ├── 3f3dd724ab925179950b35ea8d96fda5eae1ca80.nq.gz
│   ├── 45fb67b7c71e2657bf109922635e215a6e1c6874.nq.gz
│   ├── 4615bcb646ae6f3080291a2e96d4d83785051135.nq.gz
│   ├── 4834c0b715478af2ebc71a0acc69c38437bc6396.nq.gz
│   ├── 49a8e8358dd15e70d4bc081b7d3a8bc411cb1278.nq.gz
│   ├── 4b7c2ffca31c3843744f9b325aec128d15d8f00b.nq.gz
│   ├── 4fd6cba4371985a107b21100f5b267c138d8ff7c.nq.gz
│   ├── 50f8e9834e1bc8e94e4246a5c0b756e9986be1a8.nq.gz
│   ├── 524a1c66cab124514642f731baa222a818abab9b.nq.gz
│   ├── 52fac928439f630207c8be2caf3ed9c127fb0d52.nq.gz
│   ├── 561a8b2a46a5d129f1aba3c20291f8d6fb063dc7.nq.gz
│   ├── 57aedf7f4c650055ba5d54c6eeb7d1824feaf275.nq.gz
│   ├── 57cd8b6856858b3e16cd2e6c561b3610c86d38fd.nq.gz
│   ├── 5a708d99cb660ed43d8c768aa027bec671fba4e8.nq.gz
│   ├── 5d6aa8728b133bc1570fc96503de6d1706bade72.nq.gz
│   ├── 5fb9fb194bbbdfb7325ce4cbbcccb632951fed11.nq.gz
│   ├── 61101c08dd8ccdca34d23d89c7b7fb0fd979c6d8.nq.gz
│   ├── 61234b19c69729c6abed65bc91d20861875e3512.nq.gz
│   ├── 6704ce7fb57fa451512f4200fb7bbc27f2b96cf1.nq.gz
│   ├── 67d0957c674c29c586f66b86a1e8c746200d7fea.nq.gz
│   ├── 693724baf975d493af463078c36d0782976e78da.nq.gz
│   ├── 695e3bb1dece46d05c04e89ff4013b4435c5fce9.nq.gz
│   ├── 6b902d421fa0c2c8de3f5296353941fa17a69653.nq.gz
│   ├── 6d47a98ce7fb0da0e1e6341d1486b78cdedcb270.nq.gz
│   ├── 721761c82a574e29f01d4b098346e40b82fe2757.nq.gz
│   ├── 750af74edb5b7542001f074856a2d1ed9d04eb61.nq.gz
│   ├── 76003ccf4d1bada586a60f59fd69ee0ffc6f59cd.nq.gz
│   ├── 7ab60c193b734469825bca7b2473d40168449332.nq.gz
│   ├── 7adc21d90b4d785580bb942a0258101b342810ce.nq.gz
│   ├── 7c47590d640b8cf4fc125f610966bc9fa95e6e9e.nq.gz
│   ├── 7d1f444fb543450c46b0d06207a3db6afec951e3.nq.gz
│   ├── 80eb6e41d65a30dac1b15fff1cccc09675ade1b2.nq.gz
│   ├── 86bbc61f90eb6f5658036f741a03011d8b2f7cfa.nq.gz
│   ├── 8826687dffc4da78b6387d745fdbd01889da0869.nq.gz
│   ├── 886016b552a20b7c57140f75aafaf00e0da41dba.nq.gz
│   ├── 887cf8b1de87621105a107fba4baebbfedc8353e.nq.gz
│   ├── 89d5c40d063481c25139fecda3295039d59951ef.nq.gz
│   ├── 89e5a6fe5afcbb084540c47df951003b8af62f3c.nq.gz
│   ├── 8d9936e804b1d8d1f47ea0093a5e21485d75993f.nq.gz
│   ├── 8f22b0e5197d886d5689822afae3799dccb27796.nq.gz
│   ├── 8f7017f872958b55dc98742e27114373035e0fd7.nq.gz
│   ├── 8fbc37a74337f1ff70a1a65e6ed9583ec241bebf.nq.gz
│   ├── 92a937f5a4c65f45c26cd48e1b0ecc8a66c2fa8b.nq.gz
│   ├── 960bd8ae64ca7e96eb00b10ae269309eeedc2c8e.nq.gz
│   ├── 96c2c23d31472a98f9d49f2fa90e548c233767b1.nq.gz
│   ├── 99a7c468b327560c94a08a0bb68ad781a84cdf36.nq.gz
│   ├── 9daa462e81d9bbba5b1623cb5f7b60380fac8c05.nq.gz
│   ├── a3a360b96368de907483559f1df7ab67971142ca.nq.gz
│   ├── a3f019136414d7020ca1a02c4c8ddfabfe759791.nq.gz
│   ├── a3f7ae263ab34841361f99e3b543aff51a3c1e1b.nq.gz
│   ├── a93fcaaa9e3ed0a097c352e52e89ae30bd9ae32e.nq.gz
│   ├── aa0bed414adc409dba9d82f81ae9b0fa36415327.nq.gz
│   ├── ac0bbe9fe9185e345fcf3e87ce1b41b90cc3b287.nq.gz
│   ├── af4976ce11ba2e6599d815154b165af3e00b83fd.nq.gz
│   ├── b145182d324c63230d90cc9217cfccd092129ef7.nq.gz
│   ├── b4cb66c9a5518038c588c2276d8cce174ff91913.nq.gz
│   ├── b5520fb2bb6f7dc81376d3dd29dd7c63a3536acd.nq.gz
│   ├── b7a0f938dea66e23f097cf3fe291cfb91db827c6.nq.gz
│   ├── b8efd56e839a9eed5f4b0b69ee057a7be3aa81fe.nq.gz
│   ├── c14e936970dd9e9711670b071a5392b43a61589b.nq.gz
│   ├── c19a26efb31b8288abb2552a8c2bcc96e33481e7.nq.gz
│   ├── c27f98e5eb9d5bca15392d8d7c08afbd0403ab52.nq.gz
│   ├── c2d3ebf7b017a160350d234cf0cf1f9317468a6a.nq.gz
│   ├── c92f636c50989efc31c08b7561f6037eedb662c1.nq.gz
│   ├── ca76bcc338ae4eda086eccb6c79ceaa408d5f1a8.nq.gz
│   ├── cac971fcb7429fa81c626d6aac47c0b5824b5901.nq.gz
│   ├── cf5744ae8c5695ff766028c8ba405b71517e7674.nq.gz
│   ├── cffb52fe32a51021415756b5f9f132efaf9d2a28.nq.gz
│   ├── d03ae10bc6eba5d2e338fc81b791d9a333f09e06.nq.gz
│   ├── d47e3612b2754f862a48b2875f39367a43d2d53d.nq.gz
│   ├── d57fb811f8d5e25e9ec805670fefc8ef0cbd8ff7.nq.gz
│   ├── d8ce9a2a5180cbdf5aa4b1306e519d1199a983db.nq.gz
│   ├── de2bd5cb96daab6c82b4997b3d9813eda859a8bb.nq.gz
│   ├── dfafc214ee80ca4b328a85780cb2a765cc7aa63b.nq.gz
│   ├── e287ae3edab50dcaf82c9a1109d7ed62f4274609.nq.gz
│   ├── e33e7bda7be1badb80fa72088347fdb30bc0bb87.nq.gz
│   ├── e87d957b7c78d29680ec9a9cf7abda12fc9e66e2.nq.gz
│   ├── e90d6ce30345b3b7513ac8ab238f23e20b544f73.nq.gz
│   ├── e9e32c4fb44f79861e8b6b725a1994d753137ffb.nq.gz
│   ├── f099fbb2cdc3aa3569b2dfe96becaad608c5bf35.nq.gz
│   ├── f21dd00d858e47e050ae55abf1eb3f66a69f0312.nq.gz
│   ├── f468d63b1376f5be81f1182eed8ec79ed7c34209.nq.gz
│   ├── f529c6483fab343f0c8685984de685e7d05e150f.nq.gz
│   ├── f54647b6e2792e90d77faed6841f9cec97cefe47.nq.gz
│   ├── f83c3bf40ce8ac66e66410673564b090880a8624.nq.gz
│   ├── fa7ccaf6aad83fda9f03815ee7c6ca679089cd6a.nq.gz
│   ├── fa834097d761d831725adc60ca183d5c5f92968d.nq.gz
│   ├── fc11843b0a29e8e1eb326b8c03da37a371548a9e.nq.gz
│   └── fe98cfc0cd9e25601d449e1037c41ede01b1df4b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c71bd53a351d99dca12f0808ea7e1c7134ec4945.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 129 files
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

[shadcn-ui/cn](https://github.com/shadcn-ui/cn)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
