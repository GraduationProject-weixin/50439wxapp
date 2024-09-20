# [首页查询更多项目](https://github.com/GraduationProject-weixin) 包安装运行


# 50439wxapp网上花店小程序

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1NvtMeFEiw?p=99)


# 第一章  课题背景及研究内容

## 1.1 课题背景
信息数据从传统到当代，是一直在变革当中，突如其来的互联网让传统的信息管理看到了革命性的曙光，因为传统信息管理从时效性，还是安全性，还是可操作性等各个方面来讲，遇到了互联网时代才发现能补上自古以来的短板，有效的提升管理的效率和业务水平。传统的管理模式，时间越久管理的内容越多，也需要更多的人来对数据进行整理，并且数据的汇总查询方面效率也是极其的低下，并且数据安全方面永远不会保证安全性能。结合数据内容管理的种种缺点，在互联网时代都可以得到有效的补充。结合先进的互联网技术，开发符合需求的软件，让数据内容管理不管是从录入的及时性，查看的及时性还是汇总分析的及时性，都能让正确率达到最高，管理更加的科学和便捷。本次开发的网上花店微信小程序实现了收货地址管理、购物车管理、客服聊天管理、字典表管理、论坛交流管理、公告信息管理、鲜花管理、鲜花收藏管理、鲜花评价管理、鲜花订单管理、用户管理、管理员管理等功能。系统用到了关系型数据库中王者MySQL作为系统的数据库，有效的对数据进行安全的存储，有效的备份，对数据可靠性方面得到了保证。并且程序也具备程序需求的所有功能，使得操作性还是安全性都大大提高，让网上花店微信小程序更能从理念走到现实，确确实实的让人们提升信息处理效率。
## 1.2 开发目的和意义
小康时代的到来，使得人们满意度上升，生活各个方面都产生了许多变化，比如办公都有相应软件，很多工作都要求员工会操作计算机，可以说现在的时代基本被软件覆盖得差不多了，软件行业的特征就是大家都在使用软件代替传统手工记载操作，软件的出现让我们的生活还有工作又向前翻了新篇章。网上花店微信小程序是一个利用软件形式管理鲜花信息的平台。管理员管理租车信息也不再需要用纸张进行信息记录及查询管理操作，所有的操作都是利用电脑进行办公，用户需要使用密码还有用户名进行系统登录操作，按照系统主页界面的各个功能展示进行相关操作，无论添加或者是删除，拟或是修改查询等操作，时间上不需要太多，短短几分钟就会搞定。况且软件是不限制办公地点以及办公时间的，只要有操作需要，随时随地登录系统就可以完成任务。办公效率提高这个不再是难题。公告租赁店对于租车信息的管理操作早就应该进行变革了，利用软件管理租车信息，节约人力物力成本，这是一个新的租车信息管理的创举。
## 1.3 论文研究内容
本次开发的网上花店微信小程序的论文从下面几个部分进行编写：

第一章：本章介绍了程序开发背景和目的意义，罗列出了论文写作内容信息，让我们知道论文编写是如何进展的。

第二章：本章主要讲解了系统开发用到的相关技术方面的知识，比如SSM技术，MySQL数据库知识等内容。帮助人们更好的理解系统技术上面的相关知识。

第三章：文章第3章主要介绍了系统开发的可行性问题，从经济，时间，操作等内容上面进行了大致介绍，确定系统开发确实可行，然后分析了系统的开发流程，确定系统需要具备的大概的功能，保障系统能够稳定使用和运行。

第四章：这个章节主要绘制出了系统功能架构，让我们更直观了解网上花店微信小程序的功能，对后台数据库表进行了设计，还画出了对应的Ｅ－Ｒ图。

第五章：这个章节主要介绍系统各个部分功能具体实现的界面效果。让我们了解到各个部分的功能详细情况。

第六章：这个部分主要就是对网上花店微信小程序进行整体测试，看看程序是否能够达到用户使用要求，程序能否进行验收上交操作。





# 第二章 相关技术

本次开发网上花店微信小程序使用的是微信小程序结构模式进行程序开发，网上花店微信小程序的数据信息选择MySQL数据库进行存放。

