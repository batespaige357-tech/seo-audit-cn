# SEO Audit CN

**用中文说清 SEO 问题，给每个判断留证据。**

## 功能与流程

技术 SEO、抓取与收录、页面标题与内容、国际化、多语言、本地业务、优先级行动计划。上游正文及七个参考文件完整保留，包括结构化数据检测的工具限制说明。

## 中文适配补充

- 先说清搜索引擎、市场、语言和审计范围，不把 Google 数据当作所有平台的结论。
- 中文解释问题和修复建议，保留 URL、响应码与配置原文。
- 英文标题长度参考不机械当作中文通过阈值。
- 分清已观察、待核实与无法访问，未知的收录、流量与指标不补造。

## 安装与调用

```bash
npx skills add batespaige357-tech/seo-audit-cn --skill seo-audit-cn
```

对助手说“用 seo-audit-cn 审查这些页面，先给证据和优先级”；Codex 可使用 `$seo-audit-cn`。也可以把 `skills/seo-audit-cn` 整个目录复制到助手支持的技能目录，保留 references。

这是审计工作流指令，不自带爬虫或 Search Console 账号。需要助手已有的联网、文件读取或已授权的工具能力；缺少权限的数据明确列为未验证。安装不自动改站或提交页面到第三方。

## 来源与许可

基于 [coreyhaines31/marketingskills 的 seo-audit](https://github.com/coreyhaines31/marketingskills/tree/main/skills/seo-audit)，由本仓库维护。

MIT，保留 Corey Haines 版权和许可。参考提交与具体修改见 [CHANGES.md](CHANGES.md)。没有示例网页、截图或前后对比。

已检查原正文、七份参考、UTF-8、相对链接与技能格式；未进行真实网站审计或搜索流量实验，不承诺排名提升。未执行前端编译。
