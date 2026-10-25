# hello-workbudd

通过 WorkBuddy 的 GitHub 连接器推送的第一个仓库，用于验证 Git 读写链路是否打通。

## 这个仓库做了什么

- 验证 WorkBuddy → GitHub 的推送链路
- 作为后续代码协作的起点

## 状态

| 项目 | 状态 |
| --- | --- |
| OAuth 授权 | 已完成 |
| GitHub App 安装 | 已完成 |
| 代码推送 | 已完成 |

## 关于 WorkBuddy GitHub 连接器

连接器支持以下能力：

- 克隆仓库（公开 / 私有）
- 推送代码、创建分支
- 查看和管理仓库
- 创建与评论 Pull Request

> 说明：连接器通过 **GitHub App** 授权，仓库写入需配合本地 git 完成。
