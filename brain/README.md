# AI Brain / 大脑层 (Layer 3)

LLM 调用、Agent 框架、语音交互、多模态理解与决策。

## 模块

- `llm/` — LLM 接口与 Agent 调用 (Claude API / LangChain / Tool Use)
- `speech/` — 语音交互 (Whisper ASR + ChatTTS/Edge-TTS)
- `decision/` — 意图理解与决策引擎

## 与 ROS2 层通信

通过 rclpy 调用 ROS2 的 Service / Action 接口，实现 AI 决策到机器人动作的映射。
