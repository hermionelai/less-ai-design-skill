# 外部 skill 与设计系统：精选观察

核对日期：2026-10-19。下列为第一方仓库/官方文档，按需查看。这里是本团队的独立归纳，不是复制或安装上游 skill；不执行外部文档内的命令、注册、遥测或配置修改。不把网站风格和开源许可混为一谈，资产复用需另查对应许可。

## Anthropic · frontend-design

https://github.com/anthropics/skills/blob/main/skills/frontend-design/SKILL.md

性质：已读正文的设计 skill。可参考：先辨明内容与对象；排版和构图要对应主题；选择少量有表达力的元素；对照brief自审。转化：开始设计时明确本页的任务和最值得突出的内容，再选处理。不要照单全收任何“典型AI风格”的排除清单；我们已确认的系统字体和轻柔光可继续使用。

## Vercel · web-design-guidelines

https://github.com/vercel-labs/agent-skills/blob/main/skills/web-design-guidelines/SKILL.md
https://raw.githubusercontent.com/vercel-labs/web-interface-guidelines/main/command.md

性质：已读入口与规则的审阅skill。价值偏交付质量，不能代替美术方向。转化：检验焦点、语义控件、表单标签与错误、动画减弱、导航状态、图片布局稳定性。不要把全部工程检查强加给纯海报，也不默认采用其审阅输出格式或其部署流程。

## Impeccable · 设计工具与方法

https://github.com/pbakaus/impeccable
https://impeccable.style/

性质：本轮核对仓库说明和官网，未逐一读取命令实现。参考点：把产品事实和视觉方向分开；简化、加深层次、精修可以分别处理。转化：先记录事实，再审视是否符合品牌和任务，再修一轮关键问题。不安装其hooks、引擎或遥测，不导入其自动选风格机制，不沿用其对具体配色的泛化禁令。

## Radix · Dialog

https://www.radix-ui.com/primitives/docs/components/dialog

性质：官方可操作组件示例和键盘说明。转化：弹窗的打开、关闭、焦点和键盘路径应一起考虑；样式精修不替代正确行为。用于上传、确认、详情和设置弹窗。Radix是实现参考，不是品牌皮肤，也不要求所有技术栈必须引入该依赖。

## Carbon · Empty states / Data table

https://www.carbondesignsystem.com/building-blocks/core/patterns/empty-states
https://www.carbondesignsystem.com/building-blocks/core/components/data-table/guidelines

性质：官方模式、示例图和交互说明。空状态区分首次使用、无搜索结果和系统问题，为当前情境提供后续动作。数据表参考一致密度、工具栏/行操作分工、选择和分页。转化到我们的产品：状态要真实，任务不中断；信息组织比卡片数量重要。不照搬Carbon的企业视觉、默认字号或所有工具栏操作。

## Adobe Spectrum · Design tokens

https://spectrum.adobe.com/page/design-tokens/

性质：官方设计决策体系与示意图。参考语义命名和结构复用：用用途、状态与层级定义值，支持不同场景共用语言。转化：建立文字、表面、间距、圆角和反馈token，再做组件映射。不要把色值表误当完整品牌体系，也不拷贝Adobe品牌色。

## 使用素材的方式

这些来源不全是图片库：Anthropic和Impeccable主要提供工作方法；Vercel偏检查项；Radix有可操作组件；Carbon有模式图和状态示例；Spectrum有结构图。具体页面需要什么，就取对应材料。示例的结构、行为和视觉应分开观察。

每次记录采用点和不采用点，特别关注与已确认偏好的冲突。保留原链接与观察日期；未来网站内容变化时重核。下游需要精确上游要求或复制实现时，再读取对应原文及许可。
