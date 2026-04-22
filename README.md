# 🥩 食物碳足迹计算器

不讨好 · 只算真账

## 在线演示

访问 [GitHub Pages](https://YOUR_USERNAME.github.io/carbon-footprint-calculator/) 立即使用。

## 功能特点

- 🥩 **12 种食物类型** - 从牛肉到苹果，覆盖常见食材
- 🌍 **真实碳数据** - 基于 Poore & Nemecek (2018) 等研究
- 💬 **说真话模式** - 不美化，直接告诉你食物对环境的影响
- 🚗 **等量换算** - 碳排放换算成开车公里数、手机充电次数

## 本地运行

```bash
# 方法 1: 直接打开
open index.html

# 方法 2: 使用 Python 内置服务器
python3 -m http.server 8000

# 方法 3: 使用 Node.js live-server
npx live-server
```

## 部署到 GitHub Pages

1. Fork 或上传此仓库到你的 GitHub
2. 进入仓库 Settings → Pages
3. Source 选择 `gh-pages` 分支
4. 访问 `https://YOUR_USERNAME.github.io/carbon-footprint-calculator/`

或使用 GitHub Actions 自动部署：

```bash
git checkout -b gh-pages
git commit --allow-empty -m "Initial gh-pages commit"
git push origin gh-pages
```

## 数据来源

排放因子基于:
- Poore, J., & Nemecek, T. (2018). Reducing food's environmental impacts through producers and consumers. *Science*, 360(6392), 987-992.
- 其他生命周期评估 (LCA) 研究数据

单位：kg CO₂e / kg 食物（全生命周期）

## 许可证

MIT License - 详见 [LICENSE](LICENSE)
