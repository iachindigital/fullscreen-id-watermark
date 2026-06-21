# 证件全屏水印助手 (Fullscreen ID Watermark)

一个纯前端、零服务器上传的本地证件全屏水印添加工具。专门用于保护个人身份证、护照、营业执照等敏感证件图片，防止被他人盗用或冒用。

🚀 **在线使用地址**：[https://iachindigital.github.io/fullscreen-id-watermark/](https://iachindigital.github.io/fullscreen-id-watermark/)

*(本工具基于原作者 [isharmla233/fullscreen-id-watermark](https://github.com/isharmla233/fullscreen-id-watermark) 的开源项目进行部署与维护)*

---

## ✨ 核心特性

- 🔒 **绝对隐私安全**：100% 纯前端浏览器本地处理，无任何后端服务器，不消耗任何网络流量。
- ✈️ **支持完全断网使用**：您可以将本项目下载到本地，在完全断网（飞行模式）的环境下双击打开 `index.html` 运行，证件隐私绝不外泄。
- 🎨 **高度自定义调节**：支持实时调节水印文本、颜色、不透明度、字号、旋转角度、横纵间距以及交错排布。
- ⚡ **智能动态字号**：字号设为 `0` 或 `自动` 时，工具会自动根据输入的图片尺寸计算最佳视觉大小，无需手动调整。
- 🕒 **动态变量支持**：支持 `{date}`（当前日期）、`{time}`（当前时间）、`{filename}`（原文件名）等占位符，自动生成精确到秒的安全保护语。
- 📦 **批量高效处理**：支持多张图片同时拖拽或选择导入，提供 Notion 风格的流畅预览，支持一键批量处理并打包下载。

## 🛠️ 快速开始与本地开发

本项目为单文件架构，无任何复杂的打包构建流程，开箱即用。

### 1. 克隆本项目到本地
```bash
git clone [https://github.com/iachindigital/fullscreen-id-watermark.git](https://github.com/iachindigital/fullscreen-id-watermark.git)
cd fullscreen-id-watermark
