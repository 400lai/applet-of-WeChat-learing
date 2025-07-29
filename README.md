# applet-of-WeChat-learing
项目+案例学习web前端微信小程序开发



项目结构：

```bash
applet-of-WeChat-learing/
├── README.md                        # 项目说明
├── app.js                           # 小程序入口文件
├── app.json                         # 小程序全局配置
├── app.wxss                         # 小程序全局样式
├── project.config.json              # 项目配置（微信开发者工具用）
├── project.private.config.json      # 私人项目配置
├── sitemap.json                     # 页面路径地图（SEO用）
├── .eslintrc.js                     # 代码风格配置
├── .gitignore                       # Git 忽略文件列表
|
├── components/                      # 公共组件
│   └── navigation-bar/             # 自定义导航栏组件
│       ├── navigation-bar.js
│       ├── navigation-bar.json
│       ├── navigation-bar.wxml
│       └── navigation-bar.wxss
|
├── pages/                           # 页面文件夹
│   ├── contact/                     # 联系人页
│   │   ├── contact.js
│   │   ├── contact.json
│   │   ├── contact.wxml
│   │   └── contact.wxss
│   ├── home/                        # 首页
│   │   ├── home.js
│   │   ├── home.json
│   │   ├── home.wxml
│   │   └── home.wxss
│   ├── message/                     # 消息页
│   │   ├── message.js
│   │   ├── message.json
│   │   ├── message.wxml
│   │   └── message.wxss
│   └── shoplist/                    # 店铺列表页
│       ├── shoplist.js
│       ├── shoplist.json
│       ├── shoplist.wxml
│       └── shoplist.wxss
|
|
├── images/                          # 图片资源（原文件夹）
│   ├── link-01.png
│   ├── link-02.png
│   └── tabs/                        # 底部标签图标
|
├── utils/                           # 工具函数/模块
│   ├── tools.wxs                    # WXS 脚本
│   └── util.js                      # 通用 JS 工具函数

```

