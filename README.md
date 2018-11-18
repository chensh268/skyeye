# skyeye

#### 项目介绍
win10风格的一套系统，刚开始开发，内容慢慢添加。</br>
##### 启动方式
在项目skyeye上右键选用maven-build，在Goals中输入命令tomcat7:run，启动完成后，访问http://localhost:8081即可。
#### 目前功能

- 菜单管理、用户管理、角色管理、角色绑定菜单管理、用户多角色管理
- 系统ICON管理（目前只支持系统内部样式icon）
- 代码生成器完成（只能适用于该框架的代码生成器，配置模板即可生成，然后下载压缩包解压复制到项目中即可。）
- 拖拽生成小程序静态版完成，可自定义配置小程序组件

#### 软件架构
软件架构说明

#### 技术选型
##### 后端技术:
技术|名称|官网
---|---|---
SpringMVC|MVC框架|http://docs.spring.io/spring/docs/current/spring-framework-reference/htmlsingle/#mvc
MyBatis|ORM框架|http://www.mybatis.org/mybatis-3/zh/index.html
Druid|数据库连接池|https://github.com/alibaba/druid
Maven|项目构建管理|http://maven.apache.org/
redis|key-value存储系统|https://redis.io/

##### 前端技术：
技术|名称|官网
---|---|---
jQuery|函式库|http://jquery.com/
zTree|树插件|http://www.treejs.cn/v3/
layui|模块化前端UI|https://www.layui.com/
winui|win10风格UI|http://win10ui.yuri2.cn/
codemirror|codemirror代码编辑器|https://codemirror.net/
handlebars|js模板引擎|http://www.ghostchina.com/introducing-the-handlebars-js-templating-engine/

#### 效果图
- 1.登陆效果图</br>
![登陆效果图](https://images.gitee.com/uploads/images/2018/1008/100922_8c9afcf1_1541735.png "微信截图_20181008100902.png")
- 2.系统icon</br>
![系统icon](https://images.gitee.com/uploads/images/2018/1018/085200_c2e72494_1541735.png "微信截图_20181018085136.png")
- 3.角色管理</br>
![角色管理](https://images.gitee.com/uploads/images/2018/1018/085328_123d813e_1541735.png "微信截图_20181018085305.png")
- 4.小程序组件配置</br>
![小程序组件配置](https://images.gitee.com/uploads/images/2018/1107/104615_286c0cf4_1541735.png "1.png")
- 5.小程序拖拽</br>
![小程序拖拽](https://images.gitee.com/uploads/images/2018/1107/104734_d9304e60_1541735.png "2.png")
- 5-1.小程序拖拽第一版</br>
![小程序拖拽](https://images.gitee.com/uploads/images/2018/1112/125615_8f51a2a6_1541735.gif "soogif1.gif")
- 6.代码生成器</br>
![代码生成器](https://images.gitee.com/uploads/images/2018/1107/104903_f244dfde_1541735.png "3.png")
- 7.桌面二级菜单展示</br>
![桌面二级菜单](https://images.gitee.com/uploads/images/2018/1107/104946_0b1ee5d2_1541735.png "4.png")
- 8.Redis数据实时监控</br>
![输入图片说明](https://images.gitee.com/uploads/images/2018/1118/191625_d7cb1a47_1541735.png "微信图片_20181118191506.png")
![输入图片说明](https://images.gitee.com/uploads/images/2018/1118/191634_497ea929_1541735.png "微信图片_20181118191516.png")
![输入图片说明](https://images.gitee.com/uploads/images/2018/1118/191641_fba2a593_1541735.png "微信图片_20181118191521.png")

#### 环境搭建
##### 开发工具:

- MySql: 数据库</br>
- Tomcat: 应用服务器</br>
- SVN|Git: 版本管理</br>
- Nginx: 反向代理服务器</br>
- Varnish: HTTP加速器</br>
- IntelliJ IDEA|Eclipse: 开发IDE</br>
- Navicat for MySQL: 数据库客户端</br>
- Redis Manager：redis视图工具</br>

#### 资源下载

- JDK7 http://www.oracle.com/technetwork/java/javase/downloads/java-archive-downloads-javase7-521261.html</br>
- Maven http://maven.apache.org/download.cgi</br>
- Redis https://redis.io/download</br>
- Nginx http://nginx.org/en/download.html</br>

#### 在线文档

- [JDK7英文文档](http://tool.oschina.net/apidocs/apidoc?api=jdk_7u4)</br>
- [Spring4.x文档](http://spring.oschina.mopaas.com/)</br>
- [Mybatis3官网](http://www.mybatis.org/mybatis-3/zh/index.html)</br>
- [Nginx中文文档](http://tool.oschina.net/apidocs/apidoc?api=nginx-zh)</br>
- [Git官网中文文档](https://git-scm.com/book/zh/v2)</br>