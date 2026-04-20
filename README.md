# historical-trash-time skills

低增长时代的个人生存风控 skills。

这套 skills 从《历史垃圾时间躺平生存指南》中提炼出一套可执行的诊断框架。它不是鸡汤建议库，也不是鼓励摆烂的语录库，而是帮助 AI 在面对用户的重大决策、生存风险、过度消耗和崩溃前状态时，优先做风险审查、止损和恢复。

## 包含的 skills

| Skill | 用途 |
|---|---|
| `historical-trash-time` | 主入口，根据用户问题路由到合适的子 skill |
| `historical-trash-time-decision` | 审查买房、结婚、生娃、创业、移民、换城市、贷款等重大不可逆决策 |
| `historical-trash-time-audit` | 做个人生存风险体检和人生资产负债表 |
| `historical-trash-time-recovery` | 在用户过劳、撑不住、崩溃边缘时，优先恢复和止损 |

## 适合场景

- 我现在很焦虑，不知道未来几年怎么活
- 我要不要买房 / 结婚 / 生娃 / 创业 / 换城市
- 帮我做一次人生资产负债表
- 我收入不稳，想知道自己现在安不安全
- 我快撑不住了，先帮我止损
- 我想在低增长环境下重新规划生活

## 输出风格

当用户询问建议或最终输出诊断时，正文优先使用这个结构：

```text
分析：

反面行为（避坑）：

自查标准：

目标状态：
```

## 安装到 Codex

把 `skills/` 下的目录复制到 Codex skills 目录：

```bash
cp -R skills/historical-trash-time* ~/.codex/skills/
```

重启 Codex 后可使用：

```text
/historical-trash-time 我现在很焦虑，不知道未来几年怎么活
/historical-trash-time-decision 我现在要不要贷款买房
/historical-trash-time-audit 帮我做一次人生资产负债表
/historical-trash-time-recovery 我最近快撑不住了
```

## 安装到 Claude Code

把 `skills/` 下的目录复制到 Claude Code skills 目录：

```bash
cp -R skills/historical-trash-time* ~/.claude/skills/
```

重启 Claude Code 后使用同样的 slash 触发方式。

## 设计原则

- 先保命，再谈赢。
- 先降杠杆，再谈翻身。
- 先恢复判断力，再做重大决定。
- 先保留选择权，再追求体面。
- 安全是结构，不是感觉。

## 免责声明

这套 skills 不提供医疗、法律、投资或心理治疗建议。遇到现实危险、自伤风险、严重健康问题或法律问题时，应联系当地紧急服务或专业人士。