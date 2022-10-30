
## 常用命令
- `hugo new site` SITE_NAME 生成静态博客项目
- `hugo server` 启动本地服务器，加上 -D 可以渲染 draft=true 的文章
- `hugo new post/new-content.md` 在 **post** 下新建一篇文章
- `hugo` 生成站点静态文件(public 和 resources 目录)
- `hugo list drafts/expired/future` 列出特点的文件

## 踩坑记
- 文章必须放在 content/**post**/ 目录下, 否则 Home 页不会展示文章链接, 文章内也不会展示目录

<!--more-->

## 参考链接
- [Hugo 从入门到会用](https://olowolo.com/post/hugo-quick-start)
- [Hugo 搭建博客实践](https://creaink.github.io/post/Devtools/Hugo/Hugo-intro.html)
- [Hugo 官方文档](https://gohugo.io/documentation/)

