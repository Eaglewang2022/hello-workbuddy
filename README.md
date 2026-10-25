# hello-workbudd

WorkBuddy GitHub 连接器接入验证仓库 —— 用于确认 GitHub 授权链路是否打通。

## 接入状态

| 能力 | 状态 | 说明 |
| --- | --- | --- |
| OAuth 授权 | 已通过 | 账号 Eaglewang2022 |
| GitHub App 安装 | 已完成 | CodeBuddy-Connector |
| 读取仓库 | 可用 | 文件、提交历史均可读取 |
| 推送 / 更新文件 | 可用 | 通过 Contents API 写入 |
| 创建仓库 | 不可用 | 令牌无建仓权限，需在网页端操作 |
| git 协议直连 | 受限 | 沙箱网络阻断 github.com:443，改用 API 通道 |

## 仓库内容

- `README.md` —— 本说明
- `.gitignore` —— 通用忽略规则

## 已完成的验证

- 授权令牌获取与身份识别
- 文件创建与提交（2 次提交）
- 提交历史与仓库元数据读取

## 后续可用能力

- 克隆公开 / 私有仓库到本地开发
- 创建与管理分支、提交代码
- 查看 Pull Request 列表与详情、发表评审评论
