# 【Emby客户端】多平台免费优化版

![20230219210904](https://image.lckp.top/LuckyPuppy514/image/raw/main/screenshot/2023/2023-02-19/20230219210904.webp)

分享多平台优化版 Emby 客户端，同时为 windows 客户端开启弹幕功能和集成 anime4k 实时提升动漫画质<!--more-->

- 博客原文：[https://kutt.lckp.top/jOPDvh](https://kutt.lckp.top/jOPDvh)

🌟 建议阅读博客原文，以便获取 **最新内容** 和 **最佳阅读体验**

## 1. ⬇️ 打包下载

windows

- 地址：[https://kutt.lckp.top/U5ckWY](https://kutt.lckp.top/U5ckWY)
- 密码：`aq1v`

android

- 地址：[https://kutt.lckp.top/XSjUMF](https://kutt.lckp.top/XSjUMF)
- 密码：`bmfc`

🔥 建议有条件的加电报群下载最新版：[Emby 学习小秘
](https://t.me/EmbyNoisyX
)

## 2. 🧭 开启弹幕

记事本编辑 `Emby Theater/electronapp/www/index.html`，添加以下内容后保存即可

```html
<script type="text/javascript" src="https://danmaku.movie.kg/ext.js"></script>
<link rel="stylesheet" href="https://danmaku.movie.kg/ext.css"/>
```

![20230219212123](https://image.lckp.top/LuckyPuppy514/image/raw/main/screenshot/2023/2023-02-19/20230219212123.webp)

![20230219212343](https://image.lckp.top/LuckyPuppy514/image/raw/main/screenshot/2023/2023-02-19/20230219212343.webp)

## 3. 🌟 集成 Anime4K

- [https://kutt.lckp.top/fu610M](https://kutt.lckp.top/fu610M)

下载后解压到 `%appdata%` 目录下

![20230219213153](https://image.lckp.top/LuckyPuppy514/image/raw/main/screenshot/2023/2023-02-19/20230219213153.webp)

播放 1080p 及以下分辨率非 HDR 视频时自动开启

![20230219213311](https://image.lckp.top/LuckyPuppy514/image/raw/main/screenshot/2023/2023-02-19/20230219213311.webp)

如果客户端版本比较新，需要修改下列设置，否则 Anime4K 可能没有效果

![20230424133048](https://image.lckp.top/LuckyPuppy514/image/raw/main/2023/2023-04-24/20230424133048.webp)

进阶：如需修改模式及启用条件，需要自行修改以下代码

![20230219213641](https://image.lckp.top/LuckyPuppy514/image/raw/main/screenshot/2023/2023-02-19/20230219213641.webp)

## 4. 🫠 常见问题

网络无法访问 [ext.js](https://danmaku.movie.kg/ext.js) 和 [ext.css](https://danmaku.movie.kg/ext.css) 导致弹幕无效，可尝试更换下列配置

```html
<script type="text/javascript" src="https://github.rn.lckp.top/danmaku/ext.js"></script>
<link rel="stylesheet" href="https://github.rn.lckp.top/danmaku/ext.css"/>
```

## 4. 🤔 问题反馈

- [https://kutt.lckp.top/J4wW78](https://kutt.lckp.top/J4wW78)

## 5. 👏 特别感谢

- [https://t.me/EmbyNoisyX](https://t.me/EmbyNoisyX)
- [https://danmaku.movie.kg/](https://danmaku.movie.kg/)
