#Java
	
	只做演示，需要修改
Java是一种可以撰写跨平台应用软件的面向对象的程序设计语言，是由Sun Microsystems公司于1995年5月推出的Java程序设计语言和Java平台（即JavaSE, JavaEE, JavaME）的总称。Java 技术具有卓越的通用性、高效性、平台移植性和安全性，广泛应用于个人PC、数据中心、游戏控制台、科学超级计算机、移动电话和互联网，同时拥有全球最大的开发者专业社群。在全球云计算和移动互联网的产业环境下，Java更具备了显著优势和广阔前景。

##开源项目

###Spring Framework【Java开源J2EE框架】

Spring是一个解决了许多在J2EE开发中常见的问题的强大框架。Spring提供了管理业务对象的一致方法并且鼓励了注入对接口编程而不是对类编程的良好习惯。Spring的架构基础是基于使用JavaBean属性的Inversion of Control容器。然而，这仅仅是完整图景中的一部分：Spring在使用IoC容器作为构建完关注所有架构层的完整解决方案方面是独一无二的。Spring提供了唯一的数据访问抽象，包括简单和有效率的JDBC框架，极大的改进了效率并且减少了可能的错误。Spring的数据访问架构还集成了 Hibernate和其他O/R mapping解决方案。Spring还提供了唯一的事务管理抽象，它能够在各种底层事务管理技术，例如JTA或者JDBC事务提供一个一致的编程模型。Spring提供了一个用标准Java语言编写的AOP框架，它给POJOs提供了声明式的事务管理和其他企业事务--如果你需要--还能实现你自己的 aspects。这个框架足够强大，使得应用程序能够抛开EJB的复杂性，同时享受着和传统EJB相关的关键服务。Spring还提供了可以和IoC容器集成的强大而灵活的MVC Web框架。【SpringIDE：Eclipse平台下一个辅助开发插件】。

###WebWork 【Java开源Web框架】

WebWork是由OpenSymphony组织开发的，致力于组件化和代码重用的拉出式MVC模式J2EE Web框架。WebWork目前最新版本是2.1，现在的WebWork2.x前身是Rickard Oberg开发的WebWork，但现在WebWork已经被拆分成了Xwork1和WebWork2两个项目。Xwork简洁、灵活功能强大，它是一个标准的Command模式实现，并且完全从web层脱离出来。Xwork提供了很多核心功能：前端拦截机（interceptor），运行时表单属性验证，类型转换，强大的表达式语言（OGNL – the Object Graph Notation Language），IoC（Inversion of Control倒置控制）容器等。WebWork2建立在Xwork之上，处理HTTP的响应和请求。WebWork2使用ServletDispatcher将HTTP请求的变成Action（业务层Action类），session（会话）application（应用程序）范围的映射，request请求参数映射。WebWork2支持多视图表示，视图部分可以使用JSP,Velocity,FreeMarker,JasperReports，XML等。在WebWork2.2中添加了对AJAX的支持，这支持是构建在DWR与Dojo这两个框架的基础之上。
【EclipseWork：用于WebWork辅助开发的一个Eclipse插件】

###Struts 【Java开源Web框架】

Struts是一个基于Sun J2EE平台的MVC框架，主要是采用Servlet和JSP技术来实现的。由于Struts能充分满足应用开发的需求，简单易用，敏捷迅速，在过去的一年中颇受关注。Struts把Servlet、JSP、自定义标签和信息资源（message resources）整合到一个统一的框架中，开发人员利用其进行开发时不用再自己编码实现全套MVC模式，极大的节省了时间，所以说Struts是一个非常不错的应用框架。【StrutsIDE：用于Struts辅助开发的一个Eclipse插件】

###Hibernate 【Java开源持久层框架】

Hibernate是一个开放源代码的对象关系映射框架，它对JDBC进行了非常轻量级的对象封装，使得Java程序员可以随心所欲的使用对象编程思维来操纵数据库。Hibernate可以应用在任何使用JDBC的场合，既可以在Java的客户端程序实用，也可以在Servlet/JSP的Web应用中使用，最具革命意义的是，Hibernate可以在应用EJB的J2EE架构中取代CMP，完成数据持久化的重任。Eclipse平台下的Hibernate辅助开发工具：【Hibernate Synchronizer】【MiddlegenIDE】

###JFinal【Java极速WEB+ORM框架】

jfinal 是基于 Java 语言的极速 WEB + ORM 框架，其核心设计目标是开发迅速、代码量少、学习简单、功能强大、轻量级、易扩展、Restful。在拥有Java语言所有优势的同时再拥有ruby、python、php等动态语言的开发效率!主要特点1.MVC架构，设计精巧，使用简单 2.遵循COC原则，零配置，无xml 3.独创Db + Record模式，灵活便利 4.ActiveRecord支持，使数据库开发极致快速 5.自动加载修改后的java文件，开发过程中无需重启web server 6.AOP支持，拦截器配置灵活，功能强大 7.Plugin体系结构，扩展性强 8.多视图支持，支持FreeMarker、JSP、Velocity 9.强大的Validator后端校验功能 10.功能齐全，拥有struts2的绝大部分功能 11.体积小仅218K，且无第三方依赖

###Quartz 【Java开源Job调度】

Quartz是OpenSymphony开源组织在Job scheduling领域又一个开源项目，它可以与J2EE与J2SE应用程序相结合也可以单独使用。Quartz可以用来创建简单或为运行十个，百个，甚至是好几万个Jobs这样复杂的日程序表。Jobs可以做成标准的Java组件或EJBs。Quartz的最新版本为Quartz 1.5.0。

