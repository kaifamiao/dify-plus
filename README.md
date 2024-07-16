

# Diyf-plus 社区版

![image-20240717000543894](https://cdn.sa.net/2024/07/17/aWrSLHKXmJk4x6N.png)

## 演示地址：

## ![image-20240717003419572](https://cdn.sa.net/2024/07/17/6vThdorKxUO5J1w.png)

[Dify 云服务](https://cloud.dify.ai/) · [自托管](https://docs.dify.ai/getting-started/install-self-hosted) · [文档](https://docs.dify.ai/) · [预约演示](https://cal.com/guchenhe/dify-demo)

[![Static Badge](https://img.shields.io/badge/Product-F04438)](https://dify.ai/) [![Static Badge](https://img.shields.io/badge/free-pricing?logo=free&color=%20%23155EEF&label=pricing&labelColor=%20%23528bff)](https://dify.ai/pricing) [![chat on Discord](https://img.shields.io/discord/1082486657678311454?logo=discord&labelColor=%20%235462eb&logoColor=%20%23f5f5f5&color=%20%235462eb)](https://discord.gg/FngNHpbcY7) [![follow on Twitter](https://img.shields.io/twitter/follow/dify_ai?logo=X&color=%20%23f5f5f5)](https://twitter.com/intent/follow?screen_name=dify_ai) [![Docker Pulls](https://img.shields.io/docker/pulls/langgenius/dify-web?labelColor=%20%23FDB062&color=%20%23f79009)](https://hub.docker.com/u/langgenius) [![Commits last month](https://img.shields.io/github/commit-activity/m/langgenius/dify?labelColor=%20%2332b583&color=%20%2312b76a)](https://github.com/langgenius/dify/graphs/commit-activity) [![Issues closed](https://img.shields.io/github/issues-search?query=repo%3Alanggenius%2Fdify%20is%3Aclosed&label=issues%20closed&labelColor=%20%237d89b0&color=%20%235d6b98)](https://github.com/langgenius/dify/) [![Discussion posts](https://img.shields.io/github/discussions/langgenius/dify?labelColor=%20%239b8afb&color=%20%237a5af8)](https://github.com/langgenius/dify/discussions/)

[![上个月的提交次数](https://img.shields.io/badge/%E8%8B%B1%E6%96%87-d9d9d9)](http://localhost:63342/markdownPreview/1591364666/README.md) [![上个月的提交次数](https://img.shields.io/badge/%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-d9d9d9)](http://localhost:63342/markdownPreview/1591364666/README_CN.md) [![上个月的提交次数](https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-d9d9d9)](http://localhost:63342/markdownPreview/1591364666/README_JA.md) [![上个月的提交次数](https://img.shields.io/badge/%E8%A5%BF%E7%8F%AD%E7%89%99%E8%AF%AD-d9d9d9)](http://localhost:63342/markdownPreview/1591364666/README_ES.md) [![上个月的提交次数](https://img.shields.io/badge/%E6%B3%95%E8%AF%AD-d9d9d9)](http://localhost:63342/markdownPreview/1591364666/README_KL.md) [![上个月的提交次数](https://img.shields.io/badge/%E5%85%8B%E6%9E%97%E8%B4%A1%E8%AF%AD-d9d9d9)](http://localhost:63342/markdownPreview/1591364666/README_FR.md) [![上个月的提交次数](https://img.shields.io/badge/%E9%9F%93%E5%9C%8B%E8%AA%9E-d9d9d9)](http://localhost:63342/markdownPreview/1591364666/README_KR.md)

# 

[![langgenius%2Fdify | 趋势转变](https://trendshift.io/api/badge/repositories/2152)](https://trendshift.io/repositories/2152)

Dify 是一个开源的 LLM 应用开发平台。其直观的界面结合了 AI 工作流、RAG 管道、Agent、模型管理、可观测性功能等，让您可以快速从原型到生产。以下是其核心功能列表：



**1. 工作流**: 在画布上构建和测试功能强大的 AI 工作流程，利用以下所有功能以及更多功能。

https://github.com/langgenius/dify/assets/13230914/356df23e-1604-483d-80a6-9517ece318aa

**2. 全面的模型支持**: 与数百种专有/开源 LLMs 以及数十种推理提供商和自托管解决方案无缝集成，涵盖 GPT、Mistral、Llama3 以及任何与 OpenAI API 兼容的模型。完整的支持模型提供商列表可在[此处](https://docs.dify.ai/getting-started/readme/model-providers)找到。

![providersv5](https://github.com/langgenius/dify/assets/13230914/5a17bdbe-097a-4100-8363-40255b70f6e3)

**3. Prompt IDE**: 用于制作提示、比较模型性能以及向基于聊天的应用程序添加其他功能（如文本转语音）的直观界面。

**4. RAG Pipeline**: 广泛的 RAG 功能，涵盖从文档摄入到检索的所有内容，支持从 PDF、PPT 和其他常见文档格式中提取文本的开箱即用的支持。

**5. Agent 智能体**: 您可以基于 LLM 函数调用或 ReAct 定义 Agent，并为 Agent 添加预构建或自定义工具。Dify 为 AI Agent 提供了50多种内置工具，如谷歌搜索、DELL·E、Stable Diffusion 和 WolframAlpha 等。

**6. LLMOps**: 随时间监视和分析应用程序日志和性能。您可以根据生产数据和标注持续改进提示、数据集和模型。

**7. 后端即服务**: 所有 Dify 的功能都带有相应的 API，因此您可以轻松地将 Dify 集成到自己的业务逻辑中。

## 功能比较

| 功能                     | Dify.AI            | LangChain   | Flowise      | OpenAI Assistant API |
| ------------------------ | ------------------ | ----------- | ------------ | -------------------- |
| 编程方法                 | API + 应用程序导向 | Python 代码 | 应用程序导向 | API 导向             |
| 支持的 LLMs              | 丰富多样           | 丰富多样    | 丰富多样     | 仅限 OpenAI          |
| RAG引擎                  | ✅                  | ✅           | ✅            | ✅                    |
| Agent                    | ✅                  | ✅           | ❌            | ✅                    |
| 工作流                   | ✅                  | ❌           | ✅            | ❌                    |
| 可观测性                 | ✅                  | ✅           | ❌            | ❌                    |
| 企业功能（SSO/访问控制） | ✅                  | ❌           | ❌            | ❌                    |
| 本地部署                 | ✅                  | ✅           | ✅            | ❌                    |

## 使用 Dify

- **云
  
  **我们提供[ Dify 云服务](https://dify.ai/)，任何人都可以零设置尝试。它提供了自部署版本的所有功能，并在沙盒计划中包含 200 次免费的 GPT-4 调用。

- **自托管 Dify 社区版
  
  **使用这个[入门指南](http://localhost:63342/markdownPreview/1591364666/markdown-preview-index-2096572802.html?_ijt=ofo5qsdqq59fu04s6di6gpq53c#quick-start)快速在您的环境中运行 Dify。 使用我们的[文档](https://docs.dify.ai/)进行进一步的参考和更深入的说明。

- **面向企业/组织的 Dify
  
  **我们提供额外的面向企业的功能。[与我们安排会议](https://cal.com/guchenhe/30min)或[给我们发送电子邮件](mailto:business@dify.ai?subject=[GitHub]Business License Inquiry)讨论企业需求。

  > 对于使用 AWS 的初创公司和中小型企业，请查看 [AWS Marketplace 上的 Dify 高级版](https://aws.amazon.com/marketplace/pp/prodview-t22mebxzwjhu6)，并使用一键部署到您自己的 AWS VPC。它是一个价格实惠的 AMI 产品，提供了使用自定义徽标和品牌创建应用程序的选项。

## 保持领先

在 GitHub 上给 Dify Star，并立即收到新版本的通知。

![starus](https://github.com/langgenius/dify/assets/13230914/b823edc1-6388-4e25-ad45-2f6b187adbb4)

## 安装社区版

### 系统要求

在安装 Dify 之前，请确保您的机器满足以下最低系统要求：

- CPU >= 2 Core
- RAM >= 4GB

### 快速启动

启动 Dify 服务器的最简单方法是运行我们的 [docker-compose.yml](file:///Users/linrui/PycharmProjects/dify-plus/docker/docker-compose.yaml) 文件。在运行安装命令之前，请确保您的机器上安装了 [Docker](https://docs.docker.com/get-docker/) 和 [Docker Compose](https://docs.docker.com/compose/install/)：

```bash
cd docker
cp .env.example .env
docker compose up -d
```

运行后，可以在浏览器上访问 http://localhost/install 进入 Dify 控制台并开始初始化安装操作。

### 自定义配置

如果您需要自定义配置，请参考 [.env.example](file:///Users/linrui/PycharmProjects/dify-plus/docker/.env.example) 文件中的注释，并更新 `.env` 文件中对应的值。此外，您可能需要根据您的具体部署环境和需求对 `docker-compose.yaml` 文件本身进行调整，例如更改镜像版本、端口映射或卷挂载。完成任何更改后，请重新运行 `docker-compose up -d`。您可以在[此处](https://docs.dify.ai/getting-started/install-self-hosted/environments)找到可用环境变量的完整列表。

#### 使用 Helm Chart 部署

使用 [Helm Chart](https://helm.sh/) 版本或者 YAML 文件，可以在 Kubernetes 上部署 Dify。

- [Helm Chart by @LeoQuote](https://github.com/douban/charts/tree/master/charts/dify)
- [Helm Chart by @BorisPolonsky](https://github.com/BorisPolonsky/dify-helm)
- [YAML 文件 by @Winson-030](https://github.com/Winson-030/dify-kubernetes)

#### 使用 Terraform 部署

##### Azure Global

使用 [terraform](https://www.terraform.io/) 一键部署 Dify 到 Azure。

- [Azure Terraform by @nikawang](https://github.com/nikawang/dify-azure-terraform)

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=langgenius/dify&type=Date)](https://star-history.com/#langgenius/dify&Date)

## Contributing

对于那些想要贡献代码的人，请参阅我们的[贡献指南](https://github.com/langgenius/dify/blob/main/CONTRIBUTING.md)。 同时，请考虑通过社交媒体、活动和会议来支持 Dify 的分享。

> 我们正在寻找贡献者来帮助将Dify翻译成除了中文和英文之外的其他语言。如果您有兴趣帮助，请参阅我们的[i18n README](https://github.com/langgenius/dify/blob/main/web/i18n/README.md)获取更多信息，并在我们的[Discord社区服务器](https://discord.gg/8Tpq4AcN9c)的`global-users`频道中留言。

**Contributors**

[![img](https://contrib.rocks/image?repo=langgenius/dify)](https://github.com/langgenius/dify/graphs/contributors)

## 社区与支持

我们欢迎您为 Dify 做出贡献，以帮助改善 Dify。包括：提交代码、问题、新想法，或分享您基于 Dify 创建的有趣且有用的 AI 应用程序。同时，我们也欢迎您在不同的活动、会议和社交媒体上分享 Dify。

- [Github Discussion](https://github.com/langgenius/dify/discussions). 👉：分享您的应用程序并与社区交流。
- [GitHub Issues](https://github.com/langgenius/dify/issues)。👉：使用 Dify.AI 时遇到的错误和问题，请参阅[贡献指南](file:///Users/linrui/PycharmProjects/dify-plus/CONTRIBUTING.md)。
- [电子邮件支持](mailto:hello@dify.ai?subject=[GitHub]Questions About Dify)。👉：关于使用 Dify.AI 的问题。
- [Discord](https://discord.gg/FngNHpbcY7)。👉：分享您的应用程序并与社区交流。
- [Twitter](https://twitter.com/dify_ai)。👉：分享您的应用程序并与社区交流。
- [商业许可](mailto:business@dify.ai?subject=[GitHub]Business License Inquiry)。👉：有关商业用途许可 Dify.AI 的商业咨询。
- [微信](file:///Users/linrui/PycharmProjects/dify-plus/) 👉：扫描下方二维码，添加微信好友，备注 Dify，我们将邀请您加入 Dify 社区。
  ![wechat](http://localhost:63342/markdownPreview/1591364666/images/wechat.png)

## 安全问题

为了保护您的隐私，请避免在 GitHub 上发布安全问题。发送问题至 security@dify.ai，我们将为您做更细致的解答。

## License

本仓库遵循 [Dify Open Source License](file:///Users/linrui/PycharmProjects/dify-plus/LICENSE) 开源协议，该许可证本质上是 Apache 2.0，但有一些额外的限制。









<img src="https://cdn.sa.net/2024/07/17/yPZoEwn6uWFxihJ.jpg" alt="kaifamiao" style="zoom:33%;" />

# 关于开发喵AI：

开发喵AI是一款汇集市面上所有优秀AI工具的私人AI平台助手。由一群充满活力的年轻人组成的开发喵团队创立并维护，我们的使命是让AI融入生活，让更多人不受限制地使用AI。”AI that everyone can use” 是我们的口号。

我们的主营业务是AI超市，提供各类AI账号、AI教学、AIGC和GPT、知识库搭建、AI的API服务以及AI相关软件的研发。

在开发喵AI的AI超市中，您可以享受各种AI服务和工具，帮助您解决问题、提高效率，甚至创造更多价值。我们致力于让AI技术更加普及和易用，让每个人都能轻松享受AI带来的便利和创新。

我们提供的服务范围广泛，包括但不限于：

- AI账号提供：通过联系开发喵团队成员，您可以获得专属的AI账号，开始使用我们的智能解决方案。
- AI教学：我们致力于为用户提供关于AI的教育和培训，让更多人了解和熟练运用AI技术。
- AIGC和GPT：我们整合了AIGC和GPT等先进技术，为用户提供更智能的服务和支持。
- 企业级AI API服务：我们提供定制化的AI API服务，满足企业需求。
- RAG/AGENT知识库搭建：我们帮助用户构建个性化的知识库，让您更便捷地获取所需信息。

> 无论您是想解决问题、提高效率，还是创造更多价值，开发喵AI都将是您强大的助手。让我们携手努力，让AI真正走进生活，让每个人都能轻松使用AI技术！



> 暗语：学习开发RAG

<img src="https://cdn.sa.net/2024/07/17/YDVifqPZvcdJoWI.png" alt="image-20240717001443096" style="zoom:33%;" />
