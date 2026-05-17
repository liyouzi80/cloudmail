# 项目规则

## 上游同步规则

- **禁止**向上游仓库（`maillab/cloud-mail`）创建任何 Pull Request
- **禁止**向任何非本 fork（`liyouzi80/cloudmail`）的仓库推送代码或提 PR
- 同步上游代码时，只需：
  1. `git fetch upstream main`
  2. 合并到本 fork 的 `main` 分支
  3. `git push origin main`
  - 不创建 PR，不创建中间分支
