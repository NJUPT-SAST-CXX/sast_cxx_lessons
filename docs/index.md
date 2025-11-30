# SAST C++ 教程

欢迎来到 **南京邮电大学软件协会 C++ 教学课程**！

本课程旨在帮助初学者系统地学习 C++ 编程语言，从基础语法到现代 C++ 特性，从手动编译到构建系统，循序渐进地掌握 C++ 开发技能。

---

## 课程特色

<div class="grid cards" markdown>

-   :material-rocket-launch:{ .lg .middle } **从零开始**

    ---

    无需任何编程基础，从 Hello World 开始，逐步深入

-   :material-tools:{ .lg .middle } **实践导向**

    ---

    每个章节都配有可运行的代码示例和练习

-   :material-robot:{ .lg .middle } **AI 辅助编程**

    ---

    学习使用现代 AI 工具提升开发效率

-   :material-hammer-wrench:{ .lg .middle } **构建系统**

    ---

    掌握 CMake 等现代 C++ 构建工具

</div>

---

## 课程内容

### 第 0 章：Vibe Coding

学习如何利用 AI 工具辅助编程，包括：

- AI Agent 与 MCP 入门
- 主流 AI 编程工具对比
- Prompt 工程最佳实践

[:octicons-arrow-right-24: 开始学习](lessons/00-vibe-coding/index.md)

### 第 1 章：C++ 基础

从零开始学习 C++ 编程：

- 第一个 C++ 程序
- 变量、运算符、控制流
- 函数、数组、指针
- 类与对象

[:octicons-arrow-right-24: 开始学习](lessons/01-introduction/index.md)

### 第 2 章：构建系统

学习现代 C++ 项目构建：

- CMake 基础与进阶
- 跨平台构建配置
- 依赖管理

[:octicons-arrow-right-24: 开始学习](lessons/02-build-system/index.md)

---

## 快速开始

### 环境准备

=== "Windows"

    1. 安装 [Visual Studio](https://visualstudio.microsoft.com/) 或 [MinGW-w64](https://www.mingw-w64.org/)
    2. 安装 [CMake](https://cmake.org/download/)
    3. 安装 [VS Code](https://code.visualstudio.com/) + C/C++ 扩展

=== "macOS"

    ```bash
    # 安装 Xcode 命令行工具
    xcode-select --install
    
    # 使用 Homebrew 安装 CMake
    brew install cmake
    ```

=== "Linux"

    ```bash
    # Ubuntu/Debian
    sudo apt update
    sudo apt install build-essential cmake
    
    # Fedora
    sudo dnf install gcc-c++ cmake
    ```

### 克隆仓库

```bash
git clone https://github.com/AstroAir/sast_cxx_lessons.git
cd sast_cxx_lessons
```

### 本地预览文档

```bash
# 安装依赖
pip install -e ".[docs]"

# 启动本地服务器
mkdocs serve
```

访问 [http://127.0.0.1:8000](http://127.0.0.1:8000) 查看文档。

---

## 项目结构

```text
sast_cxx_lessons/
├── docs/                    # MkDocs 文档源文件
│   ├── index.md             # 首页
│   ├── getting-started.md   # 快速开始
│   ├── contributing.md      # 贡献指南
│   └── lessons/             # 课程内容
│       ├── 00-vibe-coding/  # AI 辅助编程
│       ├── 01-introduction/ # C++ 基础
│       └── 02-build-system/ # 构建系统
├── examples/                # 代码示例
│   ├── 00-vibe-coding/      # AI Agent 示例
│   ├── 01-introduction/     # C++ 基础示例
│   └── 02-build-system/     # CMake 示例项目
├── scripts/                 # 辅助脚本
├── mkdocs.yml               # MkDocs 配置
├── pyproject.toml           # Python 项目配置
└── CMakeLists.txt           # CMake 构建配置
```

---

## 贡献

欢迎提交 Issue 和 Pull Request！详见 [贡献指南](contributing.md)。

## 许可证

本项目采用 [MIT 许可证](https://github.com/AstroAir/sast_cxx_lessons/blob/main/LICENSE)。
