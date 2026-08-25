# 👋 Hi, I'm Linnnnnn666

**嵌入式 AIoT 开发者 · 电子信息工程** · 用 AI 重构硬件开发流程的实践者

## 🚀 我的代表作：EvoAgent — 自进化的 AI 硬件开发系统

> **用语音指挥 AI 为 ESP32 写固件、OTA 部署、遥测验收——而且系统能自己给自己造新能力。**

```
语音「你好小安」 → xiaozhi-server → fall-mcp 能力中枢 → ESP32 板卡（OTA）
                                    ↑ 双层自进化：工具工厂 · 经验库 · DSH 插件进化
```

**双层自进化（项目灵魂）**：
- **系统层**：干完活自动复盘 → 工具工厂生成 MCP 工具（编译+验证才注册）+ 经验库自动注入
- **智能体层**：DSH-1 干活发现能力缺口 → DSH-2 在隔离环境开发插件 → 装入 DSH-1 → 装坏可回滚（quarantine）
- **三层保险**：隔离 · 验证 · 人在环兜底

**真实成果**：23 次固件迭代全闭环 · 47 个 MCP 工具 · 语音板 5 小时从零 bring-up · 端侧毫米波雷达跌倒检测

## 📦 开源项目

| 仓库 | 角色 | 说明 |
|------|------|------|
| [evo-firmware](https://github.com/Linnnnnn666/evo-firmware) | 硬件端 | ESP32-S3 固件集合：端侧跌倒检测（LD6002B 雷达实时判定）、云端烧录板、配置化引导固件 |
| [evo-fall-mcp](https://github.com/Linnnnnn666/evo-fall-mcp) | 能力中枢 | MCP 服务器（47 工具）：部署/烧录/播报/自验收/自进化 + DSH 插件进化实物 |
| [evo-voice-terminal](https://github.com/Linnnnnn666/evo-voice-terminal) | 语音入口 | 语音板板卡包：唤醒「你好小安」→ 语音对话 → TTS 播报 |

## 🛠 技术栈

`ESP32-S3` `ESP-IDF` `FreeRTOS` `I2S/UART/SPI/RMT` `双分区 OTA` `MQTT` `WebSocket`
`毫米波雷达信号处理` `端侧状态机` `MCP` `LLM Agent` `RAG` `Python` `C/C++`


## 📬 联系

- ✉️ GitHub Discussions / Issues（欢迎交流嵌入式 AIoT）
