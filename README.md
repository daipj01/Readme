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
  
 ![启动方式](https://github.com/daipj01/Readme/blob/master/boot.jpg)

