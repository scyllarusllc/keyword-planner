# Scyllarus Keyword Planner

**把一个模糊想法，变成清晰的业务方向、好记的名字，以及可执行的关键词计划。**

由 **[Scyllarus](https://github.com/scyllarusllc)** 创建的开源 AI 创意与关键词规划项目，用于创意头脑风暴、品牌与域名构思、SEO 关键词研究，以及 Google Keyword Planner 导出数据分析。

[English](README.md) · [塞班平台示例](examples/saipan-marketplace.md) · [技能指令](skills/keyword-planner/SKILL.md) · [联系 Scyllarus](mailto:hey@scyllar.us)

## 能帮你做什么

- **打磨想法：** 找到目标用户、真实问题与值得先验证的细分方向。
- **构思名字：** 比较品牌名和域名的记忆性、发音、地域属性与扩展空间。
- **规划 SEO：** 扩展关键词，分析搜索意图，聚类并规划页面优先级。
- **理解数据：** 分析 Google Keyword Planner 导出文件，保留地区、语言、时间与指标含义。

创意假设、实际观察和真实测量会分别标注。没有数据时，不编造搜索量；没有查证时，不声称域名可注册。

## 开始使用

```sh
git clone https://github.com/scyllarusllc/keyword-planner.git
cd keyword-planner
```

让你的 AI 编程助手读取 `skills/keyword-planner/SKILL.md`，然后提出请求，例如：

> 按 skills/keyword-planner/SKILL.md 的方法，帮我研究一个面向塞班的生活信息平台，涵盖租房、超市促销和供求。先讨论定位与域名，用中文回复。区分创意与证据，不编造搜索量。

如果使用支持技能目录的助手，请按该助手的安装方式复制完整的 `skills/keyword-planner/` 文件夹。克隆项目不会自动完成全局安装。

目前通过 AI Skill 交付，在线网站版属于未来方向，尚未开发。

这是独立项目，并非 Google 官方产品，也未内置 Google Ads API 接入。可以直接做定性研究、分析已有导出文件；现在支持通过已授权、已登录的 Google Keyword Planner 浏览器会话做实时研究，也支持可用的数据连接或导出文件。浏览器方式不需要 Google Ads API 开发者令牌；浏览器控制能力由你的 AI 助手提供，仓库本身未打包浏览器驱动。

## 使用 Google Keyword Planner

> 读取 skills/keyword-planner/SKILL.md，使用我已登录的 Google Keyword Planner 研究塞班生活信息平台。地区仅选塞班，英文和简体中文分开查询，保留搜索量区间，账户研究结果保存在本地。

详见[浏览器工作流](skills/keyword-planner/references/google-browser.md)，包含地区、语言、日期、分页、意图检查和证据保留。Google 可能只提供区间数据；这个流程无需创建广告或修改付款设置。

## 带着你的想法来找我

你有一个想法，但还没想清楚给谁用、叫什么、怎么让别人找到？可以发给我：

- 你想做什么，准备帮助谁。
- 目标市场或地区。
- 目前最想解决的一个问题。

**Scyllarus · [hey@scyllar.us](mailto:hey@scyllar.us) · [GitHub](https://github.com/scyllarusllc)**

项目问题与可复用的改进建议欢迎提交 Issue 或 PR。私人项目细节请通过邮件沟通，不要在公开 Issue 中提交密钥或客户隐私。

## 命名与项目方向

产品展示名采用 **Scyllarus Keyword Planner**，仓库名和技能标识保留 `keyword-planner`。这里使用单数 **keyword** 修饰 planner。详见[命名决策记录](docs/naming.md)，包含本次讨论、项目发展方向，以及版权与商标考虑。

## 开源许可

采用 [MIT 许可证](LICENSE)，允许在保留许可声明的前提下使用、修改与分享。
