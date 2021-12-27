# 仓库说明
项目从 `chongshengB/Padavan-build` 处 Fork，修改为适用于 CR660x 路由器 Padavan 固件自动编译。即，点击 start 后利用 GitHub Action 自动编译 `hanwckf/rt-n56u` 仓库的 Padavan。

路由器型号为 CR660x（即小米CR660系列，我自己的是CR6608），自动编译精简了用于 KMS 激活的的 VLMCSD 组件、用于 Drcom 的 DOGCOM、OPENVPN、用于 IPTV 的 XUPNPD。

同时将路由器后台地址修改为 `192.168.123.1`，其余均未改动。

以下为原仓库 README

# Padavan-build说明
现在不需要新建Release了，已经更改了脚本，直接fork，修改好之后，点击右上角的 Star 星星按钮即可开始自动编译（自己点击才会编译）。
