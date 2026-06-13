# 坦克大战 · Tank Battle

一个使用原生 HTML5 Canvas + JavaScript 实现的网页版坦克大战小游戏。

## 在线试玩

直接用浏览器打开 `index.html` 即可开始游戏。

## 操作说明

- **WASD / 方向键**：移动坦克
- **鼠标**：控制炮塔瞄准方向
- **鼠标左键 / 空格键**：发射炮弹

## 游戏规则

- 驾驶绿色坦克，消灭从四面八方刷新的红色敌方坦克。
- 击中敌人获得分数，每坚持一段时间进入下一波，敌人会越来越强、刷新越来越快。
- 被敌人炮弹击中或与敌人相撞会损失血量，生命耗尽则游戏结束。
- 场地中有障碍物，可以利用它们躲避敌人火力。

## 项目结构

```
.
├── index.html   # 游戏主文件（包含 HTML/CSS/JavaScript）
└── README.md    # 项目说明
```

## 本地运行

无需任何构建工具，双击 `index.html` 或用任意本地服务器打开即可：

```bash
# 例如使用 Python 的简单 HTTP 服务器
python -m http.server 8080
```

然后在浏览器访问 `http://localhost:8080`。

## 技术栈

- HTML5 Canvas
- 原生 JavaScript（无外部依赖）
- CSS3

## License

MIT
