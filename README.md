# Claude Code

Anthropic 官方 Claude Code CLI 工具的源代码。

## 项目结构

```
src/
├── assistant/          # AI 助手核心逻辑
├── bootstrap/          # 启动初始化
├── bridge/             # 桥接模块
├── buddy/              # Buddy 系统
├── cli/                # CLI 入口
├── commands/           # 命令实现（88 个命令）
├── components/         # UI 组件
├── constants/          # 常量定义
├── context/            # 上下文管理
├── coordinator/        # 协调器
├── entrypoints/        # 入口点
├── keybindings/        # 快捷键绑定
├── tools/              # 工具集
├── types/              # TypeScript 类型
├── utils/              # 工具函数
├── vim/                # Vim 集成
├── commands.ts         # 命令注册
├── main.tsx            # 主入口
└── ...
```

## 核心功能

- **AI 对话**: 与 Claude AI 实时交互
- **代码编辑**: 智能代码生成和修改
- **终端集成**: 命令执行和输出解析
- **文件操作**: 读写、搜索、分析文件
- **Git 集成**: 版本控制操作
- **Vim 模式**: 支持 Vim 快捷键

## 技术栈

- TypeScript
- React / Ink (终端 UI)
- Node.js

## 使用

```bash
# 安装依赖
npm install

# 构建
npm run build

# 运行
npm start
```

## 许可证

MIT
