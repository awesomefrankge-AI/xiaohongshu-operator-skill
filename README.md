# xiaohongshu-operator

小红书账号运营 skill —— 从定位、选题、爆款、互动运营到变现的完整方法论，给 Claude Code / Claude Desktop 用。

## 安装

```bash
# Claude Code（用户级）
git clone https://github.com/awesomefrankge-AI/xiaohongshu-operator-skill.git ~/.claude/skills/xiaohongshu-operator

# 或项目级
git clone https://github.com/awesomefrankge-AI/xiaohongshu-operator-skill.git .claude/skills/xiaohongshu-operator
```

安装后直接问：「帮我给 xx 账号做个定位」「这条笔记数据不好，帮我诊断」「给我 10 个选题」。

## 结构

```
SKILL.md                      入口：判断用户在哪一步，只读对应的 reference
references/
  01-positioning.md           账号定位：商业模式 / 赛道 / 内容 / 人设 / 差异化
  02-content.md               六种选题法、封面四逻辑、标题六公式
  03-viral.md                 推荐机制七数据、痛痒爽点、爆款因子、涨粉公式
  04-operations.md            互动技巧、发布前后自检清单、单篇与账号复盘
  05-monetization.md          广告报价公式、知识变现、带货、影响力变现
  06-mindset.md               拆解力/系统力/内驱力、四个思维、日常工作流
  07-platform-rules.md        红线、合规引流、发布时间、限流自查
```

## 三个核心公式

```
涨粉数 = 阅读量 × 转粉率
转粉率 = 内容优质 + 人设鲜明
广告报价 = 粉丝数 × 10%
```

**质量判断**：阅读:点赞 = 10:1 基本能成爆款 / 30:1 是普通笔记。
**发布纪律**：爆款因子少于 3 个不发。

## License

MIT
