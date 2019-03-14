# GIES 后端
                        ---Geely Intelligent Efficiency System，吉利IE系统
## 一,模块介绍
  GIES系统内部进行分模块服务化架构，切分成系统管理（BS）、基础工时（ST）、工艺工时（TT）、基础数据（MD）、效率分析（KZ）、效率报表（RF）等模块

## 二,包名规范
  1. 模型  com.geely.gies.{模块名称}.model
  2. DAO接口 com.geely.gies.{模块名称}.dao
  3. 控制层 com.geely.gies.{模块名称}.controller
  4. 模块私有服务类 com.geely.gies.{模块名称}.service(公共service放到service模块)
  5. 服务实现类 com.geely.gies.{模块名称}.service.serviceImpl
 
## 三,启动方式
  1.在gies_web模块使用spring-boot插件启动
  
 ![启动方式](http://image.baidu.com/search/detail?z=0&word=%E4%BA%91%E5%B1%B1%E8%99%8E%E5%BD%B1&hs=0&pn=1&spn=0&di=0&pi=60576504324&tn=baiduimagedetail&is=0%2C0&ie=utf-8&oe=utf-8&cs=2259211748%2C1161934985&os=&simid=&adpicid=0&lpn=0&fm=&sme=&cg=&bdtype=-1&oriquery=&objurl=http%3A%2F%2Fe.hiphotos.baidu.com%2Fimage%2Fpic%2Fitem%2Ffc1f4134970a304e210531d0dfc8a786c9175cf0.jpg&fromurl=&gsm=0&catename=pcindexhot&islist=&querylist=)