## 2.1 微信小程序介绍
`	`微信小程序英文名Wechat Mini Program，它是一种不用下载及安装就可以使用的应用程序，它完成了应用程序“近在咫尺”的心愿，用户可通过扫描或检索开启应用程序。

申请办理全面对外开放后，主要类型为企业发展、政府部门、新闻媒体、其他组织或者个人的开发者可以办注册小程序。微信小程序、订阅号、微信公众平台、小程序是平行面系统软件。

微信小程序是一种不用下载就可以使用的应用程序，也是一种自主创新。通过这两年的发展趋势，造就了一个新的微信小程序开发工具和开发者绿色生态。微信小程序都是中国IT行业多年来真真正正危害一般程序猿科技创新成果，有150多万元开发者添加微信小程序开发设计，共同推进微信小程序发展趋势，微信小程序运用数量达到100万，涵盖200好几个细分领域，日客户2亿，微信小程序还在很多城市适用地铁站、公交服务。微信小程序的高速发展带来了更多就业岗位，2017年微信小程序带动就业104数万人，社会效益不断提升。
## 2.2 MySQL数据库
MySQL是一种具有安全系数、安全系数、混合开发性、高效化等特征的轻量关联数据库智能管理系统。MySQL由C语言和C语言构成  由C语言和C语言撰写成的，由于C语言和C语言  这是混合开发的，因此MySQL源码是生命期的。MySQL提供多种多样数据种类，常见的数据种类包含[34]。伴随着数据库技术发展，MySQL逐步形成数据库管理方法的重要工具之一。它不仅能提供简单实用的操作作用，还能实现复杂多变的数据检索方法和查询记录导出方式。因为MySQL具有较好的兼容模式和扩展性，因而广泛应用于各行各业。

MySQL在WEB行业越来越受单位和个人开发者的亲睐。大部分大中小型网址都采用MySQL数据库，它不仅可以提供简单高效的数据浏览作用，还会对数据进行相应的剖析解决。因为Linux电脑操作系统和MySQL数据库全是开源系统免费体验，能够为公司节约许多费用，让很多企业使用Linux   MySQL做为网址数据库，体型小，启动速度快，也不会影响网址性能，导致用户体验感极差。

## 2.3 Java语言技术
Java语言已经存在了25年有余。通过这些年的发展趋势，it行业在市场占有率上仍然占据一半，仍然受到了很多程序员的工作钟爱。许多从业者都是在学习培训。近年来随着从业者的提高，Java语言的位置并没减少，算得上是常青藤。Java语言学习培训比较简单，自然，它是对于C前辈们的  而言的，C  语言非常强劲。Java取消了许多特点，如go这种描述，也取消了主文件，让所有文件夹全是类，类是二维数组以及各种对象，也使Java处理一些对象的引入和回收利用，让开发者只需建立对象，应用对象，编写代码逻辑，不需要留意性能，让各种各样文件存储给Java自己解决，你能花很多时间科学研究应用软件相互关系，使研发更为集中化，如同跑车驾驶员一样，只要了解各种汽车的性能，实际操作，不需要科学研究如何生产车轮子，使软件开发更为详尽。

## 2.4 Spring Boot框架
Spring Boot框架是一个SpringMVC架构的快速轻量快速框架，能够帮助开发人员迅速搭建靠谱高效率的应用程序。依据自动部署和协议书，改善了Spring的研究过程，使开发人员可以更加专注于领域模型。

Spring Boot有许多特性，当中最主要的是它提供了内置Tomcat、Jetty、Undertow等Web网络服务器能够轻松搭建Web应用程序。除此之外，它也提供自动部署、无需撰写XML文件等功能。这种功能使开发人员能够迅速建立和布署应用程序，而无需解决繁杂的环境变量和其它繁琐复杂每日任务。

开发系统时，Spring Boot能够帮助开发人员完成模块化设计和松耦合的代码结构，从而更好地日常维护拓展应用程序。除此之外，它也提供了很多常见的库和部件，如Spring Data、Spring Security等，能够轻松集成化这种部件，完成数据库操作、验证、受权等功能。



