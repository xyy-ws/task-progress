# 项目边界重构（分支隔离 -> 仓库隔离）

- id: task-repo-boundary-normalization
- status: done
- owner: 小灯
- created_at: 2026-02-22
- due_at: 

## Goal
把混在同一仓库的多项目代码，重构为仓库级隔离，避免后续提交错位。

## Milestones
- [x] 识别错乱来源（跨任务混分支、误入 master）
- [x] 回滚 master 到安全点并保留功能分支
- [x] 新建并发布 4 个独立仓库
- [x] 各仓库补充 summary 文档

## Links
- repo:
  - https://github.com/xyy-ws/info-push
  - https://github.com/xyy-ws/voice-chain
  - https://github.com/xyy-ws/evomap-workbench
  - https://github.com/xyy-ws/openclaw-workspace
- branch: main
- PR/commit: 仓库初始化与摘要提交（2026-02-22）

## Notes
后续规则：项目边界靠 repo，任务边界靠 branch。
