#这是一个个人网站。

##网站简介：

  该网站主要由“诗词曲”，“短篇小说”，“长篇小说”三大功能构成。用户可以发表作品，下载作品，也有回复/收藏/点赞/搜索功能。
  希望能建一个能培养大家文学素养的网站。
  
##网站项目结构：
 
  /controllers/:     中间件目录（主要业务逻辑目录--C层）
  /models/:          存储数据和数据交互目录
  /views/:           前端页面目录
  /public/:          静态文件存放目录
  / proxys/:         数据库代理目录
  /test/:            测试目录
  /node_modules/:    node依赖目录
  /common/:          扩展目录
  
  
  web_route.js:      路由配置
  RENAME.md:         项目介绍
  app.js:            项目入口文件
  package.json:      npm项目依赖
  config.js:         项目配置文件
