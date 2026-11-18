## 伸出手，与风击个掌。

- **moshi 默识** —— 本机 Agent 记忆系统：被动观测开发痕迹，抽成事实与边，经 MCP 按需检索给 Agent 用；自带 React 记忆图谱界面（three / sigma）。记忆侧不跑 LLM，只做要点出境。（TypeScript / Python / React / MCP / CC Hook）
- **pixel-wallpaper** —— DSH像素格背景生成器：6 种生成算法统一只输出亮度场，渲染层独立处理调色板、gamma 与抖动。（JavaScript）


## 可以点开的几个仓库

| 仓库 | 描述 | 栈 |
| --- | --- | --- |
| [moshi](https://github.com/johnshere/moshi) | 本机 Agent 记忆系统：事实与边，经 MCP 按需检索；含 React 图谱界面 | TypeScript · Python · React |
| [cell-world](https://github.com/johnshere/cell-world) | 细胞世界生态模拟：Go → Python → Node → Rust 四代重写，现版 Rust + egui，含脉冲神经网络、基因与生命史追踪 | Rust · Go · Python |
| [pixel-wallpaper](https://github.com/johnshere/pixel-wallpaper) | DSH  plugin；6 种算法 → 亮度场 → 统一渲染管线 | JavaScript |
| [universal-vue-components](https://github.com/johnshere/universal-vue-components) | Vue2/Vue3 双版本组件库，分发原始 SFC 由宿主编译 | TypeScript · Vue |
| [namespace-style-link](https://github.com/johnshere/namespace-style-link) | VS Code 扩展：template 的 BEM 调用 ↔ style 的 `@include` | TypeScript |
| [print-page](https://github.com/johnshere/print-page) | Vue3 独立分页打印 / PDF / Excel 导出 | Vue 3 |
| [dsh-title-wheel](https://github.com/johnshere/dsh-title-wheel) | 会话列表改造：双行标题 + 时间轮盘编号 + 模型生成标题 | JavaScript |
| [vue-dragzoomable](https://github.com/johnshere/vue-dragzoomable) | 单文件 Vue3 组件：拖拽平移 + 以光标为锚点的滚轮缩放 | Vue 3 · TypeScript |

## 技术栈

`TypeScript` `Vue 2/3` `Node` `Python` `Go` `Rust` `GDScript` `Vite` `pnpm`

---

写东西的习惯：先定边界，再写实现——概设回答「做成什么样、怎么验收」，详设回答「怎么写」，有争议的决策走 ADR。
