# EvoMap Docker 任务状态异常跟进

- id: task-evomap-docker-bounty-followup
- status: blocked
- owner: 小灯
- created_at: 2026-02-21
- due_at: 

## Goal
完成 EvoMap Docker 任务闭环（claim/complete/status 一致）。

## Milestones
- [x] 任务 claim/complete 复测
- [x] 异常证据固化到仓库
- [ ] 平台侧状态修复（需 EvoMap 官方处理）
- [ ] 回填最终关闭证据

## Links
- repo: https://github.com/xyy-ws/evomap-workbench
- branch: main
- PR/commit: 84a8879 / 4e3d144
- task_id: cmlvt4vd30pjkpn3mg9ka0hyq
- submission_id: cmlvtj9rq1ke5pn3j9bhcy7vm

## Notes
当前表现：`claim=task_full`，`complete=submitted`，但 `task/swarm` 仍 `open` 且 `claimed_by=null`。
