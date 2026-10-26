# Agent Craft — Agent 协作说明

## 仓库目标

本仓库沉淀 CommitByRyan 本人使用 Agent 的原则、工作流、实验与演进记录。
内容应当可验证、可追溯，并在保持历史的前提下持续迭代。

## 写作方式

- 默认使用中文。
- 以维护者第一人称或客观说明的方式写作，重点写决策、依据和实践结果。
- 结论区分“已验证”“推断”“尚未验证”。
- 不把一次偶然成功直接升级为稳定原则。
- 不删除已经发生的历史判断；结论改变时新增记录并链接旧记录。

## 内容边界

- 不写入 API Key、Token、Cookie、密码、私钥或完整凭据配置。
- 不粘贴无关的完整会话记录；只保留任务背景、关键判断和可复核证据。
- 不在 README、LICENSE 或元数据中注入 AI/Agent 署名、生成标签或徽章。
- 保留 `Copyright`、`Author` 和版权持有人信息。

## 更新位置

- 新原则：`principles/`
- 可复用流程：`playbooks/`
- 有假设和结果的验证：`experiments/`
- 重要取舍：`decisions/`
- 时间节点与思想变化：`evolution/`
- 新文件格式：先检查 `templates/`

发布到 GitHub 或远端仓库前，执行用户级 `github-publish-guardrails` 技能中的发布 Gate。
