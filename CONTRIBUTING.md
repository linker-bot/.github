# Contributing to Linkerbot projects

English and Chinese contributions are welcome. A repository's own contribution guide takes precedence over this organization default.

## Before you start

Read the project's README, license, compatibility notes, and existing issues. For a substantial API change, new dependency, or new hardware integration, open an issue to discuss the approach before investing in a large implementation.

## Report a bug

Use the repository's bug report form. Include the project version or commit, operating system, dependency versions, reproduction steps, expected behavior, and sanitized logs. For hardware-related problems, also include device model, firmware, connection type, and whether the problem occurs in simulation or on a physical device. Do not include credentials, personal data, or sensitive network details.

Report security vulnerabilities privately using [SECURITY.md](https://github.com/linker-bot/.github/blob/main/SECURITY.md).

## Submit a change

1. Fork the relevant repository and create a focused branch.
2. Follow its documented environment setup and coding conventions.
3. Make a focused change; update documentation and examples when behavior changes.
4. Run the project's formatter, checks, build, and relevant tests. Add a regression test when it meaningfully verifies a bug fix.
5. Open a pull request describing the problem, solution, validation, and any compatibility impact. Link related issues.

If a check requires equipment you do not have, say which checks you ran and which hardware checks remain unverified. Do not claim a device or firmware is supported based only on mocked tests. Keep hardware movement tests separate from normal CI and follow the project's operating instructions.

For changes to this repository, verify profile links, local document links, artwork, and issue form structure. Keep the English and Chinese profiles consistent.

## Review

Maintainers may request changes before merging. Keep discussion focused on the code and user impact. Do not change an existing project's license or include third-party code/assets without preserving their required attribution and license information.

## 中文说明

欢迎用中文或英文提交贡献。请先阅读目标仓库的 README、许可证和兼容说明；较大的接口或依赖变更先通过 Issue 讨论。PR 请写明问题、改动、验证方式和兼容性影响。涉及硬件时，注明设备型号、固件与连接方式；无法完成的硬件验证应明确标注。安全问题请私下报告。
