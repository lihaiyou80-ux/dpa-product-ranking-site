# DPA 商品榜单（严格素材版）

这是一个可直接部署到 GitHub Pages 的静态站点版本。

## 页面说明

- 仅保留素材 MD5 不为空的商品
- 每个商品都带有可直接打开的素材链接
- 图片素材直接展示原图
- 视频素材会自动从视频内容中挑选更贴近商品主体的代表画面作为商品图

## 本地文件

- `index.html`：GitHub Pages 默认首页入口
- `product_ranking.html`：同内容的独立页面文件
- `ranking_data.json`：榜单原始输出数据
- `.nojekyll`：避免 Pages 走 Jekyll 处理

## 发布方式

将本目录内容上传到 GitHub 仓库根目录，并在仓库的 Pages 设置中选择从默认分支根目录发布即可。
