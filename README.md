# Pitch Skill — 必赢逻辑引擎

> 核心定位：AI影子智囊团，从"做方案"转向"造共识"。甲方买的不是创意，买的是"解决问题的确定性"。
>
> **Version 2.2.0** | SMM Level 5 (Production) | Self-Evolving

## 一句话介绍

6个专业Agent协作，把资深策略总监脑子里的「玄学感悟」拆解为可计算的赢标逻辑。支持Brief穿透与需求解构、决策者深度画像、逻辑真空区推演、第一性原理策略推导、逻辑链自检、胜率计算、决策模拟、情绪引擎优化提案表达、AIGC具象化震撼Demo、Q&A压力训练。

## 三阶段作战逻辑

```
透视 → 重构 → 表达
  |        |       |
  挖掘      构建     制造
  Brief     不可    高压迫感
  背后的    替代的    场域+
  Brief    策略     具象化震撼
```

## Agent 协作链

```
Intake Agent 📋 (项目启动/结构化)
  → Information Agent 🔍 (透视引擎 — 需求解构+决策者深度画像+竞品推演)
    → Strategy Agent 🧠 (重构引擎 — 第一性原理+逻辑链自检+策略路径)
      → Decision Agent 🎯 (决策引擎⭐核心壁垒)
        → Expression Agent 🎤 (表达引擎 — 情绪引擎+AIGC Demo+Q&A)
          → Delivery Agent 📦 (交付打包 — 6大标准交付物)
```

### 各Agent职责

| Agent | 职责 | 核心输出 |
|-------|------|---------|
| Intake 📋 | Brief结构化、隐性信号识别、质量门控 | 项目作战卡（Battle Card） |
| Information 🔍 | 需求解构(De-briefing)、决策者深度画像、竞品推演 | 真伪需求分类 + 逻辑真空区 |
| Strategy 🧠 | 第一性原理推导、逻辑链自检、策略路径 | 不可替代的策略路径 + Plan B/C |
| Decision 🎯 | 决策模式识别、胜率计算（含乘法下限）、决策模拟 | 胜率评估 + 证据链 + 优化建议 |
| Expression 🎤 | 情绪引擎、AIGC Demo、Q&A训练 | 8段式Pitch + 视觉Demo + 20题Q&A |
| Delivery 📦 | 交付打包、完整性检查、一致性校验 | 6大标准交付物 |

## 核心差异化

1. **需求解构(De-briefing)** — 穿透Brief表面，分离真痛点、伪需求、隐性需求
2. **第一性原理推导** — 从行业底层逻辑出发，否定平庸切入点
3. **逻辑链自检** — AI校验策略推导中是否有跳跃或想当然
4. **情绪引擎** — 逐段落评估情感冲击力，给出文案级优化建议
5. **AIGC具象化震撼** — 输出可直接使用的AI图像生成提示词，拉高竞争门槛
6. **胜率评估+证据链** — 区分"内容工具"和"赢标系统"的根本标志

## 执行模式

| 模式 | 触发条件 | Agent调用链 | Est. Cost |
|------|---------|------------|-----------|
| **Full** | 默认完整模式 | 全部6个Agent | ~$0.35-0.70 |
| **Preview** | 含"快速""preview""大致方案" | Intake → Information → Strategy（精简输出） | ~$0.15-0.30 |
| **Custom** | 用户指定Agent子集 | 自动补入最小依赖图 | 变化 |
| **Resume** | "从XX Agent继续" | 从指定Agent开始，复用前置输出 | 变化 |

成本估算基于 Claude Sonnet 级别模型。实际成本取决于Brief复杂度和交互轮数。

## 标准交付物

1. **Pitch Deck结构** — 内容逻辑版，每页含核心内容和演讲要点
2. **Strategy Doc** — 完整策略推导逻辑（含第一性原理+逻辑链自检报告）
3. **Q&A金句库** — 20个尖锐问题的30秒标准回答+节奏类型
4. **决策分析报告**⭐ — 决策模式 + 权力图谱 + 胜率 + 证据链 + 优化建议
5. **Win Rate评分** — 五维评分卡（含乘法下限保护）+ 优化路线图
6. **AIGC Demo提示词包**⭐ — 3-5个核心场景的AI图像生成提示词

## 文件结构

