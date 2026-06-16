## Hi there 👋

**g2rain**（开源谷雨 SaaS 平台，Grain Rain）是一个面向企业级场景的开源 SaaS 平台，围绕**多租户**、**应用交付**与**商务计费**构建完整解决方案，支持从应用开发到订阅、账单与结算的端到端闭环。

平台采用微服务架构，通过**网关**与**推送中心**实现同步与异步两种数据交付方式，并提供统一的授权与鉴权能力，基于 **DPoP**、**IAM**、**Lua** 等技术保障安全与能力扩展。

---

## 核心能力

- **多租户隔离**：保障租户间数据隔离与高效运行
- **应用交付**：微前端壳应用 + 子应用模板，支持 SSO 与快速扩展
- **商业化闭环**：订阅、计量、账单、对账与结算
- **数据洞察**：集成 BI 分析，支撑运营与决策

## 核心模块

| 模块 | 说明 |
|------|------|
| 网关 | 请求路由、身份验证与日志采集 |
| IAM | 身份认证与授权（SSO、Token 签发与校验） |
| 推送中心 | 异步任务处理与结果推送 |
| 订阅 / 账单 | 产品订阅、用量跟踪与计费结算 |
| BI | 业务数据分析与可视化 |

项目遵循 **DDD（领域驱动设计）** 理念，并提供便捷的开发工具链：

- 接口交互规范（common 包）
- Java 项目生成器
- 代码生成器
- 前端应用页面生成器

---

## 技术栈

**后端**：Java（JDK 25）、Spring Boot 4.0、Spring Cloud、Spring Gateway、MySQL、Redis 等

**前端**：TypeScript、Vue 3、qiankun（微前端）、Vite 5、Element Plus 等

---

## 快速开始

- **入口项目**：[g2rain/g2rain](https://github.com/g2rain/g2rain)
- **官方网站**：https://www.g2rain.com
- **文档站点**：https://docs.g2rain.com
- **讨论区**：[Discussions](https://github.com/g2rain/g2rain/discussions)

欢迎 Star、Fork 与贡献，一起打造更好用的企业级开源平台 🚀
