# SAST C++ 教程

[![MkDocs](https://img.shields.io/badge/docs-MkDocs-blue)](https://astroair.github.io/sast_cxx_lessons/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

南京邮电大学协会 C++ 教学课程。

## 📚 课程内容

| 章节 | 内容 | 状态 |
|------|------|------|
| 第 0 章 | [Vibe Coding - AI 辅助编程](docs/lessons/00-vibe-coding/index.md) | ✅ |
| 第 1 章 | [C++ 基础教程](docs/lessons/01-introduction/index.md) | ✅ |
| 第 2 章 | [构建系统 - CMake](docs/lessons/02-build-system/index.md) | ✅ |

## 🚀 快速开始

### 环境要求

- C++ 编译器（支持 C++17+）
- CMake 3.10+
- Python 3.12+（用于文档）

### 克隆仓库

```bash
git clone https://github.com/AstroAir/sast_cxx_lessons.git
cd sast_cxx_lessons
```

### 构建示例

```bash
mkdir build && cd build
cmake ..
cmake --build .
```

### 本地预览文档

```bash
# 安装文档依赖
pip install -e ".[docs]"

# 启动本地服务器
mkdocs serve
```

访问 [http://127.0.0.1:8000](http://127.0.0.1:8000) 查看文档。

## 📁 项目结构

```
sast_cxx_lessons/
├── docs/                    # MkDocs 文档源文件
│   ├── index.md             # 文档首页
│   ├── getting-started.md   # 快速开始
│   ├── contributing.md      # 贡献指南
│   └── lessons/             # 课程内容
│       ├── 00-vibe-coding/  # AI 辅助编程
│       ├── 01-introduction/ # C++ 基础
│       └── 02-build-system/ # 构建系统
├── examples/                # 代码示例
│   ├── 00-vibe-coding/      # AI Agent 示例代码
│   ├── 01-introduction/     # C++ 基础示例
│   └── 02-build-system/     # CMake 示例项目
├── scripts/                 # 辅助脚本
├── mkdocs.yml               # MkDocs 配置
├── pyproject.toml           # Python 项目配置
├── CMakeLists.txt           # CMake 构建配置
└── LICENSE                  # MIT 许可证
```

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！详见 [贡献指南](docs/contributing.md)。

## 📄 许可证

本项目采用 [MIT 许可证](LICENSE)
