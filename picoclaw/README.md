# PicoClaw

PicoClaw 是一款超轻量级个人 AI 助手，支持多种 LLM 提供商，强调轻量、快速与安全。

## 应用信息

- 应用名：PicoClaw
- 包名：`picoclaw`
- 当前版本：`0.2.6`
- 发布者：EWEDL
- 上游项目：<https://github.com/sipeed/picoclaw>
- 问题反馈：<https://github.com/sipeed/picoclaw/issues>

## 简介

皮皮虾，超轻量级个人 AI 助手，支持多种 LLM 提供商，比小龙虾更小、更轻快、更安全。

## 安装说明

从 FnDepot 安装后即可使用。当前仓库内提供 `picoclaw.fpk` 安装包。

## 更新说明

#### 核心改进
- 🔧 **升级至 v0.2.6** - 同步上游最新 Linux 安装包
- 🧠 **增强 hooks/respond 与通用能力** - 持续完善工具链与交互流程
- 📁 **改进 MCP 大文本处理** - 超长文本结果可更稳定地转为 artifact

#### Web/Gateway 稳定性
- ✅ **修复 WebUI 与 Gateway 连接问题** - 优化前端连接链路
- ✅ **修复 WebSocket 地址推导逻辑** - 由浏览器位置推导连接地址
- ✅ **强化 Gateway PID 存活与清理** - 校验 PID 所有权并清理陈旧 pid 文件

#### 平台与运行兼容
- ✅ **不支持平台的功能门控优化** - 避免在不兼容环境启用相关能力
- ✅ **Launcher 网络/控制台参数修复** - 提升 Linux 环境运行稳定性

---
*上次更新：2026-04-15*
