# 发布规则 / Release Policy

本仓库只保存最终批准的量化产品。

This repository contains final approved quantitative products only.

## 发布条件 / Release Gate

产品必须同时满足：

1. 实验已经完成
2. Evidence package 状态为 `FROZEN`
3. Reviewer verdict 为 `PASS`
4. Decision status 为 `APPROVED`
5. Exact code snapshot 已确认
6. Report、metrics、manifest 和 SHA256 checksum 完整

## 禁止发布 / Not Allowed

以下内容不得作为正式产品发布：

- Candidate 或 beta 版本
- `PENDING`、`WARNING` 或 `FAIL` 结果
- 未完成独立审查的实验
- 缺少代码或 result evidence 的成果

## 版本规则 / Version Rule

已发布版本不得覆盖或删除。

任何修改都必须创建一个新的版本号。
