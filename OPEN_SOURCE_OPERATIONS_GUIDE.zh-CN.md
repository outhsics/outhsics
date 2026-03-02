# 开源运营指南（中文）

## 目标

把 GitHub 账号当作产品资产来经营，而不是代码仓库堆积区。

这份指南用于统一仓库的创建、升级、维护和归档流程。

## 运营分层

- `Tier A（旗舰）`：招聘和合作主展示面，置顶并持续迭代。
- `Tier B（增长）`：正在持续交付，验证产品价值。
- `Tier C（维护）`：稳定资产，低频维护。
- `Archived（归档）`：历史资产，不再作为当前主叙事。

## 每月例行流程

1. 跑仓库审计。
2. 按“信号强度 + 活跃度”分层。
3. 归档低信号、长期不活跃仓库。
4. 补齐活跃仓库描述和 topics。
5. 更新 profile README 和项目索引。

命令：

```bash
/Users/terre/scripts/github_repo_audit.sh outhsics /Users/terre/repo-audit
```

## 活跃仓库标准

- 一句话说明清楚：做什么、解决什么问题、价值是什么。
- topics 完整且统一。
- README 顶部有 `Recruiter Snapshot`：
  - 状态
  - 定位
  - 核心价值
  - 技术栈与交付信号
  - 最近审阅时间
- 旗舰仓库保持近期提交活跃。

## 置顶仓库策略

只置顶能代表你当下竞争力的项目：

- 建议 4-6 个
- 优先系统型/产品型项目，不放学习 demo
- 已归档或停更仓库立即替换

建议置顶组合：

- `openfang-auto-clip`
- `ai-skills-control-kit`
- `upload-test-file-generator`
- `ui-diff-tool`
- `TrendRadar`
- `react-schema-form-lite`

手工更新路径：

1. 打开 `https://github.com/outhsics`。
2. 进入 `Repositories`。
3. 点击 `Customize your pins`。
4. 取消已归档仓库，按建议组合勾选并保存。

## 换电脑恢复方案

将关键资产沉淀在 GitHub：

- profile 仓库（`outhsics/outhsics`）
- `/Users/terre/scripts` 中脚本（建议镜像到仓库）
- `/Users/terre/repo-audit` 审计输出
- `templates/` 模板资产

恢复步骤：

1. 克隆 profile 仓库。
2. 安装并登录 GitHub CLI。
3. 执行审计脚本。
4. 批量处理归档和元数据。
5. 更新 README 和置顶仓库，继续迭代。

## 建议发布为技能包仓库

为了长期复用，建议把这套方法发布为公开仓库：

- 建议名：`github-brand-os`
- 内容：脚本、模板、操作手册、示例工作流
- 增补：Codex / Claude / Cursor / Gemini 的快速接入说明
