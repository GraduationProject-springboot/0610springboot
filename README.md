# [首页查询更多项目](https://github.com/GraduationProject-springboot) 包安装运行


# 0610springboot基于springboot框架的电影订票系统_wqc3k--论文

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1eMbYemE1U?p=106)


# 绪  论
## 1.1研究背景和意义
随着科学技术的不断发展，计算机现在已经成为了社会的必需品，人们通过网络可以获得海量的信息，这些信息可以和各行各业进行关联，电影订票系统也不例外，它给电影订票带来了更多的选择和便捷。

随着时代的发展和需求的不断提高，电影订票系统应对的数据量将越来越庞大，数据结构也会越来越复杂，因此本文所提出的电影订票系统具有实际意义，可提高效率，减少不必要的人力财力的损失，具有一定的现实意义。
## 1.2拟解决的问题及特性
面对高重复性机械性的工作，工作人员不可避免的会出现失误，而改正失误的成本也相当高。这些都为电影订票工作带来了新的问题[1]。从而急需开发一款这样的系统来解决这些问题，对高速发展的技术有着更强的适应性，只需要维护更新得当，大大的降低了人力成本。电影订票系统有以下几个特性：

（1）高自由度：电影订票系统是一种人性化设计的系统，可以根据用户的需要来添加不同功能的组件和界面，让电影订票系统更加的符合操作者的使用习惯，提供更多的便利功能。

（2）用户之间互动性强：电影订票系统的所有用户可以交流自己的心得。

（3）高检索率：传统管理信息检索也需要系统的支持，不过纸质载体的体积大，占地面积广，复原困难等问题，就算检索到了位置，也会出现找不到资源的情况，电影订票系统可以不受物理空间的限制，能储存的资料也没有空间的限制，大大的提高了资源搜索效率。

（4）节省资源：传统电影订票需要消耗大量人力对信息进行编辑管理，费人，费时，费力。而电影订票系统这些缺陷都没有，还节省了大量资源。极大地提高工作效率，可以精确查询和编辑各类信息，能更快、更好地满足了他们的需求。
## 1.3论文的结构
本文的主体结构如下：

第一章主要对当下的电影订票系统的背景及开发意义进行了重点论述。

第二章 重点介绍本系统的相关的开发技术，并对软件的部署环境进行必要的说明。

第三章 重点对系统进行需求分析、流程分析和可行性论述。

第四章 主要对系统整体功能进行设计和对数据库进行设计。

第五章 详细的对各个模块进行阐述，各个模块总体的设计以文字加图表的形式进行说明。

第六章 对系统的测试方法进行说明及测试结果的展示。
# 2 相关技术简介及部署环境说明
## 2.1 Java语言
Java是一种面向对象的静态式编程语言。Java编程语言具有多线程和对象定向的特点。其特点是根据方案的属性将方案分为几个不同的模块，这些模块是封闭的和多样化的，在申请过程中具有很强的独立性。Java语言在计算机软件开发过程中的运用可以达到交互操作的目的，通过各种形式的交换，可以有效地处理所需的数据，从而确保计算机软件开发的可控性和可见性。开发Java语言时，保留了网络接口，Java保留的缺省网络接口可以与web应用程序编程所依赖的类别库相匹配。为了使Java开发的应用程序更加稳定和强健，Java会自动收集程序中的垃圾，并处理程序中存在的异常。Java语言是日常开发过程中广泛使用的通用基本语言。其中Java语言课程库、句子、语法规则和关键字经常用于计算机软件的开发和编程。

