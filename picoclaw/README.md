# PicoClaw

PicoClaw 是一款超轻量级个人 AI 助手，支持多种 LLM 提供商，强调轻量、快速与安全。

## 应用信息

- 应用名：PicoClaw
- 包名：`picoclaw`
- 当前版本：`0.2.5`
- 发布者：EWEDL
- 上游项目：<https://github.com/sipeed/picoclaw>
- 问题反馈：<https://github.com/sipeed/picoclaw/issues>

## 简介

皮皮虾，超轻量级个人 AI 助手，支持多种 LLM 提供商，比小龙虾更小、更轻快、更安全。

## 安装说明

从 FnDepot 安装后即可使用。当前仓库内提供 `picoclaw.fpk` 安装包。

## 更新说明

#### 核心功能
- 🧠 **短期记忆引擎（LCM）** - Seahorse 模块核心升级，支持短期记忆管理
- 🔧 **LOCOMO 内存基准测试工具** - 新增性能评估能力
- 📁 **MCP 大文本存储** - 超长结果自动存为 artifact

#### Web/前端优化
- 💬 **聊天支持图片消息** - Pico Chat 升级
- 📊 **日志面板滚动优化** - Logs Panel 体验改进
- 🔐 **Dashboard Token 持久化** - Launcher 前端令牌保存

#### 渠道/集成
- 📢 **VK 频道支持** - 新增俄罗斯主流社交平台
- 🌍 **时区环境变量支持** - TZ/ZONEINFO 加载优化

#### 修复/维护
- ✅ write_file 嵌套 JSON 转义语义澄清 + 测试
- ✅ CLI help banner 重复 `-v` 问题修复
- ✅ Makefile 拼写错误修复
- ✅ Windows 构建支持 + 自定义构建环境

---
*上次更新：2026-04-07*
