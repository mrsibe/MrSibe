# 西贝 · MrSibe

**Go 写后端，TypeScript 写界面，做能在自己电脑上跑的 AI 工具。**

模型自己选，文档不出本机。

成都 · 🔭 天文观测 · ✍️ [博客](https://mrsibe.top) · 📺 [B站](https://space.bilibili.com/386324877) · 🐦 [X](https://x.com/Mr_Sibei)

---

## 在做的东西

### [KnowNote](https://github.com/MrSibe/KnowNote) · 本地优先的 AI 知识库桌面端

PDF、Word、网页丢进去，变成能追问的知识库，每个答案带回原文出处。解析、切分、向量检索都在本机跑，只有你发给模型服务的那一句请求会离开机器。

`TypeScript` `Electron` `1.1k ★` · [knownote.pages.dev](https://knownote.pages.dev)

### [GOAT](https://github.com/MrSibe/goat) · 可组合的 Go Agent SDK

把模型协议、流式事件、状态化 Agent 循环拆成能拼的包，同一套代码接 OpenAI、Anthropic、Gemini、Azure 或自建模型。核心只做运行时，编码工具和 CLI 放在产品层。

`Go` `v0.5.0` · [pkg.go.dev](https://pkg.go.dev/github.com/mrsibe/goat)

### [goding](https://github.com/MrSibe/goding) · 基于 GOAT 的无头编码 Agent

工具调用、文件与命令沙箱、会话持久化、MCP、TUI，一个终端里跑起来的编码 Agent。

`Go`

### [SkyEye](https://github.com/MrSibe/sky-eye) · 小行星观测的桌面软件

读多 HDU FITS、问 Gaia DR3 解 WCS、Blink 比较、做孔径测光，测完直接生成 MPC 观测报告。自己拍的那几帧自己算。

`Rust` `Tauri`

## 顺手写的

- **[godis](https://github.com/MrSibe/godis)** · Go 写的 Redis 兼容内存 KV 存储，拿 Redis 的命令语义当练习
- **[mira](https://github.com/MrSibe/mira)** · 自带 API Key 的本地优先 ChatGPT 桌面客户端，Windows / macOS / Linux
- **[streamgate](https://github.com/MrSibe/streamgate)** · HLS 感知的 IPTV 流网关，只做代理和改写这一件事

## 在别人的仓库里

- [apache/dubbo-go #3195](https://github.com/apache/dubbo-go/pull/3195) · 给 Go SDK 加 `CtxLogger` 接口，打通 OpenTelemetry trace
- [apache/dubbo-go-samples](https://github.com/apache/dubbo-go-samples) · OTel 接入示例（#1030）与异步 RPC 的 Java 互操作（#992）
- [apache/dubbo-website #3190](https://github.com/apache/dubbo-website/pull/3190) · Go SDK 的 OpenTelemetry 接入文档
- [apache/gravitino #12711](https://github.com/apache/gravitino/pull/12711) · drop-event 日志限流改成原子操作
- [vllm-project/aibrix #2794](https://github.com/vllm-project/aibrix/pull/2794) · TensorRT-LLM generation-first 的 P/D 路由

## 在学的

MIT 6.5840（Raft / MapReduce labs）· MIT 6.S081 · CS 61B · [手写 GPT-2 与 Llama 风格模型](https://github.com/MrSibe/learn-llm)

## 找到我

[博客](https://mrsibe.top) · [B站](https://space.bilibili.com/386324877) · [X](https://x.com/Mr_Sibei) · 公众号「西贝茶馆」
