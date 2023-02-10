# 【mpv.net_CM】Windows 平台动漫最强播放器

## 1. ⬇️ 下载

- 🔗 地址：[https://kutt.lckp.top/Rm4SZN](https://kutt.lckp.top/Rm4SZN)
- 🔑 密码：`7toz`

## 2. 🔩 安装

解压到想要安装的路径即可

🔥 **注意：安装路径不要包含中文和空格等特殊字符，并且建议不要使用 C 盘**

![20230210193638](https://github.lckp.top/LuckyPuppy514/blog/main/mpv.net_CM/图片/20230210193638.jpg)

## 3. ⚙️ 设置

鼠标右键，工具，mpv 选项设置

![20230210194331](https://github.lckp.top/LuckyPuppy514/blog/main/mpv.net_CM/图片/20230210194331.jpg)

### 3.1. 独显运行（单显卡可不设置）

基础：d3d11-adapter 和 vulkan-device 填写 **任务管理器** 中的 **显卡名称** 即可

![20230210194832](https://github.lckp.top/LuckyPuppy514/blog/main/mpv.net_CM/图片/20230210194832.jpg)

### 3.2. 性能相关（卡顿可尝试修改）

基础：vo，gpu-context，hwdec

![20230210195814](https://github.lckp.top/LuckyPuppy514/blog/main/mpv.net_CM/图片/20230210195814.jpg)

视频：video-sync

![20230210195853](https://github.lckp.top/LuckyPuppy514/blog/main/mpv.net_CM/图片/20230210195853.jpg)

> 其他选项建议有需求或有问题再按说明进行修改

## 5. ⌨️ 快捷键

鼠标右键，工具，自定义快捷键，可查看和修改所有快捷键

![20230210200117](https://github.lckp.top/LuckyPuppy514/blog/main/mpv.net_CM/图片/20230210200117.jpg)

## 6. 🐳 使用建议

### 6.1. 着色器

动漫建议使用 Anime4K（电视剧/电影可自行尝试其他选项，个人感觉效果不明显）

![20230210200357](https://github.lckp.top/LuckyPuppy514/blog/main/mpv.net_CM/图片/20230210200357.jpg)

### 6.2. 视频滤镜

个人对补帧感知不强，建议自行尝试

![20230210200715](https://github.lckp.top/LuckyPuppy514/blog/main/mpv.net_CM/图片/20230210200715.jpg)

使用快捷键 i ，可以查看是否丢帧（Dropped Frames）以及当前帧数（estimated）

![20230210201209](https://github.lckp.top/LuckyPuppy514/blog/main/mpv.net_CM/图片/20230210201209.jpg)

如果 Dropped Frames 数值一直增加，则说明硬件无法负载，建议尝试其它模式

## 7. 🌟 在线播放插件

安装教程：[https://kutt.lckp.top/lPFDM7](https://kutt.lckp.top/lPFDM7)

支持网站：[https://kutt.lckp.top/CfCIIc](https://kutt.lckp.top/CfCIIc)

## 8. 🤔 常见问题

### 8.1. 设置为默认应用

找到一个视频，鼠标右键，打开方式，选择其他应用（如果可以看到 `mpv.net` 则直接选择即可）

![20230210202356](https://github.lckp.top/LuckyPuppy514/blog/main/mpv.net_CM/图片/20230210202356.jpg)

在电脑上选择应用，选择安装路径下的 mpvnet.exe，点击始终，则以后所有同类型文件都会默认使用 mpvnet 打开

![20230210202551](https://github.lckp.top/LuckyPuppy514/blog/main/mpv.net_CM/图片/20230210202551.jpg)

### 8.2. B站看不到弹幕

点击右下角的字幕图标开启弹幕

![20230210202833](https://github.lckp.top/LuckyPuppy514/blog/main/mpv.net_CM/图片/20230210202833.jpg)

### 8.3. Anime4K 没有效果

请确保 gpu-context 选择的是 d3d11（亲测选择 winvk 时没有效果）

![20230210202924](https://github.lckp.top/LuckyPuppy514/blog/main/mpv.net_CM/图片/20230210202924.jpg)

### 8.4. 打开后窗口很小

请尝试无边框模式

![20230210203054](https://github.lckp.top/LuckyPuppy514/blog/main/mpv.net_CM/图片/20230210203054.jpg)

## 9. 👏 特别感谢

- [https://github.com/hooke007/mpv.net_CM](https://github.com/hooke007/mpv.net_CM)
- [https://github.com/hooke007/MPV_lazy](https://github.com/hooke007/MPV_lazy)
