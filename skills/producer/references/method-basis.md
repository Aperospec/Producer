# 方法来源与适用范围

在需要解释方法依据、选择操作或审查迁移边界时阅读。以下是一手实践指导的有限综合，不能据此声称本技能已获得跨领域的效果验证。工作方法见各操作参考；这里不收录项目案例、原始研究或测试记录。

| 一手依据 | 支持的操作 | 迁移边界 |
|---|---|---|
| NASA, *Systems Engineering Handbook*, NASA/SP-2016-6105 Rev 2：[§4.1](https://www.nasa.gov/reference/4-1-stakeholder-expectations-definition/)、[§4.2](https://www.nasa.gov/reference/4-2-technical-requirements-definition/)、[§6.2](https://www.nasa.gov/reference/6-2-requirements-management/) | 从使用情境区分需要与实现；保存要求的理由，双向查找遗漏和无依据增项 | 工程指南；仅对重要或易漏要求保留必要连接，不引入全量量化、正式基线审查或层级签字 |
| 同手册 [§6.5](https://www.nasa.gov/reference/6-5-configuration-management/)、[§6.8](https://www.nasa.gov/reference/6-8-decision-analysis/) | 区分变更决定、落实与检查；先检查硬条件，再比较偏好与可能改变选择的未知 | 不固定配置委员会、评分工具或价值权重；局部已定修改直接处理 |
| Michael Nygard, [Documenting Architecture Decisions](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions)，2011-11-15 | 重要决定保留情境、理由、后果与替代关系 | 源于软件架构经验；不为例行小修建立独立决策文档，不迁移目录或编号惯例 |
| GDS, [Learning about users and their needs](https://www.gov.uk/service-manual/user-research/start-by-learning-user-needs)，2017-03-23 更新；[Writing user stories](https://www.gov.uk/service-manual/agile-delivery/writing-user-stories)，2016-05-23 更新 | 从使用问题建立条件，分开假设与证据，用可观察结果检查兑现 | 源于政务服务；不强制用户故事句式、项目阶段、角色或每次都做受众研究 |
| Ryan Singer, *Shape Up*：[Map the Scopes](https://basecamp.com/shapeup/3.3-chapter-12)、[Show Progress](https://basecamp.com/shapeup/3.4-chapter-13) | 按可完成成果和真实依赖拆分；区分未知与已知待执行项 | 作者实践方法；不迁移固定周期、山形图、角色，不能自行把必交项降为可选 |
| AHRQ TeamSTEPPS, [Tool: Handoff](https://www.ahrq.gov/teamstepps-program/curriculum/communication/tools/handoff.html)，2023-05 | 责任交接需有接收者理解并接手的实际证据 | 医疗教学方法；只在真实转交时使用，不产生新权限或固定用户批准手续 |
| [The Kanban Guide](https://kanbanguides.org/the-kanban-guide/)，v2025.5 | 依据实际容量安排在制工作，处理阻塞并保留未完义务 | 只取局部工作流原则，不宣称完整实施 Kanban，不预设在制量、周期或预测值 |
| Google, *SRE Workbook*, [Postmortem Culture: Learning from Failure](https://sre.google/workbook/postmortem-culture/)，2018 | 从具体偏差形成改进，跟踪可验证终态，复发时核对措施是否实施及是否有效 | 经验与案例；不把小修当事故，不引入事故等级、复盘会议或默认公开制度 |

这些方法分别解决要求、决定、依赖、交接和学习问题，不组成必经顺序。Producer 的文件约定、授权判断和组合方式是本技能的有限综合，相关来源没有为其整体背书。遇到新情境须重新检查方法与问题是否匹配。
