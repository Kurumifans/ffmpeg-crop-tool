# FFmpeg Crop Helper

English | [中文版](./README.md)

A pure front-end web utility designed to help users generate FFmpeg video crop commands through an intuitive visual interface.

### 🌟 Key Features
- **Video Frame Extraction**: Import video files directly and use a seek bar to select any frame as a reference for cropping.
- **Clipboard Support**: Supports direct pasting (Ctrl+V) of screenshots—no need to save and upload files.
- **Auto-Maximizing UI**: The preview window automatically adapts to your browser's window size for a maximized workspace.
- **High Precision**: Calculates coordinates based on the original resolution of the source, ensuring production-ready commands.
- **One-Click Export**: Real-time generation of the `-vf 'crop=w:h:x:y'` command.

### 🚀 Quick Start
1. Visit [Your GitHub Pages Link] or download the `index.html` file.
2. Drag & drop a video or paste a screenshot.
3. Adjust the cropping box as needed.
4. Click the "Copy" button to get your FFmpeg command.

### 🛠️ Tech Stack
- [Cropper.js](https://github.com/fengyuanchen/cropperjs) - Core cropping engine
- HTML5 Video/Canvas API - Video handling and frame capture
- Vanilla JavaScript & CSS3 - No backend required
