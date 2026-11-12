# 公开项目索引

wtsswt 的公开项目总览页：按类别列出全部公开仓库，每个项目给出一段说明与直达链接（在线页面 / 源代码）。

- **在线页面**：https://wtsswt.github.io/projects/
- **仓库地址**：https://github.com/wtsswt/projects

## 页面说明

- 单文件 `index.html`，无依赖、无构建，双击即开
- 顶部按类别筛选（数学 / 图形 / 仿真 / 工具），筛选按钮带数量、支持键盘操作
- 卡片式索引：编号、类别、中英标题、一段说明、两组链接
- 响应式：`clamp()` 流式字号与间距，768 / 1024 断点；触控目标不小于 44px
- 尊重 `prefers-reduced-motion`

## 收录项目

| 项目 | 类别 | 在线页面 |
| --- | --- | --- |
| [taylor-lab](https://github.com/wtsswt/taylor-lab) | 数学 | [打开](https://wtsswt.github.io/taylor-lab/) |
| [calculus-cheatsheet](https://github.com/wtsswt/calculus-cheatsheet) | 数学 | [打开](https://wtsswt.github.io/calculus-cheatsheet/) |
| [metaball-liquid](https://github.com/wtsswt/metaball-liquid) | 图形 | [打开](https://wtsswt.github.io/metaball-liquid/) |
| [section-lab](https://github.com/wtsswt/section-lab) | 图形 | [打开](https://wtsswt.github.io/section-lab/) |
| [verlet-sandbox](https://github.com/wtsswt/verlet-sandbox) | 仿真 | [打开](https://wtsswt.github.io/verlet-sandbox/) |
| [pe-score-calculator](https://github.com/wtsswt/pe-score-calculator) | 工具 | [打开](https://wtsswt.github.io/pe-score-calculator/) |
| [cau-freshman-pe-score-calculator](https://github.com/wtsswt/cau-freshman-pe-score-calculator) | 工具 | [打开](https://wtsswt.github.io/cau-freshman-pe-score-calculator/) |
| [seats-rotation-50-51](https://github.com/wtsswt/seats-rotation-50-51) | 工具 | — |

新增项目时，在 `index.html` 的 `.grid` 里追加一个 `<article class="card">`，同步更新筛选按钮上的数量与上表。

## 本地预览

直接双击 `index.html`，或用任意静态服务器：

```bash
python3 -m http.server 8000
```
