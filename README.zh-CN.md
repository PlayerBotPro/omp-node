# open.mp SDK 示例

## 工具

* [CMake 3.19+](https://cmake.org/)
* [Conan 1.33+](https://conan.io/)

## Windows 所需工具

* [Visual Studio 2019+](https://www.visualstudio.com/)

Visual Studio 需要安装“使用 C++ 的桌面开发”（`Desktop development with C++`）工作负载，以及 `MSVC v142`、`Windows 10 SDK` 和 `C++ Clang tools for Windows` 组件。

## 获取源码

```bash
# 使用 HTTPS：
git clone --recursive https://github.com/openmultiplayer/open.mp-sdk-example
# 使用 SSH：
git clone --recursive git@github.com:openmultiplayer/open.mp-sdk-example
```

请注意使用 `--recursive` 参数，因为此仓库包含子模块。

## 在 Windows 上构建

```bash
cd  open.mp-sdk-example
mkdir build
cd build
cmake .. -A Win32 -T ClangCL
```

打开 Visual Studio 并构建解决方案。
