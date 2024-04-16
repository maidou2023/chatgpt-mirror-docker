# Changelog

## [1.2.1](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/compare/v1.2.0...v1.2.1) (2024-04-16)


### Bug Fixes

* remove unused ctx ([60b472a](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/60b472acd097efb13d9577b89b34ad229fa66e47))
* 修复标题获取失败导致无法保存聊天记录的问题 ([af78fe2](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/af78fe2718ee771ae2b45def7efb775adfb26cf4))

## [1.2.0](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/compare/v1.1.0...v1.2.0) (2024-04-16)


### Features

* 增加ws的兼容 ([45e87aa](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/45e87aa550962cd002db7592ac5ee151018c7387))
* 适配最新的gpts store ([2aeb536](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/2aeb536128b1fda191652d645a53d8282552fb31))
* 增加JA3_PROXY的配置，配置项目在config.yaml或者环境变量增加JA3_PROXY


### Bug Fixes

* remove any console ([22e2cbb](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/22e2cbb695703e2e59507867ac5176f63129cd90))
* update ui version ([c2cf4d1](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/c2cf4d1624dd4ff0a8497c6f798195167935557e))
* 修复点击gpts页面白屏问题 ([2aeb536](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/2aeb536128b1fda191652d645a53d8282552fb31))
* 修复网关地址问题 ([b12d4d1](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/b12d4d18240d9f57b803f815a1b48da45339db46))
* 修复账号保存后，无法自动更新token ([fbbccc1](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/fbbccc1e22b7d6004c87267221815a7b46bd159a))
* 修复账号密码登录的错误问题 ([8c424fd](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/8c424fd55360ef6ca8cc3b85539af5d076ed0453))
* 修改一些细节 ([fbd43e1](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/fbd43e1f59649794dc2f9b6d9111d581da0cb8f8))
* 增加JA3_PROXY的配置，方便后续更新 ([d8633a8](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/d8633a86755111247835629be5d31831c52eee86))
* 增加websocket代理地址 ([b30f4ba](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/b30f4baf595d9e93f260a91959b8423f41544b53))
* 调整一些调试日志info-&gt;debug ([bb9d470](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/bb9d47055e78a39023ee41cfd053a26ff9f6df51))
* 调整部分细节 ([eed4abb](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/eed4abbebf1d412c2a1ffe233cb6b01671049f5c))
* 适配最新的gps的UI ([0d38e0b](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/0d38e0bdd32662979943b8c196382b5a9310f345))

## [1.1.0](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/compare/v1.0.0...v1.1.0) (2024-01-06)


### Features

* 由于独立计费，所以增加gpt4-mobile ([6b70eb4](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/6b70eb4cf4b0b1a99d4e0bd1b938641af8613ba3))


### Bug Fixes

* 修复Prompt的错误，同时汉化 ([7b63e30](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/7b63e30ffd3d4ab9b100011f68dee56979287b02))
* 修复自动登录的问题 ([2fa28f7](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/2fa28f70a6de71a953e74db0d817801d128183cb))
* 修补部分接口未对接造成的异常 ([48a289d](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/48a289d2a8a84fc71141027e9e57ad31df0f8e19))
* 删除无用的next ([42f6f65](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/42f6f6579b1ccd67ed13c323198b3592fde31b30))
* 增加授权码，增加开发使用的网关 ([d397396](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/d3973966d90338d8979e6e8cd28d3ad2ff1951ca))
* 引入账号关联会话机制，切换账号等于切换聊天记录 ([62002b3](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/62002b3f4a6bc4896f51debd31fa0ba97278b86d))
* 测试prompt ([b9ab10a](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/b9ab10a46d9d2495b2e6d308b9e191e911439f77))
* 调整会话ID的唯一 ([7d14825](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/7d148252c41dc278203d2b3e7f2a30a55e6281e2))
* 调整部分细节代码 ([7ab3246](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/7ab32464b760f3793b83df5076f11e25122a0d27))
* 还原配置 ([0583439](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/0583439665dae4f5447dd6db6af6e8df3aae6bd4))

## 1.0.0 (2023-12-05)


### Features

* openai账号增加手工刷新，自动shuaxin ([b7d155d](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/b7d155d4744f571bfa4b7ede511ff3d1a4eda1b2))
* 后台增加会话隔离，账号密码登录 ([b7d155d](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/b7d155d4744f571bfa4b7ede511ff3d1a4eda1b2))
* 增加github-action/release ([d958a85](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/d958a85e878c179001345f38fb8d9fdf962e221a))
* 增加share能力 ([9303c26](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/9303c26e8916faea58f2695c01e6c667a5c770d7))
* 增加支持品牌化 ([b29fe27](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/b29fe2765fc36f08345bf0f708cbdc4d8b9ef6f8))
* 增加文件服务的代理 ([f6c4929](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/f6c4929d0169a1d9a51b1ce0f02f150ade06c6ef))
* 完善登录逻辑，sessionkey刷新机制 ([5366720](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/5366720a6f2ba7aad32cb16cefd728be5347d017))
* 完善聊天隔离 ([b9c6097](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/b9c609729c5e5f3ee912e09543f6a3861492d529))
* 支持不同用户分别配置隔离 ([eab169d](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/eab169d5ca72b5eecf002562e5afbaa4dd639e82))


### Bug Fixes

* 修复STATIC_CDN_URL变量 ([46e6efa](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/46e6efa31dcd634275a833e6011836539be0fa57))
* 修复删除会话错误 ([a7cb72b](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/a7cb72b6fe27d0c389ab335f5d04cc0e4c67b1b7))
* 增加静态资源的CDN加速，更改ArkoseUrl ([31a7537](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/31a75376ed05d22456078f4b1a99e10e1a514454))
* 支持同步删除会话 ([d343f5a](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/d343f5a1caaacfd508ea45b1098afd8c98eeadfe))
* 改成GITHUB_TOKEN ([7873f84](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/7873f84d7d3d227e6b61ebeef7b54394a655678e))
* 更新arkoseurl 缓存记录 ([fde264b](https://github.com/liuhuapiaoyuan/chatgpt-mirror-server/commit/fde264b0d12d14fe9831a9725c9d7c1624d43973))
