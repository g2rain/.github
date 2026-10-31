<p align="center">
  <img src="https://github.com/g2rain.png" alt="G2rain（谷雨）开源智能体平台" width="120" />
</p>

# G2rain（谷雨）开源智能体平台

**面向企业的开源智能体平台，连接模型、知识与业务工具，让智能体在明确的身份和权限边界内执行任务。**

G2rain 面向希望将 AI 接入实际业务的开发者与企业团队，结合 SaaS基座、知识库和前后端开发工具链，支撑企业智能应用落地。平台采用 Java 微服务与 Vue 3 微前端。

**私有部署已可用。** 企业可以在自己的环境部署现有 SaaS基座、知识库及业务应用。智能体平台与智能客服已开发完成、待开放；交易、订阅、计量计费等商业化能力面向云端运营，处于规划设计中，不是私有部署的前置条件。

**[从主仓库开始探索](https://github.com/g2rain/g2rain)** · [官方网站](https://www.g2rain.com) · [平台文档](https://github.com/g2rain/g2rain/blob/main/docs/index.md) · [社区交流](https://github.com/g2rain/g2rain/discussions)

欢迎 **[Star g2rain/g2rain](https://github.com/g2rain/g2rain)** 收藏项目总入口，并在本组织主页点击 **Follow**，关注后续动态。

## 在线体验

- [知识对话演示](https://demo.g2rain.com/chat/?entry=ek_xV3IEOTK8HfexoR3PupYcF)：无需登录。
- [主应用演示](https://demo.g2rain.com/main/)：演示用户名和密码均为 `admin`。
- [联系维护者](https://www.g2rain.com/platform/contact.html)：交流部署、使用和项目接入。

演示可体验与正式开放分别说明，智能体平台和智能客服的开放安排另行公布。

## 当前能力

| 方向 | 当前状态 |
| --- | --- |
| 基础搭建 | 已可用，具备应用开发、部署与更新基础 |
| SaaS基座能力 | 现有组织租户、身份、应用授权和资源权限能力已可用 |
| 知识库能力 | 服务与运营端 v1.0.0 已发布，可部署使用 |
| 智能体平台 | 已开发完成，待开放 |
| 智能客服 | 已开发完成，待开放 |
| 云端商业化 | 交易开通、订阅、计量计费与账单等处于规划设计中 |

当前版本与后续目标见[平台路线图](https://github.com/g2rain/g2rain/blob/main/docs/roadmap.md)。

## 平台价值

| 核心方向 | 解决的问题 |
| --- | --- |
| **企业级权限管控** | 用组织、应用授权、角色、控制域、控制单元与资源关系，组织租户能力开通和岗位权限；由 IAM、Gateway 与业务服务分层校验 |
| **智能体编排** | 连接知识、业务能力与任务执行，以身份与权限边界连接模型、知识和业务工具；智能体平台已开发完成、待开放 |
| **应用开发与交付** | 通过微服务、微前端、研发工具与版本化架构规则，让多仓库项目协同演进 |

## 从知识到对话，看到业务场景

围绕平台入门指南连续提问，回答中显示知识参考来源；管理侧围绕知识版本、发布信息和执行追踪组织操作。

[![G2rain（谷雨）开源智能体平台 知识问答界面：连续提问与知识参考](https://raw.githubusercontent.com/g2rain/.github/main/profile/assets/knowledge-conversation.png)](https://github.com/g2rain/g2rain#看看谷雨如何连接知识与业务)

[前往主仓库查看更多界面、权限说明与项目进展 →](https://github.com/g2rain/g2rain)

截图由维护者提供，展示可见交互；各项目的可用版本、运行条件与集成验证状态以项目文档为准。

## 选择你的探索方向

| 方向 | 推荐入口 | 了解什么 |
| --- | --- | --- |
| 平台总览 | **[g2rain/g2rain](https://github.com/g2rain/g2rain)** | 平台定位、能力状态、项目导航与使用入口 |
| 企业权限与身份 | [Basis](https://github.com/g2rain/g2rain-basis) · [IAM](https://github.com/g2rain/g2rain-iam) · [Gateway 架构](https://github.com/g2rain/g2rain/tree/main/docs/architecture/profiles/gateway-service) | 组织与应用主数据、身份协议与接口授权边界 |
| 知识与 Agent | [知识与智能体集成](https://github.com/g2rain/g2rain/blob/main/docs/architecture/knowledge-integration.md) | 知识生命周期、检索证据与 Runtime 协作 |
| 前端应用 | [Main Shell](https://github.com/g2rain/g2rain-main-shell) · [App Template](https://github.com/g2rain/g2rain-app-template) | 微前端主壳与业务应用基础 |
| 研发工具 | [App CLI](https://github.com/g2rain/g2rain-app-cli) · [Crafter](https://github.com/g2rain/g2rain-crafter) · [Generator](https://github.com/g2rain/g2rain-generator-maven-plugin) | 前后端项目创建与代码生成 |
| 部署与运行 | [g2rain-deploy](https://github.com/g2rain/g2rain-deploy) | 环境初始化、部署编排与生命周期管理 |
| 架构协作 | [架构基线](https://github.com/g2rain/g2rain/tree/main/docs/architecture) · [项目目录](https://github.com/g2rain/g2rain/blob/main/docs/architecture/catalog/projects.yaml) | Profile、ADR 与项目采用状态 |

平台定位、当前能力状态与项目导航由主仓库维护；具体项目维护实现、配置、部署和测试。部署请从 [g2rain-deploy](https://github.com/g2rain/g2rain-deploy)开始，介绍或引用项目可使用[统一介绍资料](https://github.com/g2rain/g2rain/blob/main/docs/project-introduction.md)。

## 一起参与建设

欢迎使用者、开发者与业务实践者加入。第一次参与，可以从修正文档、反馈一个上手问题或分享一个业务场景开始。

- **问题与反馈**：[提交 Issue](https://github.com/g2rain/g2rain/issues/new/choose)，说明目标仓库、版本、环境和复现步骤。
- **场景与经验**：[参与 Discussions](https://github.com/g2rain/g2rain/discussions)，交流企业权限、知识库与 Agent 应用。
- **文档与代码**：[阅读贡献指南](https://github.com/g2rain/.github/blob/main/CONTRIBUTING.md)，在责任仓库提交 PR。
- **社区与安全**：遵守[行为准则](https://github.com/g2rain/.github/blob/main/CODE_OF_CONDUCT.md)，安全问题按[私下报告流程](https://github.com/g2rain/.github/blob/main/SECURITY.md)处理。

## 联系项目维护者

项目邮箱：[g2rain_developer@163.com](mailto:g2rain_developer@163.com)

**微信一对一交流**：欢迎添加维护者「行者」，交流项目使用、企业权限、知识库与智能体编排。添加时可备注“G2rain + 交流主题”。

<a href="https://raw.githubusercontent.com/g2rain/.github/main/profile/assets/wechat.jpg">
  <img src="https://raw.githubusercontent.com/g2rain/.github/main/profile/assets/wechat.jpg" alt="维护者行者的微信二维码，扫码进行 G2rain 一对一交流" width="240" />
</a>

扫码不便时，可[打开二维码原图](https://raw.githubusercontent.com/g2rain/.github/main/profile/assets/wechat.jpg)。通用使用问题也欢迎公开交流，方便社区共同参考。

## 开源协议

已开放模块统一采用标准 Apache License 2.0。各模块入口及适用范围见[开源协议说明](https://github.com/g2rain/g2rain/blob/main/docs/licenses.md)；第三方依赖与外部服务遵循各自条款。

感谢每一位使用、反馈、分享与贡献 G2rain（谷雨）开源智能体平台的朋友。
