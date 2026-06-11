# GitHub Labels 建议

以下 Labels 建议用于 VieilAmiIMS / 家庭物品管理系统 - 无限探索版 RC1 公开测试阶段的问题分类。

| Label | 用途 | 建议颜色 |
| --- | --- | --- |
| `bug` | 程序错误、功能异常或行为不符合预期。 | `#d73a4a` |
| `crash` | 启动崩溃、运行中崩溃或无响应退出。 | `#b60205` |
| `database` | 数据库初始化、迁移、读写、目录或结构相关问题。 | `#5319e7` |
| `install` | 安装、卸载、重装、证书导入或首次启动相关问题。 | `#fbca04` |
| `msix` | MSIX 打包、签名、安装包识别或包版本相关问题。 | `#f9d0c4` |
| `ui` | 界面显示、布局、交互、可用性和视觉问题。 | `#1d76db` |
| `printing` | PDF 导出、标签打印、打印机设置相关问题。 | `#006b75` |
| `localization` | 多语言、翻译、语言切换和区域显示相关问题。 | `#bfdadc` |
| `backup` | 备份、恢复、备份文件读取和恢复后数据验证。 | `#0e8a16` |
| `data-loss` | 数据丢失、覆盖、误删或可能造成数据风险的问题。 | `#e11d21` |
| `enhancement` | 功能建议、体验优化和非紧急改进。 | `#a2eeef` |
| `test-feedback` | 测试记录、测试结论、通过项和综合反馈。 | `#c5def5` |
| `documentation` | README、安装说明、测试说明或 Release 说明相关问题。 | `#0075ca` |
| `high-priority` | 需要优先处理的问题，例如阻塞安装、崩溃或数据风险。 | `#d93f0b` |
| `need-reproduction` | 信息不足，需要补充复现步骤、日志、截图或环境信息。 | `#ededed` |

## 使用建议

- 一个 Issue 可以同时使用多个 Label，例如安装失败可标记 `bug`、`install`、`msix`。
- 涉及崩溃的问题建议同时标记 `crash` 和对应模块标签。
- 涉及数据风险的问题建议同时标记 `data-loss` 和 `high-priority`。
- 测试用户提交的综合体验记录可标记 `test-feedback`。
- 信息不足但方向明确的问题可先标记 `need-reproduction`，等待补充后再调整。