# 第三章 系统分析

## 3.1可行性分析
可行性分析从时间，经济以及操作和技术上面进行调查和研究，确保合理利用信息资源，避免在进行程序设计过程中因为考虑不周到所带来的困扰，帮助我们更好的进行程序设计。

3.1.1时长可行性

系统开发，预计2个月进行完成，从系统需求分析、结构与功能设计方案、作用总体设计和功能测试，2个月能完成程序流程开发操作，我计划早上和晚上进行程序编写操作，在这段时间还包含查看所有信息，再加上学生及老师的指导和引导，坚信程序流程开发时间能减少许多。因此时长是合理的。

3.1.2 经济发展可行性

网上花店小程序的开发平台是IDEA。数据库挑选MySQL数据库，应用浏览器全是大家电脑浏览器，能够下载最新版，不用收费标准。在系统开发的硬件选择时，我通过自己的笔记本电脑开发操作。因而，在开展系统开发时，不需要大量的经济开支。开发程序能够提升工作效率，产生相对较高的经济收益，系统开发的投入产出率相当可观。

3.1.3 操作可行性

网上花店小程序的页面设计较为简单，界面风格根据用户日常用户习惯来设计。网址的每一个作用在导航条里都清楚可见，页面的数据信息操作数据可视化。大家可以在不学习培训的情形下操作网址，只需遵照页面的作用提醒。

3.1.4 技术性可行性

作为一名电子计算机专业的同学，我在学校收获了很多有关程序编写的基础知识，例如SSM技术以及MySQL数据库。我就娴熟操作IDEA开发平台与MySQL数据库，所以对技术性有一定的掌握。

3.1.5 法律法规可行性

我开发的软件和信息来源全是公共图书馆、百度图书馆、百度网页，不属于违纪行为。在自己的毕业设计论文中，不论是源码或是毕业论文撰写具体内容，也没有剽窃个人行为。

从上述经济发展、运营时间分析，得到网上花店小程序开发的观点，系统开发能够创造更多的经济收益，越快开发发展潜力越多。
## 3.2系统流程分析
网上花店微信小程序的开发也是有对应的流程，开发之前必须要进行用户功能需求的分析，最后根据功能需求进行网站设计还有数据库相关数据的设计工作，此次开发的网上花店微信小程序开发流程如图3.1所示。

![](/md/blog.004.png)

图3.1 程序操作流程图

系统开发完成之后会给用户提供登录入口，在这个界面用户输入的信息会得到验证，通过验证之后才能进去网上花店微信小程序的访问主界面，系统登录执行流程如下：

![](/md/blog.005.png)

图3.2 系统执行流程图
## 3.3系统功能需求分析
系统的开发离不开前期的需求分析，这个阶段就是让程序员知道自己该做什么事情，在进行需求分析的时候，着重点就是用户对系统的功能要求，这个阶段要是分析得很到位，系统开发出来投入使用时，用户就会发现系统的功能跟用户需求保持一致，程序稳定性也是达标的，可以说需求分析是决定系统开发成败的关键，它主要就是把现实世界进行抽象化，然后把抽象化的对象用来构建模型。

网上花店微信小程序的受益群体主要是工作人员，该网站能够方便使用者进行数据信息的查找和管理工作，本次开发的网站我们设计的界面展示主要分为管理员界面以及用户界面，具体界面的功能分布如下。

网上花店微信小程序管理员可以管理用户的基本信息，可以管理公告信息，可以管理公告信息等。
## 3.4 系统非功能需求分析
（1）完整性需求

本次开发的网上花店微信小程序里面记录的数据信息不能保持为空，并且数据信息一定要核对正确才行，系统里面数据之间存在的联系不能出错，不能够张冠李戴，数据表里面同一数据在不同数据表里面的显示内容要一样。

（2）性能需求

用户在操作网上花店微信小程序的各个部分内容时，弹出的页面响应时间不能太长，最好控制在三秒钟以内，最大限制值就是四秒，这个是给用户一个好的程序体验。并且系统还要能够承载多人同时在线进行网上花店微信小程序的访问操作。

