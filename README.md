# lvsea-renwu

`lvsea-renwu` 是一个面向 Codex 的通用复杂任务门控 Skill，借鉴 [amj-lang/anderson](https://github.com/amj-lang/anderson) 的计划、审查、人工确认、实现、复核和交付思想，但使用 Codex 的 Skill、工具和本地工作流重新实现。

## 能做什么

- 把复杂任务拆成可验收阶段；
- 进行有限、针对性的 Grilling 式提问；
- 在实施前后做独立反方审查；
- 记录计划、假设、验收证据和剩余风险；
- 连接视频、数据、网页、文档和代码等领域 Skill；
- 在获得明确授权后推送 GitHub 或创建 PR。

## 安装

将本仓库目录复制到：

```text
C:\Users\Administrator\.codex\skills\lvsea-renwu
```

重启 Codex 后，可显式调用：

```text
使用 $lvsea-renwu 执行这个复杂任务：……
```

## 边界

它不是领域生产工具，也不会因为计划通过就自动删除、部署、发布或推送；外部变更仍需要用户明确授权。原始 Anderson 项目是 Claude Code 插件，本仓库是独立的 Codex 适配版。
