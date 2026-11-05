<p align="center">
  <img src="https://raw.githubusercontent.com/linker-bot/.github/main/profile/assets/banner.png" alt="LinkerBot — Clever Hands Create Everything" width="100%">
</p>

<p align="center">面向 LinkerBot 灵巧手与机械臂的开源 SDK、通信库、遥操作工具和仿真项目。</p>

<p align="center">
  <a href="https://linkerbot.cn">官网</a> ·
  <a href="https://github.com/linker-bot/SDK">SDK 项目目录</a> ·
  <a href="https://github.com/linker-bot/.github/blob/main/profile/README.md">English</a>
</p>

## 从这里开始

先在 [SDK 项目目录](https://github.com/linker-bot/SDK)中选择维护中的项目，并查看旧版 SDK 的迁移说明。安装与构建步骤以各项目仓库为准。

- **灵巧手控制**：使用 [C++ SDK](https://github.com/linker-bot/linkerbot-hand-cpp-sdk)、[Python SDK](https://github.com/linker-bot/linkerbot-hand-python-sdk)，或通过 [Hand ROS 2 SDK](https://github.com/linker-bot/linkerbot-hand-ros2-sdk) 接入 ROS 话题与服务。
- **机械臂控制**：使用 [Arm Python SDK](https://github.com/linker-bot/linkerbot-arm-python-sdk) 或 [Arm ROS 2 SDK](https://github.com/linker-bot/linkerbot-arm-ros2-sdk)。
- **通信集成**：使用 [C++ 通信库](https://github.com/linker-bot/linkerbot-transport-cpp)或 [Python 通信库](https://github.com/linker-bot/linkerbot-transport)，独立于设备控制 API 接入通信。
- **仿真**：从 [linker-sim](https://github.com/linker-bot/linker-sim) 和仓库中的使用说明开始。

运行硬件示例前，请先核对各项目支持的型号、固件、适配器、操作系统和安装步骤。

## 项目导航

### 工具与遥操作

- [linkerbot-hand-tools](https://github.com/linker-bot/linkerbot-hand-tools)：灵巧手 CLI/TUI 与 Web 工具，支持遥测、触觉可视化和离线仿真。
- [linkerhand-telop-ros2](https://github.com/linker-bot/linkerhand-telop-ros2)：ROS 2 数据手套到灵巧手的运动重定向。
- [linkerbot-teleop-arm](https://github.com/linker-bot/linkerbot-teleop-arm)：通过 SocketCAN 读取双臂输入设备，提供 C++ 核心、CLI 和 ROS 2 节点；该项目不负责机械臂运动控制。

### 已有应用与旧版 SDK

旧版 SDK 保留供已有应用使用。更换 SDK 前，请查阅 [SDK 目录与旧版迁移指南](https://github.com/linker-bot/SDK/blob/main/MIGRATION.md)。后继项目不一定能够直接替换旧版，需核对型号覆盖与接口差异。

### 仿真与资产

- [linker-sim](https://github.com/linker-bot/linker-sim)：仿真项目。
- [linker-sim-isaac](https://github.com/linker-bot/linker-sim-isaac)：Isaac 仿真项目。
- [linker-sim-viser](https://github.com/linker-bot/linker-sim-viser)：基于 Viser 的可视化项目。
- [linker-sim-assets](https://github.com/linker-bot/linker-sim-assets)：供仿真项目使用的机器人描述文件与资产。

[查看全部仓库 →](https://github.com/orgs/linker-bot/repositories)

## 参与贡献

欢迎提交问题反馈、文档改进、使用示例和代码贡献。请先阅读项目 README 与[贡献指南](https://github.com/linker-bot/.github/blob/main/CONTRIBUTING.md)。

- **使用问题与 Bug**：在对应仓库提交 Issue，参阅[支持指南](https://github.com/linker-bot/.github/blob/main/SUPPORT.md)。
- **安全问题**：按[安全策略](https://github.com/linker-bot/.github/blob/main/SECURITY.md)私下报告。
- **创建新项目**：参阅[仓库规范、文档模板和目录参考](https://github.com/linker-bot/.github#repository-standards-and-templates)。

参与讨论时，请遵守[社区行为准则](https://github.com/linker-bot/.github/blob/main/CODE_OF_CONDUCT.md)。
