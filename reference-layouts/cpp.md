# C++ SDK / 库目录参考

```text
project/
├── README.md
├── LICENSE
├── CHANGELOG.md
├── CMakeLists.txt
├── .github/workflows/ci.yml
├── include/<project_name>/
├── src/
├── tests/
├── examples/
├── cmake/
└── docs/compatibility.md
```

在 CMake 中声明最低版本、C++ 标准和依赖。公共头文件与内部实现分开；说明构建、安装与下游链接方式。CI 至少构建库并运行无设备测试，使用 CTest 时记录调用方式。硬件通信示例与设备测试不在普通 CI 中运行；ABI/API 变化记录升级影响。

公共协作文件可使用组织默认配置；工作流必须在项目自身配置。示例目录按实际用途保留。
