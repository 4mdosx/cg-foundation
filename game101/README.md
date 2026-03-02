# Games 101 作业环境

这是一个专门为 **macOS 环境**设计的 Games 101 学习项目，使用 C++、CMake 构建系统。

## 环境要求

- **操作系统**：macOS（推荐 macOS 12.0 或更高版本）
- **C++标准**：C++17 或更高版本
- **构建工具**：CMake 3.10 或更高版本
- **依赖管理**：Homebrew

## How to start

```bash
# 在 macOS 上使用 Homebrew 安装所需依赖：
brew install cmake eigen

# build and run
cd game101/homework0
mkdir -p build && cd build
cmake ..
make
```


