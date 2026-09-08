# Awesome GPT-6 Games

收集主要通过手机端 GPT-6 创作、打磨，并适合手机浏览器体验的网页小游戏。

这个仓库记录在手机上使用 GPT-6 创建游戏的作品与方法：优先单文件 HTML、少依赖或 CDN 依赖、触屏友好、横竖屏都能浏览。

## 游戏列表

| 游戏 | 简介 | 入口 | 技术 |
| --- | --- | --- | --- |
| 瓶中沧海 · A Sea, Sealed | 封存在玻璃瓶中的 3D 海洋微缩景观，可环视、调节时间并呼唤风暴。 | [games/bottled-ocean](games/bottled-ocean/) | HTML / CSS / JavaScript / Three.js |

## 在线访问

如果仓库启用了 GitHub Pages，可以通过下面的路径访问游戏：

- `https://yushangcl.github.io/awesome-gpt-6-games/games/bottled-ocean/`

也可以在本地直接打开对应目录下的 `index.html`。

## 目录结构

```text
.
├── README.md
├── docs/
│   └── how-to-add-a-game.md
└── games/
    └── bottled-ocean/
        ├── README.md
        └── index.html
```

每个游戏放在 `games/<game-slug>/` 下，并至少包含：

- `index.html`：可运行的游戏入口。
- `README.md`：游戏说明、玩法、设备要求和创作备注。

## 收录原则

- 手机端优先：触摸操作清晰，按钮尺寸适合移动浏览器。
- 直接可玩：尽量不需要构建步骤，打开 HTML 即可体验。
- 文档齐全：每个游戏都写清楚玩法、依赖和兼容性说明。
- 内容安全：不要提交密钥、账号信息、私有接口或不可公开素材。

更多提交规范见 [docs/how-to-add-a-game.md](docs/how-to-add-a-game.md)。
