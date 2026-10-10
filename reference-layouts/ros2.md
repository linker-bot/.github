# ROS 2 包目录参考

```text
project/
├── README.md
├── LICENSE
├── CHANGELOG.md
├── .github/workflows/ci.yml
├── docs/compatibility.md
└── <package_name>/
    ├── package.xml
    ├── CMakeLists.txt 或 setup.py + setup.cfg
    ├── include/ + src/ 或 <package_name>/ + resource/
    ├── launch/
    ├── config/
    └── test/
```

仓库可以包含一个或多个 ROS 2 包；依照 ament_cmake 或 ament_python 的实际包结构创建文件，图中的“或”不是文件名。说明支持的 ROS 2 发行版、系统、消息依赖和工作空间构建步骤。记录 colcon build、colcon test 与 colcon test-result 的验证结果。默认测试不启动真实设备；launch 参数区分仿真与硬件模式，记录 topic、service、坐标系和单位。

公共协作文件可使用组织默认配置；工作流必须在项目自身配置。示例目录按实际用途保留。
