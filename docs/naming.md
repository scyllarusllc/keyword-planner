# Naming decision / 命名决策记录

日期：2026-11-14（Pacific/Saipan）

## 当前决定

| 项目 | 采用名称 |
| --- | --- |
| 产品展示名 | Scyllarus Keyword Planner |
| GitHub 仓库 | keyword-planner |
| 技能目录与调用标识 | skills/keyword-planner/ · $keyword-planner |
| 功能描述 | AI Brainstorming & SEO Research |
| 作者与联系 | Scyllarus · hey@scyllar.us · https://github.com/scyllarusllc |

这是当前产品命名决定，不代表完成商标核查、取得商标权或确认域名可注册。

## 为什么创建这个项目

讨论最初来自一个面向塞班的生活信息平台构想：租房、超市促销和本地供求。我们希望先研究业务方向、关键词与域名，随后发现可以把这套研究方法做成可复用的开源 AI 技能。

项目也应成为发现 Scyllarus 的入口：让访客通过清楚的能力介绍、具体案例和公开联系方式，了解可以找作者一起打磨什么样的想法。通过作品展示创意价值，不承诺业务成功或搜索排名。

## 讨论过的命名方向

| 方案 | 考虑与取舍 |
| --- | --- |
| Keyword Planner | 简洁、描述用途，但品牌辨识度不足，与 Google 现有工具名称相近 |
| Keywords Planner | 曾作为备选讨论；复数不会自动避开商标混淆问题，英文搭配也不如单数自然 |
| keyword-planner-skill | 能直接说明当前交付形式，但会限制未来网站与其他工具形态的表达 |
| 名称加入 AI / OpenAI / Codex / Gemini / Grok | AI 可用于功能描述；不将供应商品牌堆进项目名称，也不暗示未经验证的兼容、背书或合作关系 |
| Scyllarus Keyword Planner | 当前选择：突出作者品牌，保留功能含义，为未来在线版留空间 |

最初倾向直接保留 Keyword Planner；在讨论 Google 名称及商标混淆后，将展示名调整为 Scyllarus Keyword Planner。仓库仍保留简洁的 keyword-planner。

## Keyword 还是 Keywords？

采用 **Keyword Planner**。这里 keyword 是修饰 planner 的名词，单数是更自然的产品类别表达，并不意味着只能规划一个关键词。在正文里描述多个关键词时仍使用 keywords，例如 “research keywords” 和 “keyword clusters”。这是语言与产品表达选择，不是法律上的避险结论。

## Skill 与未来网站的关系

项目定位为通用的 AI 创意与关键词规划工具，当前只交付 AI Skill。先通过真实使用打磨业务头脑风暴、品牌与域名构思、SEO 研究和数据解释方法，再根据重复出现的需求提取可复用代码，后续可以建设在线网站。

网站尚未开发；没有宣称已提供在线服务或已实现 Google Ads API 集成。技能放在独立的 skills/keyword-planner/ 文件夹，项目文档和示例放在仓库层，避免未来网站代码与技能安装内容混在一起。

## 版权与商标：分别考虑

以下依据美国官方公开资料，属于项目命名的初步研究记录，不是法律意见或完整商标清查。

- **版权：** 美国版权局说明，名称、标题和短语通常不受版权保护。这不意味着相同名称在商标法下也可自由使用。原创代码、文档、图形等表达需要另行考虑；本项目的 MIT 许可不授予第三方商标权。[美国版权局](https://copyright.gov/help/faq/faq-protect.html)
- **Google 的使用：** Google 官方确实使用 Keyword Planner 名称提供关键词研究功能。我们的功能存在交集，因此需要考虑来源、赞助或关联关系方面的误解。[Google 官方说明](https://support.google.com/google-ads/answer/7337243)
- **混淆判断：** USPTO 说明，名称不必完全一致；外观、读音、含义或商业印象相近，加上相关商品或服务，都可能与混淆判断有关。增加一个 s、AI 或作者前缀，不等于自动排除风险。[USPTO 混淆说明](https://www.uspto.gov/trademarks/search/likelihood-confusion)
- **核查范围：** 本次没有完成商标数据库检索、普通法使用情况调查或其他司法辖区核查，也没有确认 Google 对 Keyword Planner 词组是否持有单独注册商标。不能从没有查询结果或名称具有描述性，推断不存在权利。[USPTO 完整检索指引](https://www.uspto.gov/trademarks/search/comprehensive-clearance-search-similar-trademarks)

当前采用独立的 Scyllarus 品牌，并在首页解释与 Google 的关系。这是品牌区分措施，不是法律安全保证。在投入正式商业推广、域名或商标申请前，仍需按目标市场做相应清查，必要时请商标专业人士评估。

## 后续命名变更

如将来清查、用户反馈或业务范围显示应使用更独特的主品牌，可重新命名产品。记录变更理由，并同步 README、技能 UI 元数据、安装说明与链接；不要把当前选择描述成永久决定。
