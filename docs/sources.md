# 来源与许可证

本页记录游戏的来源、GPT-6 创作依据和再分发许可。第三方作品固定到收录时核验过的提交；仓库公开但没有许可证，不代表可以复制。

## 本地收录

| 游戏 | 原作者与来源 | GPT-6 创作依据 | 许可证 | 本地处理 |
| --- | --- | --- | --- | --- |
| 瓶中沧海 | 仓库维护者直接提交的原始 HTML | 维护者在收录请求中声明由手机端 GPT-6 创建 | 未单独声明 | 原始单文件与说明文档 |
| Iron Wilds | [TimelessP](https://github.com/TimelessP) · [提交 `38cf0f2`](https://github.com/TimelessP/mech/tree/38cf0f2419b120b50c30763e37873f8cb43bb33a) | 上游仓库简介声明由 GPT-6 Astra vibe coding 完成 | [MIT](../games/iron-wilds/LICENSE) | 将上游 `mech.html` 重命名为 `index.html`，未修改游戏逻辑 |
| Last Beacon · 最后的灯塔 | [stackloomdev](https://github.com/stackloomdev) · [提交 `102ca4c`](https://github.com/stackloomdev/last-beacon/tree/102ca4cfca542f9cca7a6020b12e20db78ac0003) | [创作记录](https://github.com/stackloomdev/last-beacon/blob/102ca4cfca542f9cca7a6020b12e20db78ac0003/docs/CREATION.md)明确记录 GPT-6 Astra 参与 | [MIT](../games/last-beacon/LICENSE) | 使用上游无依赖构建脚本生成单文件版，重命名为 `index.html` 并清理两处行尾空格 |
| THUNDERFALL · 雷霆战机 | [jackroc](https://github.com/jackroc) · [固定来源 `bcdb799`](https://github.com/MartinDelophy/awesome-gpt-6-astra/tree/bcdb79927e80a50164d1145574523bf64ead0485/works/thunderfall) | [结构化创作记录](https://github.com/MartinDelophy/awesome-gpt-6-astra/blob/bcdb79927e80a50164d1145574523bf64ead0485/works/thunderfall/metadata.json)记录 GPT-6 Astra ultra 的参与范围 | [CC0-1.0](../games/thunderfall/LICENSE) | 复制上游构建脚本列出的 9 个静态运行文件，未修改游戏逻辑 |

收录日期：2026-09-08。

## 社区来源

以下项目来自社区帖子或开源目录，但没有复制到本仓库：

| 游戏 | 社区出处 | 开源项目 | 在线体验 | 处理方式 |
| --- | --- | --- | --- | --- |
| Little Flock · 小羊慢慢 | [作者原帖](https://x.com/songkeys/status/2097231024375935286) | [songkeys/little-flock @ `eaaa561`](https://github.com/songkeys/little-flock/tree/eaaa56184ad8f1b513ae81960075846663803886) · MIT 代码 / CC BY 4.0 素材 | [sharpherd.song.work](https://sharpherd.song.work) | 项目包含 Go 后端、账号和多人同步，因此不制作不完整静态镜像 |

## 核验原则

- 来源声明只能证明作者公开声称使用了 GPT-6，不等于本仓库独立验证了模型运行记录。
- 每个第三方游戏保留自己的许可证；许可证不自动适用于本仓库其他内容。
- 固定提交用于复核本次收录版本，上游后续更新不会自动同步。
- 发现署名、许可证或素材权利问题时，应先停止分发对应目录并联系原作者核实。
