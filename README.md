# 二维码生成器 (QR Code Generator)

功能齐全的浏览器端二维码生成工具，单文件 HTML，打开即用。

## 快速开始

直接在浏览器中打开 `二维码生成器.html` 即可使用，无需安装任何依赖。

## 支持的类型

| 类型 | 说明 | 示例 |
|------|------|------|
| 网址 | URL 跳转 | `https://example.com` |
| 文本 | 任意文字内容 | 欢迎语、说明文字 |
| Wi-Fi | 扫码连 Wi-Fi | `WIFI:S:SSID;T:WPA;P:password;;` |
| 名片 | 电子名片 vCard | 姓名、电话、邮箱、公司 |
| 邮件 | 快捷发邮件 | `mailto:user@example.com` |

## 定制选项

- **色彩** — 前景色和背景色自由搭配，支持透明背景
- **码点样式** — 5 种风格：方块、圆点、圆角、大圆角、典雅
- **定位角** — 外框和内点分别可调样式
- **中心 Logo** — 上传自定义图片，可调节大小和边距
- **分辨率** — 300 / 500 / 1000 / 2000 px
- **纠错等级** — L (7%) / M (15%) / Q (25%) / H (30%)

## 导出方式

- 下载高清 PNG 图片
- 下载 SVG 矢量文件
- 复制到剪贴板

## 其他特性

- 暗黑模式，跟随系统或手动切换
- 本地历史记录（最近 10 条），支持恢复
- 响应式布局，适配桌面和移动端

## 技术栈

- [qr-code-styling](https://github.com/kozakdenys/qr-code-styling) — 二维码渲染
- [Tailwind CSS](https://tailwindcss.com/) — 样式框架
- [Font Awesome](https://fontawesome.com/) — 图标
