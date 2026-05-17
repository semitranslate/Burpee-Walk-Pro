# Burpee Walk Pro · 智能跟练系统

[![Demo](https://img.shields.io/badge/Live%20Demo-在线体验-10b981?style=for-the-badge)](https://semitranslate.github.io/Burpee-Walk-Pro/)

这是一个专为「波比走 (Burpee Walk)」打造的现代化、沉浸式网页端跟练工具。以单文件的形式，提供了堪比专业级商业健身 App 的视觉质感与交互体验。无需下载安装，点击即用。

👉 **在线体验地址**：[https://semitranslate.github.io/Burpee-Walk-Pro/](https://semitranslate.github.io/Burpee-Walk-Pro/)

## ✨ 核心特性 (Features)

* **沉浸式视觉架构**
  * 采用暗黑模式 (Dark Mode) 与高级毛玻璃 (Glassmorphism) 质感设计。
  * 底层植入巨幅“深呼吸”动态情绪文字与微光律动特效，提供极强的心流体验。
* **无缝视觉节拍器**
  * 摒弃传统的 CSS 过渡与渐变重绘，采用多图层纯色覆盖算法渲染 SVG 进度环，彻底消除闪烁与视觉违和感。
  * 精准将单个动作拆解为 4 个指令段（俯身、后撤、收腿、起身），实时文字高亮引导。
* **零延迟原生音效**
  * 抛弃传统的外部音频文件，使用浏览器原生 `Web Audio API` 实时合成电子蜂鸣音。
  * 内置免版权轻快 BGM，工作与休息状态自动切换提示音轨。
* **隐私级本地数据看板**
  * 静默记录每一秒的有效运动数据。
  * 提供极具科技感的横向滚动柱状图面板，支持查看无上限的历史训练记录。
  * 数据 100% 留存于浏览器本地 (`localStorage`)，绝对保护隐私。

## 📱 最佳使用建议 (Usage Tips)

本项目为**零依赖 (Zero-dependency)** 的纯前端项目，已部署至 GitHub Pages。

**获取 App 级体验：**
建议在移动端（iOS Safari / Android Chrome）或桌面端浏览器中打开链接后，选择 **“添加到主屏幕 (Add to Home Screen)”**。
这样不仅可以获得隐藏浏览器地址栏的**全屏沉浸体验**，还能像打开原生 App 一样一键进入跟练状态。

*(注：系统会记录您的每日运动时长并保存在浏览器本地，为防止数据丢失，请避免在“无痕/隐身模式”下使用。)*

## ⚙️ 科学参数预设 (Scientific Configurations)

基于科学的负荷控制理念，系统默认提供以下初始参数（适合初中级训练者建立心肺耐力）：

| 参数项 | 默认值 | 科学依据 |
| :--- | :--- | :--- |
| **训练组数** | `4` 组 | 适中的训练容量，避免单次过量导致延迟性肌肉酸痛影响次日计划。 |
| **每组个数** | `10` 个 | 保证在乳酸大量堆积、核心卸力前完成单组，**动作质量优先于数量**。 |
| **单次耗时** | `6` 秒 | 匀速发力，单次完整动作耗时 6 秒（每阶段 1.5 秒），最适合维持核心收紧。 |
| **组间休息** | `60` 秒 | 遵循 1:1 的合理运动与休息比，确保心率回落至燃脂区间，ATP 充分恢复。 |

## 🛠 技术栈 (Tech Stack)

* **HTML5**：语义化结构与 SVG 矢量图形渲染。
* **CSS3**：Flexbox / CSS Grid 现代布局，CSS 变量控制全局主题，原生 Keyframes 动画实现律动效果。
* **Vanilla JavaScript (ES6+)**：纯原生 JS 驱动的核心状态机 (State Machine) 与 `requestAnimationFrame` 60fps 高性能渲染流。
* **Web API**：`AudioContext` (音频合成), `localStorage` (数据持久化)。