# TCM-health v1.0.0 — 版本快照

> 基于内调日志智能体框架，经过 SKILL.md 框架重构后的完整版本。
> 快照日期：2026-07-18
> 状态：✅ 全部核心框架完成

---

## 一、版本进展总览

| 模块 | 状态 | 文件 |
|------|------|------|
| SKILL.md 入口 | ✅ | `SKILL.md` |
| 概述（动态回路） | ✅ | `SKILL.md` §概述 |
| 核心规则（8条） | ✅ | `SKILL.md` §核心规则 |
| 工作流程（3阶段+渐进采集） | ✅ | `SKILL.md` §工作流程 |
| 常见陷阱（10条） | ✅ | `SKILL.md` §常见陷阱 |
| 示例（一日完整场景） | ✅ | `SKILL.md` §示例 |
| 参考资源索引 | ✅ | `SKILL.md` §参考资源 |
| 首次接入问卷 | ✅ | `templates/onboarding-questionnaire.md` |
| USER.md 身体说明书 | ✅ | `templates/USER.md` |
| 存疑清单模板 | ✅ | `templates/dispute-log.md` |
| 日报展示框架 | ✅ | `references/daily-report-framework.md` |
| 周报展示框架 | ✅ | `references/weekly-report-framework.md` |
| 月报展示框架 | ✅ | `references/monthly-report-framework.md` |
| 年报展示框架 | ✅ | `references/yearly-report-framework.md` |
| SOUL.md 灵魂说明书 | ✅ | `SOUL.md` |
| HEARTBEAT.md 心跳节律 | ✅ | `HEARTBEAT.md` |
| 优化手稿（11章） | ✅ | `OPTIMIZATION-JOURNAL.md` |

---

## 二、核心规则列表（8条）

| 规则 | 核心要点 |
|------|----------|
| 🔴 规则1：三锚定餐分析 | 身体成分+舌苔+排便，三锚缺一不可。严禁只做性味不做营养或反之 |
| 🔴 规则2：图片识别强制路由 | 视觉模型识别→类型确认回执→用户纠错窗口。不准跳过、不准猜 |
| 🔴 规则3：时间自动确认 | session_status 确认日期→生成文件第一行显式打印日期。严禁猜日期 |
| 🔴 规则4：信息自动归档 | 10类数据各有归档路径。分析完不写文件视为未完成 |
| 🔴 规则5：感知引导提问 | 4节点必问（舌象/饭后/排便/睡醒）。目的是让用户学会自己回答 |
| 🔴 规则6：风险模式匹配 | 回溯历史相似模式→主动提醒。不翻旧账、不吓人、不替用户决定 |
| 🔴 规则7：决策权归用户 | 所有建议以「你看行不行」收尾。分析在我，选择在你 |
| 🔴 规则8：存疑机制 | 健康问题严禁绝对化词汇。客户质疑→不争辩→记录存疑→管理员介入 |

---

## 三、配套文件清单

### templates/
| 文件 | 用途 |
|------|------|
| `onboarding-questionnaire.md` | 6模块首次接入问卷，先种意识再收数据 |
| `USER.md` | 8模块身体使用说明书（身份/体成分/体质/健康史/生活方式/目标/三锚基线/采集追踪） |
| `dispute-log.md` | 存疑清单模板，客户质疑时记录 |

### references/
| 文件 | 用途 |
|------|------|
| `daily-report-framework.md` | 日报10板块框架，含排便/睡眠渐进式采集策略 |
| `weekly-report-framework.md` | 周报8板块框架 |
| `monthly-report-framework.md` | 月报9板块框架，含季节调理 |
| `yearly-report-framework.md` | 年报8板块框架，含体质演变/四季回顾 |

### 核心配置
| 文件 | 用途 |
|------|------|
| `SOUL.md` | 语气基调/信念/说什么话/不说什么话/沟通节奏 |
| `HEARTBEAT.md` | 日/周/月/年主动触发节点+风险/存疑/沉默保护 |

---

## 四、与原始模板的对应关系

| 原始模板章节 | v1.0.0 落位 |
|-------------|-------------|
| 一、智能体总览 | `SKILL.md` frontmatter + 概述 |
| 二、核心工作流 | `SKILL.md` §工作流程 |
| 三、强制规则 | `SKILL.md` §核心规则（优化为8条） |
| 四、每日工作节奏 | `HEARTBEAT.md` + `SKILL.md` §工作流程-阶段二 |
| 五、图片处理流程 | `SKILL.md` §规则2（含类型确认回执） |
| 六、饮食分析模板 | `references/daily-report-framework.md` §三餐分析 |
| 七、文件夹结构 | `SKILL.md` §规则4 归档路径 |
| 八、SOUL.md | `SOUL.md` |
| 十、USER.md | `templates/USER.md` |
| 十一、MEMORY.md 规则 | 已融入 `SKILL.md` §核心规则 |
| 十三、体质信号追踪 | `references/daily-report-framework.md` + `weekly-report-framework.md` |
| 十四、模板文件清单 | `templates/` + `references/` |

---

> 🌿 TCM-health v1.0.0 — 同一具身体，中医性味 + 现代营养，两个维度，一个动态回路。
