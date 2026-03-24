# 运维与部署文档

适用于在持久化或类生产环境中运行 ZeroClaw 的运维人员。

## 核心运维

- 日常运行手册：[./operations-runbook.md](./operations-runbook.md)
- 发布手册：[../contributing/release-process.md](../contributing/release-process.md)
- 故障排除矩阵：[./troubleshooting.md](./troubleshooting.md)
- 安全网络/网关部署：[./network-deployment.md](./network-deployment.md)
- Mattermost 安装（特定渠道）：[../setup-guides/mattermost-setup.md](../setup-guides/mattermost-setup.md)

## 通用流程

1. 验证运行时（`status`、`doctor`、`channel doctor`）
2. 每次只应用一个配置更改
3. 重启服务/守护进程
4. 验证渠道和网关健康状态
5. 如果行为退化则快速回滚

## 相关文档

- 配置参考：[../reference/api/config-reference.md](../reference/api/config-reference.md)
- 安全合集：[../security/README.md](../security/README.md)
