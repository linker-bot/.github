# 机器人模型与仿真资产目录参考

```text
project/
├── README.md
├── LICENSE
├── THIRD_PARTY_NOTICES.md
├── .github/workflows/ci.yml
├── robots/<model_name>/
│   ├── urdf/
│   ├── mjcf/
│   ├── meshes/
│   └── README.md
├── scenes/
├── scripts/
└── docs/compatibility.md
```

只保留实际提供的格式目录。每个模型说明来源、许可、版本、单位、坐标系、关节限制和适用仿真器；不同授权资产逐项列明，不用仓库顶层 LICENSE 覆盖第三方许可。检查模型引用和网格文件存在、描述文件能被目标工具解析；涉及物理参数时注明测量或估计来源。大型文件按团队选择的存储方式管理并记录下载步骤。

公共协作文件可使用组织默认配置；工作流必须在项目自身配置。示例目录按实际用途保留。
