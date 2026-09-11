# 新作品收录说明

这个仓库用于整理通过 GPT-6 创作的网页游戏与互动体验，尤其关注手机浏览器里的直接体验。

## 推荐目录

根据作品类型选择目录：

```text
games/<slug>/ 或 experiences/<slug>/
├── README.md
├── index.html
└── assets/
```

有目标、规则或胜负条件的游戏使用 `games/`；以探索、观赏和交互为主的作品使用 `experiences/`。

如果作品是单文件 HTML，可以不创建 `assets/`。

## README 内容

每个作品的 `README.md` 建议包含：

- 作品名称：中文名和英文名都可以写。
- 简短介绍：一句话说明核心体验。
- 操作：列出触屏、键盘、鼠标操作。
- 运行方式：说明直接打开 HTML、通过本地服务器或 GitHub Pages 访问。
- 技术栈：例如 HTML、Canvas、Three.js、WebGL、Web Audio。
- 兼容性：说明手机端、桌面端、网络依赖或性能要求。
- 创作备注：记录提示词方向、生成方式或人工修改点，不放隐私和密钥。
- 来源信息：作者、原始仓库、固定提交、GPT-6 创作依据和许可证。

## 质量检查

提交前建议确认：

- `index.html` 可以在 Chrome 或 Safari 中打开。
- 手机端首屏没有明显遮挡，核心按钮可点击。
- 触摸操作不会触发浏览器页面滚动或误操作。
- 外部 CDN、图片或音频链接是公开可访问的。
- 没有 `.env`、token、cookie、私钥、账号信息等敏感内容。
- 文件名使用小写英文、数字和连字符，例如 `bottled-ocean`。
- 第三方代码的许可证允许再分发，且许可证正文已随作品保留。

## 第三方作品

- 公开可见不等于开源；没有明确许可证的项目只可链接，不复制源码。
- 优先固定到完整提交哈希，避免来源内容变化后无法复核。
- 不删除原作者的版权声明、许可证或第三方素材归因。
- 如果对上游构建产物做了重命名、移除统计代码等调整，要在来源文档中逐项说明。
- 无法确认 GPT-6 参与依据、素材权利或运行安全时，不进入本地作品目录。

## 命名建议

- 游戏目录使用 `games/<english-slug>/`，互动体验使用 `experiences/<english-slug>/`。
- 入口文件固定为 `index.html`。
- 文档文件固定为 `README.md`。
- 多媒体素材放进作品目录内的 `assets/`。

## 发布到 GitHub Pages

如果仓库启用了 GitHub Pages，作品通常可以通过下面格式访问：

```text
https://<github-user>.github.io/<repo-name>/<category>/<slug>/
```

例如：

```text
https://yushangcl.github.io/awesome-gpt-6-creations/experiences/bottled-ocean/
```
