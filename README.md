# Game Theory Playground

交互博弈论小沙盒（静态网页）：
- 输入 payoff matrix
- 自动找 Pure Nash / Mixed Nash（小规模支持集枚举）
- IESDS 一步步删策略动画
- 学生风解释按钮（通俗讲解）

## 本地打开
直接打开 `index.html` 即可。

## 发布到 GitHub Pages（建议）
1. 新建 GitHub 仓库（例如 `game-theory-playground`）
2. 推送本目录代码到 `main`
3. 在仓库 Settings -> Pages 开启 GitHub Pages（Branch: `main`, folder: `/root`）

## 说明
IESDS 当前实现的是“被纯策略严格支配”的入门版；Mixed Nash 以小规模课堂案例为主，退化情形可能漏解。
