# 新游戏收录说明

这个仓库用于整理主要通过手机端 GPT-6 创作的网页小游戏，尤其关注手机浏览器里的试玩体验。

## 推荐目录

新增游戏时使用下面的结构：

```text
games/<game-slug>/
├── README.md
├── index.html
└── assets/
```

如果游戏是单文件 HTML，可以不创建 `assets/`。

## README 内容

每个游戏的 `README.md` 建议包含：

- 游戏名称：中文名和英文名都可以写。
- 简短介绍：一句话说明游戏体验。
- 玩法：列出触屏、键盘、鼠标操作。
- 运行方式：说明直接打开 HTML、通过本地服务器或 GitHub Pages 访问。
- 技术栈：例如 HTML、Canvas、Three.js、WebGL、Web Audio。
- 兼容性：说明手机端、桌面端、网络依赖或性能要求。
- 创作备注：记录提示词方向、生成方式或人工修改点，不放隐私和密钥。

## 质量检查

提交前建议确认：

- `index.html` 可以在 Chrome 或 Safari 中打开。
- 手机端首屏没有明显遮挡，核心按钮可点击。
- 触摸操作不会触发浏览器页面滚动或误操作。
- 外部 CDN、图片或音频链接是公开可访问的。
- 没有 `.env`、token、cookie、私钥、账号信息等敏感内容。
- 文件名使用小写英文、数字和连字符，例如 `bottled-ocean`。

## 命名建议

- 游戏目录使用稳定 slug：`games/<english-slug>/`。
- 入口文件固定为 `index.html`。
- 文档文件固定为 `README.md`。
- 多媒体素材放进游戏目录内的 `assets/`。

## 发布到 GitHub Pages

如果仓库启用了 GitHub Pages，游戏通常可以通过下面格式访问：

```text
https://<github-user>.github.io/<repo-name>/games/<game-slug>/
```

例如：

```text
https://yushangcl.github.io/awesome-gpt-6-games/games/bottled-ocean/
```
