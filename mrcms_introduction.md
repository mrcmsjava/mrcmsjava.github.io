# MRCMS 简介

mrcms是一款基于Java语言开发的内容管理系统，采用自定义的模板化语言解决快速建站问题。

# MRCMS dsadsa 

>  MRCMS 是一款开源免费的内容管理系统。系统采用Spring为核心，支持页面静态化、页面国际化、文件上传、富文本编辑、Markdown、SEO优化、站内统计、主题、前后端分离、插件等功能。

### 技术设计如下：
* 【持久层】Spring Data作为数据访问接口。
* 【表现层】采用SpringMVC实现了视图与数据分离，并集成freemarker、FastJson。
* 【Web前端】HTML5、CSS3、Ajax、JQuery、UEditor、Echart、Handlebars、fontawesome、Bootstrap等三方插件。
* 【性能优化】采用EHCache作为数据高速缓存，使用Druid作为数据库连接池，多线程处理技术，提高系统响应性能。
* 【扩展性】采用与Java无缝集成Groovy动态脚本语言实现动态添加，分发器、过滤器、标签、内容模型等模块。
* 【安全性】集成了各种加密技术MD5、Base64、DES等、利用Spring AOP功能拦截用户后台登录，Session生命周期30分钟，防范Cookies欺骗，防范XSS攻击。

### 【边缘技术】
URL规则引擎、跨平台、 Nginx集成、纯真IP数据库、ansj(中文分词)、模块热部署、FileUpload、主题等等

### 开源中国

http://www.oschina.net/p/mrcms