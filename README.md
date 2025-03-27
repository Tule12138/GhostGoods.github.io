# 潦草的自用 README

## authentication

generated: SSH, Personal Access Token
using: SSH (device-github)
两种认证应当在部署的具体设置中设置不同格式的仓库地址。

## 文件

### config.yml

因为 theme 设置的原因，一个 yml 文件在 blog 下，另一个 yml 文件在 node 文件夹的主题文件夹中。（以下分别称为 main config 和 theme config）

#### main config

主要设置博客名称，部署设置，页面基础设置
目前是用 SSH，git@github.com 的 repo 地址
基于 gh-pages

#### theme config

更详细的页面设置。包括作者简介，文章分类，博客导航栏，友链，评论，主题色。

### package.json

需要正确列出 dependencies，更新信息后运行
`
npm install
`
