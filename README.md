# ryo 的个人项目网站

在线访问：[https://ryoth13.github.io/](https://ryoth13.github.io/)

展示个人项目与软硬件实践，目前重点介绍 [Netmate](https://github.com/ryoth13/Netmate)。

## 文件说明

- `docs/index.html`：当前网站的页面、样式和少量脚本。
- `docs/.nojekyll`：使用纯静态方式发布。
- `LICENSE`：保留原 Fork 仓库的许可证记录。

## 更新网站

编辑 `docs/index.html` 并提交到 `main` 分支，GitHub Pages 会自动重新部署。

添加新项目时，复制页面中带有 `class="project"` 的 article 区块，再修改项目名称、介绍、链接与配置。文件内已标注新增项目的位置。

## 部署设置

GitHub 仓库 Settings → Pages：

- Source：Deploy from a branch
- Branch：`main`
- Folder：`/docs`

本网站无需构建、服务器或外部字体与脚本，可直接在浏览器打开 `docs/index.html` 进行预览。

## 仓库历史

此仓库最初 Fork 自 [GuangLun2000/GuangLun2000.github.io](https://github.com/GuangLun2000/GuangLun2000.github.io)。当前展示站点已独立重写，旧模板及无关内容已清理；原始记录仍可通过 Git 历史查看。
