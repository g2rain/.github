# 贡献指南

感谢你对 g2rain 的关注。本文作为组织默认贡献说明；仓库自己的 `CONTRIBUTING.md`、`AGENTS.md`、README 和开发文档有更具体要求时，以项目文档为准。

## 开始前

1. 先阅读目标仓库的 README、`AGENTS.md`、`docs/index.md` 和贡献说明。
2. 搜索已有 Issue 和 Discussions，避免重复问题或重复实现。
3. 对跨项目架构、协议、安全模型或发布规则的变更，先在 [g2rain/g2rain](https://github.com/g2rain/g2rain) 提出讨论或 ADR，而不是仅在单一项目中实现。

## Issue 与 Pull Request

- Issue 请说明目标仓库、版本或提交、运行环境、复现步骤、实际结果和预期结果；不要提交凭据、Token、私钥或未修复漏洞细节。
- Pull Request 保持单一目的，说明动机、影响范围、验证命令和结果；关联相关 Issue/Discussion。
- 遵循目标仓库既有的分支、代码风格、测试和文档要求。不要在无关改动中重排或覆盖维护者已有修改。
- 行为、API、配置、部署、依赖、数据迁移或长期设计变化应同步更新直接相关文档。

## 文档与架构变更

平台级 Profile、跨项目 ADR、项目目录和治理资料由中央仓库维护。项目代码、需求、配置、部署、测试和项目级偏差由各项目仓库维护。详细边界见[组织默认文档约定](https://github.com/g2rain/g2rain/blob/main/docs/organization-defaults.md)。

提交前确认 Markdown 链接有效、`git diff --check` 通过，且文档不包含敏感信息。

## 社区规范

参与者须遵守[行为准则](CODE_OF_CONDUCT.md)。安全问题请遵循[安全报告流程](SECURITY.md)，不要在公开 Issue 中披露未修复漏洞。
