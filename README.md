# 个人使用的 Clash 内核的覆写规则配置

仓库结构:
- `directRules.list`: 一些用于直连的匹配规则集
- `proxyRules.list`: 一些需要经过代理的规则集
- `rejectRules.list`: 一些需要拒绝的广告/追踪规则集
- `example.js`: Clash Verge 的样例脚本

android端的flclash也可以使用, 只需要将开头的 `function main(config, profileName) {` 更改为 `const main = (config) => {` 即可