面向对象编程是Java语言最显着的特点。它具有原始接口和补充接口以及继承，不仅可以实现相同类型的单个继承，而且还支持接口之间的多个继承，从而实现类、接口和接口之间以及类和接口之间的有效通信。Java的面向对象特性主要包括三个方面:继承、多态性和封装。封装是Java的核心，可以封装所有数据操作。多态性是指由面向对象行为派生的相关行为。继承作为特殊编程模式有两种类型:父类和子类，这两种类型的属性具有相同的功能和特性。对于父类的属性特性，子类可以实现继承和优化。
## 2.2 SpringBoot框架
Spring Boot是由Pivota公司的团队在Spring框架的基础上所开发出的一个轻量级应用框架，其设计目的是为了简化使用传统Spring框架开发时初始搭建、配置、开发、测试和部署等复杂的流程，满足快速、敏捷开发的需要[[49]。传统Spring框架开启某些特性或引入第三方依赖时，需要配置大量的XML文件，比较繁琐且非常容易出错。而SpringBoot的理念则是“约定大于配置”，它集成了大量第三方依赖的配置，再配合内部自动装配的机制，仅需在Maven工程的POM文件中添加相关依赖即可实现开箱即用的效果，这使得开发人员更加专注于实现业务逻辑，而不是繁琐的配置。此外，Spring Boot内置了S ervlet容器如Tomcat和Jetty，项目可以直接通过} ar命令在本地启动，无需打包成wa:文件再部署到服务器上，大大减少了测试和部署的成本。目前，Spring Boot己经成为了后端服务器应用开发的主流技术[[50]，其特点和优势总结如下:

(1)简化配置，遵循“约定大于配置”的理念，减少了样板代码、注释和XML配置文件的编写。

(2)内置Servlet容器，可在本地独立运行项目，方便测试和部署。

(3)自动装配，可以非常方便地与Spring生态系统中其他框架或第三方依赖集成。

(4)便于快速构建项目，尤其适合构建本系统。
## 2.3 MySQL简介
MySQL是一种关系型的数据库管理系统，属于Oracle旗下的产品。MySQL的语言是非结构化的，使用的用户可以在数据上进行工作。这个数据库管理系统一经问世就受到了社会的广泛关注。在各个方面，与同等的数据库相比，MySQL的优点极为突出，它的运行速度快，适用的范围广泛，而且数据库的安全性这一方面独树一帜。在语言结构方面，MySQL的语言简单，其他数据库需要一大段代码来实现的操作，MySQL仅需要一小部分代码甚至几行。综上所述，MySQL这种关系型数据库管理系统，已经成为了开发者进行项目的数据开发、存储的不二之选。MySQL的功能也多种多样，如数据操纵和数据库的建立维护等。而且该数据库的数据共享性高、冗余度低而且容易扩充。MySQL在安全性这一方面也具有自身的特点，它应用了用户的标识和鉴别技术，对试图和数据进行加密，确保资料信息的可靠性。介于数据库系统的功能与强大等性质之间，本数据库系统的设计中主要使用了MySQL实现对数据的处理。本系统运用MySQL数据库，在Web应用这一块，MySQL是最好的选择。对于该系统整个的开发、搭建、运行和维护具有极其重要的作用。
## 2.4 B/S结构
B/S结构就是指系统客户端与服务器分离，客户端通过浏览器访问服务端进行操作[10]。

B/S结构目前广泛应用于绝大部分系统搭建中，这种结构摒弃C/S结构客户端服务端不分离的缺点，具有更多的优势：

（1）跨平台性：B/S的标准由标准化组织确立，适用于绝大多数的系统搭建，通用于应用之间。

（2）低维护成本：客户端和服务器端分离，减轻了两端的压力，尤其是客户端，对客户端设备，硬件、软件要求都比较低，并且系统需要升级或维护时，只需要在服务器端升级或维护就可以，使相应的费用减少。
## 2.5 系统的开发环境
系统使用Java语言，以SPRINGBOOT作为框架进行开发，其所使用的硬件和软件环境如下：

硬件环境：Intel(R) Core(TM) i5-7300HQ CPU @ 2.50GHz 2.50 GHz 处理器，16.0GB 运行内存。

软件环境：Windows10 64位操作系统，TomCat服务器，IDEA开发工具。
## 2.6 小结
本章详细的介绍了开发电影订票系统所需要的技术与工具，工欲善其事必先利其器，对于技术和工具了解的越多越清晰，才会在开发过程中如鱼得水。


# 3 系统分析
## 3.1系统的可行性分析
电影订票系统的可行性分析基于当下的互联网背景，从经济、技术、法律和用户使用上进行了调查，从此验证次系统开发的可行性[6]。下面分别从以下几点进行分析:

1. 经济可行性分析：此系统所用的框架技术完全是开源的，其余的软件使用也都是免费的，在开发方面所消耗的成本可以忽略不计。而建立系统信息库所需的费用远远少于其带来的社会收益，从经济上分析系统是完全可行的。
1. 技术可行性分析：对系统进行分析，电影订票系统的大部分功能都需要管理员完成，系统只需要添加少量代码就可以很好适配管理员功能[7]。可以提高文件的复用率，提高效率。在数据库方面，ORM简化了表的创建和使用，采用了Oracle旗下开源的关系型数据管理系统MySQL，多表存储的特点使数据更加规范化，增删改查更容易[8]。综上所述，技术开发上并无太大的难点。
1. 用户使用可行性分析：鉴于系统的使用用户，有统一的账号和密码，且系统无需用户有过多的操作，界面清晰简洁，用户使用可行性上无问题。
1. 法律可行性分析：即分析本系统是否与各类法律相悖。本系统使用市面开源免费软件开发，且作为个人毕设，无商用，均为本人自主开发，并且页面设计合理，发布的信息要求符合常规。整个系统无抵触法律法规的问题。因此在法律上，本系统可行。
## 3.2系统需求分析
需求分析在系统开发中有着十分重要的作用[9]。软件项目凭借软件工程的思想和步骤可以大大的提高开发效率，缩短软件开发周期，保证了软件项目的质量。需求分析作为软件工程方法中的一步是至关重要的。软件需求工程是一门分析并记录软件需求的学科[10]。需求分析简单的来说就是用户需要什么，系统需要什么，对此进行问题的列举，等级的排列，需要缜密的思分析和大量的调研[11]。

电影订票系统在国内有很多值得借鉴的例子，功能也都趋于完善，因此此次电影订票系统将轻量化开发，要完成以下功能：

（1）要支持完整的用户注册，登录功能，账号的管理通过管理员来实现。

（2）电影订票系统的前端页面简单明了，功能让用户快速上手，一目了然，不需要教程也能直接使用。

（3）为了用户能够方便的搜寻信息。

（4）管理员通过后台系统来完成对电影订票信息的编辑，包括添加、删除等操作。
## 3.3开发目标
电影订票系统主要开发目标如下：

（1）对零碎化、分布散的电影订票信息进行收纳、整理，通过网络服务平台使这些信息内容更加调理，更加方便化和清晰化，让访问该系统的每个用户享受浏览的过程。

（2）生活中存在的一些现象：人员冗余。电影订票系统应尽量减少用户的需求压力，给他们提供省时省力省心的服务系统，降低其工作量。

（3）便于查询信息及管理信息等。

（4）通过计算机网络技术,提升解决管理问题和技术工作的质量，为用户一种规范方便的服务。

（5）该系统的面向用户为管理员和用户，系统的设计风格应该简约整洁，操作容易上手，目标信息明确，避免花里胡哨。

（6）为社会稳定和发展贡献一份力量。
## 3.4系统用例分析 
电影订票系统综合网络空间开发设计要求。目的是将电影订票系统将传统管理方式转换为在网上管理，完成电影订票的方便快捷、安全性高、交易规范做了保障，目标明确。电影订票系统可以将功能划分为管理员功能和用户功能。

（1）、管理员关键功能包含个人中心、用户管理、资讯类型管理、资讯信息管理、电影类型管理、电影信息管理、系统管理、订单管理等进行管理。管理员用例如下：

![](/md/blog.002.png)

图3-1 管理员用例图

（2）、用户关键功能包含首页、资讯信息、电影信息、公告信息、后台管理、在线咨询、个人中心等进行管理。用户用例如下：

![](/md/blog.003.png)

图3-2 用户用例图
## 3.5系统流程设计
### 3.5.1 用户登录流程
登录流程实现了管理员和用户的登录，在登录页面需要用户填写自己的信息，前端页面会将信息传递给后端接口，然后查询数据库确定该身份有效后登录成功，否则此用户登录失败，需要重新填写信息，进行再次验证，如图3-3所示。

![](/md/blog.004.png)

图3-3登录流程图
### 3.5.2 系统操作流程
系统操作流程分析是软件开发过程中的一个关键环节，它是整个系统整体的运行过程，必须保证其中的每一个步骤都是确定的，这样一个规范的流程图可以使开发者易于理解，快速的投入到接口开发中，从而提升系统开发效率。

同时，流程图还能减少开发者对系统操作流程产生歧义和降低沟通的成本，系统操作流程如图3-4所示。

![](/md/blog.005.png)

图3-4系统操作流程图
## 3.6小结
电影订票系统旨在让用户能够轻松便捷的管理系统信息，让管理员的工作负担减轻。本章主要对系统的经济、技术、法律、市场可行性进行分析。确认可行后，对电影订票系统进行了需求分析和流程分析，从用户和管理员角度思考了可能会有的需求，是后续论文和应用开发的基础指导。


# 4 系统总体设计
## 4.1系统功能结构设计图
系统采用了结构化开发的方法。这种开发方法的优点是控制性比较强，开发过程中采用了结构化和模块化的设计思想，自顶向下，从总体到部分，合理划分系统的结构和模块。结构化开发时使用模块式开发，各模块之间互不影响，方便系统的开发与管理。 系统总体功能如下图所示：

![](/md/blog.006.png)

图 4-1系统总体功能图
## 4.2 数据库设计与实现
在每一个系统中数据库有着非常重要的作用，数据库的设计得好将会增加系统的效率以及系统各逻辑功能的实现。所以数据库的设计我们要从系统的实际需要出发，才能使其更为完美的符合系统功能的实现。
### 4.2.1 概念模型设计
概念模型是对现实中的问题出现的事物的进行描述，ER图是由实体及其关系构成的图，通过E-R图可以清楚地描述系统涉及到的实体之间的相互关系。

电影信息实体图如图4-2所示：

![](/md/blog.007.png)

图4-2电影信息实体图

用户实体图如图4-3所示：

![](/md/blog.008.png)

图4-3用户实体图

公告信息实体图如图4-4所示：

![](/md/blog.009.png)

图4-4公告信息实体图

资讯信息实体图如图4-5所示：

![](/md/blog.010.png)

图4-5资讯信息实体图

订单实体图如图4-6所示：

![](/md/blog.011.png)

图4-6订单实体图
### 4.2.2 系统数据表设计
数据库表的设计通常是根据业务逻辑设置的。数据库模型在数据库中设计，并根据模型创建数据库表。数据库包涵了以下数据表来实现了对数据库的存储、调用。以下分别列出数据表的每个字段名称、类型、长度、字段说明、主键、默认值。

表4-1：用户

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yonghuzhanghao|varchar|200|用户账号|||
|mima|varchar|200|密码|||
|yonghuxingming|varchar|200|用户姓名|||
|xingbie|varchar|200|性别|||
|touxiang|longtext|4294967295|头像|||
|yonghudianhua|varchar|200|用户电话|||
|money|float||余额||0|

表4-2：资讯信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|zixunbianhao|varchar|200|资讯编号|||
|zixunbiaoti|varchar|200|资讯标题|||
|zixunleixing|varchar|200|资讯类型|||
|fengmian|longtext|4294967295|封面|||
|zixunjianjie|longtext|4294967295|资讯简介|||
|zixunxiangqing|longtext|4294967295|资讯详情|||
|fabushijian|date||发布时间|||


表4-3：配置文件

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|name|varchar|100|配置参数名称|||
|value|varchar|100|配置参数值|||

表4-4：用户表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|username|varchar|100|用户名|||
|password|varchar|100|密码|||
|role|varchar|100|角色||管理员|
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|

表4-5：资讯类型

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|zixunleixing|varchar|200|资讯类型|||

表4-6：在线咨询

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|userid|bigint||用户id|||
|adminid|bigint||管理员id|||
|ask|longtext|4294967295|提问|||
|reply|longtext|4294967295|回复|||
|isreply|int||是否回复|||

表4-7：token表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|userid|bigint||用户id|||
|username|varchar|100|用户名|||
|tablename|varchar|100|表名|||
|role|varchar|100|角色|||
|token|varchar|200|密码|||
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|
|expiratedtime|timestamp||过期时间||CURRENT\_TIMESTAMP|

表4-8：关于我们

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|title|varchar|200|标题|||
|subtitle|varchar|200|副标题|||
|content|longtext|4294967295|内容|||
|picture1|longtext|4294967295|图片1|||
|picture2|longtext|4294967295|图片2|||
|picture3|longtext|4294967295|图片3|||

表4-9：收藏表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|userid|bigint||用户id|||
|refid|bigint||商品id|||
|tablename|varchar|200|表名|||
|name|varchar|200|名称|||
|picture|longtext|4294967295|图片|||
|type|varchar|200|类型(1:收藏,21:赞,22:踩,31:竞拍参与,41:关注)||1|
|inteltype|varchar|200|推荐类型|||
|remark|varchar|200|备注|||

表4-10：订单

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|orderid|varchar|200|订单编号|||
|tablename|varchar|200|商品表名||dianyingxinxi|
|userid|bigint||用户id|||
|goodid|bigint||商品id|||
|goodname|varchar|200|商品名称|||
|picture|longtext|4294967295|商品图片|||
|buynumber|int||购买数量|||
|price|float||价格||0|
|discountprice|float||折扣价格||0|
|total|float||总价格||0|
|discounttotal|float||折扣总价格||0|
|type|int||支付类型||1|
|status|varchar|200|状态|||
|address|varchar|200|地址|||
|tel|varchar|200|电话|||
|consignee|varchar|200|收货人|||
|remark|varchar|200|备注|||
|logistics|longtext|4294967295|物流|||
|goodtype|varchar|200|商品类型|||

表4-11：公告信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|title|varchar|200|标题|||
|introduction|longtext|4294967295|简介|||
|picture|longtext|4294967295|图片|||
|content|longtext|4294967295|内容|||

表4-12：资讯信息评论表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|refid|bigint||关联表id|||
|userid|bigint||用户id|||
|avatarurl|longtext|4294967295|头像|||
|nickname|varchar|200|用户名|||
|content|longtext|4294967295|评论内容|||
|reply|longtext|4294967295|回复内容|||

表4-13：电影信息评论表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|refid|bigint||关联表id|||
|userid|bigint||用户id|||
|avatarurl|longtext|4294967295|头像|||
|nickname|varchar|200|用户名|||
|content|longtext|4294967295|评论内容|||
|reply|longtext|4294967295|回复内容|||

表4-14：电影信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|dianyingmingcheng|varchar|200|电影名称|||
|dianyingleixing|varchar|200|电影类型|||
|dianyingfengmian|longtext|4294967295|电影封面|||
|dianyingpiaoshu|int||电影票数|||
|dianyingpianduan|longtext|4294967295|电影片段|||
|dianyingdiqu|varchar|200|电影地区|||
|changci|varchar|200|场次|||
|dianyingyuyan|varchar|200|电影语言|||
|daoyan|varchar|200|导演|||
|zhuyan|longtext|4294967295|主演|||
|dianyingjianjie|longtext|4294967295|电影简介|||
|shangyingshijian|date||上映时间|||
|thumbsupnum|int||赞||0|
|crazilynum|int||踩||0|
|clicktime|datetime||最近点击时间|||
|clicknum|int||点击次数||0|
|price|float||价格|||
|number|int||座位总数|||
|selected|longtext|4294967295|已选座位[用,号隔开]|||

表4-15：电影类型

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|dianyingleixing|varchar|200|电影类型|||

## 4.3小结
本章刚开始总结了整个系统的总体功能，以树型图展示出来，使得看上去更加清晰明朗，而后介绍了每一个模型的属性和对数据库表的设计。


# 5 系统详细设计与实现
按照软件工程的流程来说，在系统的详细设计与实现阶段，要把模块、视图、模板进行相应的组合完成一个个所需的功能，此章将会把设计中模块一一说明如何设计和实现的。
## 5.1系统功能实现
当人们打开系统的网址后，首先看到的就是首页界面。在这里，人们能够看到系统的导航条，通过导航条导航进入各功能展示页面进行操作。系统首页界面如图5-1所示。                               

![](/md/blog.012.png)

图5-1 系统首页界面

用户注册：在用户注册页面的输入栏中输入用户注册信息进行注册操作，用户注册界面如图5-2所示：

![](/md/blog.013.png)

图5-2用户注册界面

资讯信息：在资讯信息页面通过输入资讯标题和选择资讯类型进行查询资讯详情信息，并根据需要对资讯详情信息进行评论或收藏操作；资讯信息详情界面如图5-3所示：

![](/md/blog.014.png)

图5-3资讯信息详情界面

电影信息：在电影信息页面通过输入电影名称、选择电影类型和价格进行查询电影详情信息，并根据需要对电影详情信息进行选座，立即预订，评论或收藏操作；电影信息详情界面如图5-4所示：

![](/md/blog.015.png)

图5-4电影信息详情界面

个人中心：在个人中心页面通过填写个人信息可以更新个人详细信息，还可以对我的订单和我的收藏进行详细操作。个人中心界面如图5-5所示：

![](/md/blog.016.png)

图5-5个人中心界面
## 5.2管理员模块实现
管理员登录，在登录页面正确输入用户名和密码，点击登录进入操作系统进行操作。管理员登录界面如图5-6所示：

![](/md/blog.017.png)

图5-6管理员登录界面

管理员进入主页面，主要功能包括对系统首页、个人中心、用户管理、资讯类型管理、资讯信息管理、电影类型管理、电影信息管理、系统管理、订单管理等进行操作。管理员主界面如图5-7所示：

![](/md/blog.018.png)

图5-7管理员主界面

管理员点击用户管理。在用户页面输入用户账号可以查询、新增或删除用户列表，并根据需要对用户详情信息进行详情、修改或删除操作。如图5-8所示：

![](/md/blog.019.png)

图5-8用户管理界面

管理员点击资讯信息管理。在资讯信息页面输入资讯标题和选择资讯类型可以查询、新增或删除资讯信息列表，并根据需要对资讯详情信息进行详情、修改、查看评论和删除等操作。如图5-9所示：

![](/md/blog.020.png)

图5-9资讯信息管理界面

管理员点击电影信息管理。在电影信息页面输入电影名称、选择电影类型和价格可以查询、新增或删除电影信息列表，并根据需要对电影详情信息进行详情、修改、查看评论或删除操作。如图5-10所示：

![](/md/blog.021.png)

图5-10电影信息管理界面

管理员点击系统管理。在公告信息页面输入标题可以查询、新增或删除公告信息列表，并根据需要对公告详情信息进行详情、修改或删除操作；还可以对在线咨询、关于我们、系统简介和轮播图管理进行详细操作。如图5-11所示：

![](/md/blog.022.png)

图5-11系统管理界面

管理员点击订单管理。在已完成订单页面输入订单编号和商品名称进行查询或删除已完成订单列表，并进行查看日销量、月销量、年销量、日销额、月销额和年销额并根据需要对已完成订单详情信息进行详情或删除操作；还可以对已发货订单、已支付订单、已取消订单和已退款订单等进行相应操作。如图5-12所示：

![](/md/blog.023.png)

图5-12订单管理界面
## 5.3小结
` 	`本章介绍了系统的各个模块和实现功能，对模块下的关键功能进行了介绍，并通过图片展示了实现效果。
# 










