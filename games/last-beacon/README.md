# Last Beacon · 最后的灯塔

一款中英双语的等距海岛塔防游戏。连接有限容量的电网，建造哨戒炮、迫击炮、寒潮塔和中继站，在十波机械生物的进攻中守住灯塔。

## 玩法

- 选择底部设施，再点击岛上的空基座建造。
- 已连接且电力容量足够的设施才会开火；出售中继站会重新计算下游供电。
- 战斗中可以升级、出售、扩容电网、切换双倍速并开启六秒超频。
- 手机端使用触摸操作；桌面端可用 `1` 至 `4` 选择设施，`Space` 开始或暂停波次。
- 游戏纪录只保存在当前浏览器，不需要登录或后端。

## 运行方式

直接打开 [index.html](index.html)，或通过静态服务器、GitHub Pages 访问。当前文件是上游构建生成的完整单文件版，没有 CDN、图片或音频依赖。

## 来源与许可

- 原作者：[stackloomdev](https://github.com/stackloomdev)
- 原始仓库：[stackloomdev/last-beacon](https://github.com/stackloomdev/last-beacon)
- 收录版本：[提交 `102ca4c`](https://github.com/stackloomdev/last-beacon/tree/102ca4cfca542f9cca7a6020b12e20db78ac0003)
- GPT-6 依据：[上游创作记录](https://github.com/stackloomdev/last-beacon/blob/102ca4cfca542f9cca7a6020b12e20db78ac0003/docs/CREATION.md)明确记录了 GPT-6 Astra 的参与范围。
- 许可证：[MIT License](LICENSE)，版权声明为 `Copyright (c) 2026 stackloomdev`。
- 本地调整：在固定提交运行上游 `npm run build`，将生成的 `dist/last-beacon.html` 重命名为 `index.html`，并清理两处行尾空格；游戏逻辑未修改。
