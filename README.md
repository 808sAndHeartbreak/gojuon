# 五十音 · Gojūon | Japanese Kana Wallpaper

[![Wallpaper Engine](https://img.shields.io/badge/Wallpaper%20Engine-Workshop-blue)](https://steamcommunity.com/sharedfiles/filedetails/?id=3635766356)
[![Version](https://img.shields.io/badge/version-7-brightgreen)](https://github.com/808sAndHeartbreak/gojuon)

一个动态的日语五十音假名表动态壁纸，支持音频可视化、实时时钟和音乐信息显示。

> **Wallpaper Engine Workshop:** [点击订阅](https://steamcommunity.com/sharedfiles/filedetails/?id=3635766356)

## ✨ 特性

### 🎵 音频响应
- **实时音频可视化**：假名随音乐律动
- **频段分配**：不同列响应低频/中频/高频
- **暂停时静止**：播放时抖动，暂停后立即静止

### 🕐 智能时钟
- **动态显示**：播放音乐时自动切换为专辑信息
- **时分秒分离**：时分大字体，秒小字体
- **日期显示**：YYYY-MM-DD + 英文/日语星期

### 🎧 音乐信息
- **专辑封面**：自动显示当前播放的专辑图片
- **歌曲信息**：标题 + 艺术家/播放器名称
- **流畅切换**：与时钟平滑过渡（0.8s 淡入淡出）

### 📋 交互功能
- **显隐开关**：ROMAN / HIRA / KATA / ORIGIN 可独立控制
- **双页切换**：清音 + 浊音/拗音 两页
- **简洁菜单**：右上角汉堡菜单，低调不打扰

### 🎨 视觉风格
- **Punk/Emo 美学**：青色霓虹 + 紫色 glitch 效果
- **悬停交互**：鼠标悬停假名时发光并浮起
- **音源联动**：假名与汉字互相高亮

## 🖼️ 预览

![预览图](preview.jpg)

## 📦 文件结构

```
gojuon/
├── gojuon.html          # 主HTML文件
├── project.json         # Wallpaper Engine 配置
├── preview.jpg          # 预览图
├── defaultcursor.png    # 默认光标（已移除）
├── cursor_hover.png     # 悬停光标（已移除）
└── README.md            # 本文档
```

## 🚀 安装使用

### 方法1：Steam Workshop（推荐）
1. 在 Steam 中打开 [Workshop 页面](https://steamcommunity.com/sharedfiles/filedetails/?id=3635766356)
2. 点击「订阅」
3. 在 Wallpaper Engine 中选择该壁纸

### 方法2：本地安装
1. 下载本仓库
2. 打开 Wallpaper Engine
3. 点击「+」→「从文件创建壁纸」
4. 选择 `gojuon.html`

## ⚙️ 配置选项

在 Wallpaper Engine 中右键壁纸 → 属性，可调整：

- **Show Roman**：显示/隐藏罗马音
- **Show Hiragana**：显示/隐藏平假名
- **Show Katakana**：显示/隐藏片假名
- **Show Origin**：显示/隐藏汉字来源

> 💡 也可以点击右上角的 ☰ 菜单快速切换

## 🎯 使用场景

- 💻 **学习日语**：五十音记忆辅助工具
- 🎵 **听音乐**：专辑封面 + 音频可视化
- 🕐 **看时间**：无音乐时显示时钟日期
- 🎨 **桌面美化**：赛博朋克风格动态壁纸

## 📊 技术细节

- **类型**：Web 壁纸（HTML + CSS + JavaScript）
- **音频处理**：支持 Wallpaper Engine 音频 API
- **媒体信息**：支持播放器元数据显示
- **自适应布局**：最小宽度 1000px
- **性能优化**：
  - 暂停时停止音频处理
  - CSS 硬件加速
  - 事件节流

## 🔧 开发

### 调试模式
直接在浏览器中打开 `gojuon.html` 即可预览（无音频功能）

### 音频测试
在 Wallpaper Engine 编辑器中加载，播放音乐测试

## 📝 更新日志

### v7 (2026-01)
- ✨ 新增：实时时钟显示
- ✨ 新增：与音频信息的智能切换
- ✨ 新增：汉堡菜单，简化界面
- 🎨 优化：header 区域放大，表格略微缩小
- 🐛 修复：音频暂停后的抖动问题
- 🐛 修复：专辑封面切换时的缺失图标

### v6 及之前
- 基础五十音显示
- 音频可视化效果
- 专辑信息显示

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 📄 许可

本项目仅供学习交流使用。

## 🔗 链接

- **GitHub**: https://github.com/808sAndHeartbreak/gojuon
- **Workshop**: https://steamcommunity.com/sharedfiles/filedetails/?id=3635766356
- **作者**: [@808sAndHeartbreak](https://github.com/808sAndHeartbreak)

---

💭 *Listening to Kanye while coding Japanese* 🎵
