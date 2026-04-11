# Repolex Knowledge Graph of ljharb/qs

RDF knowledge graph data for [ljharb/qs](https://github.com/ljharb/qs), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download ljharb/qs
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 05b0e9cf2251a66cb68a2823cba930d184267fc9
│   │   │   └── chunk-001.nq.gz
│   │   ├── 062334aa584809829822c077f5f9f41c1e253dab
│   │   │   └── chunk-001.nq.gz
│   │   ├── 0db55386013a5d92503944ad42022fd8c112c983
│   │   │   └── chunk-001.nq.gz
│   │   ├── 0f2b1e2806628463f32f580b8a23a4a168bb9008
│   │   │   └── chunk-001.nq.gz
│   │   ├── 125e103b61f2bef245970f5a2a8dceffe5aab59a
│   │   │   └── chunk-001.nq.gz
│   │   ├── 179fafc920123e60466a1729f9f2b43b2fd67212
│   │   │   └── chunk-001.nq.gz
│   │   ├── 1aa4bd9bc950de26645210cbc063a48e7d289450
│   │   │   └── chunk-001.nq.gz
│   │   ├── 29dda211e8b02654f60975bdb703bcc73a8ee409
│   │   │   └── chunk-001.nq.gz
│   │   ├── 32dcc637f90be175c0d4617b429263115a87e3a8
│   │   │   └── chunk-001.nq.gz
│   │   ├── 34af57edde61639054ea7b38fdfce050cffdab29
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3a6d9f8e298703028bbd426a3bc49a1fb6a66363
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3fa11a5f643c76896387bd2d86904a2d0141fdf7
│   │   │   └── chunk-001.nq.gz
│   │   ├── 408ff95f1ab94ea73027bc8a7443afb62d41a72d
│   │   │   └── chunk-001.nq.gz
│   │   ├── 410bdd3c8ae7f5d7ae9b52648b8642b8adc5e1c0
│   │   │   └── chunk-001.nq.gz
│   │   ├── 47247f4ec3b527e5f71551fb6af5434672ecf756
│   │   │   └── chunk-001.nq.gz
│   │   ├── 479d4b189a0da939110b59344eb87daad7f081b3
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4cc653c08c583c0b39e2eea0bf1cd2226ac5ec51
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4cd003291fe3b347884f797e548b58a12150a0e3
│   │   │   └── chunk-001.nq.gz
│   │   ├── 511e1c9e527679ca182b055895ce301ea82213ee
│   │   │   └── chunk-001.nq.gz
│   │   ├── 56763c12ec4fbf723333cbb32371cbd386c33cbb
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5cf516c0dd557d85d5f18d4a916c96cd9cfc2305
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5e1c72c13fe2be3bc18eb479fb9ac918aa70d623
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6302f3539360edbd3a157634b2ca2c0c885af9d8
│   │   │   └── chunk-001.nq.gz
│   │   ├── 670254b63fc7770894eed9a0f020bc0b72698ce3
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6ccb8806887c79b51f9302614799ee3d88ae54ac
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7b368004723b8d11d4d237ff0479b9edcfb41449
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7c1fcc53047ed2d7555910fbce9f72eed1e450b1
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7ebe4ad78f6abc9fcc15bdfd0e5a9a771b855cf5
│   │   │   └── chunk-001.nq.gz
│   │   ├── 808b0b233e9408e0b5a7d7d19eb01093944240c5
│   │   │   └── chunk-001.nq.gz
│   │   ├── 834389afb51ac8cc03a22a0c76604c65776dc468
│   │   │   └── chunk-001.nq.gz
│   │   ├── 85cc8cac6b444c9b4cb1172a151ac8fdee0a0301
│   │   │   └── chunk-001.nq.gz
│   │   ├── 896fe4b2d8470f571b66dd838192e31497559938
│   │   │   └── chunk-001.nq.gz
│   │   ├── 8e014a7b1749ccec52104121950e7b0d251caa78
│   │   │   └── chunk-001.nq.gz
│   │   ├── 92f97f25e40bcc7cb3396ddc2ea813bcac0b4dac
│   │   │   └── chunk-001.nq.gz
│   │   ├── 95bc0185e157d400da4f43f1fcf1c7f008fd847e
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9d85d24e92a4e1de993290ad51ae2603888bdf14
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9dca37f15de317fe9ad0ced907cdf250ba310880
│   │   │   └── chunk-001.nq.gz
│   │   ├── a67173ec4573acd0b00037e630a34c9a53554886
│   │   │   └── chunk-001.nq.gz
│   │   ├── b522d2e9993a47afd810ed9a19d35aadb6323988
│   │   │   └── chunk-001.nq.gz
│   │   ├── b70bd5bc7441889bfdc266733c09ab9f09647433
│   │   │   └── chunk-001.nq.gz
│   │   ├── ba9703c0340dfdeb73cb4387d6ab32c37768aa5b
│   │   │   └── chunk-001.nq.gz
│   │   ├── bdcf0c7f82387c18ac8fabfccd2f440645cef47b
│   │   │   └── chunk-001.nq.gz
│   │   ├── bf93c5719c88e4c7ace17d747c62844988a65018
│   │   │   └── chunk-001.nq.gz
│   │   ├── d0dff11f06be1b2588e62865f5e4aa91f2dabafb
│   │   │   └── chunk-001.nq.gz
│   │   ├── d38e43af76c6fa7405f70a49726603d917f1e31e
│   │   │   └── chunk-001.nq.gz
│   │   ├── d60bab35a42b3c789d7a1461ea176eaee74eb751
│   │   │   └── chunk-001.nq.gz
│   │   ├── d8a8ab38a06f244bc9adfd43636f96c873bc8107
│   │   │   └── chunk-001.nq.gz
│   │   ├── d9b4c66303375493c68c42d68e363e50b1753771
│   │   │   └── chunk-001.nq.gz
│   │   ├── dd0f954e4c00b02915f4cdc3ee5174ebc351f1c8
│   │   │   └── chunk-001.nq.gz
│   │   ├── ddc1ff9ca16a4b8963d7cf72d0a881732e54b8c9
│   │   │   └── chunk-001.nq.gz
│   │   ├── f1ee0376c1dfd06606520f3268ee0c5f3aaece65
│   │   │   └── chunk-001.nq.gz
│   │   ├── f90cc35dd65c7099c35ae75d7a1a67aab85220e1
│   │   │   └── chunk-001.nq.gz
│   │   ├── f92ddb56089ae2c74f5ca7b0447fef3a97e8c9bc
│   │   │   └── chunk-001.nq.gz
│   │   └── ffc12aa71030f508ab28cccbb1987424abf52379
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 05b0e9cf2251a66cb68a2823cba930d184267fc9.nq.gz
│   │   ├── 062334aa584809829822c077f5f9f41c1e253dab.nq.gz
│   │   ├── 0db55386013a5d92503944ad42022fd8c112c983.nq.gz
│   │   ├── 0f2b1e2806628463f32f580b8a23a4a168bb9008.nq.gz
│   │   ├── 125e103b61f2bef245970f5a2a8dceffe5aab59a.nq.gz
│   │   ├── 179fafc920123e60466a1729f9f2b43b2fd67212.nq.gz
│   │   ├── 1aa4bd9bc950de26645210cbc063a48e7d289450.nq.gz
│   │   ├── 29dda211e8b02654f60975bdb703bcc73a8ee409.nq.gz
│   │   ├── 32dcc637f90be175c0d4617b429263115a87e3a8.nq.gz
│   │   ├── 34af57edde61639054ea7b38fdfce050cffdab29.nq.gz
│   │   ├── 3a6d9f8e298703028bbd426a3bc49a1fb6a66363.nq.gz
│   │   ├── 3fa11a5f643c76896387bd2d86904a2d0141fdf7.nq.gz
│   │   ├── 408ff95f1ab94ea73027bc8a7443afb62d41a72d.nq.gz
│   │   ├── 410bdd3c8ae7f5d7ae9b52648b8642b8adc5e1c0.nq.gz
│   │   ├── 47247f4ec3b527e5f71551fb6af5434672ecf756.nq.gz
│   │   ├── 479d4b189a0da939110b59344eb87daad7f081b3.nq.gz
│   │   ├── 4cc653c08c583c0b39e2eea0bf1cd2226ac5ec51.nq.gz
│   │   ├── 4cd003291fe3b347884f797e548b58a12150a0e3.nq.gz
│   │   ├── 511e1c9e527679ca182b055895ce301ea82213ee.nq.gz
│   │   ├── 56763c12ec4fbf723333cbb32371cbd386c33cbb.nq.gz
│   │   ├── 5cf516c0dd557d85d5f18d4a916c96cd9cfc2305.nq.gz
│   │   ├── 5e1c72c13fe2be3bc18eb479fb9ac918aa70d623.nq.gz
│   │   ├── 6302f3539360edbd3a157634b2ca2c0c885af9d8.nq.gz
│   │   ├── 670254b63fc7770894eed9a0f020bc0b72698ce3.nq.gz
│   │   ├── 6ccb8806887c79b51f9302614799ee3d88ae54ac.nq.gz
│   │   ├── 7b368004723b8d11d4d237ff0479b9edcfb41449.nq.gz
│   │   ├── 7c1fcc53047ed2d7555910fbce9f72eed1e450b1.nq.gz
│   │   ├── 7ebe4ad78f6abc9fcc15bdfd0e5a9a771b855cf5.nq.gz
│   │   ├── 808b0b233e9408e0b5a7d7d19eb01093944240c5.nq.gz
│   │   ├── 834389afb51ac8cc03a22a0c76604c65776dc468.nq.gz
│   │   ├── 85cc8cac6b444c9b4cb1172a151ac8fdee0a0301.nq.gz
│   │   ├── 896fe4b2d8470f571b66dd838192e31497559938.nq.gz
│   │   ├── 8e014a7b1749ccec52104121950e7b0d251caa78.nq.gz
│   │   ├── 92f97f25e40bcc7cb3396ddc2ea813bcac0b4dac.nq.gz
│   │   ├── 95bc0185e157d400da4f43f1fcf1c7f008fd847e.nq.gz
│   │   ├── 9d85d24e92a4e1de993290ad51ae2603888bdf14.nq.gz
│   │   ├── 9dca37f15de317fe9ad0ced907cdf250ba310880.nq.gz
│   │   ├── a67173ec4573acd0b00037e630a34c9a53554886.nq.gz
│   │   ├── b522d2e9993a47afd810ed9a19d35aadb6323988.nq.gz
│   │   ├── b70bd5bc7441889bfdc266733c09ab9f09647433.nq.gz
│   │   ├── ba9703c0340dfdeb73cb4387d6ab32c37768aa5b.nq.gz
│   │   ├── bdcf0c7f82387c18ac8fabfccd2f440645cef47b.nq.gz
│   │   ├── bf93c5719c88e4c7ace17d747c62844988a65018.nq.gz
│   │   ├── d0dff11f06be1b2588e62865f5e4aa91f2dabafb.nq.gz
│   │   ├── d38e43af76c6fa7405f70a49726603d917f1e31e.nq.gz
│   │   ├── d60bab35a42b3c789d7a1461ea176eaee74eb751.nq.gz
│   │   ├── d8a8ab38a06f244bc9adfd43636f96c873bc8107.nq.gz
│   │   ├── d9b4c66303375493c68c42d68e363e50b1753771.nq.gz
│   │   ├── dd0f954e4c00b02915f4cdc3ee5174ebc351f1c8.nq.gz
│   │   ├── ddc1ff9ca16a4b8963d7cf72d0a881732e54b8c9.nq.gz
│   │   ├── f1ee0376c1dfd06606520f3268ee0c5f3aaece65.nq.gz
│   │   ├── f90cc35dd65c7099c35ae75d7a1a67aab85220e1.nq.gz
│   │   ├── f92ddb56089ae2c74f5ca7b0447fef3a97e8c9bc.nq.gz
│   │   └── ffc12aa71030f508ab28cccbb1987424abf52379.nq.gz
│   └── repolex
│       └── 3a6d9f8e298703028bbd426a3bc49a1fb6a66363
│           └── chunk-001.nq.gz
└── blob
    ├── 0126380439e6ac357a8e77958d80be7f0f6fbe58.nq.gz
    ├── 017c2b3b6aea5c7f5a270dfc4340cfe549486389.nq.gz
    ├── 027aed07975a5c299c50a1d9d77f1519103e45ca.nq.gz
    ├── 02a6b504fc9c96e65d8c7a8a766acfe6646b692d.nq.gz
    ├── 02d5d1cc4b1332d2d2526dfd4cc23fb6fabf5d22.nq.gz
    ├── 02f0e68e3ca407b84af7a7ef4c95c89f5dae7723.nq.gz
    ├── 0355f4f5fbecd763def967aca1130cd2dfbb3479.nq.gz
    ├── 04493e1df3753f520ebb33c006a02ca6793b3cbb.nq.gz
    ├── 0483dda9babedd59298764bd66053c8d906e4a02.nq.gz
    ├── 0483f15cf9bc58dc5b0a188b9227a9a2393e6370.nq.gz
    ├── 053fe1f27f7fc498d280f005ea7288cb03c82886.nq.gz
    ├── 057adc85d9dc2090cdfdacd0f358038e121b45d8.nq.gz
    ├── 08335520a6181d7d9322295e8a35f06994f4cbad.nq.gz
    ├── 083e220ae956cd0089f049f946fd450f114466a2.nq.gz
    ├── 097ed3da6d699875dfc6b6fb8a20d70dce71af77.nq.gz
    ├── 0980c9ab65482f02145d7b7c15153e14c51fb19c.nq.gz
    ├── 09e2cc9eb189f976c67f9956dde763b3bbe0a545.nq.gz
    ├── 0a6504c3fb759615acbeb3ace41c27c9c6529118.nq.gz
    ├── 0bdc26eb153d6e2517981cae6f42da7be09f99ad.nq.gz
    ├── 0c6a66683dda1faabd1ea33044d5b75fa6af7ffb.nq.gz
    ├── 0d304ea49f527c880cc2338781bcc44bcd00c3a0.nq.gz
    ├── 0d412559a6bf5eb661925d6f67c0c3227179b0c6.nq.gz
    ├── 0d4aecffd121907471c7d1ff05445288e18a573a.nq.gz
    ├── 0d55d416f968c0cc0ee90ed740fcb76c485df0bb.nq.gz
    ├── 0d6a97dcf096449e7100cb63bb05f232a7f790a5.nq.gz
    ├── 0e397620c337252554b36902636f8226635cbbe1.nq.gz
    ├── 0e440f42ddf58ec244b5c5baf14497ffe7ef9c9b.nq.gz
    ├── 0ea91d99525e60ae962a12108a8e529ce6bcfa32.nq.gz
    ├── 0f8df7c2fec842dae5db06661ae0b0b7a9f9b693.nq.gz
    ├── 0fcaddbe7f5c1059d1494721410915ea47b31935.nq.gz
    ├── 106c0c16af4b42af3368f5ac63fe8d5acd77bff5.nq.gz
    ├── 10d7e1b1ce278dbb40dcd4607a69a7e805247471.nq.gz
    ├── 11a9db5c1272855abaa0956858067cdb12b5da96.nq.gz
    ├── 11be8531dd587984a378408c61dee80057842c63.nq.gz
    ├── 124fa8428796e9e0a8e0907835c9c516105ede6a.nq.gz
    ├── 128346575f114a6665dddbd40e487daec0550123.nq.gz
    ├── 12a96e658fb442cf9432ee90d759a4848d452e2b.nq.gz
    ├── 12b1c71d6dc3be9e254a58a5d1540a79675b307d.nq.gz
    ├── 13e2c77cfc1bc190c40896f95c4240f4de5dd46f.nq.gz
    ├── 14254193b16be26f7c49a3cef90c9b508c549d0b.nq.gz
    ├── 14bec39220dd1063b3f5414222d618c66152bdd7.nq.gz
    ├── 1521c8b7652b1eec8ed4fe50877aae880c758ee3.nq.gz
    ├── 154e72e575b03030c71cfb3caf4a66855d2750ac.nq.gz
    ├── 16461736aee6b21bc267b48bfa3193577466656c.nq.gz
    ├── 1696baf1755d2c1e03eccda6d2cb3f92b51fef82.nq.gz
    ├── 173b241556fbc9f74ca30d2cd5cf07abcdb4cac8.nq.gz
    ├── 1751c7bee4cd98e7b943ceabd15d31c9fddedff1.nq.gz
    ├── 17c1ba2a2f720a4d740831c1a1126e8208534a13.nq.gz
    ├── 1809f526847bf0759697e5c63255e71729317191.nq.gz
    ├── 181819135f69aec6b0e08fe8aa38e4212504dc94.nq.gz
    ├── 18b7986f5a9bbdcf92d06b0970a680003fdd337c.nq.gz
    ├── 193fb7389686eac923b5a9c51a980b78a6844a61.nq.gz
    ├── 1a58d9a8128320bd86f6a2ed11fd47866eb0319b.nq.gz
    ├── 1a5da02c0c8704f11015191d61917fe58c98fbd7.nq.gz
    ├── 1b219cdde29d5624858b592f89f4badf17fb0f43.nq.gz
    ├── 1bb4ffcd6d4a8dde2778a2f4855b037ebea5f547.nq.gz
    ├── 1c4b85b756a968f4fcad0e76cbf67cad78113510.nq.gz
    ├── 1c620a48d38da78120ae19850e9a00c1e17b9b0a.nq.gz
    ├── 1cee149d7bc661ef8fffdacd6560b918f379ada7.nq.gz
    ├── 1d57cabe1b647c742d82f896933bf4af5dfcdc0d.nq.gz
    ├── 1e0d9adc482d3b0c844953186373b09069c552ae.nq.gz
    ├── 1e545381131a9665a5561d22fc0cfe05d5a60315.nq.gz
    ├── 202dabbb86702e6752643d6c387218cbdea0a62d.nq.gz
    ├── 209e157244b598c806b489b7c14ca56164b23832.nq.gz
    ├── 20c91d36b09a5c12d6dc622bcf284df507ef6e0f.nq.gz
    ├── 213adb267e088d24bcbc6ad82a865a94a8c48955.nq.gz
    ├── 218f3e4cc393da78a8f233c636de15441489bb0c.nq.gz
    ├── 22a08a2df8f110d20af1241bca737da5323dc126.nq.gz
    ├── 22c411dfecac6adc7e821b34f5c44b0d2c815f78.nq.gz
    ├── 22fcfda2d042d4f2f3f4ae03b77e4c9bd5938f7c.nq.gz
    ├── 234241e23cc260cf656b259c09fb015211873689.nq.gz
    ├── 23ae201d0ec459e1bb751791b0cf7d003204ad31.nq.gz
    ├── 23ca99c4e78c965e0ea014812dfa23f4743aedda.nq.gz
    ├── 24183cc487de8513b60204b3a9e55f12ebfd0488.nq.gz
    ├── 24519a9c928bb27076471ef79e982fca3b7884dc.nq.gz
    ├── 2585e8a92477f1e52b2816d5555670c5ed3773c3.nq.gz
    ├── 25fd472ad13c221a316db86113eba86c8acc8ae4.nq.gz
    ├── 262c7fa638bef13171d445f24fa1bf67111f69db.nq.gz
    ├── 26328b1baaa3ca827bd36c34708cb19ef574fb80.nq.gz
    ├── 2666eaf9c6a3cc03840c5b56011a24c345927fc0.nq.gz
    ├── 268d5b4cc46355c20aa9a7bb477ab7437d8cb02e.nq.gz
    ├── 26caf6a7021b796fd0d2521be2bfbb5f9d024918.nq.gz
    ├── 26e48e96b74993094e2168ac7ae3462dd5334a53.nq.gz
    ├── 2710bad0203eafd6c86b45c282dac5d741499032.nq.gz
    ├── 272575cb7ce8310025a32cea16373fb517ee2898.nq.gz
    ├── 28d98a11bb16e70ee9dfbe590fb1bcae4b522e1b.nq.gz
    ├── 2905ff0177dff27ee130cdef0486bae9ead72c7d.nq.gz
    ├── 292039d1d12177365446845dc0d5d2b2dd49de15.nq.gz
    ├── 2aa1c485ba631ed86bb79f3c62c80635c1c87790.nq.gz
    ├── 2aa668c61d557190fc1c755a17e4ef3defd0d025.nq.gz
    └── 2b1190ef5a4fe07d96e137a062a5eb41c1170e35.nq.gz

61 directories, 200 files
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

## Source repository

[ljharb/qs](https://github.com/ljharb/qs)

---
*Parsed on 2026-04-11 by [repolex](https://repolex.ai)*
