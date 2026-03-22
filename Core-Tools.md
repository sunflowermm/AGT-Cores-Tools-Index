## 🛠️ 核心工具与通用组件索引

这里用于索引可在多个 XRK-AGT 项目中复用的 **通用工具库、核心中间件、适配层、脚手架** 等。

> 优先收录与 XRK-AGT 耦合度较高、可被其他项目直接依赖的「基础设施级」仓库。

| 名称 | 作者 / 团队 | 仓库地址 | 说明 | 推荐程度 |
|------|-------------|----------|------|----------|
| Telegram-Core | sunflowermm | [GitHub](https://github.com/sunflowermm/Telegram-Core) | XRK-AGT Telegram Bot 通道 Core：基于 node-telegram-bot-api 长轮询，事件与 NTBA `processUpdate` 对齐，经 `e.reply` 与专用应答进入插件 | ★★★★★ |
| Wechat-entreprise-Core | sunflowermm | [GitHub](https://github.com/sunflowermm/Wechat-entreprise-Core) | XRK-AGT 企业微信通道 Core：自建应用回调收消息 + `message/send` 主动发消息，事件 `wecom.message` / `wecom.notice`，`e.reply` 走插件 | ★★★★★ |
| QQbot-Core | sunflowermm | [GitHub](https://github.com/sunflowermm/QQbot-Core) | XRK-AGT QQ 官方机器人通道 Core：基于 qq-group-bot 接入 QQ 群与频道，将消息标准化为 XRK 事件，支持主动消息 | ★★★★★ |
| Feishu-Core | sunflowermm | [GitHub](https://github.com/sunflowermm/Feishu-Core) | XRK-AGT 飞书通道 Core：基于 @larksuiteoapi/node-sdk 连接飞书，将 Lark 消息标准化为 XRK 事件，与插件链无缝对接 | ★★★★★ |
| xiaozhi-Core | sunflowermm | [GitHub](https://github.com/sunflowermm/xiaozhi-Core) | XRK-AGT 对接 xiaozhi-esp32 的语音 Core：实现 WebSocket 协议，设备直连即可走 ASR→LLM→TTS 零延迟链路 | ★★★★★ |
| Openclaw-Core | sunflowermm | [GitHub](https://github.com/sunflowermm/Openclaw-Core) | XRK-AGT ↔ OpenClaw 桥接 Core：通过 Tasker+插件将受控消息安全转发到 OpenClaw Agent 并回流到前端 | ★★★★★ |
| 占位示例工具 | - | - | 在此处补充你的核心工具 / 中间件项目 | ★★★★☆ |

> 新增条目时，请按从上到下「新到旧」排序。

