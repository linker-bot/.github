# Python SDK / 工具目录参考

```text
project/
├── README.md
├── LICENSE
├── CHANGELOG.md
├── pyproject.toml
├── .github/workflows/ci.yml
├── src/<package_name>/
├── tests/
├── examples/
└── docs/
    ├── installation.md
    ├── quickstart.md
    ├── compatibility.md
    └── troubleshooting.md
```

在 pyproject.toml 中声明构建系统、支持的 Python 版本和依赖。选用项目已有的格式与测试工具，不叠加重复工具。单元测试使用模拟传输或固定数据；真实 CAN/设备测试单独标记并由操作者显式运行。CI 验证实际声明支持的 Python 版本，必要时在干净环境检查包构建和安装。

公共协作文件可使用组织默认配置；工作流必须在项目自身配置。示例目录按实际用途保留。
