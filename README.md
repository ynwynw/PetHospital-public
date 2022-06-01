**需要完整代码可以加qq   931708230 或者加微信   ynwwxid**

**需要完整代码可以加qq  931708230 或者加微信  ynwwxid**

后台访问地址http://localhost:8094/main.html

java基于springboot的宠物商城 Spring Boot+Mybatis+mysql+Thymeleaf+Shiro

### 使用的技术

本项目核心技术采用Spring Boot+Mybatis；开发工具idea；数据库MySQL5.6；模版引擎采用的是Thymeleaf；安全框架采用Shiro，实现了完整权限系统，Controller方法采用Shiro注解来实现有效的权限控制；前台界面采用了Bootstrap技术；后台界面采用了EasyUI技术；

### 功能介绍

> 本系统的详细功能需求如下所示

#### 未注册用户

非注册用户（即游客身份）进入医院官网首页，可以浏览关于医院的宣传以及医院发布的文章，进入医院商城浏览正在发售的商品，搜索已发布的文章和商品，注册以及登录。

#### 已注册用户

注册用户可以修改个人信息和宠物信息，发布预约单（预约医生和美容师），在医院的商城购物，收藏商品，给官方留言，查看与自己相关的记录信息，如：病例记录、预约记录、问诊记录、订单记录等，注销退出系统。

#### 业务管理员

业务管理员具有进货管理（包括进货入库、退货出库、进货单据查询、退货单据查询以及当前库存查询）、销售管理（包括销售出库、客户退货入库、销售单据查询、退货单据查询）、库存管理（包括商品报损、商品报溢、库存报警、报损报溢记录查询）、查看统计数据（供应商进退货单统计、客户进退货单统计、按日统计销售利润、按月统计销售利润）、供应商管理、客户管理、商品管理、期初库存管理、前台轮播图管理、设备类型管理、设备管理、设备使用管理、设备使用记录管理、文章类型管理、文章管理、客户留言管理、医院用品管理、医院用品出入库管理、医院用品出入库记录管理、客户消息管理、客户订单处理、客户预约单管理、客户问诊记录管理、病历单管理、化验记录管理、疫苗注射记录管理、客户回访记录管理、寄养记录管理、修改密码、安全退出系统。

#### 系统管理员

系统管理员除了具备业务管理员的所有权限外，还有创建角色并赋予角色权限的功能，还可以查看系统操作日志。

#### 系统自身

系统每天0点自动创建明天的分别属于各个医生或美容师各个时间段的空预约单（未被客户接受的预约单）、每分钟自动筛选出5分钟后过期的空预约单并从数据库删除、每分钟自动筛选和取消客户提交的超过一天未支付的订单并释放库存、每天凌晨1点自动将发布日期超过3个月的商品的"新品"标签去掉、医院上班后（8点）系统自动给当天有预约的客户发送提醒消息

### 图片展示

#### 前台

##### 首页

![img](https://image.zoutl.cn/hexo-blog/blogImage/20201017001151.jpg)

![img](https://image.zoutl.cn/hexo-blog/blogImage/20201017001236.jpg)

![img](https://image.zoutl.cn/hexo-blog/blogImage/20201017001310.jpg)

![img](https://image.zoutl.cn/hexo-blog/blogImage/20201017001352.jpg)

![img](https://image.zoutl.cn/hexo-blog/blogImage/20201017001428.jpg)

##### 客户登录界面

![img](https://image.zoutl.cn/hexo-blog/blogImage/20201017001525.jpg)

##### 客户注册页面

![img](https://image.zoutl.cn/hexo-blog/blogImage/20201017001613.jpg)

##### 医院商城首页

![img](https://image.zoutl.cn/hexo-blog/blogImage/20201017001654.jpg)

##### 查看商品详情

![img](https://image.zoutl.cn/hexo-blog/blogImage/20201017001744.jpg)

![img](https://image.zoutl.cn/hexo-blog/blogImage/20201017001853.jpg)

##### 查看已收货客户评论

![img](https://image.zoutl.cn/hexo-blog/blogImage/20201017001927.jpg)

##### 商品推荐和浏览记录

![img](https://image.zoutl.cn/hexo-blog/blogImage/20201017001959.jpg)

##### 购物车

![img](https://image.zoutl.cn/hexo-blog/blogImage/20201017002119.jpg)

##### 订单成功提交

![img](https://image.zoutl.cn/hexo-blog/blogImage/20201017002200.jpg)

##### 支付订单

![img](https://image.zoutl.cn/hexo-blog/blogImage/20201017002233.jpg)

##### 查看订单详情

![img](https://image.zoutl.cn/hexo-blog/blogImage/20201017002317.jpg)

##### 查看全部订单

![img](https://image.zoutl.cn/hexo-blog/blogImage/20201017002357.jpg)

##### 查看已收藏商品

![img](https://image.zoutl.cn/hexo-blog/blogImage/20201017002442.jpg)

##### 个人中心功能列表

![img](https://image.zoutl.cn/hexo-blog/blogImage/20201017002526.jpg)

##### 查看可预约医生

![img](https://image.zoutl.cn/hexo-blog/blogImage/20201017002628.jpg)

##### 预约医生

![img](https://image.zoutl.cn/hexo-blog/blogImage/20201017002654.jpg)

##### 按类别查看文章

![img](https://image.zoutl.cn/hexo-blog/blogImage/20201017002735.jpg)

##### 查看文章详情

![img](https://image.zoutl.cn/hexo-blog/blogImage/20201017002807.jpg)

##### 客户留言

![img](https://image.zoutl.cn/hexo-blog/blogImage/20201017002905.jpg)

#### 后台

##### 后台登录

![img](https://image.zoutl.cn/hexo-blog/blogImage/20201017003134.jpg)

##### 管理员功能介绍

![img](https://image.zoutl.cn/hexo-blog/blogImage/20201017003233.jpg)

![img](https://image.zoutl.cn/hexo-blog/blogImage/20201017003317.jpg)

![img](https://image.zoutl.cn/hexo-blog/blogImage/20201017003349.jpg)

#程序员 #java #毕业设计 #宠物交易领养系统 #springboot#课程设计#编程#vue#mybatis#源代码

### 基础环境 :IDEA，maven3.6+，JDK 1.8，  Mysql 5.7

### 源码+数据库脚本 

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

**需要完整代码可以加qq  931708230 或者加微信  ynwwxid**

**需要完整代码可以加qq  931708230 或者加微信  ynwwxid**
