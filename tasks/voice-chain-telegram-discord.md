# Telegram/Discord 语音链路独立化与打通

- id: task-voice-chain-telegram-discord
- status: done
- owner: 小灯
- created_at: 2026-02-21
- due_at: 

## Goal
打通 Telegram/Discord 语音转写与回复，并将语音链路沉淀到独立仓库。

## Milestones
- [x] 语音转写链路可用（Telegram/Discord）
- [x] 本地 ASR（faster-whisper）接入并调优（A档：base + beam=1）
- [x] 独立仓库 `voice-chain` 建立并发布
- [x] OpenClaw 配置文档补齐（config/env 示例）

## Links
- repo: https://github.com/xyy-ws/voice-chain
- branch: main
- PR/commit: cd96561 / cc60f38

## Notes
早期存在“误入 master/错分支”问题，已修正为独立分支与独立仓库归属。