（3）界面需求

网上花店微信小程序界面设计上面应该考虑到用户日常操作习惯，比如导航栏的设计不能在右边，这个完全违背了用户使用网站的操作习惯，同时功能导航的字体以及颜色应该比较显眼，方便用户容易找寻，避免用户在进行功能操作上面浪费太多时间。

（4）安全性需求

网上花店微信小程序的安全性要有保证，给用户一种可靠，可以信赖的感觉，系统在运行过程中，不能总是出错，与用户进行功能界面交互时，要及时给出反馈信息，另外系统要设置登录窗口，让不是系统的用户不可以进行系统功能界面的访问操作。系统用户也要经过用户名密码的填写操作，才可以进入系统主界面，这样就可以保障系统数据信息处于一种安全状态。



# 第四章 系统设计

## 4.1 总体功能
网上花店微信小程序是根据需求定制开发，开发软件选用IDEA平台配合MySQL数据库进行开发环境的搭建操作，网站采用WEB应用程序中最流行的小程序结构进行开发，用户访问系统数据仅仅需要在客户端安装谷歌浏览器或者是当下常用浏览器就可以访问网站内容。
## ` `4.2 系统模块设计
网上花店微信小程序系统在进行系统中功能模块的划分时，采用层次图来进行表示。层次图具有树形结构，它能使用矩形框来描绘数据信息。顶层代表的数据结构很完整，顶层下面的矩形框表示的数据就是子集数据，当然处于最下面的矩形框就是不能再进行细分的数据元素了，使用层次方框图描述系统功能能让用户一目了然，能够明白系统的功能，以及对应功能板块下面的子功能都可以清楚领会。网上花店微信小程序分为管理员和用户两部分操作角色，下面将对他们的功能进行阐述。

管理员可以管理用户的基本信息，可以管理等功能。管理员功能结构图如下：

![结构设计图](/md/blog.006.jpeg "结构设计图")

图4.1 管理员功能结构图

## 4.3 数据库设计
### 4.3.1 数据库设计
数据库设计它是建立在数据库还有它对应的应用系统的一门技术，只要是信息系统开发还有系统建设，都会用到数据库设计，但是这个数据库设计并不是很简单就可以完成的，设计期间会遇到很多麻烦事，在设计期间需要考虑再考虑，逐步完善。主要内容也就是把数据库里面的对象还有对象之间的联系进行系统规划操作，还有把他们结构化的过程。
### 4.3.2 数据库E-R 图
E-R 图分成三部分内容，分别是实体，实体的属性以及实体之间的关系这三个部分的内容，通常长方形表示的就是实体，椭圆形表示的就是属性，菱形表示的就是关系了。在E-R 图里面，实体就是对象，比如学生，人，音乐等都能代表实体，实体都具备自己的成员，比如张三就是学生实体里面的成员。一个学生会具有自己的姓名，年龄，出生日期等信息，这些信息就是学生这个实体的属性，因此E-R 图属性代表的就是数据对象具备的属性，E-R 图的关系就是实体跟实体之间的关系了，比如学生跟课程会存在一定的关系，这种关系使用菱形进行表示。

（1）下图是客服聊天实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\客服聊天.jpg](/md/blog.007.jpeg "C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\客服聊天.jpg")
客服聊天实体属性图

（2）下图是用户实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\用户.jpg](/md/blog.008.jpeg "C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\用户.jpg")
用户实体属性图

（3）下图是鲜花评价实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\鲜花评价.jpg](/md/blog.009.jpeg "C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\鲜花评价.jpg")
鲜花评价实体属性图

（4）下图是鲜花订单实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\鲜花订单.jpg](/md/blog.010.jpeg "C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\鲜花订单.jpg")
鲜花订单实体属性图

（5）下图是公告信息实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\公告信息.jpg](/md/blog.011.jpeg "C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\公告信息.jpg")
公告信息实体属性图

（6）下图是字典表实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\字典表.jpg](/md/blog.012.jpeg "C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\字典表.jpg")
字典表实体属性图

