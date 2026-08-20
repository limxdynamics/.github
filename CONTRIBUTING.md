# Contributing to LimX Dynamics Open-Source Projects

Thanks for your interest in contributing. This file is the **organization-wide
default**. If a repository has its own `CONTRIBUTING.md`, that file's
instructions apply for that repository instead of this one.

## Before you start

- For anything more than a small fix, please open an issue first to discuss
  the change. This avoids wasted work on pull requests that don't fit the
  project's direction.
- Check existing issues and pull requests to avoid duplicating work.
- Real-robot safety-, security-, and control-related contributions may need
  additional maintainer review before merge — this is expected, not a sign
  something is wrong with your PR.

## Ways to contribute

- Bug reports with clear, minimal reproduction steps.
- Documentation fixes and translations (README, Quick Start, FAQ).
- New examples, tests, and small feature additions.
- Larger features or API changes — please discuss in an issue first.

## What we generally do not accept

- Trained model weights, checkpoints, or ONNX/JIT policy exports.
- Real robot logs, camera captures, or datasets that could contain
  identifiable people, sites, or customer information.
- Vendor CAD, calibration data, or firmware.
- Code copied from sources with an unclear or incompatible license.
- Large binary files (videos, simulation packages, large sample data) unless
  they are actually necessary and a maintainer has agreed to them.

## Development workflow

1. Fork the repository and create a branch from the default branch.
2. Make your change, following the repository's existing code style and
   linting/formatting setup.
3. Add or update tests where practical.
4. Run the repository's local checks (lint, tests, build) before opening a
   pull request.
5. Open a pull request against the default branch and fill in the PR
   template.

## Commit messages

Please follow [Conventional Commits](https://www.conventionalcommits.org/):

```
type(scope): short imperative summary

Longer explanation if needed.
```

Common types: `feat`, `fix`, `docs`, `refactor`, `test`, `chore`.

## License of contributions

License varies by repository — check the `LICENSE` file at the root of the
repository you're contributing to before submitting. Most LimX Dynamics
repositories use Apache License 2.0, but not all (some are BSD-3-Clause, and
a few do not yet have a LICENSE file). By submitting a contribution, you
agree it is licensed under whatever terms actually apply to that repository.

## Code of conduct

Participation in LimX Dynamics open-source projects is governed by our
[Code of Conduct](https://github.com/limxdynamics/.github/blob/main/CODE_OF_CONDUCT.md).
Please report unacceptable behavior to **contact@limxdynamics.com**.

## Reporting security issues

Do not report security vulnerabilities through public issues or pull
requests. See
[SECURITY.md](https://github.com/limxdynamics/.github/blob/main/SECURITY.md)
for the private reporting process.

## Questions

If you're not sure where to start, see
[SUPPORT.md](https://github.com/limxdynamics/.github/blob/main/SUPPORT.md) or
open a discussion/issue in the relevant repository.

---

# 参与 LimX Dynamics 开源项目贡献指南

感谢你对参与贡献的兴趣。本文件是**组织级默认贡献指南**。如果某个仓库自带了
`CONTRIBUTING.md`，以该仓库自己的文件为准。

## 开始之前

- 如果不是很小的修改，请先提一个 Issue 讨论方案，避免 PR 方向与项目规划不符导致返工。
- 提交前请先搜索现有 Issue / PR，避免重复劳动。
- 涉及实机安全、安全策略或底层控制相关的改动，可能需要额外的维护者评审才能合并，这是正常流程，不代表你的 PR 有问题。

## 可以贡献的内容

- 有清晰、最小复现步骤的 Bug 报告。
- 文档修正与翻译（README、Quick Start、FAQ）。
- 新增示例、测试用例，以及小型功能改进。
- 较大的功能或 API 变更——请先在 Issue 中讨论。

## 通常不接受的内容

- 训练好的模型权重、Checkpoint 或 ONNX / JIT 导出的策略文件。
- 可能包含可识别个人、场地或客户信息的真实机器人日志、摄像头录制或数据集。
- 厂商 CAD 图纸、标定数据或固件。
- 来源或授权不明确的第三方代码。
- 大型二进制文件（视频、仿真包、大型样例数据等），除非确实必要且已获得维护者同意。

## 开发流程

1. Fork 仓库，并从默认分支创建你的分支。
2. 按照仓库现有的代码风格和 lint / 格式化配置进行修改。
3. 在合理范围内补充或更新测试。
4. 在提交 PR 前，先在本地跑通仓库自带的检查（lint、测试、构建）。
5. 向默认分支提交 PR，并按模板填写内容。

## Commit 信息规范

请遵循 [Conventional Commits](https://www.conventionalcommits.org/) 规范：

```
type(scope): 简要祈使句描述

如有需要，补充更详细的说明。
```

常用 type：`feat`、`fix`、`docs`、`refactor`、`test`、`chore`。

## 贡献内容的许可

各仓库使用的许可证不完全相同——提交前请先查看目标仓库根目录下的 `LICENSE` 文件。LimX Dynamics 大多数仓库采用 Apache License 2.0，但并非全部（部分仓库为 BSD-3-Clause，还有少数仓库暂未添加 LICENSE 文件）。提交贡献即表示你同意该贡献采用该仓库实际适用的许可证条款。

## 行为准则

参与 LimX Dynamics 开源项目须遵守我们的[行为准则](https://github.com/limxdynamics/.github/blob/main/CODE_OF_CONDUCT.md)。如遇到不当行为，请举报至 **contact@limxdynamics.com**。

## 报告安全问题

请勿通过公开 Issue 或 PR 报告安全漏洞，请参阅
[SECURITY.md](https://github.com/limxdynamics/.github/blob/main/SECURITY.md)
中的私密报告流程。

## 有疑问？

如果不确定从何入手，请参阅
[SUPPORT.md](https://github.com/limxdynamics/.github/blob/main/SUPPORT.md)，或在对应仓库中发起讨论 / 提 Issue。
