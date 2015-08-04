title: "自定义详情页前端简易开发说明"
date: "2015-08-03 18:17:16"
---

对于未用过NodeJs的普通开发者我们准备了简易的开发流程说明。


### 目录结构

请务必按照以下目录结构来进行开发：

```text
├── css                         //样式表目录
│   └── style-promo.css
├── html                        //HTML目录
│   └── index.html
├── js                          //js目录
│   └── index.js
└── img                         //图片目录
    └── bg.png
```

> 目录中文件请保证只存在html、js、css和常用图片格式的文件，不得包含其他类型的文件。
> 请注意检查是否含有.svn/.git/.DS_Store/Thumbs.db/.log 等隐藏系统文件，若存在需删除。

### 开发完成

**打包项目**

在本地开发完成后，请将您的项目在根目录打包成zip格式文件，交给我们的项目接口人。

> 请注意是根目录打包，不要包含上级目录，压缩包打开后里面是html、css、js、img的根级目录。
> 打包必须使用zip格式打包，请不要使用rar打包后修改拓展名来伪装zip格式！

**压缩包命名**

命名规则：YYYYMMDD-promo-品牌名称。
YYYYMMDD 为 4 位年份，2 位月份，2 位日期数字组成，品牌名称为全小写英文字母。