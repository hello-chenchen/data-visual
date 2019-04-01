# 技术栈选型调研
  此文档用于记录针对本项目所选用的技术栈的一些调研和设计
## 目标用户
- 暂无

## 项目目标
  一套适用于多产业的大数据可视化系统

## 技术目标
- 扩展性强：需要能够兼容多产业数据结构和数据接口格式
- 可定制化：接口和前端组件名称尽量通用，可随业务变更而修改
- 维护性强：技术选型尽量选择文档齐全(最好是中文友好)，尽量选用大公司开源技术栈。编程语言对新手友好，尽量符合通用设计模式

## 硬件选型
- linux服务器
- 公网网络
- 无CDN

## 前端选型
- TODO: 多组件支持，针对不同行业
- https://echarts.baidu.com/ | https://github.com/apache/incubator-echarts
- http://antv.alipay.com/zh-cn/index.html | https://github.com/antvis/
- http://recharts.org/zh-CN/ | https://github.com/recharts/recharts

## 通信接口选型
- Rest接口(前后台交互, 微服务之间的交互)

## Server选型
- TODO: 是否支持负载均衡和请求分发 | https://blog.csdn.net/w05980598/article/details/79007194
- nginx 负载均衡和请求转发，待选
- tomcat servelt 服务器，做servelt的 request | parse | response

## 后端框架选型
- spring cloud(微服务架构,便于扩展和维护) | https://cloud.spring.io/spring-cloud-static/Greenwich.RELEASE/single/spring-cloud.html
- spring boot(自动化) TODO: 自动化编译和部署工具 gradle(配置看上去更简单,用户友好度比maven高) | https://docs.spring.io/spring-boot/docs/2.1.3.RELEASE/reference/htmlsingle/
- spring framework(后端rest接口) | https://docs.spring.io/spring/docs/5.1.6.RELEASE/spring-framework-reference/core.html#beans-introduction
- Mybatis(持久化层) https://www.jianshu.com/p/687de634c8f0 | https://blog.csdn.net/q283614346/article/details/83119757

## 数据库选型
- TODO: 更多是数据供应商提供，需要支持的数据库类型
- 支持列表：mysql

## 相关文档
https://zh.wikipedia.org/wiki/%E6%95%B0%E6%8D%AE%E5%8F%AF%E8%A7%86%E5%8C%96
https://help.aliyun.com/document_detail/30360.html?spm=a2c4g.11186623.6.542.4c761bdbvd1QZ2
https://www.zhihu.com/question/49749071
https://www.zhihu.com/question/26685414
https://www.zhihu.com/question/19929609
https://www.douban.com/group/topic/90518068/
