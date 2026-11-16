# Google AI Studio 汉化脚本

一个用于汉化 [Google AI Studio](https://aistudio.google.com/) 的 Tampermonkey / Violentmonkey 用户脚本。本仓库基于上游 [izscc/AIstudio-zh](https://github.com/izscc/AIstudio-zh) 维护升级，持续适配新版登录态工作台界面。

## 安装

- GitHub Raw 一键安装与自动更新：<https://raw.githubusercontent.com/shixiaogaoya/AIstudio-zh/main/google-ai-studio-zh.user.js>
- 上游原版 Greasy Fork：<https://greasyfork.org/zh-CN/scripts/556804>

推荐直接通过上方 GitHub Raw 链接安装，安装后可通过 `@updateURL` 从本仓库 `main` 分支自动更新（若此前已安装原版 `3.7.6`，直接打开该链接覆盖升级即可）。

## 本次覆盖重点

- AI Studio 登录态新版工作台：Playground / Chat、Build Apps（`Default / Plan / Max` 模式）、History、API Keys / Dashboard 与命令面板（`Ctrl + /`）。
- 2026-11 新版模型与模态：Gemini 4 系列、Gemini Omni 1.2 / 1.1、Nano Banana 2.1、Gemini 3.8 Flash / TTS / Live、Gemini Decision 1、Robotics-ER 2、Lyria 3.5、Gemma 4 及托管代理（Antigravity Agent / Deep Research）。
- 动态日期、Token、层级、限时优惠价格、安全设置、网络白名单与用量等常见 UI 文案。

## 发版流程

1. 修改 `google-ai-studio-zh.user.js` 并递增 `@version`。
2. 同步更新 `CHANGELOG.md`。
3. 推送到 `shixiaogaoya/AIstudio-zh` 的 `main` 分支，Tampermonkey / Violentmonkey 通过 GitHub Raw `@updateURL` 自动获取更新。

## 许可证

MIT
