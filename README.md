# William Portfolio

William（郭泽宇）的个人作品集网站。

**在线访问：** https://william-1219.github.io/william-portfolio/

当前网站版本：**v3.32**。

## 网站内容

- 星空主页与交互工牌 About Me
- 交互设计、工业设计、IP 设计、AIGC 探索
- 能力展示与联系方式
- 项目内目录及跨项目切换

## 发布文件

本仓库保存网站运行产物，不包含本地完整 React/Vite 源码归档。

完整生产包按字节拆为 20 MiB 的分卷：`site.zip.part-001` 至 `site.zip.part-007`；`site.zip.sha256` 是重组后 `site.zip` 的 SHA256 校验文件。

GitHub Actions 会按文件名顺序合并这些分卷，验证 SHA256，再解压并部署 GitHub Pages，公开网址保持不变。若分卷不存在，则兼容此前单文件 `site.zip` 的发布方式。

后续更新需同时替换全部分卷及校验文件；如果新版本分卷数量减少，需删除多余旧分卷，避免它们被误合并。

分卷与完整 ZIP 均只包含浏览器运行所需的 HTML、JS、CSS、图片、字体和视频等文件，不包含源码 ZIP、node_modules 或私密配置。
