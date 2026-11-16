# Changelog

## 4.0.0 - 2026-11-16

- 全面适配 2026-11 登录态工作台新版模型与界面：Gemini 4 Hydrogen / Carbon / Argon、Gemini Omni 1.2 / 1.1 视频、Nano Banana 2.1 / 2 Lite、Gemini 3.8 Flash / TTS / Live、Gemini Decision 1、Robotics-ER 2、Lyria 3.5 及 Gemma 4。
- 补齐托管代理（Antigravity Agent / Deep Research）环境来源挂载、网络白名单配置、单次会话 Token 上限弹窗、命令面板（`Ctrl + /`）、Build `Default / Plan / Max` 构建模式及 `Interactions API` 弹窗文案。
- 新增通用定价行解析函数 `translatePricingLine`（支持限时优惠截止日期、星号分隔、大小写兼容及单边价格）与半本地化发布日期（如 `11月 13, 2026`）转换。
- 重构核心汉化引擎：改用 `WeakMap` 值比对修复 `characterData` 动态文本更新漏翻；保护 `.material-symbols-outlined` / `.google-symbols` 图标连字、`textarea` 输入内容及 `ms-chat-turn ms-cmark-node` 模型回复正文；移除首屏 1000ms 延迟并支持 SPA 路由与页面标题同步汉化。

## 3.7.6 - 2026-05-06

- 补齐左下角"新功能"悬浮弹窗中 3 个新增条目标题与描述：Antigravity Agent Preview、Gemini 3.5 Flash、Gemini 3.1 Flash Lite GA。
- 补齐代理页面免责声明、环境设置（Environment / Sources / Network 等）区域漏翻。
- 补齐"构建APP"页面中 Build an Android app、Contacts 等建议按钮文案。
- 补齐 404 页面（Page not found）及资料库入口文案。

## 3.7.4 - 2026-05-02

- 深入补齐 `generate-speech` TTS 页面：逐一点击快速模板后出现的场景、示例上下文、语音片段、添加语音片段、播放器、发言者设置、语音设置等界面文案。
- 对 TTS 默认模板中的已知示例值做精确匹配汉化，避免影响用户自行输入的内容。

## 3.7.3 - 2026-05-02

- 补齐 `generate-speech` / Gemini TTS 页面可见漏翻：页面主标题、快速模板、8 个语音模板标题与描述、模型卡片标题、Speaker settings 等。
- 按用户要求改用已运行的主 Chrome 窗口检查页面，不再使用临时 Chrome profile 调试该页面。

## 3.7.2 - 2026-05-02

- 补齐模型探索首页卡片页漏翻：Explore Google models、Code and Chat、Speech and Music、实时卡片描述等。
- 补充模型列表中的 Release date、图像/视频/歌曲输出价格等动态文案。

## 3.7.1 - 2026-05-02

- 新增 AI Studio 2026-05 可见页面巡检补翻。
- 补齐左下角“新功能”弹层、账号区域、设置菜单、Build with Agents、Deep Research Agents、Prompt Manager 等文案。
- 新增 `aria-description` 翻译支持，补充 tooltip / placeholder / title 覆盖。
- 增加 GitHub homepage/support metadata，便于开源维护和后续 Greasy Fork 同步。
