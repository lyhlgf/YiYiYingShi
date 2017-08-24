## 一一影视网站项目

项目采用nodejs和express作为服务端框架，ejs作为html模板，bootstrap模板作为前端框架
采用Webstorm开发，项目可直接在webstorm中打开

+ 目录：
    + bin: 项目启动脚本
    + public：public文件夹下存放静态文件，包括js，css和img等，相应的模板存储于git文件夹相同目录下，以zip包形式存储，可根据页面需求选用。模板的进入路径为：Unify-v1.9.5/HTML/index.html
    + routes: 控制器，为每个页面编写控制器，指定路由映射
    + views：使用ejs作为html模板，与后端交互
