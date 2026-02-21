# task-progress

统一存储所有项目任务进度（跨仓库）。

## 结构
- `tasks/`：每个任务一个文件（状态、负责人、里程碑、链接）
- `daily/`：按日期记录推进日志
- `templates/`：任务与日报模板

## 使用方式
1. 新任务：复制 `templates/task.md` 到 `tasks/<task-id>.md`
2. 每次推进：更新任务状态并在 `daily/YYYY-MM-DD.md` 追加记录
3. 完成任务：标记状态为 `done` 并附上成果链接
