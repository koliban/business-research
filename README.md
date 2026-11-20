# 业务调研

一个 Codex 插件，用于把会议纪要、访谈转写和 Excel 调研重点整理成可编辑的 Word 业务调研报告。

支持单家试稿、多单位全量编写、批注修订、跨单位分析和 Word 版式复核。需要时可将流程画成泳道图，并另附可编辑 PowerPoint。

## 安装

使用 Codex CLI 添加本仓库的插件目录。

```sh
codex plugin marketplace add koliban/business-research
```

重新打开 Codex 桌面端，在插件目录的「业务调研」来源下安装「业务调研」。也可以克隆本仓库，在仓库根目录运行 `codex plugin marketplace add .` 注册本地副本。

## 使用

在 Codex 中调用插件并提供调研纪要、访谈转写或 Excel 调研重点。可同时指定调研单位、范围、现有 Word 模板、统计基准年份、审阅方式和需要绘制的流程图。

多单位报告默认先交付一家试稿供确认。已有确认稿或明确要求直接生成全量稿时，按当前要求推进。最终交付可编辑 Word，待核事项随审阅稿提供。可编辑泳道图 PowerPoint 按需交付。

插件提供工作流和模板。读取素材、生成和渲染 Word、制作 PowerPoint 需要当前 Codex 环境具备相应文件能力。素材核对表供写作和审阅使用。

## 许可证

本仓库使用 [MIT 许可证](LICENSE)。
