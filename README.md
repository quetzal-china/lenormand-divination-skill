# 🔮 Lenormand Oracle · 雷诺曼神谕

> 为 AI 助手注入神秘力量 · Empower your AI with mystical divination skills

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![OpenCode Skills](https://img.shields.io/badge/OpenCode-Skills-blue)](https://opencode.ai/docs/skills/)

---

## ✨ 这是什么？

这是一个专为 **OpenCode AI 助手** 设计的 **雷诺曼十字牌阵占卜技能**。让你的 AI 不再只是冷冰冰的代码机器，而是能成为一位神秘的占卜师，为用户提供情感、学业、决策的全景式指引。

借助 **qwen3.5-plus AI**, 创作skill.

**仅供学习参考!**

> 🎴 **十字牌阵 (The Cross Spread)** 是雷诺曼系统中最经典的 5 张牌阵，揭示时间线（过去 - 现在 - 未来）与行动策略（助力 - 挑战）的双重维度。

---

## 🚀 快速开始

### 安装

```bash
# 克隆到你的 OpenCode 项目
git clone https://github.com/quetzal-china/lenormand-divination-skill.git

# 复制 skill 到你的 OpenCode 配置目录
cp -r lenormand-divination-skill/.opencode/skills/lenormand-cross-spread ~/.config/opencode/skills/

# 或者项目级安装
cp -r lenormand-divination-skill/.opencode/skills/lenormand-cross-spread .opencode/skills/
```

### 使用

启动 OpenCode 后直接提问：

```
帮我用雷诺曼十字牌阵占卜一下我的学业运势
```

或

```
我想问问和 TA 的关系发展，请用十字牌阵
```

---

## 📋 示例输出

一次完整的占卜包含：

| 位置 | 含义 |
|------|------|
| 🃏 **中心** | 问题的核心本质 |
| 🃏 **左侧** | 过去的影响/背景 |
| 🃏 **右侧** | 未来的趋势/发展 |
| 🃏 **上方** | 有意识的助力/资源 |
| 🃏 **下方** | 潜意识的阻碍/挑战 |

**完整解读维度：**
- ⏳ 时间流分析（过去 → 核心 → 未来）
- 🎯 行动流分析（助力 vs 挑战）
- 🔍 镜像洞察（深层联系）
- 💡 综合结论与行动建议

---

## 🎯 适用场景

- 💕 **情感咨询**: 关系发展、复合可能、暗恋走向
- 📚 **学业指导**: 考试运势、专业选择、学习状态
- 💼 **决策辅助**: 职业选择、项目方向、投资建议
- 🔮 **日常指引**: 周运势、月运势、特定问题

---

## 🛠️ 技术细节

### 文件结构

```
.opencode/skills/lenormand-cross-spread/
└── SKILL.md          # Skill 定义文件（符合 OpenCode 规范）
```

### Frontmatter

```yaml
---
name: lenormand-cross-spread
description: 执行专业的雷诺曼十字牌阵（5 张牌）占卜
license: MIT
compatibility: opencode
metadata:
  category: divination
  spread_type: cross
  card_count: 5
---
```

### 核心特性

- ✅ **真随机抽牌**: 基于时间戳模拟洗牌切牌
- ✅ **36 张标准牌**: 完整雷诺曼牌义库
- ✅ **十字牌阵**: 经典 5 位置结构
- ✅ **组合解读**: 横轴 + 纵轴 + 镜像三维度
- ✅ **客观中立**: 不回避负面牌义

---

## 📜 许可证

MIT License - 自由使用、修改、分发

---

## 🙏 致谢

- [OpenCode](https://opencode.ai/) - 强大的 AI 助手框架
- [Lenormand Tradition](https://lenormant.org/) - 传统雷诺曼占卜系统

---

## 🌟 名字由来

**Lenormand Oracle** 致敬 18 世纪传奇占卜师 **Marie Anne Lenormand**，她曾是拿破仑和约瑟芬皇后的御用占卜师。

> "命运之轮转动，钥匙已在手中" 🔑

---

<div align="center">

**Made with 🔮 and ✨ for the curious minds**

[Report Bug](https://github.com/quetzal-china/lenormand-divination-skill/issues) · [Request Feature](https://github.com/quetzal-china/lenormand-divination-skill/issues)

</div>
