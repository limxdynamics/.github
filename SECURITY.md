# Security Policy

This is the **organization-wide default** security policy for LimX Dynamics
open-source repositories. If a repository has its own `SECURITY.md`, that
file's process applies for that repository instead of this one.

## Reporting a vulnerability

**Do not** report security vulnerabilities through public GitHub issues,
discussions, or pull requests.

Preferred: use GitHub's private **"Report a vulnerability"** (Security
Advisory) feature on the affected repository, if it is enabled.

If that is not available, email **contact@limxdynamics.com** with the
subject prefix `[security] <repo-name>`.

Please include:

- Affected repository, file(s), and commit/tag.
- A concise description of the issue and its impact.
- Reproduction steps or a proof of concept, if safe to share privately.
- Whether the issue could affect real-robot safety, data exposure,
  authentication, or command execution.
- Suggested mitigation, if you have one.

Do not include secrets, tokens, private keys, customer data, or live robot
credentials in the report.

## Response

This is an open-source project security channel, handled on a best-effort
basis rather than under a guaranteed SLA. We will acknowledge and triage
reports as soon as practical. We support coordinated disclosure — please
don't publish details until a fix or advisory is available, or until we've
agreed on a disclosure timeline with you.

## Scope

This process covers software vulnerabilities in LimX Dynamics' public
repositories. Physical/operational safety of a real robot (falls, actuator
behavior, cabling, on-site setup) is a product-safety concern — contact
LimX Dynamics product support via https://www.limxdynamics.com instead of
using this channel.

## Supported versions

Unless a repository's own `SECURITY.md` says otherwise, security fixes
target the default branch and the latest tagged release. Older tags are
provided as-is.

## Responsible research guidelines

If you are testing for vulnerabilities, please avoid privacy violations and
service disruption, and do not access data beyond what is necessary to
demonstrate the issue. Do not run experiments against a physical robot that
could cause damage or endanger operators.

---

# 安全策略

本文件是 LimX Dynamics 开源仓库的**组织级默认安全策略**。如果某个仓库自带
`SECURITY.md`，以该仓库自己的流程为准。

## 如何报告安全漏洞

**请勿**通过公开的 GitHub Issue、Discussion 或 PR 报告安全漏洞。

首选方式：如果目标仓库已启用，请使用 GitHub 的私密 **"Report a
vulnerability"（安全公告）** 功能提交。

如无法使用该功能，请发送邮件至 **contact@limxdynamics.com**，邮件主题请加前缀
`[security] <仓库名>`。

请在报告中包含：

- 受影响的仓库、文件及 commit / tag。
- 问题及其影响的简要描述。
- 复现步骤或 PoC（如可以安全地私下分享）。
- 该问题是否可能影响实机安全、数据泄露、身份验证或命令执行。
- 如有，建议的缓解方案。

请勿在报告中包含密钥、Token、私钥、客户数据或真实机器人凭证。

## 响应时间

本渠道是开源项目的安全响应渠道，按尽力而为的原则处理，不承诺固定 SLA。我们会尽快确认收到报告并进行初步研判。我们支持协同披露——在修复方案或安全公告发布前，或在与你就披露时间达成一致前，请勿公开细节。

## 适用范围

本流程覆盖 LimX Dynamics 公开仓库中的软件安全漏洞。实机物理 / 运行安全问题（跌倒、执行器异常、线缆、现场部署等）属于产品安全范畴，请通过官网 https://www.limxdynamics.com 联系 LimX Dynamics 产品支持，而非通过本渠道报告。

## 支持的版本

除非仓库自带的 `SECURITY.md` 另有说明，安全修复面向默认分支和最新的正式发布版本，较旧的 tag 按原样提供，不再修复。

## 研究行为规范

如果你在测试漏洞，请避免侵犯隐私、造成服务中断，并且不要访问超出验证问题所必需范围的数据。请勿对实体机器人进行可能造成损坏或危及操作人员安全的实验。
