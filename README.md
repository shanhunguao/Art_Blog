# Art_Blog
&emsp;&emsp;基于Spring+SpringMVC+Mybatis架构的博客：**博客管理**、**图表数据**、**日志分析**、**访问记录**、**图库管理**、**资源管理**、**友链通知**等。良好的页面预加载，无限滚动加载，文章置顶，博主推荐等。提供 **<font color=#FF6347 size=2 >用户端+管理端</font>** 的整套系统源码。**<font color=#FF6347 size=2 >响应式设计，支持手机、平板、PC，都有良好的视觉效果！</font>**

### 最新版演示站点
[www.luotf.com](http://www.luotf.com/)   <br>
后台账号：luotf&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;密码:admin

### 技术栈
#### 后端

名称 | 描述 | 官网
---|--- |---
Spring Framework | 容器	| http://projects.spring.io/spring-framework/
SpringMVC | MVC框架	| http://docs.spring.io/spring/docs/current/spring-framework-reference/htmlsingle/#mvc
MyBatis | ORM框架 |  	http://www.mybatis.org/mybatis-3/zh/index.html
MyBatis Generator | 代码生成 | http://www.mybatis.org/generator/index.html
Apache Shiro | 安全框架 | http://shiro.apache.org/
PageHelper | MyBatis分页 | http://git.oschina.net/free/Mybatis_PageHelper
Maven | 项目构建管理 | http://maven.apache.org/
MySQL | 数据库 | https://www.mysql.com/
Tomcat 8.0 | 服务器 | http://tomcat.apache.org/


#### 前端

名称 | 描述 | 官网
---|--- |---
jQuery | 函数库 | http://jquery.com/
Bootstrap | 前端框架 | 	http://getbootstrap.com/
Bootstrap-table | 数据表格 | http://bootstrap-table.wenzhixin.net.cn/
echarts | 图表 | http://echarts.baidu.com/
web uploader | 图片上传 | http://fex.baidu.com/webuploader/
layui | 弹出层 | http://www.layui.com/
sweetalert | 弹出层 |http://mishengqiang.com/sweetalert/
highlight | 代码高亮 |https://highlightjs.org/
summernote | 富文本编辑 |https://summernote.org/
pace | 进度条 |https://github.hubspot.com/pace/
datapicker | 时间选择器 | https://jqueryui.com/datepicker/
Font-awesome | 字体图标 | http://fontawesome.io/
fancybox | 图片展示 |http://fancybox.net/
fakeLoader | 页面预加载 |https://www.awesomes.cn/repo/joaopereirawd/fakeloader-js
content | 菜单栏 
contabs | 选项卡

### 界面预览
#### <font color=#1E90FF size=3 >[ 首页 ]</font> 显示 置顶的博客，特别推荐，点击排行，最新博客等，无限滚动加载。
![首页](images/index.png)

#### <font color=#1E90FF size=3 >[ 列表页 ]</font> 显示某个类别的博客列表，关键字搜索，博客数量，专题等。
![列表页](images/list.png)

#### <font color=#1E90FF size=3 >[ 详情页 ]</font> 显示博客的具体内容，评论，推荐博客等。（截长屏 导致图片浮动元素 出现多次）
<html>
  <img src="https://github.com/luotf/Art_Blog/raw/master/images/info.png" width="590" div align=left height="750" alt="PC"/>
  <img src="https://github.com/luotf/Art_Blog/raw/master/images/mobile.png" width="240" div align=right height="426" alt="手机"/>
</html>
<br>

#### &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;移动端
<br><br><br><br><br><br><br>  <br><br><br>
<br><br><br><br><br><br><br>
<br><br><br><br><br><br>

---

#### <font color=#1E90FF size=3 >[ 后端首页 ]</font> 显示博客数，资源数，垃圾数，访客图表等。
![后台首页](images/后台首页.png)

#### <font color=#1E90FF size=3 >[ 博客管理 ]</font> 增/删/改/查博客，设置博客专栏等。
![博客管理](images/博客管理.jpg)

#### <font color=#1E90FF size=3 >[ 添加博客 ]</font> 封面图片可以直接选择服务器目录，也可以自己上传。富文本采用summernote，整合heightlight 实现代码高亮。提供发布前预览功能。
![添加博客](images/addBlog.png)

#### <font color=#1E90FF size=3 >[ 图表页 ]</font> 以图表的形式显示出博客的浏览量，网站访问量，发表量，日志数等。
![图表](images/图表.jpg)

#### <font color=#1E90FF size=3 >[ 操作日志 ]</font> 可以记录管理员的增删改查操作，可以记录下用户具体的查询内容等。
![操作日志](images/操作日志.jpg)

#### <font color=#1E90FF size=3 >[ 访问记录 ]</font> 获取用户的真实IP、地理位置、浏览器及操作系统等。 用户每天第一次登录将会被记录、一天内多次登录或清除cookie将不会被记录。
![访问记录](images/访问记录.jpg)

