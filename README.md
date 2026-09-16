# 🔥 ASU FORGE · 阿酥式简历锻造炉

**把真实经历，锻造成作品级履历。只放大，不虚构。**

蒸馏阿酥（LofiSu）公开简历的高密度叙事方法，融合「同一份事实 → AI 产品经理 / Agent 全栈 / 中台架构师 / FDE 四份岗位简历」的锻造实战。每一句强表述，都能守住面试官 **15 分钟连续追问**。

> 仓库内的示例均为**虚构数据**，不对应任何真实个人——保护候选人隐私本身就是本 Skill 的红线之一。

🌐 **官网**：https://zhiqingheyi.github.io/asu-resume-forge/

---

## 它解决什么问题

普通技术简历是任务流水账：

```
负责开发、参与联调、修复问题、配合上线。
```

锻造后的每段经历回答六个问题：

```
为什么做 → 你负责哪一段 → 难点是什么 → 如何设计 → 结果如何 → 怎么证明
```

并输出固定三段式：**背景与目标 → 指标与效果 → 我的职责（含 ↳ 技术链路行）**。

## 锻造流水线（F1 → F7）

```
原始材料 → F1 事实账本 → F2 六问重构 → F3 岗位透镜 → F4 链路行铸造
        → F5 指标口径校验★ → F6 抓手埋点 → F7 红线门禁★ → 成稿交付
                          └ 两道门禁不过 = 不算成稿
```

| 工序 | 做什么 |
|---|---|
| F1 事实账本 | 只登记事实不登记修辞，无法确认的信息进待确认清单 |
| F2 六问重构 | 流水账 → 背景/指标/职责三段式 + 难点→解法→收益因果链 |
| F3 岗位透镜 ★独创 | 同一份事实，按 PM / 全栈 / 架构 / FDE 切换叙事重心 |
| F4 链路行铸造 ★独创 | `↳ 技术链路：A → B → C`，每环可讲 3 分钟 |
| F5 指标口径校验 ★门禁 | 重算 · 自洽 · 可归因（示例：抓出"提效 8 倍 + 成本 1/10"双硬伤） |
| F6 抓手埋点 | 埋入面试官可追问、你正好能答的技术锚点 |
| F7 红线门禁 ★门禁 | 16 类夸大模式逐条过，越级与虚构零容忍 |

## 与同类项目的差异

| 能力 | ASu-resume-skills (306★) | sushen | sharpen-technical-resume | **ASU FORGE** |
|---|---|---|---|---|
| 证据审计 / 原子主张 | ✓ | ✓ | ✓ | ✓ 吸收 |
| 平台无关使用 | Codex 插件 | ✓ | ✓ | ✓ 标准 SKILL.md |
| 包装强度控制 | — | — | ✓ 三档 | ✓ 追问测试 |
| **岗位透镜（4 岗位）** | — | — | — | ★ 独创 |
| **链路行格式** | — | — | — | ★ 独创 |
| **指标口径校验公式卡** | 部分 | 部分 | 部分 | ★ 独立门禁 |
| **多岗位对照示例** | — | — | 1 例 | ★ 4 岗位透镜对照 |

致谢三位先行者的开源工作：[ASu-resume-skills](https://github.com/Claycui828/ASu-resume-skills)、[sushen](https://github.com/junlin-233/sushen)、[sharpen-technical-resume](https://github.com/susie-jpg/sharpen-technical-resume)。

## 快速开始

```bash
git clone https://github.com/ZhiqingHeyi/asu-resume-forge.git

# Claude Code
cp -r asu-resume-forge/skills/asu-resume-forge ~/.claude/skills/

# WorkBuddy
cp -r asu-resume-forge/skills/asu-resume-forge ~/.workbuddy/skills/
```

然后在 AI 对话里说：

```
用 asu-resume-forge 锻造我的简历，目标岗位：AI Agent 工程师，模式 Forge。
```

也可以直接阅读 `skills/asu-resume-forge/SKILL.md` 当方法论手册使用——不装也能学。

## 工作模式

- `Forge`（默认）：完整 F1→F7，围绕目标岗位重建简历
- `Polish`：保留原结构，只做措辞、密度与口径修复
- `Audit`：只诊断不改写（口径矛盾 / 角色越级 / 缺指标 / 追问风险）
- `Interviewer`：扮演面试官做 15 分钟追问模拟

## 仓库结构

```
asu-resume-forge/
├── skills/asu-resume-forge/
│   ├── SKILL.md                      # 主流程：F1-F7 流水线 + 硬约束
│   └── references/
│       ├── methods.md                # 阿酥六层技法 × 六问重构 × 角色四级
│       ├── job-lenses.md             # ★ 岗位透镜：PM/全栈/架构/FDE
│       ├── metric-check.md           # ★ 指标口径校验公式卡
│       ├── phrasebook.md             # 句式库
│       ├── inflation-patterns.md     # 16 类夸大模式红线
│       └── fact-ledger.md            # 事实账本模板
├── examples/
│   └── before-after-worked-example.md  # 锻造示例（虚构数据，含 F2-F7 五例对照）
├── docs/
│   └── index.html                    # 官网（GitHub Pages）
├── LICENSE                           # MIT
└── README.md
```

## 红线

- 不虚构经历、数字、头衔；角色词不得越级（参与 ≠ 负责 ≠ 主导 ≠ Owner）
- "0→1" 必须说明"0"指什么；极值词必须有可验证的限定范围
- 规划中的方向不得写成已上线收益
- 作品列表与项目经历必须互相印证

## 事实边界声明

本项目是对公开写作模式的分析与抽象，与阿酥（LofiSu）本人无关，不代表其参与、授权或背书，也不复制其简历正文。方法的价值在于**让真实贡献获得更好的表达**，任何使用者不得用它虚构事实。

## License

[MIT](LICENSE) © ZhiqingHeyi
