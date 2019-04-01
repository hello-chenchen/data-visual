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
- Rest接口

## Server选型
- TODO: 是否支持负载均衡和请求分发
- nginx 负载均衡和请求转发，待选
- tomcat servelt 服务器，做servelt的 request | parse | response
- TODO: 是否采用微服务架构

## 后端框架选型
- spring boot(视图层和业务层) TODO: 自动化编译和部署工具 maven or gradle
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
