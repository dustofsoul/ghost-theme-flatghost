# FlatGhost v0.3.0
一个响应式设计的扁平化 ghost 博客主题，主题预览：[blog.imzhengfei.com](https://blog.imzhengfei.com)

**仅支持 Ghost v1.x**


## Installing

1. 前往 [release](https://github.com/imzhengfei/ghost-theme-flatghost/releases) 页面下载最新版 zip 安装包。
2.修改源码中关于disque和社交媒体链接的部分
3. 登录 ghsot 博客管理后台或者打开 ghost 桌面 app 进入管理，在 `SETTINGS > Design > Themes > Upload a theme` 上传主题 zip 安装包并 `Active now` 启用主题，点右上角 `Save` 保存。
4. 前往 `Labs > Enable Beta Features` ，勾选 `Public API` ，点右上角 `Save` 保存。

## Features

*   扁平化响应式设计，移动设备采用安卓风格侧滑菜单（仿 Ionic 3 on Android）；
*   支持代码语法高亮显示（via Prism）；
*   智能 SEO，自动给所有页面添加 `title`、`keywords`、`description`  标签；
*   侧边栏多种小工具支持（推荐文章，标签云，博客统计）；
*   额外的社会化链接图标：GitHub、知乎、微博（需手动在主题文件中修改链接）。

## Planning

-   [x] 响应式设计
-   [x] 代码高亮显示
-   [ ] 重新设计分页
-   [ ] 主题切换颜色
-   [ ] 文章大纲小工具
-   [ ] 独立的文章时间轴页面

## Thx

* [neat.css](https://github.com/thx/cube) ：全新的样式重置方案。

* [prism](https://github.com/PrismJS/prism) ：代码高亮显示。

## License

MIT

