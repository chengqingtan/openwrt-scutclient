# 自用软件包合集
* 源码来自 https://github.com/scutclient/luci-app-scutclient 和 https://github.com/scutclient/scutclient
* 在 feeds.conf.default 内添加以下一行即可
```
src-git scut https://github.com/chengqingtan/openwrt-scutclient;main
```
* 如果原仓库里已带有 scutclient 和 luci-app-scutclient  ，需要在 `./feed/script update -a` 后删除原仓库拉取的插件并修改.mk文件
