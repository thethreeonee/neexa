# Neexa

一款以 macOS 原生体验为核心，融合快速启动、效率工具、扩展生态和 AI Agent 的个人效率应用。

当前处于产品定义阶段。先明确需求与交互，再决定技术架构和上游代码复用方式。

## 产品方向

- 参考 Asky 的原生界面、窗口交互与 AI 能力。
- 吸收 Tinycast 的内置效率工具及 Raycast 插件兼容能力。
- 统一应用、文件、命令、工具与 AI 的使用入口。
- 主要满足个人日常使用，重视响应速度、资源占用与键盘操作。

## 目录

```text
neexa/
├── AGENTS.md             # 项目事实入口与协作约束
├── App/                  # macOS 应用预留目录
│   ├── Sources/          # 应用源码
│   └── Resources/        # 图标、本地化与其他资源
├── Tests/                # 测试预留目录
├── Scripts/              # 开发、构建与检查脚本
└── docs/
    ├── product/          # 产品概要、PRD 与范围
    ├── design/           # 交互、视觉规范与设计稿
    ├── architecture/     # 架构与模块边界
    ├── research/         # 上游调研与复用审计
    └── decisions/        # 已采纳的决策记录
```

从[文档索引](docs/README.md)和[产品概要](docs/product/brief.md)开始。

## 当前状态

尚无应用代码、Xcode 工程或构建命令。目录只预留职责，不代表已确定模块边界、Swift Package 拆分或 Runtime 方案。

下一步是梳理核心使用场景、功能清单和首版范围，再核验上游实现。

## 参考项目

- [Asky](https://github.com/Niall-Young/Asky)
- [Tinycast](https://github.com/abue-ammar/tinycast)

参考来源与核验状态见[上游调研](docs/research/upstreams.md)。
