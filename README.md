# chinese-text

中文正式写作与文稿审核 Skill。本仓库现为合并后的正式 Skill「chinese-text」的源码，用于替换原先的 `chinese-text-auditor` 与 `contract-audit`。仓库名称仍为 `skill-chinese-text-auditor`，以便沿用既有地址。

本 Skill 用于：

- Agent 的全部输出，以及 Agent 生成的内容
- 用户口语化或语义不明的输入审核
- 对外公文、计划书、方案、纪要、邮件、合同、采购订单、SOW、验收文件等的写作、润色、审核
- 经用户确认后，写入飞书云文档或 Word

## 安装

将本仓库中的 `SKILL.md` 与 `references/comment-style.md` 一并安装到 Agent 的 Skill 目录，Skill 名称（id 与显示名）为 `chinese-text`。

```bash
npx skills add huhupeng123456-lgtm/skill-chinese-text-auditor
```

## 主要规则

- 正式但不晦涩，不把正式书面语改成口语短句；正式不等于拘谨或一板一眼，不要使用「此致敬礼」「专此函达」这类过于一板一眼的收束语。
- 已清楚的原句不要为了套格式改坏。
- 已有完整、通行的说法不要随意省字（例如不可将「弄清楚」省略为「弄清」）。
- 意思、事实或条款拿不准时，先向用户确认再生成；写入飞书云文档或 Word 前须用户确认后再落笔。
- 审核时须依次说明改哪里、改成什么样、以及为什么。
- 合同与条款审核为辅助审阅，不能替代具备相应资质的法律意见。

完整规则见 [SKILL.md](SKILL.md)，批注体例见 [references/comment-style.md](references/comment-style.md)。

## License

MIT