（7）下图是鲜花实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\鲜花.jpg](/md/blog.013.jpeg "C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\鲜花.jpg")
鲜花实体属性图

（8）下图是鲜花收藏实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\鲜花收藏.jpg](/md/blog.014.jpeg "C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\鲜花收藏.jpg")
鲜花收藏实体属性图

（9）下图是论坛交流实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\论坛交流.jpg](/md/blog.015.jpeg "C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\论坛交流.jpg")
论坛交流实体属性图

（10）下图是购物车实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\购物车.jpg](/md/blog.016.jpeg "C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\购物车.jpg")
购物车实体属性图

（11）下图是收货地址实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\收货地址.jpg](/md/blog.017.jpeg "C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\收货地址.jpg")
收货地址实体属性图








### 4.3.3 数据库表设计
数据库里面的数据表存放的就是各种数据记录，我们在进行系统增删改查操作时，其实也是在对应数据表里面进行的增删改查操作，一个好的数据库能够缩短信息处理时间，所以说数据库的设计工作不容小觑，数据库里面设置哪些表，表里面的字段设计以及字段类型和字段长度等信息都要考虑周到才行，比如时间这个字段，它的数据类型就不能是int型，不然在系统操作中就会弹出输入数据格式不符合要求的报错提示。下面简单介绍网上花店微信小程序的一些数据表。

表4.1收货地址表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|创建用户|是|
|3|address\_name|String|收货人|是|
|4|address\_phone|String|电话|是|
|5|address\_dizhi|String|地址|是|
|6|isdefault\_types|Integer|是否默认地址|是|
|7|insert\_time|Date|添加时间|是|
|8|update\_time|Date|修改时间|是|
|9|create\_time|Date|创建时间|是|
表4.2购物车表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|所属用户|是|
|3|xianhua\_id|Integer|鲜花|是|
|4|buy\_number|Integer|购买数量|是|
|5|create\_time|Date|添加时间|是|
|6|update\_time|Date|更新时间|是|
|7|insert\_time|Date|创建时间|是|
表4.3客服聊天表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|提问用户|是|
|3|chat\_issue|String|问题|是|
|4|issue\_time|Date|问题时间|是|
|5|chat\_reply|String|回复|是|
|6|reply\_time|Date|回复时间|是|
|7|zhuangtai\_types|Integer|状态|是|
|8|chat\_types|Integer|数据类型|是|
|9|insert\_time|Date|创建时间|是|
表4.4字典表表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|dic\_code|String|字段|是|
|3|dic\_name|String|字段名|是|
|4|code\_index|Integer|编码|是|
|5|index\_name|String|编码名字|是|
|6|super\_id|Integer|父字段id|是|
|7|beizhu|String|备注|是|
|8|create\_time|Date|创建时间|是|
表4.5论坛交流表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|forum\_name|String|帖子标题|是|
|3|yonghu\_id|Integer|用户|是|
|4|users\_id|Integer|管理员|是|
|5|forum\_content|String|发布内容|是|
|6|super\_ids|Integer|父id|是|
|7|forum\_types|Integer|帖子类型|是|
|8|forum\_state\_types|Integer|帖子状态|是|
|9|insert\_time|Date|发帖时间|是|
|10|update\_time|Date|修改时间|是|
|11|create\_time|Date|创建时间|是|
表4.6公告信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|gonggao\_name|String|公告名称|是|
|3|gonggao\_photo|String|公告图片|是|
|4|gonggao\_types|Integer|公告类型|是|
|5|insert\_time|Date|发布时间|是|
|6|gonggao\_content|String|公告详情|是|
|7|create\_time|Date|创建时间|是|
表4.7鲜花表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|xianhua\_name|String|鲜花名称|是|
|3|xianhua\_uuid\_number|String|鲜花编号|是|
|4|xianhua\_photo|String|鲜花照片|是|
|5|xianhua\_huayu|String|花语|是|
|6|zan\_number|Integer|赞|是|
|7|cai\_number|Integer|踩|是|
|8|xianhua\_types|Integer|鲜花类型|是|
|9|xianhua\_kucun\_number|Integer|鲜花数量|是|
|10|xianhua\_old\_money|BigDecimal|鲜花原价|是|
|11|xianhua\_new\_money|BigDecimal|现价|是|
|12|xianhua\_clicknum|Integer|鲜花热度|是|
|13|xianhua\_content|String|鲜花介绍|是|
|14|shangxia\_types|Integer|是否上架|是|
|15|xianhua\_delete|Integer|逻辑删除|是|
|16|insert\_time|Date|录入时间|是|
|17|create\_time|Date|创建时间|是|
表4.8鲜花收藏表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|xianhua\_id|Integer|鲜花|是|
|3|yonghu\_id|Integer|用户|是|
|4|xianhua\_collection\_types|Integer|类型|是|
|5|insert\_time|Date|收藏时间|是|
|6|create\_time|Date|创建时间|是|
表4.9鲜花评价表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|xianhua\_id|Integer|鲜花|是|
|3|yonghu\_id|Integer|用户|是|
|4|xianhua\_commentback\_text|String|评价内容|是|
|5|insert\_time|Date|评价时间|是|
|6|reply\_text|String|回复内容|是|
|7|update\_time|Date|回复时间|是|
|8|create\_time|Date|创建时间|是|
表4.10鲜花订单表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|xianhua\_order\_uuid\_number|String|订单编号|是|
|3|address\_id|Integer|收货地址|是|
|4|xianhua\_id|Integer|鲜花|是|
|5|yonghu\_id|Integer|用户|是|
|6|buy\_number|Integer|购买数量|是|
|7|xianhua\_order\_true\_price|BigDecimal|实付价格|是|
|8|xianhua\_order\_courier\_name|String|派送人|是|
|9|xianhua\_order\_courier\_number|String|联系方式|是|
|10|xianhua\_order\_types|Integer|订单类型|是|
|11|xianhua\_order\_payment\_types|Integer|支付类型|是|
|12|insert\_time|Date|订单创建时间|是|
|13|create\_time|Date|创建时间|是|
表4.11用户表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_uuid\_number|String|用户编号|是|
|3|yonghu\_name|String|用户姓名|是|
|4|yonghu\_phone|String|用户号|是|
|5|yonghu\_id\_number|String|用户身份证号|是|
|6|yonghu\_photo|String|用户头像|是|
|7|yonghu\_email|String|用户邮箱|是|
|8|new\_money|BigDecimal|余额|是|
|9|jinyong\_types|Integer|账户状态|是|
|10|create\_time|Date|创建时间|是|
表4.12管理员表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|username|String|员工名|是|
|3|password|String|密码|是|
|4|role|String|角色|是|
|5|addtime|Date|新增时间|是|



