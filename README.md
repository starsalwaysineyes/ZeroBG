# ZeroBG 🚀

**ZeroBG** 是一个极致精简、响应毫秒级的图片去背景（透明化）工具。它完全基于 HTML5 Canvas 开发，无需任何后端支持，支持剪贴板粘贴与精准吸色，是您处理 Logo、图标和简单素材的极速助手。

![ZeroBG Demo](https://img.shields.io/badge/Speed-Zero--Latency-brightgreen)
![ZeroBG License](https://img.shields.io/badge/License-MIT-blue)
![ZeroBG Type](https://img.shields.io/badge/Standalone-Single--File-orange)

## ✨ 主要特性

- 📦 **单文件封装**：全工具仅一个 HTML 文件，无需安装任何环境，双击即用。
- ⚡ **零延迟响应**：采用 Canvas 离轴计算技术，所有像素处理均在本地完成，响应速度 < 5ms。
- 📋 **剪贴板支持**：支持直观的 `Ctrl+V` 粘贴图片，省去寻找文件的烦恼。
- 🎯 **精准吸色**：点击原图任意位置即可吸取目标色，不局限于去除白底。
- 🔒 **隐私至上**：100% 离线计算。图片数据永不离开您的浏览器，绝对安全。
- 🎨 **现代视觉**：玻璃拟态 (Glassmorphism) UI 设计，配有棋盘格预览展示透明效果。

## 🚀 快速开始

1. **下载文件**：下载本项目中的 `standalone.html`（或您重命名后的 `index.html`）。
2. **运行工具**：在任意现代浏览器中双击打开该文件。
3. **处理图片**：
   - 粘贴图片或点击上传。
   - (可选) 点击原图选取要去除的特定背景色。
   - 拖动滑动条微调去除程度。
   - 点击 **下载 PNG** 获取透明结果。

## 🛠️ 技术实现

- **Canvas API**: 利用 `getImageData` 读取原始像素矩阵，通过高效的数组遍历实现色彩阈值判断。
- **Modern CSS**: 使用 CSS 变量、Grid/Flex 布局、线性梯度与模糊滤镜打造高级感界面。
- **No-Framework**: 纯原生 JavaScript 驱动，无第三方依赖包，轻量且强大。

## 💡 技巧

- **去除不干净？** 尝试缓慢增加滑块阈值，这会扩大目标色的判定范围。
- **多色背景？** 本工具适合处理单色或过渡均匀的背景。对于极复杂的摄影背景，建议结合 AI 模型使用。

## 📄 开源协议

本项目采用 [MIT License](LICENSE)。

---

> 觉得好用？请给个 ⭐️ Start 鼓励一下！
