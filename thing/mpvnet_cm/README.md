# 【mpv.net_CM】动漫最强播放器

![mpv](https://image.lckp.top/LuckyPuppy514/image/raw/main/2023/2023-02-17/mpv.webp)

一款功能强大的 windows 平台视频播放器，已经集成了 anime4k，多种补帧滤镜和脚本，可实时提升动漫画质和帧数<!--more-->

- 博客原文：[https://kutt.lckp.top/uVaT3U](https://kutt.lckp.top/uVaT3U)
- 视频教程：[https://kutt.lckp.top/GMVmJr](https://kutt.lckp.top/GMVmJr)

🌟 建议阅读博客原文，以便获取 **最新内容** 和 **最佳阅读体验**

## 1. ⬇️ 下载

- 地址：[https://kutt.lckp.top/Rm4SZN](https://kutt.lckp.top/Rm4SZN)
- 密码：`7toz`

## 2. 🧭 安装

鼠标右键解压到想要安装的路径即可

🔥 安装路径 **不要包含中文**，C 盘建议放在当前用户目录下

![20230215102832](https://image.lckp.top/LuckyPuppy514/image/raw/main/2023/2023-02-15/20230215102832.webp)

## 3. ⚙️ 设置

鼠标右键，工具，mpv 选项设置

![20230215103833](https://image.lckp.top/LuckyPuppy514/image/raw/main/2023/2023-02-15/20230215103833.webp)

### 3.1. 独显运行（单显卡可不设置）

基础：`d3d11-adapter` 和 `vulkan-device` 填写 **任务管理器** 中的 **显卡名称** 即可

![20230215104822](https://image.lckp.top/LuckyPuppy514/image/raw/main/2023/2023-02-15/20230215104822.webp)

### 3.2. 性能相关（建议卡顿才尝试修改）

基础：`vo`，`gpu-context`，`hwdec`

![20230215104947](https://image.lckp.top/LuckyPuppy514/image/raw/main/2023/2023-02-15/20230215104947.webp)

视频：`video-sync`

![20230215105053](https://image.lckp.top/LuckyPuppy514/image/raw/main/2023/2023-02-15/20230215105053.webp)

### 3.3. 其他设置

💡 建议 **有需求** 或 **有问题** 再按说明进行修改

## 4. ⌨️ 快捷键

鼠标右键，工具，自定义快捷键，可查看和修改所有快捷键

![20230215113110](https://image.lckp.top/LuckyPuppy514/image/raw/main/2023/2023-02-15/20230215113110.webp)

## 5. 🌟 使用建议

### 5.1. 着色器

动漫建议使用 `Anime4K`（电视剧和电影可自行尝试其他选项，个人感觉效果不明显）

![20230215105600](https://image.lckp.top/LuckyPuppy514/image/raw/main/2023/2023-02-15/20230215105600.webp)

### 5.2. 视频滤镜

个人对补帧感知不强，建议自行尝试

![20230215105645](https://image.lckp.top/LuckyPuppy514/image/raw/main/2023/2023-02-15/20230215105645.webp)

使用快捷键 i ，可以查看当前视频信息

- 丢失帧数：`Dropped Frames`
- 当前帧数：`FPS (estimated)`

🔥 如果 `Dropped Frames` 数值 **一直增加**，则说明硬件无法负载，建议尝试其它模式

![20230215110048](https://image.lckp.top/LuckyPuppy514/image/raw/main/2023/2023-02-15/20230215110048.webp)

## 6. ▶️ 在线播放插件

安装教程：[https://kutt.lckp.top/lPFDM7](https://kutt.lckp.top/lPFDM7)

支持网站：[https://kutt.lckp.top/CfCIIc](https://kutt.lckp.top/CfCIIc)

![20230215110805](https://image.lckp.top/LuckyPuppy514/image/raw/main/2023/2023-02-15/20230215110805.webp)

## 7. 🫠 常见问题

### 7.1. 设置为默认应用

找到一个视频，鼠标右键，打开方式，找到并选择 `mpvnet`

![20230215111410](https://image.lckp.top/LuckyPuppy514/image/raw/main/2023/2023-02-15/20230215111410.webp)

![20230215111629](https://image.lckp.top/LuckyPuppy514/image/raw/main/2023/2023-02-15/20230215111629.webp)

### 7.2. B站看不到弹幕

点击右下角的字幕图标开启弹幕

![20230215112551](https://image.lckp.top/LuckyPuppy514/image/raw/main/2023/2023-02-15/20230215112551.webp)

### 7.3. Anime4K 没有效果

① 确保是 2D 动漫
② 确保 `gpu-context` 选择的是 `d3d11`（亲测选择 `winvk` 时没有效果）

![20230215112647](https://image.lckp.top/LuckyPuppy514/image/raw/main/2023/2023-02-15/20230215112647.webp)

### 7.4. 打开后窗口很小

请尝试无边框模式

![20230215113330](https://image.lckp.top/LuckyPuppy514/image/raw/main/2023/2023-02-15/20230215113330.webp)

### 7.5. 杜比视界颜色发绿

基础：`vo` 选择 `gpu-next`

![20230215113536](https://image.lckp.top/LuckyPuppy514/image/raw/main/2023/2023-02-15/20230215113536.webp)

## 8. 🤔 问题反馈

- [https://kutt.lckp.top/J4wW78](https://kutt.lckp.top/J4wW78)

## 9. 👏 特别感谢

- [https://github.com/hooke007/mpv.net_CM](https://github.com/hooke007/mpv.net_CM)
- [https://github.com/hooke007/MPV_lazy](https://github.com/hooke007/MPV_lazy)
- [https://github.com/d87/mpv-persist-properties](https://github.com/d87/mpv-persist-properties)
- [https://github.com/itKelis/MPV-Play-BiliBili-Comments](https://github.com/itKelis/MPV-Play-BiliBili-Comments)
