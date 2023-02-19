# 【qBittorrent】两款简洁美观的UI

![20230219215508](https://image.lckp.top/LuckyPuppy514/image/raw/main/2023/2023-02-19/20230219215508.webp)

![20230219220057](https://image.lckp.top/LuckyPuppy514/image/raw/main/2023/2023-02-19/20230219220057.webp)

分享两款简洁美观，适配了手机端，且支持中文的 qBittorrent WebUI<!--more-->

- 博客原文：[https://kutt.lckp.top/hTE34Z](https://kutt.lckp.top/hTE34Z)

🌟 建议阅读博客原文，以便获取 **最新内容** 和 **最佳阅读体验**

## 1. ⬇️ 下载

- vuetorrent：[https://kutt.lckp.top/8BKRCO](https://kutt.lckp.top/8BKRCO)
- qb-web：[https://kutt.lckp.top/oHGOA3
](https://kutt.lckp.top/oHGOA3
)

## 2. 🧭 安装

1. 解压并放到 qBittorrent 可以读取的目录中
2. 点击工具，设置，Web UI，填写文件路径（可参考下列路径），并勾选 `使用备用 Web UI` 后保存即可

```text
/config/webui/vuetorrent
/config/webui/qb-web-nightly/dist
```

![20230219220850](https://image.lckp.top/LuckyPuppy514/image/raw/main/2023/2023-02-19/20230219220850.webp)

## 3. 🫠 常见问题

## 3.1. 错误路径导致无法打开页面

修改配置文件 `/.../config/qBittorrent/qBittorrent.conf`

```text
WebUI\AlternativeUIEnabled=false
```

保存后，重启 qBittorrent 即可

## 4. 🤔 问题反馈

- [https://kutt.lckp.top/J4wW78](https://kutt.lckp.top/J4wW78)

## 5. 👏 特别感谢

- [https://github.com/WDaan/VueTorrent](https://github.com/WDaan/VueTorrent)
- [https://github.com/CzBiX/qb-web](https://github.com/CzBiX/qb-web)
