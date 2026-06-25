# 🛤️ Road to Godhood (成神之路)

> 目标明确，步步为营。流水不争先，争的是滔滔不绝。

**Road to Godhood** 是一款轻量级、沉浸式的个人学习与目标管理桌面端应用。
无论你是用于硬核的底层代码自学规划、日常的剑术体能训练打卡，还是长期的项目开发周期管理，它都能帮你把宏大的目标拆解为可执行的子任务，并以绝对理性的数据记录你的成长轨迹。

## ✨ 核心功能 (Features)

*   **📅 全局周期专注**：自定义学习/训练周期，支持 5 种难度等级（从“拉完了”到“夯/顶级”），直观的倒计时看板让你保持紧迫感。
*   **✅ 任务层级拆解**：支持“大任务 -> 子任务”的无限期拆分。今天该练几组动作、该啃透哪几个底层原理，一目了然。
*   **📊 动态进度追踪**：可视化的进度条与子任务状态切换（待办/完成/跳过），实时反馈你的执行力。
*   **📦 历史档案库 (Archive)**：周期结束后一键“任务终了”并归档。系统会自动计算你的完成率（%），让你所有的汗水都有迹可循。
*   **⚡ 极速轻量**：基于 Tauri + Vanilla JS 构建，没有臃肿的框架，告别卡顿，内存占用极低。

## 🛠️ 技术栈 (Tech Stack)

*   **前端**：HTML5, CSS3, 原生 JavaScript (无框架，极致纯粹)
*   **客户端框架**：[Tauri](https://tauri.app/) (基于 Rust 驱动的桌面端构建工具)
*   **数据存储**：LocalStorage (数据完全保留在用户本地，绝对隐私)

## 🚀 本地运行与开发 (Getting Started)

要参与开发或在本地编译运行此项目，请确保你的电脑已安装 [Node.js](https://nodejs.org/) 和 [Rust 开发环境](https://www.rust-lang.org/tools/install)。

### 1. 克隆仓库
```bash
git clone [https://github.com/你的用户名/Road_to_Godhood.git](https://github.com/你的用户名/Road_to_Godhood.git)
cd Road_to_Godhood
```

### 2. 安装依赖包
```bash
npm install
```
### 3. 启动开发环境
```bash
npm run dev
```
(首次启动 Tauri 可能会下载并编译 Rust 依赖，请耐心等待)

### 4. 打包构建
```bash
npm run build
```
 🤝 参与贡献 (Contributing)
欢迎提交 Pull Request 或发布 Issue。不论是修 Bug、增加新功能（比如数据导出功能、多维度图表），还是优化 UI，都非常感谢你的参与！
本项目基于 MIT License 开源，你可以自由地使用、修改和分发。







