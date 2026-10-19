# 全球对标与 Skill 扫描

扫描日期：2026-10-19。在线项目可能继续变化；正式发布前重新核对维护状态、许可证、版本、内容和来源。

## 可借鉴项目

| 项目/来源 | 观察到的设计 | 可迁移点 | 限制 |
|---|---|---|---|
| [SkillMedev lesson-plan-builder](https://github.com/SkillMedev/skills/blob/main/skills/lesson-plan-builder/SKILL.md) | 单课；先目标、再退出任务、再课堂活动；时间弧、形成性检查和差异化；目标与退出题一致 | 采用目标—证据—活动顺序；明确继续/重教决策；写清讲师与学员动作 | 聚焦单课，不是完整课程系统；单个 GitHub skill 不能证明实际教学效果 |
| [Gareth Manning education-agent-skills](https://github.com/GarethManning/education-agent-skills) | 按教学决策拆成可组合 skills，含学习科学、形成性评价、课程设计与教学活动 | 把备课任务拆成可复用工具；每个工具输入/产物清晰；按需要组合 | 仓库规模和作者自述需独立核验；质量与效果要逐项审查 |
| [Backwards Design Unit Planner](https://github.com/garethmanning/education-agent-skills/blob/main/skills/curriculum-assessment/backwards-design-unit-planner/SKILL.md) | 目标、评价证据、学习计划三阶段，显式检查对齐和迁移 | 用追踪矩阵查漏项、反向检查考试是否教过 | 框架不能替代学科标准、试教与测量 |
| [Hermes teacher-lesson-planning](https://github.com/hezkvectory/hermes-edu-skills/blob/main/skills/teacher-tools/teacher-lesson-planning/SKILL.md) | 采集年级、教材、学情、时长等输入；生成适配教案 | 需求字段和情境化输入；将用户没有提供的内容标记假设 | 面向其平台流程的技能，调用接口未必适用于其他 Agent |
| [SkillHub 360 教案设计器](https://skillhub.360.com/skills/qizhitang/xiaozhi-teach-lesson-planner) | UbD 逆向设计、六步时间矩阵、Bloom 提问链和分层任务；页面展示版本、更新日期、依赖及适用年段 | 中文教师工作流、学情缺失时诚实降级、按职能边界拆分能力、教师审定与隐私提醒 | 页面公开信息可供结构对标，不是独立课堂效果评估；面向 K–12 且依赖平台能力，不能直接代替跨年龄课程设计 |

## SkillHub 搜索结论

“SkillHub”对应多个不同服务。本次可直接检查到 SkillHub 360 的教案设计器详情和版本信息；SkillHub.cn 的教案图像页本次打开失败，因此不把其内容当作已核实对标。目录收录或页面热度不能证明“全球最佳”或课堂效果；正式采用前仍须审查正文、作者、更新时间、许可与调用要求。

## 对标结论

本 skill 吸收的通用做法：单课可运行性、先定证据再选活动、课程学习进阶、输出模块化、形成性判断规则、学情输入和来源标注。新增的组合价值是把知识库、课程分级、公开课、转化测量、多模态教学物料、口笔试、激励和迭代纳入同一条可追溯流程。

不直接复制其他 skill 的文字、模板细节或受限内容；只抽象设计机制。仓库 star/fork、SkillHub 上架状态不能当作学生学习成效。
