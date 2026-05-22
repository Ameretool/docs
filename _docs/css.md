---
title: CSS 完全导航 | 从入门到精通
permalink: /css
description: 覆盖所有 CSS 特性、布局、动画、工具与新规范的终极导航，适合任何阶段的前端开发者。
---

# 📘 CSS 完全导航  
*Curated CSS Resources — 基础 · 布局 · 动画 · 新特性 · 工具*

> 点击 🚀 符号可直达权威教程，🔧 为实用工具，🎮 为趣味游戏，📄 为规范或博文。

---

## 📌 目录
1. [入门与核心概念](#入门与核心概念)
2. [选择器（Selectors）](#选择器selectors)
3. [盒模型 & 布局基础](#盒模型--布局基础)
4. [现代布局：Flexbox & Grid](#现代布局flexbox--grid)
5. [定位与层叠上下文](#定位与层叠上下文)
6. [响应式设计 & 容器查询](#响应式设计--容器查询)
7. [背景、边框与特效](#背景边框与特效)
8. [文本、字体与排版](#文本字体与排版)
9. [颜色、渐变与滤镜](#颜色渐变与滤镜)
10. [动画、过渡与变换](#动画过渡与变换)
11. [CSS 变量（自定义属性）](#css-变量自定义属性)
12. [CSS 函数（calc, clamp, 逻辑函数等）](#css-函数calc-clamp-逻辑函数等)
13. [伪类 & 伪元素](#伪类--伪元素)
14. [CSS 新特性（2024~2025）](#css-新特性20242025)
15. [工具、生成器与调试](#工具生成器与调试)
16. [性能 & 最佳实践](#性能--最佳实践)
17. [CSS 框架与预处理器](#css-框架与预处理器)
18. [学习社区与博客](#学习社区与博客)

---

## 入门与核心概念
| 资源 | 说明 |
|------|------|
| 🚀 [MDN: CSS 入门](https://developer.mozilla.org/zh-CN/docs/Web/CSS) | 最权威的官方文档（多语言） |
| 🚀 [CSS 教程 - 现代方式](https://web.dev/learn/css/) | Google 出品的交互式课程 |
| 🎮 [CSS Diner](https://flukeout.github.io/) | 通过游戏学习选择器 |
| 📄 [W3C CSS 规范](https://www.w3.org/Style/CSS/) | 官方标准与工作组动态 |

---

## 选择器（Selectors）
涵盖所有基本、组合、属性、伪类选择器。
| 资源 | 说明 |
|------|------|
| 🚀 [MDN 选择器参考](https://developer.mozilla.org/zh-CN/docs/Web/CSS/CSS_Selectors) | 每种选择器的详细解释 |
| 📄 [CSS 选择器详解（中文）](https://www.zhangxinxu.com/wordpress/2023/03/css-selector-module/) | 张鑫旭深度文章 |
| 🎮 [CSS 选择器挑战](https://css-selectors-challenge.vercel.app/) | 交互式练习平台 |

---

## 盒模型 & 布局基础
margin、padding、border、box-sizing、display 基础。
| 资源 | 说明 |
|------|------|
| 🚀 [盒模型完全指南](https://css-tricks.com/the-css-box-model/) | CSS-Tricks 经典 |
| 🚀 [box-sizing 详解](https://developer.mozilla.org/zh-CN/docs/Web/CSS/box-sizing) | MDN 精讲 |
| 📄 [边距折叠现象](https://www.joshwcomeau.com/css/rules-of-margin-collapse/) | 深入 margin collapse（英） |

---

## 现代布局：Flexbox & Grid
| 分类 | 资源 | 说明 |
|------|------|------|
| **Flexbox** | 🚀 [Flexbox 完全指南](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) | 图文并茂，一图胜千言 |
| | 🎮 [Flexbox Froggy](https://flexboxfroggy.com/) | 青蛙游戏，快乐学习 |
| | 🔧 [Flexbox Playground](https://flexbox.help/) | 可视化调节参数 |
| **CSS Grid** | 🚀 [Grid 完全指南](https://css-tricks.com/snippets/css/complete-guide-grid/) | CSS-Tricks 神作 |
| | 🎮 [Grid Garden](https://cssgridgarden.com/) | 种胡萝卜学 Grid |
| | 🚀 [Grid by Example](https://gridbyexample.com/) | Rachel Andrew 的实战案例 |
| **新布局** | 📄 [Subgrid 用法](https://developer.mozilla.org/zh-CN/docs/Web/CSS/CSS_grid_layout/Subgrid) | 嵌套网格 |
| | 📄 [多列布局](https://developer.mozilla.org/zh-CN/docs/Web/CSS/CSS_multicol_layout) | 像报纸一样分栏 |

---

## 定位与层叠上下文
position (static/relative/absolute/fixed/sticky) 和 z-index。
| 资源 | 说明 |
|------|------|
| 🚀 [定位详解](https://developer.mozilla.org/zh-CN/docs/Web/CSS/position) | MDN 示例丰富 |
| 🔧 [z-index 与层叠上下文](https://www.joshwcomeau.com/css/stacking-contexts/) | 彻底搞懂层叠规则 |
| 📄 [粘性定位（sticky）实战](https://www.zhangxinxu.com/wordpress/2018/12/css-position-sticky/) | 张鑫旭中文案例 |

---

## 响应式设计 & 容器查询
包括 media queries、容器查询、视口单位、clamp 流体排版等。
| 资源 | 说明 |
|------|------|
| 🚀 [响应式设计基础](https://web.dev/responsive-web-design-basics/) | Google 开发教程 |
| 🚀 [容器查询（Container Queries）](https://developer.mozilla.org/zh-CN/docs/Web/CSS/CSS_Container_Queries) | 下一代响应式 |
| 🔧 [响应式断点生成器](https://responsivebreakpoints.com/) | 自定义设备断点 |
| 🎮 [媒体查询小测验](https://www.codecademy.com/learn/learn-responsive-design) | 互动练习 |

---

## 背景、边框与特效
背景渐变、背景图片、边框圆角、阴影、outline、mask 等。
| 资源 | 说明 |
|------|------|
| 🚀 [背景与边框](https://developer.mozilla.org/zh-CN/docs/Learn/CSS/Building_blocks/Backgrounds_and_borders) | MDN 模块 |
| 🔧 [CSS 边框半径生成器](https://9elements.github.io/fancy-border-radius/) | 可视化复杂圆角 |
| 🔧 [Neumorphism 生成器](https://neumorphism.io/) | 新拟态阴影 |
| 📄 [CSS mask 与裁剪](https://css-tricks.com/clipping-masking-css/) | 高级遮罩技巧 |

---

## 文本、字体与排版
font 属性、@font-face、line-height、text-transform、web 字体加载。
| 资源 | 说明 |
|------|------|
| 🚀 [Web 字体最佳实践](https://web.dev/font-best-practices/) | 性能与体验 |
| 🔧 [Google Fonts 中文](https://fonts.google.com/earlyaccess) | 免费字体 |
| 📄 [line-height 深度解析](https://zhuanlan.zhihu.com/p/32710267) | 行高与垂直对齐 |
| 🔧 [字体加载策略检测](https://www.fontfaceobserver.com/) | Font Face Observer |

---

## 颜色、渐变与滤镜
color 系统（hex、rgb、hsl、oklch）、渐变、backdrop-filter、blend-mode。
| 资源 | 说明 |
|------|------|
| 🚀 [颜色与 CSS 颜色模块](https://developer.mozilla.org/zh-CN/docs/Web/CSS/CSS_colors) | 新版 oklch 介绍 |
| 🔧 [渐变生成器](https://cssgradient.io/) | 超好用 |
| 🔧 [CSS 滤镜交互实验室](https://cssfiltergenerator.com/) | 预览 blur、brightness 等 |
| 📄 [混合模式 blend-mode 指南](https://css-tricks.com/basics-css-blend-modes/) | 创意合成 |

---

## 动画、过渡与变换
transition、animation (@keyframes)、transform 2D/3D。
| 资源 | 说明 |
|------|------|
| 🚀 [CSS 动画指南](https://developer.mozilla.org/zh-CN/docs/Web/CSS/CSS_animations) | MDN 权威 |
| 🎮 [Keyframes 可视化](https://keyframes.app/) | 交互式动画编辑器 |
| 🔧 [Bounce.js](http://bouncejs.com/) | 缓动曲线生成器 |
| 📄 [transform 3D 详解](https://3dtransforms.desandro.com/) | 立体翻转教程 |
| 🚀 [Animate.css 库](https://animate.style/) | 开箱即用的动画库 |

---

## CSS 变量（自定义属性）
var()、自定义属性作用域、动态主题切换。
| 资源 | 说明 |
|------|------|
| 🚀 [CSS 变量完全指南](https://css-tricks.com/a-complete-guide-to-custom-properties/) | 含 fallback 技巧 |
| 📄 [CSS 变量与主题切换](https://www.smashingmagazine.com/2021/08/css-variables-theming/) | 实战方案 |
| 🔧 [CSS 变量调试工具](https://www.30secondsofcode.org/css/s/css-variables-devtools/) | Chrome 技巧 |

---

## CSS 函数（calc, clamp, 逻辑函数等）
calc、min/max/clamp、attr、三角函数、颜色函数等。
| 资源 | 说明 |
|------|------|
| 🚀 [calc() 使用场景](https://developer.mozilla.org/zh-CN/docs/Web/CSS/calc) | 混合单位计算 |
| 🚀 [clamp() 响应式排版](https://web.dev/min-max-clamp/) | 流体字体大小 |
| 📄 [CSS 数学函数全解](https://www.smashingmagazine.com/2022/08/modern-css-math-functions/) | 三角函数、指数 |
| 🔧 [CSS 函数实验室](https://cssfunctions.com/) | 在线测试 |

---

## 伪类 & 伪元素
:is()、:where()、:not()、:has()、::before/after 等。
| 资源 | 说明 |
|------|------|
| 🚀 [伪类大全](https://developer.mozilla.org/zh-CN/docs/Web/CSS/Pseudo-classes) | MDN 索引 |
| 📄 [:has() 超级选择器](https://www.bram.us/2021/12/21/the-css-has-selector-is-way-more-than-a-parent-selector/) | 父级选择器革命 |
| 🔧 [逻辑伪类组合使用](https://www.zhangxinxu.com/wordpress/2021/07/css-is-where-not-has/) | 中文深度解析 |

---

## CSS 新特性（2024~2025）
- **CSS 嵌套 (Nesting)**：原生类似 Sass 的 & 语法
- **视图过渡 (View Transitions)**：单页应用切换动画
- **作用域样式 (@scope)**：限制选择器范围
- **滚动驱动动画 (Scroll-driven Animations)**
- **@property**：自定义属性类型与继承控制

| 资源 | 说明 |
|------|------|
| 🚀 [CSS 嵌套规范](https://developer.chrome.com/blog/css-nesting?hl=zh-cn) | Chrome 官方说明 |
| 📄 [视图过渡入门](https://developer.mozilla.org/en-US/docs/Web/API/View_Transitions_API) | MDN（英） |
| 🚀 [滚动驱动动画](https://scroll-driven-animations.style/) | 官方演示与代码 |
| 📄 [@property 使用教程](https://www.zhangxinxu.com/wordpress/2021/05/css-property-override/) | 中文介绍 |

---

## 工具、生成器与调试
| 工具 | 用途 |
|------|------|
| 🔧 [Chrome DevTools CSS 技巧](https://developer.chrome.com/docs/devtools/css/) | 官方调试指南 |
| 🔧 [CSS 统计工具（CSS Stats）](https://cssstats.com/) | 分析页面 CSS 复杂度 |
| 🔧 [PurgeCSS](https://purgecss.com/) | 删除未使用的 CSS |
| 🔧 [Stylelint](https://stylelint.io/) | CSS 代码检查器 |
| 🔧 [WhatCSS](https://whatcss.vercel.app/) | 提取元素最终样式 |
| 🔧 [Animista](https://animista.net/) | 在线生成 CSS 动画代码 |

---

## 性能 & 最佳实践
| 资源 | 说明 |
|------|------|
| 📄 [关键 CSS 与渲染阻塞](https://web.dev/defer-non-critical-css/) | 优化首次内容绘制 |
| 🚀 [CSS 优化指南](https://developer.mozilla.org/zh-CN/docs/Learn/Performance/CSS) | MDN 性能专题 |
| 🔧 [CSS 组合器与选择器效率](https://webhint.io/docs/user-guide/hints/hint-selector-list/) | 避免低性能选择器 |

---

## CSS 框架与预处理器
| 框架/工具 | 说明 |
|-----------|------|
| 🚀 [Tailwind CSS](https://tailwindcss.com/) | 实用优先的原子类框架 |
| 🚀 [Bootstrap 5](https://getbootstrap.com/) | 最流行的组件库 |
| 🚀 [UnoCSS](https://unocss.dev/) | 即时按需生成 CSS |
| 🚀 [Sass](https://sass-lang.com/) | 成熟预处理器 |
| 🚀 [PostCSS](https://postcss.org/) | 用 JS 插件转换 CSS |
| 📄 [Less](https://lesscss.org/) | 动态样式语言 |

---

## 学习社区与博客
| 社区/博客 | 特点 |
|-----------|------|
| 🚀 [CSS-Tricks](https://css-tricks.com/) | 全球顶级 CSS 博客 |
| 🚀 [MDN Blog](https://developer.mozilla.org/en-US/blog/) | 最新 Web 标准 |
| 📄 [张鑫旭博客](https://www.zhangxinxu.com/wordpress/) | 中文深度 CSS 文章 |
| 📄 [前端之巅 (InfoQ)](https://www.infoq.cn/frontend) | 中文技术趋势 |
| 🎮 [CodePen 探索](https://codepen.io/) | 前端灵感/作品集 |
| 💬 [CSS Discord / Reddit](https://www.reddit.com/r/css/) | 国际社区交流 |

---

## 🌟 最后：保持探索
这份导航会随着 CSS 规范更新而持续扩充。欢迎 **Star / Fork** 你的本地版本，每天学习一小节，成为 CSS 大师。

📎 **建议收藏此页**，随时查阅对应模块的权威文档。

> *“CSS 不是 bug，而是特性。” – 每个布局实现者*
