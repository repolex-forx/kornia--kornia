# Repolex Knowledge Graph of kornia/kornia

RDF knowledge graph data for [kornia/kornia](https://github.com/kornia/kornia), parsed by [repolex](https://repolex.ai).

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
rlex download kornia/kornia
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2d8b49be0308d1ccdc404b32a9fc72cbc8ea5c40
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2d8b49be0308d1ccdc404b32a9fc72cbc8ea5c40
│           └── chunk-001.nq.gz
└── blob
    ├── 0003ff9a63b4e79ce22f2a0ff02a424abaa3c248.nq.gz
    ├── 004e37d42ebc7fe42c26fdf26dce15cfa80e09e7.nq.gz
    ├── 00d374eed4621e4ceda44e7f255c0b8cc21598bf.nq.gz
    ├── 013d78e7f7890fab9a9a6b3c98bcf1dcde8bd8c5.nq.gz
    ├── 0160871789a414edff9b49933eeb7a64bef3ed97.nq.gz
    ├── 01e051d2bb0cb9551641892c05542ea97fff5a32.nq.gz
    ├── 01e48334b4b5eb97ad91a7141fe466e518a094ea.nq.gz
    ├── 02544f1f63b3a7de176c6d8d6bb424e8dfef611c.nq.gz
    ├── 029fe2d0fd1927ba5f86a7f8b5ffb22351601fbb.nq.gz
    ├── 02c97e15894edfcb4c6295ef7c11a4f02ca42533.nq.gz
    ├── 032950337f483b20dca70c2de09c69b57ed95800.nq.gz
    ├── 04e86fa1b4cf47cf307cb7060d532f69b48ff772.nq.gz
    ├── 0627e83645828b15a1d23c2d2eb1e19bb44876e6.nq.gz
    ├── 072692abf0a0b6e9b8f5ac994b38aae701adc637.nq.gz
    ├── 078a4d697002610e4821b5182e820747d114b075.nq.gz
    ├── 07bb999d1e6b4bf8e8dd72e0a7bacd5de8482dc9.nq.gz
    ├── 07fdcb8d4c2457bbb9714e29dfb1e11d41dfc1ef.nq.gz
    ├── 09cab516bdbf6b6d7cef0466753f4265875e7711.nq.gz
    ├── 0c6bf568560111777c8e66a5ae15de8ef05147a3.nq.gz
    ├── 0d6758b2241cc4e1d9c9d18ccf956d0d4110bcfa.nq.gz
    ├── 0da35a8e8122048960540177c8bb96ebe3cc8fdf.nq.gz
    ├── 0dca83d7c1600846ffc59f9c70181243675ce293.nq.gz
    ├── 0dccf96a7a19179b168cbc3774bb543dcacc9224.nq.gz
    ├── 0dd41e3e96101e53665772e39afdef8cec1ab0a7.nq.gz
    ├── 0eed2312b8bd33cb570eac270578e94930149f0a.nq.gz
    ├── 0f0f5c1ef2116235104410b704ac85bd3423120c.nq.gz
    ├── 111fd965fd14e166ddc16e1e6c1ac66ef13ae6d1.nq.gz
    ├── 11f9d0a0255a4a11ffb21d9e349feda2cde6df53.nq.gz
    ├── 1256612e21b4e3a197a52498a81be66144164387.nq.gz
    ├── 1274e19bab0d7c36281a240263a335df8811d719.nq.gz
    ├── 12a915b211ed52cdc3b9b37a8cff8a415425eb4d.nq.gz
    ├── 12ad544fe50783daaf02c194b0c02a28dc41d005.nq.gz
    ├── 13b77ddaa9ad339306bfce36d4e019e4473f8c7c.nq.gz
    ├── 140a95a3be5f38071bf90e81e5cbe4d0ff592d41.nq.gz
    ├── 150460edab9b46ff2e9a0be4050631bd4c4c5ae3.nq.gz
    ├── 16678393105246d19e8f5addc012ca990b6b2048.nq.gz
    ├── 16aefd225cbe25dab219ef1580f40ea1eb64fc03.nq.gz
    ├── 16fba0939bfe37a6ca412c519071dc4689cb7a17.nq.gz
    ├── 17988ce14074c3962503881f61a8569ce0108b57.nq.gz
    ├── 17f0d912e8f8f7b559a7eef67e1273d568b579be.nq.gz
    ├── 187623b7a8957c34fe2ae26bede38768f160ced0.nq.gz
    ├── 188a129b282c24dc0588e44084923f1f0b78bffa.nq.gz
    ├── 1916d964fed20ed04b7913572ed69f1d118cacba.nq.gz
    ├── 196e815bd04db7abd82cd41fdc65fce0bfaf420b.nq.gz
    ├── 19e582620092fde203823cfd82036ec126bf1d59.nq.gz
    ├── 1a7c8f8c8b51edfd5bd3774d8c2abb5a1bad15bb.nq.gz
    ├── 1a8b21b21feff0ff0258192b2311c22826243e1e.nq.gz
    ├── 1ae15c450f41645e6f8eaf1e17132f1cc679b072.nq.gz
    ├── 1bf229f08ae720a6a56ccf5671dd724eb32bbc40.nq.gz
    ├── 1bf706a796ebc5db3b4d5de437b92ac809b27d99.nq.gz
    ├── 1c2952caa0077929ac9becb38e1cf936bf79123b.nq.gz
    ├── 1c4c580041b0c4203dd461ce077e8a41833686a5.nq.gz
    ├── 1d0d305f7cb0019aaf06c482876430a1ac0c7cf3.nq.gz
    ├── 1dd36f11d7a1d80417ac8ec0e1efcc1016333e12.nq.gz
    ├── 1e86d832b0733839429503b2545ffece6d4769f8.nq.gz
    ├── 1e8d04e1bed103a3de248634608fbe6562926401.nq.gz
    ├── 1fb1bea8af22c4f9f860a925827f2282a4d4b34c.nq.gz
    ├── 20531dd760708fd1f7110999fa476ddff312c949.nq.gz
    ├── 2086a0b27140a16e43cb22f94b6e4bcfe982ad8d.nq.gz
    ├── 217aa92ca9202a05b29453fef1b24a88b1c4ca17.nq.gz
    ├── 227bc84e735c852b2cd550c53cc0e46bdedad798.nq.gz
    ├── 228bccd467a3e9d2c0687f3a1307e12212090d5b.nq.gz
    ├── 22db5583605b9c6205dfb15d02046b65913e3c0e.nq.gz
    ├── 22e0f062007f2650ca0f2c33e5e1b8ed200e177b.nq.gz
    ├── 234955a281c079133a12e649d30147b1de6bffea.nq.gz
    ├── 23bc4a447be8072ec57c2ef8dcf896f614fc5a1a.nq.gz
    ├── 245e7e6a891d6f8efbbd75972d442e79cc547f53.nq.gz
    ├── 24d7e2f7e2ddb69e7eab99bb7d03abcd8cc7f49a.nq.gz
    ├── 25cfa7662266bbf041d1d4dcf0b563be133f009f.nq.gz
    ├── 265db01a794383dcc4998336c2f258063c19228e.nq.gz
    ├── 2737c73a1d0769d520932b079fe9541e65841f72.nq.gz
    ├── 284cc738cca12d6aa7d4a8b6fb3559f970109d5d.nq.gz
    ├── 28c8d2f12d505bd40370577456ab1b9236fe4d4d.nq.gz
    ├── 2911d30085ccccc34b11d07e7adef238712f87ad.nq.gz
    ├── 2979f8ec40182e937e59e4c8904913da40124b8d.nq.gz
    ├── 2a73b637523006392a72ff4770fcd1511e9665a5.nq.gz
    ├── 2a94b699c897d3ec28cdf03db81c781a877d18e7.nq.gz
    ├── 2b97df77376f0760d38b8ce92cd5610c9995967a.nq.gz
    ├── 2be21ab41a83cdf977bddaf0f626103d954720ad.nq.gz
    ├── 2c668c4666fa7cebea40ad816d787168c7f98985.nq.gz
    ├── 2c89d60169b8f788ac796731065fa41c87f1cbe4.nq.gz
    ├── 2dab6e232b46e519bf752493010d76e2d43f689b.nq.gz
    ├── 2dc499b49b332c92fb88baaa4fe72eacdd36683f.nq.gz
    ├── 2e27772e88a3d05b334fdc6f5addc997fa4c70d6.nq.gz
    ├── 2ea0306b7c30b90a6dbce805a504ef6b6852665b.nq.gz
    ├── 2ecec3750283e8ae315a4ff3be183b7e0814fb51.nq.gz
    ├── 2ee9d3c01dd50e6fd11a562c3d82f17163e5b592.nq.gz
    ├── 2f129405b6b0ef7cbca76dff6756549e6709c9e1.nq.gz
    ├── 2f29211bb7ab693c12a8a98e8e8172b3b3a63258.nq.gz
    ├── 2f6589a0cf9a02f40817c129425c93daccbe23c8.nq.gz
    ├── 2f97fe8e926f30220d704c2b04e75b1163b8bad9.nq.gz
    ├── 2f9ce23be5b1488126d5c73840273b78dd949937.nq.gz
    ├── 3076017794a2906927cd412d5d32c0e8732e1877.nq.gz
    ├── 3095943cd5d6dd05e44ae1b58a3ca934ca1bc392.nq.gz
    ├── 3113382df863d65d6d8c4f576c2ddafaa9ea8ce1.nq.gz
    ├── 31df08994478151bccd96b84b93ea617be855466.nq.gz
    ├── 3222cf2328fe3f3a5f479474e20b0fb31c0bc5b2.nq.gz
    ├── 337cf0b849b9d7d7291d07bed2b5a9a3678810d2.nq.gz
    ├── 342a617044b95bd13be278b6c8e542a87aa852db.nq.gz
    ├── 34c6d014914c4db53a2d6274be0092e868628951.nq.gz
    ├── 3604467681972969d3aeaa3f1de0d926051c9130.nq.gz
    ├── 362884cc945859a14e7288a6787699cfe40abe0f.nq.gz
    ├── 36700c4da6e2309711356e13f7122c118255e6d4.nq.gz
    ├── 36d8e24ff4e077c3b2ef2700322ce658496ddc20.nq.gz
    ├── 379c1ad206b48933a40a6219f4af2024d8a6f936.nq.gz
    ├── 37cf8958861035fbb5a1de896b804efdfe4ea5f7.nq.gz
    ├── 387eba295b944a2cd91d6b9329c3b13d5410aaab.nq.gz
    ├── 38fd416d23622f8d8108c211b937d46f1a026482.nq.gz
    ├── 39424bd5493949979c96798f210fe3fe566cf7ab.nq.gz
    ├── 3975738be6d4cf3f4df77cadbc41893dabb018ae.nq.gz
    ├── 39e14dd4208ff6378470fd76534739c5406d73d9.nq.gz
    ├── 39f4e52cc3f930698e9395b362e72addba086593.nq.gz
    ├── 3a3fa093a43be415785f0398f66d112f5fec9bcd.nq.gz
    ├── 3a936359a39794a9ab7104bbb0cec08b640033b9.nq.gz
    ├── 3ab4c8f5cffa7373ea1369d79a98b4ef080c4344.nq.gz
    ├── 3e029b6b3e25bd48674396c1c02ef72e6ad6e316.nq.gz
    ├── 3e70034cca7a5414229b4fcb41ea066c6750be83.nq.gz
    ├── 3eb734df41e9c6958440fa52da5f08421fcd1fb1.nq.gz
    ├── 3f462c524c17d938aca5cd19f874af67ba9801b0.nq.gz
    ├── 3f4854b1612dfe7a0d9d62c017c940a7a4195e45.nq.gz
    ├── 425ad22e328ee68161054823e78e0c30a840aa6d.nq.gz
    ├── 42d31c9dcdbf15f7314b2c22d0602354b24bb72c.nq.gz
    ├── 433e18b92d7f7ec04964399301d4ca8da2b0d6fd.nq.gz
    ├── 4356a3731060f23a51ecd6cc08779569db7720e2.nq.gz
    ├── 43fbe24cb42f4c7f92c6105f9a1bbd8cfe9d0b66.nq.gz
    ├── 44a7628fdad795d2d308a541704cf1af702dc691.nq.gz
    ├── 45445e3fbd0a6c1393d7f805716166823cf441af.nq.gz
    ├── 456ff15079c726ee697c80c90be912816874b2e7.nq.gz
    ├── 466c8aaa8b92f6a11cd378cd6364bd17805c2b24.nq.gz
    ├── 46c828e73210a180911cea385318f943469e4fcb.nq.gz
    ├── 46d888d32527d4208654cadbeac76a6f687e9787.nq.gz
    ├── 46e0247ec9ba5cba70fa59de075fe3c7c99c5203.nq.gz
    ├── 46ea792f2de46575330383ad41e43089c31f02d1.nq.gz
    ├── 473d179d049d4f3da7bbbd5d11248cb9ec9e7ec1.nq.gz
    ├── 49c18014d319a7a5033de1ea8e969d65a53073a9.nq.gz
    ├── 4aa04b7f1127516d94d940f6b67bc6412f7c525a.nq.gz
    ├── 4b3c0d77c96618e78543b1b0a99b6b3b67de2f1d.nq.gz
    ├── 4b9a5f64d88d96799fe3b9c439b769fc28e5ddfd.nq.gz
    ├── 4c0eb2136e223596560486ba540e3b77c662ce9b.nq.gz
    ├── 4cb7cdf89148de6937691afbe31a707d377a2dbd.nq.gz
    ├── 4cfc53f2180ab423d265d180cbcdf350a53756db.nq.gz
    ├── 4d273d5cba09827eabbe13c7f953f35f94a5f9ea.nq.gz
    ├── 4e1ae62451b1342ab63e45fd57680b911b50a922.nq.gz
    ├── 4e1c3092915631ed5a9262b54151e3ec92a436bf.nq.gz
    ├── 4ea6870199506926de4c32123d4d1425ce3ebe64.nq.gz
    ├── 4ea68a869c864d88d35124a02255c74d1159f315.nq.gz
    ├── 4eaebc2f4c3866c3c43e9600679e0c5765e013bf.nq.gz
    ├── 4f717bc48dcdb0a9a0f2a5b87e4b11c2cb9b9b15.nq.gz
    ├── 50549491aab68cc074b6eddd5efa08428ca022c1.nq.gz
    ├── 518cb416ea0efe92764fc70b8549c9270d28b73e.nq.gz
    ├── 51b1ac32680def23e9211f9cdfb62862c2e36677.nq.gz
    ├── 521a5f55fdb0c8dd8bf2c4dcbac78da1ffa6685f.nq.gz
    ├── 5245a2541b864d9e2782fc782883185493a3226f.nq.gz
    ├── 5273759eeb55e0e89c3f244abc72070b408e5048.nq.gz
    ├── 52eb3ed4d09ab7ba225b9607edef49b12bffc028.nq.gz
    ├── 535bbb6795faa57f282590692a601b3fbf6d42ba.nq.gz
    ├── 55124d971939ed576e2c2bdf2a6421cb72454b17.nq.gz
    ├── 55d5c245997f1dc9480496671c3dca49c33556e5.nq.gz
    ├── 56f1156b837f69710bd0524eecfbcde7561af455.nq.gz
    ├── 570b93483bcb38ecfe70f845fd8bcabb8ac568a7.nq.gz
    ├── 570e7e32792bea415fd886e6c8e2c5c6c5011b94.nq.gz
    ├── 573874b49abde09742cf8d9f3cb334f96b3b4603.nq.gz
    ├── 574a6c03e44094dc398f9ddfebdaf6eccb100a78.nq.gz
    ├── 579c329fe292dee341ad67d40543678482c765bf.nq.gz
    ├── 5833a4a35e243e7c3c26369beb52b0be3537aa14.nq.gz
    ├── 58c2f8cb0ea2d731af305cdcafe512d0bfc244b3.nq.gz
    ├── 58e99a519eeb2e023e998da808fcb52af5310aae.nq.gz
    ├── 5960d8e1dd93ac1e9455b753018fbc17779c385c.nq.gz
    ├── 598e6234fccf8c1501e9db3de3849499089cf183.nq.gz
    ├── 59c8bf2b347d5e246b1e9825b50552d032f6e715.nq.gz
    ├── 59ef9651cd6d6f691f2a7035d98772d9cf23a8dc.nq.gz
    ├── 5a896b4b6eb0057f389234573b6d957f04f76ebe.nq.gz
    ├── 5ab93621ac186788ebf3b5f25b0e0623c607c713.nq.gz
    ├── 5b11ef99ecec984c74c918647e84f079bdfdcb01.nq.gz
    ├── 5b339f3ca0d72af20f8790094ccbf925e6718efc.nq.gz
    ├── 5b7d8e873ecbf4a217c404344994797bd130424d.nq.gz
    ├── 5c104ad00e135ef7502d5bb161029e05481e366c.nq.gz
    ├── 5d81c815e503b35bd8e8f34d67d086c499e28ce4.nq.gz
    ├── 5e336d096cce4973efb5b0f26f552c8bb40a7c1d.nq.gz
    ├── 5e4aa31898e8b61f65c0691520573e748a203a86.nq.gz
    ├── 5e68f0b5dc6028292af37a53ecc5ef44950b5398.nq.gz
    ├── 5f53fc9c318124b8bd5772b3c26441c0228a44d7.nq.gz
    ├── 5f5ccd408e82b2eca5cd87fdea4d9fba66c5e066.nq.gz
    ├── 5f7dc36585c2a7db415130446a9966812cf4855b.nq.gz
    ├── 5fc7ab316038bb3aab61d76f4b5c9c0e109e5917.nq.gz
    ├── 600c1d5b35d3a32c7e5efec1bc4bc2173f1d9adf.nq.gz
    ├── 61788f899a205b2b17d2ab0ce7e963cd241d9f38.nq.gz
    ├── 621bae456dbf8c6c36882b3c67d8d15ef3472df2.nq.gz
    ├── 62379debe295e2088244df2cb3a9d6c56d48104c.nq.gz
    ├── 62af921f873fd000a10bc823ef8e5adda84c4a62.nq.gz
    ├── 63898781c1d74ff55e76e33343776693b3c40cfd.nq.gz
    ├── 646747c9da201e4fd621491d96aa51934dca86e3.nq.gz
    ├── 64f39d8552bf744138c1d8f25a0fe85db6564f7a.nq.gz
    ├── 6592227b9833ce0a1b9165e5d2c1789e6035a67d.nq.gz
    ├── 65ba81708f8cfb5a1acc94037a1a87276f06003c.nq.gz
    ├── 65d0a94ce344edb50d044b98cad09c94d8722a57.nq.gz
    ├── 6650808564f4cd529ed8cebb8108f82b41c33ec1.nq.gz
    └── 67717e557c52d983ef5c1f79f35a494fa5be8763.nq.gz

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

[kornia/kornia](https://github.com/kornia/kornia)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
