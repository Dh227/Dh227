# 作品集

这里集中展示我围绕本地优先、可解释流程和真实业务场景完成的产品原型、交付实验与工具。

[查看个人作品集网站](https://lixinyang-portfolio-d1bbcf4760fa-1351247393.tcloudbaseapp.com)

## 产品与业务原型

| 项目 | 简介 | 技术与特点 |
| --- | --- | --- |
| [JetLinks 智慧水务本地模拟平台](https://github.com/Dh227/jetlinks-water-station-demo) | 面向 Apple Silicon 的智慧水务本地模拟、故障注入和交付验收实验室。 | JetLinks、Node.js、Docker Compose；保留自研交付层，并标明上游来源。 |
| [Travel Workbench](https://github.com/Dh227/travel-workbench) | 将目的地、预算、偏好和节奏转成可执行的逐日行程。 | Node.js、React、SQLite；路线、天气、预算、约束、Plan B 与本地离线包。 |
| [医疗设备售前支持与销售运营](https://github.com/Dh227/medical-sales-support-ops) | 围绕样机、库存、交付异常、商机和成交复盘设计的业务原型。 | Spring Boot、Vue 3、MySQL；基于 JeecgBoot 并保留 Apache-2.0 来源说明。 |

## 本地优先工具

| 项目 | 简介 | 技术与特点 |
| --- | --- | --- |
| [个人求职作品集](https://github.com/Dh227/lixinyang-portfolio) | 面向售前与解决方案工程师岗位的中文个人网站源码。 | React、TypeScript、GSAP；响应式排版、低动态模式和腾讯云静态部署。 |
| [Resume Multi-Agent Studio](https://github.com/Dh227/resume-multi-agent-studio) | macOS 单用户求职桌面工具，覆盖简历优化、岗位解析、安全投递和面试训练。 | Electron、React、TypeScript；人工确认优先的工作流。 |
| [简填 · 网申资料助手](https://github.com/Dh227/jian-tian-job-form-extension) | 浏览器扩展：预览、脱敏并辅助填写网申表单。 | Chrome/Edge Extension；不自动提交、不处理验证码、不上传隐私资料。 |
| [中文个人工作日报 Skill](https://github.com/Dh227/daily-work-report-skill) | 从用户提供的证据生成、校验并准备脱敏同步的中文工作日报。 | Python、Markdown；27 项测试，公开快照不含真实日报和企业资料。 |
| [LiveCaptionOverlay](https://github.com/Dh227/live-caption-overlay) | macOS 实时中文字幕透明悬浮工具原型。 | SwiftUI、AppKit、ScreenCaptureKit；短时内存缓冲，不落盘保存字幕。 |
| [Clipboard History](https://github.com/Dh227/clipboard-history) | macOS 菜单栏历史粘贴板工具。 | SwiftUI、Core Data；搜索、置顶、到期清理与本地数据存储。 |

## 设计原则

- 本地优先：个人资料、旅行数据与离线包默认不上传。
- 真实边界：对外部数据、系统估算与本地兜底明确标注。
- 人工确认：涉及投递、修改日程、删除和敏感填写时保留用户最终决定权。
