# WorkBuddy 工作区

用于 Git / GitHub 连接与提交签名链路的端到端验证。

## 环境

| 项目 | 值 |
| --- | --- |
| 认证方式 | SSH (ed25519) |
| 提交签名 | SSH 格式 (`gpg.format=ssh`) |
| 提交身份 | yuchen <2741640139@qq.com> |

## 验证项

- [x] SSH 认证连通 (`ssh -T git@github.com`)
- [x] 本地提交签名生效 (`git log --show-signature`)
- [ ] 远程推送成功
- [ ] GitHub 显示 Verified 徽章
