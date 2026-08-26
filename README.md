# 👋 半夏的 AI 自托管与自动化仓库

> 深圳家庭 NAS + Windows PC 的 AI 工具栈实战沉淀。涵盖 **飞牛 fnOS NAS 自托管 AI 服务**、**Tailscale 组网**、**反代**、**微信通知**，以及一批 **WorkBuddy 自动化技能**。
> 所有教程均已**脱敏**（内网 IP / Token / 订阅节点 / 本机路径均替换为占位符），可安全公开参考。

---

## 🧩 WorkBuddy 自动化技能（代码仓库）

| 仓库 | 说明 |
|---|---|
| [gemini-browser-image-gen](https://github.com/seeyouagain-laoda/gemini-browser-image-gen) | 通过 Chrome DevTools Protocol (CDP) 驱动已登录的 gemini.google.com 标签页生图，内置自校验（提示词已发送 + 新图已渲染），无需 API Key。 |
| [multi-ai-query](https://github.com/seeyouagain-laoda/multi-ai-query) | 并行向 5 个 AI（DeepSeek / Qwen / Kimi / ChatGPT / Perplexity）提问并自动汇总答案；不可达的 AI 自动禁用，兼容 Chrome 151。 |
| [pplx-image-gen](https://github.com/seeyouagain-laoda/pplx-image-gen) | 复用已登录的 Chrome 登录态，在 Perplexity 网页版生图并自动下载到本地，消耗 Perplexity Pro 每日图像额度，无需 API Key。 |

---

## 🖥️ NAS / fnOS 自托管 AI 工具栈教程（中文实战）

> 合集索引：`[nas-selfhosted-ai-guides](https://github.com/seeyouagain-laoda/nas-selfhosted-ai-guides)` —— 下面每个主题已拆为独立仓库，此仓为导航。

| 仓库 | 说明 |
|---|---|
| [openclaw-fnOS-guide](https://github.com/seeyouagain-laoda/openclaw-fnOS-guide) | OpenClaw 在飞牛 fnOS NAS 上的完整部署：安装、每日健康报告、Server酱任务完成通知、fygo 浏览器 CDP（127.0.0.1:16002）接管。 |
| [mihomo-stack-guide](https://github.com/seeyouagain-laoda/mihomo-stack-guide) | 自建 Mihomo (Clash.Meta) 代理栈：机场节点筛选方法论、Clash Verge Rev 热更新避坑、透明代理与规则分流。 |
| [tailscale-mesh-guide](https://github.com/seeyouagain-laoda/tailscale-mesh-guide) | Tailscale 异地/家庭组网：NAS + 多终端 mesh、代理注入修复、PCVR 串流与 SMB/NFS 共享的透明代理分流。 |
| [reverse-proxy-guide](https://github.com/seeyouagain-laoda/reverse-proxy-guide) | 自建反代实战：Google Gemini 与 Perplexity (pplx-proxy) 的 web-to-API 反代部署、客户端接入、模型别名与故障排查。 |
| [gemini-reverse-proxy-nas](https://github.com/seeyouagain-laoda/gemini-reverse-proxy-nas) | 在 NAS/Linux 上把 Google Gemini 部署为 web-to-API 反代（Docker + nginx + HTTPS 证书），局域网内供 ChatBox / Agent 应用调用，含对话与生图。 |
| [wechat-notify-guide](https://github.com/seeyouagain-laoda/wechat-notify-guide) | Server酱（方糖）微信通知自动化：WorkBuddy / OpenClaw 任务完成自动推微信，含脚本、命令速查与避坑。 |
| [minimax-h3-guide](https://github.com/seeyouagain-laoda/minimax-h3-guide) | MiniMax H3（海螺 3.0）视频生成工作流：本地 ComfyUI + 开源 H3-Base 模型、提示词结构、角色一致性、lip-sync 验证与 Server酱进度通知。 |
| [tdai-unified-memory-guide](https://github.com/seeyouagain-laoda/tdai-unified-memory-guide) | 把 WorkBuddy、主机 OpenClaw、NAS OpenClaw 接入腾讯云 TencentDB Agent Memory，实现三端统一共享记忆（中文为主 + 英文摘要）。 |

---

## 🔗 引用与致谢

- [TencentCloud/TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory) — 三端统一记忆方案的上游参考
- [Mihomo (Clash.Meta)](https://github.com/MetaCubeX/mihomo) · [Tailscale](https://github.com/tailscale/tailscale) · [Clash Verge Rev](https://github.com/clash-verge-rev/clash-verge-rev) · [MiniMax H3](https://www.minimax.io/) · [Server酱](https://sct.ftqq.com/) · [Gemini](https://gemini.google.com/) · [Perplexity](https://www.perplexity.ai/)

---

> ⚠️ 本主页与所有仓库内容均为**脱敏后的通用方法论与踩坑经验**，不含任何个人凭据或内网拓扑。如需复现，请结合自身网络环境替换占位符。
