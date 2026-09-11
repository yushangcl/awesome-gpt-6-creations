# Awesome GPT-6 Games

收集主要通过手机端 GPT-6 创作、打磨，并适合手机浏览器体验的网页小游戏。

这个仓库记录在手机上使用 GPT-6 创建游戏的作品与方法：优先单文件 HTML、少依赖或 CDN 依赖、触屏友好、横竖屏都能浏览。

## 游戏列表

| 游戏 | 简介 | 入口 | 来源 | 许可 |
| --- | --- | --- | --- | --- |
| 瓶中沧海 · A Sea, Sealed | 封存在玻璃瓶中的 3D 海洋微缩景观，可环视、调节时间并呼唤风暴。 | [开始体验](games/bottled-ocean/) | 仓库维护者提交 | 未单独声明 |
| 汴京入梦 · 千门长卷 | 以《清明上河图》为灵感的动态 3D 微缩汴京，可游览超长画卷并切换春昼、黄昏与灯火夜游。 | [开始体验](games/bianjing-living-scroll/) | 仓库维护者提交 | 未单独声明 |
| Iron Wilds | 驾驶重型机甲恢复中继站，在开放的 3D 盆地中迎战六台哨兵。 | [开始体验](games/iron-wilds/) | [TimelessP/mech](https://github.com/TimelessP/mech) | MIT |
| Last Beacon · 最后的灯塔 | 连接海岛电网、建造防御设施，在十波进攻中守住最后一束光。 | [开始体验](games/last-beacon/) | [stackloomdev/last-beacon](https://github.com/stackloomdev/last-beacon) | MIT |
| THUNDERFALL · 雷霆战机 | 支持触控的纵向弹幕射击游戏，包含三种战机、五关战役和四色武器。 | [开始体验](games/thunderfall/) | [awesome-gpt-6-astra](https://github.com/MartinDelophy/awesome-gpt-6-astra/tree/main/works/thunderfall) | CC0-1.0 |

## 在线访问

如果仓库启用了 GitHub Pages，可以通过下面的路径访问游戏：

- `https://yushangcl.github.io/awesome-gpt-6-games/games/bottled-ocean/`
- `https://yushangcl.github.io/awesome-gpt-6-games/games/bianjing-living-scroll/`
- `https://yushangcl.github.io/awesome-gpt-6-games/games/iron-wilds/`
- `https://yushangcl.github.io/awesome-gpt-6-games/games/last-beacon/`
- `https://yushangcl.github.io/awesome-gpt-6-games/games/thunderfall/`

也可以按各游戏 README 的说明本地运行；单文件作品可直接打开，使用 ES Modules 的作品需要静态服务器。

## 目录结构

```text
.
├── README.md
├── docs/
│   ├── how-to-add-a-game.md
│   └── sources.md
└── games/
    ├── bottled-ocean/
    ├── bianjing-living-scroll/
    ├── iron-wilds/
    ├── last-beacon/
    └── thunderfall/
```

每个游戏放在 `games/<game-slug>/` 下，并至少包含：

- `index.html`：可运行的游戏入口。
- `README.md`：游戏说明、玩法、设备要求和创作备注。
- `LICENSE`：第三方收录作品的原始许可证副本。

## 收录原则

- 手机端优先：触摸操作清晰，按钮尺寸适合移动浏览器。
- 直接可玩：尽量不需要构建步骤，打开 HTML 即可体验。
- 文档齐全：每个游戏都写清楚玩法、依赖和兼容性说明。
- 内容安全：不要提交密钥、账号信息、私有接口或不可公开素材。
- 来源透明：第三方作品标注作者、原始仓库、固定提交和许可证。

更多提交规范见 [新增游戏收录说明](docs/how-to-add-a-game.md)，完整归因见 [来源与许可证](docs/sources.md)。
