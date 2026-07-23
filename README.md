# 🍜 今天吃什么 - Food Wheel

<p>
  <a href="https://chankrelune.github.io/food-wheel/"><img src="https://img.shields.io/badge/在线体验-Visit-brightgreen?style=flat-square" alt="在线体验"></a>
  <a href="https://github.com/chankrelune/food-wheel/releases"><img src="https://img.shields.io/github/v/release/chankrelune/food-wheel?style=flat-square" alt="GitHub Release"></a>
  <img src="https://img.shields.io/github/last-commit/chankrelune/food-wheel?style=flat-square" alt="Last Commit">
</p>

> 🔄 还在纠结今天吃什么？让转盘帮你决定！

**Food Wheel** 是一个融合阿里巴巴（Ali）设计风格的美食转盘网页应用，内置美团热门美食词库，加权随机抽选解决你的每日吃饭选择困难症。

---

## ✨ 功能亮点

| 版本 | 功能 |
|:----:|------|
| v1.0.0 | 🎡 Canvas 精美转盘 · 🔥 美团美食词库 · 🔄 一键刷新 · 🎉 庆祝动效 · 📱 响应式 |
| **v1.1.0** | **🎯 抽奖权重系统 · 📋 抽奖历史记录** |

### v1.1.0 新增

- 🎯 **抽奖权重系统** — 每次抽中的美食自动降权，没被抽中的逐渐恢复，越常吃到越难再抽到，鼓励你尝鲜
- 📋 **抽奖记录面板** — 每次结果自动保存，按时间倒序展示最近 50 条，支持清空
- 📊 **权重指示器** — 每个美食标签下方显示橙色进度条，相对权重一目了然

### 核心功能

- 🎡 **Canvas 精美转盘** — 径向渐变扇形区块，每块显示美食名称 + Emoji，转盘动画流畅自然
- 🔥 **美团热门美食词库** — 内置 20 个美团热门美食分类，每次随机抽取 10 个展示
- 🔄 **一键刷新换一批** — 点击刷新按钮即可重新随机抽取热门美食关键词
- 🎲 **加权随机抽奖** — 权重越高概率越大，Cubic ease-out 缓动动画，旋转 4-7 圈后精准指向结果
- 🎉 **庆祝动效** — 抽中结果弹出渐变色大字弹窗 + 彩色纸屑撒花动画
- 📱 **全平台响应式** — 手机 / 平板 / 桌面端完美适配

---

## 🛠️ 技术栈

```
HTML5 Canvas   转盘绘制与动画
CSS3           Ali 风格 UI（渐变、阴影、弹性布局）
Vanilla JS     转盘逻辑、加权随机、缓动动画、localStorage 持久化
GitHub Pages   静态部署
```

---

## 🚀 在线体验

👉 **[https://chankrelune.github.io/food-wheel/](https://chankrelune.github.io/food-wheel/)**

---

## 📦 版本历史

| 版本 | 日期 | 内容 |
|:----:|:----:|------|
| v1.1.0 | 2026-07 | 抽奖权重系统 + 抽奖历史记录 + 权重指示器 |
| v1.0.0 | 2026-07 | 初始发布：Canvas 转盘、Ali 设计、美团词库 |

查看完整 [Release Notes](https://github.com/chankrelune/food-wheel/releases)

---

## 🧑‍💻 关于作者

**chankrelune**

香港科技大学 (HKUST) 大二学生 · 数据科学与分析 (DASC) 专业

热爱用代码解决生活中的小问题，这个项目是我课余时间的一个小玩具，希望能帮到和我一样每天纠结"今天吃什么"的朋友 🍽️

---

## 🌟 灵感来源

灵感来自美团美食热榜和经典的"今天吃什么"转盘游戏，结合了阿里巴巴的设计美学，打造一个既好看又好用的美食决策工具。

---

*如果这个项目对你有帮助，欢迎 ⭐ 星标支持！*