```
pitch-skill/
├── SKILL.md                          # 主文件（入口）v2.2.0 含自进化协议
├── version.json                      # SSOT版本追踪 + 进化配置 + 性能基线
├── baseline.json                     # 评估基线快照
├── .gitignore                        # 排除运行时日志
├── agents/
│   ├── __init__.md                   # Lazy-loading注册表 + 降级策略 + 摘要协议 + 成本估算
│   ├── intake-agent.md               # 项目启动引擎（含Brief质量门控）
│   ├── information-agent.md          # 透视引擎（需求解构+决策者深度画像+竞品推演）
│   ├── strategy-agent.md             # 重构引擎（第一性原理+逻辑链自检+策略路径）
│   ├── decision-agent.md             # 决策引擎⭐（决策模式+胜率计算+模拟）
│   ├── expression-agent.md           # 表达引擎（8段式Pitch+情绪引擎+AIGC Demo+Q&A）
│   └── delivery-agent.md             # 交付引擎（完整性检查+一致性校验+6大交付物）
├── references/
│   ├── decision-engine.md            # 决策引擎方法论（含乘法下限公式）
│   ├── pitch-structure.md            # Pitch结构模板 + 情绪引擎模板 + AIGC Demo模板
│   ├── strategy-frameworks.md        # 策略框架库 + 第一性原理方法论 + 逻辑链校验
│   └── bilingual-templates.md        # 中英文术语对照与英文输出模板
├── evals/
│   ├── evals.json                    # 10个测试用例（4标准+6对抗/边界）
│   └── trigger-eval.json             # 30个触发测试（20原始+10边界）
├── learnings/                        # 自进化数据层（TLSE Loop 3）
│   ├── execution-log.jsonl           # 运行时数据捕获（.gitignore排除）
│   ├── knowledge-base.json           # 领域知识库（5条种子知识）
│   ├── pattern-library.json          # 已验证模式库（3条）
│   └── creator-vnext.json            # 改进队列（1条待实施）
└── pitch-skill.skill                 # 可安装的打包文件
```

## 自进化机制 (TLSE Loop 3)

Pitch Skill v2.2.0 实现了三环技能工程（TLSE）进化周期，与 XGEO 同级架构：

```
L7 运行时捕获 → L7.5 反馈分类 → L6 模式提取 → L6.5 知识更新 → Creator vNext
      ↑                                                          |
      └──────────── L2 Creator (下一版本) ←──────────────────────┘
```

**6种进化触发器：**
| 触发器 | 条件 | 动作 |
|--------|------|------|
| `scheduled` | 每30天 | 完整进化周期 |
| `event_feedback` | 用户报告准确性问题 | 分类 → 更新KB → 安排vNext |
| `event_external` | 行业趋势变化（如新评审标准） | 标记受影响Agent → 紧急vNext |
| `performance_drop` | Eval通过率<80% | 紧急审计 → 回归修复 |
| `pattern_threshold` | 新模式 confidence>=0.7 + 3次强化 | 推广到pattern-library |
| `usage_signal` | 新Brief类型出现3次以上 | 新分类/Agent增强候选 |

**每次会话自动执行：** 启动时检查进化状态 → 加载相关KB上下文 → 执行结束后捕获运行数据。

## 触发场景

**应触发：**
- 比稿、竞标、pitch、提案竞标、agency pitch
- RFP响应、招标方案、赢标策略、竞标方案
- 选代理商、换代理商、年度比稿、创意比稿、媒介比稿
- 客户要求正式presentation给管理层评审
- "帮我做个提案""有个比稿""要去pitch""客户要方案""准备比稿材料""帮我们赢下这个客户"

**不应触发：**
- 内部营销方案、融资路演、PPT美化
- 竞品调研、品牌定位、培训汇报

## 工程质量

| 维度 | v2.0 | v2.2.0 |
|------|:----:|:------:|
| SMM Level | 2 (Workflow) | **5 (Production)** |
| Evals | 4 标准 | **10 (4标准+6对抗)** |
| Trigger Tests | 20 | **30 (20原始+10边界)** |
| Context Management | 无 | **Inter-Agent摘要协议** |
| Fallback | 无 | **6-Agent降级表** |
| Self-Evolution | 无 | **TLSE Loop 3 完整闭环** |
| Version Tracking | 无 | **version.json + baselines** |
| Cost Estimation | 无 | **Per-mode成本估算** |

## 安装

将 `pitch-skill.skill` 文件导入OpenClaw、Hermes Agent等即可使用。


## 加入群聊

<div align="center">
  <img src="https://qomob.ai/xskill.jpg" width="600" alt="XSkill">
</div>

## License

Apache-2.0
