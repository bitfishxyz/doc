1.  init环境的搭建
2. 
3. 分析user实体，一步步添加entity相关的注解
4. 编写接口层，分析接口之间的关系
5. 编写单元测试
6. 编写servlice层，引出相关设计
7. 编写单元此时
8. 开始我们的controler层，以及我们的api设计
9. 单元测试
10. 对实体进行参数校验，编写我们的valida
11. 对controller层进行校验


谈谈我们的模块化风

rest api设计
。。。

先写出来让打击用，一段时间之后在发布吧。。。

SpringMVC
SpringBoot。。


社区博客推荐？
github项目总结？
到底怎么做？
细节没有考录好。。。
项目摆在这里， 
卡顿的问题怎么解决？？

提前放出来的把。。。



编写plate实体

跳过service，直接写我们的control

用过参数校验的模板代码，引出我们的aop

开始使用自定义注解

功能测试



开始写我们article

主要是实体之间的关系，

复杂的查询，条件和分页。



大功告成

有很多优秀的教程了，复制黏贴也没有意思，

很多技术细节放在这里。了



## 广告时间
非战斗人员请迅速撤离

这个项目本生是基于GPL开源的一个经典的（或者说是烂大街的）社区论坛项目，
但同时我为这个项目编写一个精心制作的付费教程。

### 这个教程包含了下面内容

- 详细的SpringDataJPA的攻略
  
  讨论如何设计我们的实体，如何使用JPA进行查询操作，以及我们实体之间的关系
  

- 精心准备的git历史
  
  上面的项目是我一个人开发时使用的，所以commit记录有点凌乱。
  但是为了读者的学习，我又重新编写了一个Git厂库，每个commit代表一个
  功能模块，从中可以更好的掌握项目开发的逻辑
  
- 编写完整的测试用例
   
   好的项目离不开单元测试，这里我会和大家一起编写单元测试，为我们的项目保驾护航
   
- aop和反射技术的实际应用
  
   当初学aop的时候，只听讲师一顿猛吹aop技术有多么厉害，但是却发现自己实际项目
   中就是用不到。这里就和大家一起来看看实际项目中AOP是如何简化我们的代码的。


### 购买前的条件
- maven、lombok、junit的使用

- 基本的SpringBoot、SpringMVC知识

  项目是以这个两个技术为我们的基本盘的，但是这个教程的核心是上面提及的内容，
  所以我不会在这个方面做过多的赘述。
  当然这个项目只用到了简单的SpringBoot、SpringMVC知识，大家有点基础就行了

- 了解前后端分离的设计

  这个项目的最终产品是一个RESTful API的后端系统，前后端完全采取JSON格式来
  交流，所以这方面的知识大家要了解。

- 有一定的抽象能力，能够理解我这个的业务逻辑
  
  一定要先更正我之前的业务逻辑走一遍，这个很重要。不然就会发生我是谁，我在
  干什么的尴尬事情。
  
- 能写SpringDataJpa的hello world代码
  
  为了保证教程知识的精炼，请大家能先写一个hello world程序，需要能
  - 知道@Entity是干什么的
  - 使用过 repository.save(T t)方法
  - 见过@JpaRepository<T, S>这个接口
  
### 教程不包括哪些内容？
- 不包含前端内容

  github上已经有很多优秀的论坛前端项目了，大家有兴趣的话可以自行对接一下就行了。
  我自己之前尝试用vue来写，主要是用了vue就想用ts，就想写单元测试，就想写
  e2e测试，结果把自己陷进去了，浪费了很多精力也没写出来。
  而我自己又很排斥模板引擎这个东西。其实我也推荐后端开发的可以忽略这方面的内容
  
- 不包含邮箱验证系统

  一般来说，用户通过邮箱注册的时候还要发一个验证码来验证，但是这个就忽略
  
- 没有做字符转义处理

  一般来说，对于用户的输入需要做转义处理，但是这里就忽略了，因为这件事
  也可以交给前端来做。
  
- SpringDataJpa的技术细节非常复杂，这里只能涉及它的一个子集。

  不过笔者另外有两个开源项目，试图涵盖多数的SpringDataJPA的
  技术细节，大家在学完这个教程后可以考虑看下。

#### 如何购买？

1. 点击这个链接，系统会要求您使用github账号登录

2. 微信扫描二维码支付，价格是28元

3. 购买后，刷新页面

相关的教程都是放在github的私有仓库中的。购买后，后端系统会自动邀请您
加入相关的私有仓库，同时给出私有仓库的链接。

进入私有仓库后，大家可以
- 直接阅读（推荐octotree这个浏览器插件）
- clone到本地阅读（推荐typora这个软件）
- fork到自己的仓库。 
  
  如果打算fork到自己的厂库，请保持这个仓库为私有状态。
  
#### 其他问题
- 支持退款吗？
  
  目前不支持，如果您担心教程的质量，可以参考下我其他的博客。