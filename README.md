# 番茄免费小说 GKD 补充规则

配合 [id667 订阅](https://gkd667.vv.ax/gkd.json5) 使用的番茄免费小说补充规则。

## 订阅地址

国内推荐（gh-proxy 镜像，已在 GKD 实测可订阅）：

```
https://gh-proxy.com/https://raw.githubusercontent.com/chen-pi-2007/gkd-fanqie-fix/main/fanqie_fix.json5
```

可直连 GitHub 时：

```
https://raw.githubusercontent.com/chen-pi-2007/gkd-fanqie-fix/main/fanqie_fix.json5
```

> 国内网络下 jsDelivr 会被重置连接（Connection reset），不建议使用。

## 包含的规则

| 规则组 | 说明 |
|---|---|
| 功能类-听书时长不足自动看视频领到上限 | 时长不足/用完时自动打开领时长面板，连续看视频领取；不点含「畅听」的特殊奖励 |
| 全屏广告-番茄红包弹窗 | 关闭「番茄发来的红包」弹窗 |
| 局部广告-右侧悬浮红包挂件 | 关闭「登录领取/登录赚钱」悬浮挂件（兼容两种界面实现） |
| 功能类-看广告自动静音 | 激励广告开始时点一次左上角喇叭 |

## 注意

- 需要较新版本的 GKD，旧版不支持 `~=` 正则等语法，会导致规则不生效。
- 开启本订阅后，请在 id667 订阅的番茄规则里关闭以下三组，避免重复点击：
  - 「功能类-看广告自动领奖励」
  - 「局部广告-首页右侧悬浮广告」
  - 「功能类-观看广告自动静音」（两边都开会点两次，又变回有声）