###Velocity 【Java开源模板引擎】

Velocity是一个基于java的模板引擎（template engine）。它允许任何人仅仅简单的使用模板语言（template language）来引用由java代码定义的对象。当Velocity应用于web开发时，界面设计人员可以和java程序开发人员同步开发一个遵循MVC架构的web站点，也就是说，页面设计人员可以只关注页面的显示效果，而由java程序开发人员关注业务逻辑编码。Velocity将java代码从web页面中分离出来，这样为web站点的长期维护提供了便利，同时也为我们在JSP和PHP之外又提供了一种可选的方案。Velocity的能力远不止web站点开发这个领域，例如，它可以从模板（template）产生SQL和PostScript、XML，它也可以被当作一个独立工具来产生源代码和报告，或者作为其他系统的集成组件使用。Velocity也可以为Turbine web开发架构提供模板服务（template service）。Velocity+Turbine提供一个模板服务的方式允许一个web应用以一个真正的MVC模型进行开发。【VeloEclipse ：Velocity在Eclipse平台下的一个辅助开发插件】

###IBATIS 【Java开源持久层框架】

使用ibatis提供的ORM机制，对业务逻辑实现人员而言，面对的是纯粹的Java对象，这一层与通过Hibernate 实现ORM 而言基本一致，而对于具体的数据操作，Hibernate 会自动生成SQL 语句，而ibatis 则要求开发者编写具体的SQL语句。相对Hibernate等“全自动”ORM机制而言，ibatis 以SQL开发的工作量和数据库移植性上的让步，为系统设计提供了更大的自由空间。作为“全自动”ORM 实现的一种有益补充，ibatis 的出现显得别具意义。

###Compiere ERP&CRM 【Java开源ERP与CRM系统】

Compiere ERP&CRM为全球范围内的中小型企业提供综合型解决方案，覆盖从客户管理、供应链到财务管理的全部领域，支持多组织、多币种、多会计模式、多成本计算、多语种、多税制等国际化特性。易于安装、易于实施、易于使用。只需要短短几个小时，您就可以使用申购-采购-发票-付款、报价-订单-发票-收款、产品与定价、资产管理、客户关系、供应商关系、员工关系、经营业绩分析等强大功能了。
Roller Weblogger 【Java开源Blog博客】[4]
这个weblogging 设计得比较精巧，源代码是很好的学习资料。它支持weblogging应有的特性如：评论功能，所见即所得HTML编辑，TrackBack，提供页面模板，RSS syndication，blogroll管理和提供一个XML-RPC接口。

###Eclipse 【Java开源开发工具】

Eclipse平台是IBM向开放源码社区捐赠的开发框架，它之所以出名并不是因为IBM宣称投入开发的资金总数 —4千万美元，而是因为如此巨大的投入所带来的成果：一个成熟的、精心设计的以及可扩展的体系结构。

###NetBeans 【Java开源开发工具】

NetBeans IDE 是一个为软件开发者提供的自由、开源的集成开发环境。您可以从中获得您所需要的所有工具，用Java、C/C++ 甚至是Ruby 来创建专业的桌面应用程序、企业应用程序、web 和移动应用程序。此IDE 可以在多种平台上运行，包括Windows、Linux、Mac OS X 以及Solaris；它易于安装且非常方便使用。

###XPlanner 【Java开源项目管理】

XPlanner 一个基于Web的XP团队计划和跟踪工具。XP独特的开发概念如iteration、user stories等，XPlanner都提供了相对应的的管理工具，XPlanner支持XP开发流程，并解决利用XP思想来开发项目所碰到的问题。XPlanner特点包括：简单的模型规划，虚拟笔记卡（Virtual note cards),iterations、user stories与工作记录的追踪，未完成stories将自动迭代，工作时间追踪，生成团队效率，个人工时报表，SOAP界面支持。

###HSQLDB 【Java开源DBMS数据库】

HSQLDB(Hypersonic SQL）是纯Java开发的关系型数据库，并提供JDBC驱动存取数据。支持ANSI-92 标准SQL语法。而且他占的空间很小。大约只有160K，拥有快速的数据库引擎。

###Liferay 【Java开源Portal门户】

代表了完整的J2EE应用，使用了Web、EJB以及JMS等技术，特别是其前台界面部分使用Struts 框架技术，基于XML的portlet配置文件可以自由地动态扩展，使用了Web Services来支持一些远程信息的获取，使用Apache Lucene实现全文检索功能。

###JetSpeed 【Java开源Portal门户】

Jetspeed是一个开放源代码的企业信息门户(EIP）的实现，使用的技术是Java和XML。用户可以使用浏览器，支持WAP协议的手机或者其它的设备访问Jetspeed架设的信息门户获取信息。Jetspeed扮演着信息集中器的角色，它能够把信息集中起来并且很容易地提供给用户。

###JOnAS 【Java开源J2EE服务器】

JOnAS是一个开放源代码的J2EE实现，在ObjectWeb协会中开发。整合了Tomcat或Jetty成为它的Web容器，以确保符合Servlet 2.3和JSP 1.2规范。JOnAS服务器依赖或实现以下的Java API：JCA、JDBC、JTA 、JMS、JMX、JNDI、JAAS、JavaMail。

###JFox3.0 【Java开源J2EE服务器】

JFox是Open Source Java EE Application Server，致力于提供轻量级的Java EE应用服务器，从3.0开始，JFox提供了一个支持模块化的MVC框架，以简化EJB以及Web应用的开发！ 如果您正在寻找一个简单、轻量、高效、完善的Java EE开发平台，那么JFox正是您需要的。