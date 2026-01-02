# FFmpeg Crop Helper | FFmpeg 视频裁剪助手

[English](./README_EN.md) | 中文版

这是一个纯前端实现的 Web 小工具，旨在帮助用户通过可视化界面快速生成 FFmpeg 的视频裁剪（crop）指令。

### 🌟 功能特点
- **视频帧提取**：直接导入视频文件，通过进度条选择任意时刻的画面作为裁剪参考。
- **剪贴板支持**：支持直接粘贴（Ctrl+V）截图，无需保存文件后再上传。
- **全屏自适应**：预览窗口根据浏览器尺寸自动最大化，提供最佳编辑体验。
- **精准计算**：基于图片/视频原始分辨率计算坐标，生成的指令可直接用于生产环境。
- **一键生成**：实时生成 `-vf 'crop=w:h:x:y'` 格式指令。

### 🚀 快速开始
1. 访问 [你的 GitHub Pages 链接] 或直接下载 `index.html`。
2. 拖入视频或粘贴截图。
3. 调整裁剪框。
4. 点击“复制”按钮获取 FFmpeg 指令。

### 🛠️ 技术栈
- [Cropper.js](https://github.com/fengyuanchen/cropperjs) - 核心裁剪引擎
- HTML5 Video/Canvas API - 视频处理与帧提取
- 纯原生 JavaScript/CSS3 - 无需后端支持
