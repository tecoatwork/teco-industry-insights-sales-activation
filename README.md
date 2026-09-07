# teco-industry-insights-sales-activation

一个将经过核验的 B2B 行业情报转化为商业机会和买家相关销售内容的 Codex Skill。

## 功能概述

本 Skill 可以建立公司与产品基线，监测每周市场动态，分析消费者行为变化、监管政策、供应链及头部品牌动向，评估商业机会，并运用 SCRP 模型生成：

- 冷开发邮件（Cold Email）
- LinkedIn 私信
- WhatsApp 消息
- LinkedIn 帖子
- 内部行业情报报告

本 Skill 会明确区分事实、企业声明、弱信号、分析推断和行动建议。它不会自动发送消息或发布内容。

## 输入信息

请提供行业、公司、产品、目标国家、买家角色和所需输出。若需持续使用，可将 `references/configuration-template.md` 复制到私有项目文件中并填写完整。

## 输出内容

报告首先呈现对业务决策的影响及按优先级排序的商业机会，随后提供证据、SCRP 分析和所需的客户开发内容草稿。重要结论会附上直接来源并说明证据局限。

## 安装方法

将本仓库复制或克隆到 Codex Skills 目录：

```bash
git clone https://github.com/tecoatwork/teco-industry-insights-sales-activation.git ~/.codex/skills/teco-industry-insights-sales-activation
```

如果 Codex 未立即识别该 Skill，请重启或重新加载 Codex。

## 调用示例

```text
使用 teco-industry-insights-sales-activation 的 baseline 模式，了解我们的公司、产品、买家和重点市场。
```

```text
运行 weekly 模式，研究过去七天的信息。识别不超过三个经过核验的商业机会，并起草一篇 LinkedIn 帖子和一条买家消息。
```

```text
针对我们在德国和阿联酋的专业美容设备业务运行 full 模式。区分现行法规与提案，并标注所有企业声明。
```

## 依赖说明

本 Skill 不依赖特定的研究服务商，可以使用当前环境中的网页搜索、浏览器或公开数据工具。企业私有配置应保存在本仓库之外。

## 验证范围

本 Skill 已通过 Codex Skill 验证工具的结构检查，检查范围包括 Skill 命名、YAML frontmatter 和目录结构完整性。该检查不会独立验证未来研究中出现的每一项市场结论；每次研究仍须单独审核信息来源和具体声明。

## 许可证

本项目采用 MIT 许可证，详见 `LICENSE`。
