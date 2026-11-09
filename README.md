# William · Personal Portfolio

郭泽宇 / William 的个人作品集网站。

在线访问：https://william-1219.github.io/william-portfolio/

本仓库通过 `site.zip` 保存已构建的静态网站，包含首页、作品、About Me 工牌交互及联系方式。GitHub Actions 解压该文件，并部署到 GitHub Pages。

## 更新方式

在本地 React + Vite 项目完成修改后运行 `npm run build`，把 `dist/` 里面的全部文件压缩为 `site.zip`，然后替换仓库根目录中的同名文件并提交到 `main` 分支，即会触发自动发布。

压缩包根目录应直接包含 `index.html`、`assets/`、`fonts/`、`licenses/` 和 `.nojekyll`，不要多包一层 `dist/` 文件夹。可在仓库的 Actions 页面查看发布结果，也可手动运行部署工作流。

第三方组件和字体的许可信息保留在发布包的 `licenses/`、`fonts/` 中。
