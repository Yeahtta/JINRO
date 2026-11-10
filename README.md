# JINRO · Fill The Moment — GitHub Pages 部署专用

这是**无需任何外部图片路径**的单文件版本。图片都嵌入 `index.html`，因此 GitHub Pages 上不会再因为 `assets/` 目录缺失而出现破图。

## 如何发布

1. 进入你的 GitHub 仓库。
2. 把本包的 `index.html` 上传到你选定的 Pages 发布目录（最简单为仓库根目录），替换原来的 `index.html`。
3. 在 Settings → Pages → Build and deployment 选择 `Deploy from a branch`，Branch 选择 `main`，Folder 选择 `/(root)`，然后 Save。（如果你已有其他分支/目录的 Pages 配置，则文件要上传到实际发布目录。）
4. 等 GitHub 完成部署后访问 Pages 链接，并使用强制刷新 Ctrl+Shift+R / Cmd+Shift+R 避免旧页面缓存。

注意：**不要把 ZIP 文件原封不动上传到仓库根目录当作网页**，应当先解压，把 `index.html` 放在正确位置。可以同时上传 `.nojekyll`，避免 Jekyll 的处理。

## 仍可使用的交互

- 主页三张专区入口：#FillTheMoment 话题 / What's Your Moment? H5 / 真露旗舰店
- 话题页左上角箭头直接返回三区主页，无额外搜索弹窗
- 活动 H5 与许愿池同页连续滚动、活动规则、模拟发布积分
- 旗舰店商品详情与模拟购物车

## 说明

这是一份内部演示用的互动营销原型。页面内容中的平台数据、活动日期、商品价格、积分和奖品仅为演示，不代表真实官方运营活动。
