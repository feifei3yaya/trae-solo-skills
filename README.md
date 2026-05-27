# 智能生活助手技能集

> 🏆 11个解决真实生活场景的AI技能，让生活更简单

## 📖 项目介绍

这是一个包含11个实用AI技能的集合，每个技能都针对日常生活中的真实痛点设计。从宝宝辅食到合同审查，从情绪管理到旅行规划，覆盖生活的方方面面。

所有技能均可在AI助手平台中安装使用，无需编程基础，开箱即用。

---

## 📋 技能清单

### 👶 育儿生活
| 技能名称 | 文件 | 功能描述 |
|---------|------|---------|
| **宝宝辅食营养师** | `baby-food-nutritionist.skill` | 为6个月-3岁宝宝生成一周科学辅食计划，自动规避过敏原 |

### 🏠 居家生活
| 技能名称 | 文件 | 功能描述 |
|---------|------|---------|
| **租房避坑指南** | `rent-trap-guide.skill` | 租房全流程避坑，从找房到签约全覆盖 |
| **合同风险扫描器** | `contract-risk-scanner.skill` | 自动识别合同中的潜在风险条款，给出修改建议 |

### 💼 职场效率
| 技能名称 | 文件 | 功能描述 |
|---------|------|---------|
| **面试模拟教练** | `interview-coach.skill` | 模拟真实面试场景，提供个性化反馈和改进建议 |
| **AI去AI味改写器** | `de-ai-rewriter.skill` | 让AI生成的文字更像人写的，去除机械感 |
| **帖子质量检测器** | `post-quality-checker.skill` | 检测社区帖子质量，提供优化建议 |

### 🧠 内容创作
| 技能名称 | 文件 | 功能描述 |
|---------|------|---------|
| **小红书违规词检测器** | `xiaohongshu-content-checker.skill` | 检测文案中的违规敏感词，避免限流封号 |
| **旅行预算精算师** | `travel-budget-planner.skill` | 输入目的地和天数，生成详细预算表和省钱攻略 |

### 💡 创意灵感
| 技能名称 | 文件 | 功能描述 |
|---------|------|---------|
| **情绪急救箱** | `emotion-first-aid.skill` | 情绪崩溃时的即时心理支持工具 |
| **Skill创意灵感生成器** | `skill-idea-generator.skill` | 输入职业和兴趣，推荐最适合的创意方向 |
| **比赛监控助手** | `competition-monitor.skill` | 监控技能创作赛动态，分析竞争态势 |

---

## 🚀 快速开始

### 安装技能

1. **下载技能文件**
   - 点击上方列表中的 `.skill` 文件
   - 点击 "Download" 按钮下载

2. **在AI助手中安装**
   - 打开你的AI助手客户端
   - 进入「技能」或「插件」面板
   - 点击「上传技能」或「安装技能」
   - 选择下载的 `.skill` 文件
   - 安装完成后即可使用

### 使用示例

**宝宝辅食营养师使用示例：**
```
用户：我家宝宝8个月了，对鸡蛋过敏
AI：为您生成8个月宝宝的一周辅食计划（已排除鸡蛋）...
```

**合同风险扫描器使用示例：**
```
用户：[粘贴租房合同文本]
AI：发现3处风险条款：1.押金退还条件模糊 2.违约责任不对等...
```

---

## 📁 文件说明

```
.
├── README.md                          # 本文件
├── baby-food-nutritionist.skill       # 宝宝辅食营养师
├── baby-food-nutritionist/
│   └── SKILL.md                       # 技能源码（YAML+Markdown）
├── contract-risk-scanner.skill        # 合同风险扫描器
├── contract-risk-scanner/
│   └── SKILL.md
├── emotion-first-aid.skill            # 情绪急救箱
├── emotion-first-aid/
│   └── SKILL.md
├── interview-coach.skill              # 面试模拟教练
├── interview-coach/
│   └── SKILL.md
├── post-quality-checker.skill         # 帖子质量检测器
├── post-quality-checker/
│   └── SKILL.md
├── rent-trap-guide.skill              # 租房避坑指南
├── rent-trap-guide/
│   └── SKILL.md
├── skill-idea-generator.skill         # Skill创意灵感生成器
├── skill-idea-generator/
│   └── SKILL.md
├── travel-budget-planner.skill        # 旅行预算精算师
├── travel-budget-planner/
│   └── SKILL.md
├── xiaohongshu-content-checker.skill  # 小红书违规词检测器
├── xiaohongshu-content-checker/
│   └── SKILL.md
├── de-ai-rewriter.skill               # AI去AI味改写器
├── de-ai-rewriter/
│   └── SKILL.md
├── competition-monitor.skill          # 比赛监控助手
└── competition-monitor/
    └── SKILL.md
```

---

## 🎯 设计原则

每个技能都遵循以下设计原则：

1. **解决真实问题** - 不是空想，而是来自真实生活场景
2. **简单易用** - 无需学习成本，打开即用
3. **安全可靠** - 内置安全机制，避免错误建议
4. **持续优化** - 根据用户反馈不断改进

---

## 🤝 参与贡献

欢迎提出建议或贡献新的技能创意！

**提交方式：**
- 在Issues中提交功能建议
- Fork本仓库，提交Pull Request
- 分享你的使用体验和改进建议

---

## 📄 开源协议

MIT License - 自由使用、修改和分享

---

> 💡 **提示**：这些技能都是基于真实生活场景设计的，希望能帮助你提升效率、解决问题！
