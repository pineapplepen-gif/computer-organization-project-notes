# 计算机组成原理项目作业网站

该目录是由 Obsidian 插件 **Webpage HTML Export 1.9.2** 导出的静态网站。

## 在线地址

https://pineapplepen-gif.github.io/computer-organization-project-notes/

GitHub 仓库：

https://github.com/pineapplepen-gif/computer-organization-project-notes

## 入口

- `index.html`：项目首页与导航
- `项目文档（批注版）.html`：项目总览
- `边缘设备实验方案.html`：Jetson Orin Nano 实验
- `gpu实验方案.html`：云 GPU 对照实验
- `site-lib/`：搜索、图谱、主题和站点资源
- `attachments/`：Jetson 官方 PDF 与中文硬件手册

网站不需要构建工具，可直接部署到 GitHub Pages。

## 更新方式

1. 在临时 Obsidian 库中更新笔记；
2. 用 Webpage HTML Export 重新导出；
3. 保留或重新添加 `index.html`、`.nojekyll`、`404.html`；
4. 提交并推送到 `main`，GitHub Pages 会自动构建。
