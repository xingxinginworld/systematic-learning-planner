# 系统性学习规划 · Systematic Learning Planner

> 把"想学某样东西"变成一条**可在周期内执行、能从入门走到精通**的系统化路线。
> 全流程采用「先思考规划、用户确认后执行」的里程碑节奏——你只在关键节点拍板，其余交给 AI 推进。

[![license](https://img.shields.io/badge/license-CC%20BY--NC%204.0-blue.svg)](NOTICE.md)
[![author](https://img.shields.io/badge/author-xingxinginworld-brightgreen.svg)](919092099@qq.com)

## 这是什么

一个 WorkBuddy 技能（Skill），帮助任何人在设定周期内系统性地学习任意主题——从 FDE / AI / 编程，到外语 / 考研考证 / 商业分析。它把"学习"做成一条可执行的流水线：

需求澄清 → 摸底测试 → 水平评估 → 路径规划 → 执行拆解(周/日+里程碑) → 每日内容 → 总复习 → 复测闭环。

## 核心能力

- 🧭 **需求澄清**：结构化提问 + 回答模板，一次摸清主题 / 水平 / 目标 / 时间 / 粒度 / 侧重。
- 📝 **摸底测试**：纯选择题 HTML 试卷，一键收集答案、一键复制，便于回收与推送。
- 📊 **水平评估**：产出《摸底评估报告》，判定零基础 / 初级 / 中级 / 高级，定位优先短板。
- 🗺️ **路径规划**：认知逻辑自洽的章节目录 + 学时分配（HTML 呈现）。
- 📅 **执行拆解**：把路径拆成 week / day 计划 + 里程碑，附弹性缓冲，杜绝"中断即失败"。
- 📖 **每日内容**：每节产出 6 板块交互式 HTML（目标 / 讲解 / 动手 / 速查 / 测验 / 金句），动手形式按内容类型适配。
- 🔁 **总复习 + 复测**：知识地图 + 综合测验 + 速查索引 + 进阶建议，闭环验证效果。

## 安装

```bash
# 方式一：从 Release 下载 zip，解压到技能目录
#   macOS / Linux: ~/.workbuddy/skills/
#   Windows:       C:\Users\<你>\.workbuddy\skills\
# 解压后目录名应为 systematic-learning-planner

# 方式二：git 克隆
git clone https://github.com/xingxinginworld/systematic-learning-planner.git \
  ~/.workbuddy/skills/systematic-learning-planner
```

安装后在 WorkBuddy 对话中说"帮我系统学习 XXX"即可触发。

## 目录结构

```
systematic-learning-planner/
├── SKILL.md                      # 技能定义 + 8 步工作流编排
├── NOTICE.md                     # 版权与署名声明
└── references/
    ├── example_fde.md            # 以 FDE 学习跑通全技能的贯穿示例
    ├── example_fde/              # FDE 结构样板（00-总览 / week-01 / 周模板 / 日模板）
    ├── prompts/                  # 001–008 八步提示词模板
    └── templates/                # quiz_template / fde_diagnostic_radar / day_content_template
```

## 许可证与署名

- **第一作者**：`xingxinginworld`
- **联系**：919092099@qq.com（QQ 邮箱）
- **许可证**：`CC BY-NC 4.0`（署名—非商业性使用—禁止演绎）。个人 / 非商业用途可免费复制、分发、修改（须保留署名）；商业用途或付费版本须事先获得作者授权。
- 完整声明见 [`NOTICE.md`](NOTICE.md)。