# 第五章 系统实现

## 5.1 管理员功能模块的实现
### 5.1.1 鲜花列表
如图5.1显示的就是鲜花列表页面，此页面提供给管理员的功能有：查看鲜花、新增鲜花、修改鲜花、删除鲜花等。

![](/md/blog.018.png)

图5.1 鲜花列表页面
### 5.1.2 公告信息管理
管理员可以对公告信息进行管理，可以新增公告信息,修改公告信息,删除无效的公告信息。公告信息管理界面如图5.2所示。

![](/md/blog.019.png)

图5.2 公告信息管理页面
### 5.1.3 公告类型管理
公告类型管理页面显示所有公告类型，在此页面既可以让管理员添加新的公告信息类型，也能对已有的公告类型信息执行编辑更新，失效的公告类型信息也能让管理员快速删除。下图就是公告类型管理页面。公告类型管理界面如图5.3所示。

![](/md/blog.020.png)

图5.3公告类型管理界面
## 5.2 用户功能介绍
### 5.2.1 鲜花管理
如图5.4显示的就是鲜花管理页面，此页面提供给用户的功能有：查看鲜花。

![](/md/blog.021.png)

图5.4 鲜花管理页面
### 5.2.2 公告管理
如图5.5显示的就是公告管理页面，此页面提供给用户的功能有：查看公告。

![](/md/blog.022.png)

图5.5 公告管理页面











