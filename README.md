# ResumeOptimizer

求职方法论 Skill 集合。基于一次完整求职实战（2026 求职季：10 年全栈/汽车软件背景，转型 AI 工程方向，成都回流）沉淀的流程化求职技能，覆盖从收到 JD 到 offer 决策的完整闭环。

## Skill 清单

| Skill | 职责 | 触发场景 |
|-------|------|----------|
| [qiuzhi-flow](qiuzhi-flow/SKILL.md) | 求职流程编排总入口，判断阶段路由到子 skill | 开始求职、收到 JD、谈薪资 |
| [qiuzhi-company-analysis](qiuzhi-company-analysis/SKILL.md) | 企业独立分析（五维评分+结论先行），输出 公司分析/{企业}分析.md | 这家公司怎么样、分析这个 JD |
| [qiuzhi-resume](qiuzhi-resume/SKILL.md) | 简历编写（AI 实践优先+素材追问+md/html/pdf 三格式产出） | 写简历、改简历 |
| [qiuzhi-interview-prep](qiuzhi-interview-prep/SKILL.md) | 面试准备（岗位理解+预判问答+分轮应对+主线速记） | 这个岗位怎么面试、准备面试清单 |
| [qiuzhi-interview-review](qiuzhi-interview-review/SKILL.md) | 面试复盘（概率评估+情报回流+自我误判修正） | 刚面完复盘、这轮怎么样 |
| [qiuzhi-offer-compare](qiuzhi-offer-compare/SKILL.md) | 多 Offer 对比（福利折算+放弃铁律+长期路径） | 几个 offer 怎么选、要不要放弃 |
| [qiuzhi-negotiation](qiuzhi-negotiation/SKILL.md) | 薪资谈判（价值锚定+福利折算话术+退路条款） | 一会儿谈薪资、薪资怎么谈 |

## 使用方式

1. **入口**：以 qiuzhi-flow 为总入口，它根据用户所处阶段路由到对应子 skill
2. **安装**：将所需 skill 目录复制到目标项目的 `.trae/skills/` 下（如 `<项目>/.trae/skills/qiuzhi-flow/`）
3. **依赖**：子 skill 相互独立可单独复用；候选人硬约束（目标城市、排除外包、措辞谦逊）在 qiuzhi-flow 中统一定义

## 方法论核心

- **流程闭环**：企业独立分析 → 简历编写 → 面试准备 → 面试执行复盘 → 多 Offer 对比 → 薪资谈判
- **结论先行**：每份文档开头一句话给结论，再展开论证
- **确定性 > 想象**：已落袋的 offer 是底盘，未到手的按"有戏但不是救命稻草"对待
- **放弃铁律**：放弃已落袋的稳定 offer，对方必须同时满足"薪资不输 + 稳定性不差 + 价值明显更高"，三条缺一不换
- **第一决策标准**：岗位 5-10 年后能否让人持续处在"定义问题"的位置，而非仅作为执行指令的纯程序员
