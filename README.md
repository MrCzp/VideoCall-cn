<p align="center">
  <img src="static/logo.png" alt="视频聊天 Logo" width="120">
</p>

# 视频聊天

## 简介

**视频聊天** 是这个数字人扩展的简体中文版，运行在 [SillyTavern](https://github.com/SillyTavern/SillyTavern) 第三方扩展体系内。打开扩展后会直接进入视频通话流程，在运行时加载绑定好的数字人，并自动播放 AI 回复语音与驱动口型同步。

## 当前行为

- 打开扩展后直接进入通话流程
- 数字人加载完成前，会先显示视频通话等待界面
- 运行时底部只保留摄像头、挂断、语音录制三个按钮
- 数字人加载过程中，摄像头和语音按钮会禁用，只有挂断可点击

## 功能

- 聊天中的 3D 数字人实时渲染
- AI 回复自动语音播报
- 基于语音的口型同步动画
- 数字人与角色或群组绑定
- 运行时内置摄像头预览与截图发送
- 数字人加载完成后支持一键语音录制输入
- 支持中断当前播放与生成

## 安装

### 方式一：SillyTavern 内置安装

1. 打开 SillyTavern。
2. 点击顶部扩展按钮。
3. 选择“安装扩展”。
4. 填入仓库地址：

```text
https://github.com/MrCzp/VideoCall-cn
```

5. 安装完成后刷新页面。

### 方式二：手动安装

```bash
cd SillyTavern/public/scripts/extensions/third-party
git clone https://github.com/MrCzp/VideoCall-cn VideoCall-cn
```

然后刷新 SillyTavern 页面。

## 环境要求

- SillyTavern 1.12.0 或更高版本
- 支持 WebGL 2.0 的现代浏览器
- 可访问中文服务节点的网络环境
- 麦克风权限（语音录制时需要）

## 相关链接

- [GitHub 仓库](https://github.com/MrCzp/VideoCall-cn)
- [问题反馈](https://github.com/MrCzp/VideoCall-cn/issues)
- [MIT License](./LICENSE)