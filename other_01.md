# 冯若航-简历-2017

- 冯若航 Feng Ruohang
- 联系方式: fengruohang@outlook.com / (+86) 18801100571 
- 个人站点:  [Vonng.com](http://vonng.com) , [Github](https://github.com/Vonng), [LinkedIn](www.linkedin.com/in/vonng), [详细履历](https://vonng.com/about/resume/)

## 目标

北京/杭州全职工作。感兴趣岗位排序为：架构师/全栈工程师/Go后端工程师/PgDBA。12.15可入职

## 专长

擅长架构设计，PostgreSQL，Go，Python，Javascript，数据库，Web应用开发，信息爬取等。

全栈工程师，优秀的Common Sense，可与各领域专家无障碍沟通。擅长快速产出原型，独立完成小型项目。

## 履历

2年半的阿里工作经验，2年的大学实验室工作经验。

- 2015.08 - 2017.11：阿里巴巴-数据产品与技术-CNZZ / 友盟+  研发工程师
  - 2016.07 DMP/Finplus项目组：金融风控业务线架构师，PD，前端、后端、DBA，运维，数据研发。
  - 2017.05 U-DIP项目组：知识库建设，后端开发
  - 2017.01 API-Gateway：架构师，运维
  - 2016.03 UDP项目组：友盟+统一数据平台建设，架构设计，运维，DBA
  - 2015.09 OPlus项目组：软硬件结合工程师，后端开发，前端开发
  - 2015.08 数据小组：数据研发，数据分析师
- 2014.07 - 2014.09：阿里巴巴-阿里妈妈-CNZZ-云推荐  实习算法工程师
  - 负责Redis索引与元数据爬虫开发。
- 2011.07 - 2015.07：哈尔滨工程大学本科，信息安全专业，HEU AI-Lab成员
  - 期间负责“海工知识管理平台”项目一期的设计与实现，获黑龙江省科技进步一等奖。





## 代表项目

友盟+Finplus，三人起步，年营收过亿的项目。在项目中负责除算法外的所有技术工作，包括：

* 架构师：架构设计、数据库模型设计、技术选型。
* PD：产品设计
* 后端工程师：三个大版本的具体实现（Node，Go，Python）
* 前端工程师：后台界面设计开发，统计报表设计开发。
* PE/DBA/测试/数据研发ETL





## 经验、技能、项目细节

### 1. 数据库: Advanced

- 能够从业务抽象出数据模型，设计数据库模式。
- 能够熟练运用SQL，解决各类OLTP/OLAP问题。
- 熟练掌握PostgreSQL：编译安装、部署运维、管理监控、高级查询、存储过程、ETL方法、扩展编写(FDW)。
- 能够熟练编写plpgsql/plpython存储过程并实现魔幻的数据库内应用：推荐系统，神经网络，爬虫等。
- 阅读Redis源码，了解底层原理，熟悉API。
- 熟悉MongoDB数据模型与API，编写`mongo_fdw`。熟悉HBase数据模型与API，编写了[`hbase_fdw`](https://github.com/Vonng/hbase_fdw)。
- 熟悉ODPS SQL, ODPS Shell, ODPS Python UDF, DataX, pyodps, Seahawks等工具的使用
- 编写了阿里云ODPS的Golang SDK，SQL数据驱动：[goodps](https://github.com/Vonng/goodps)
- 上述数据库的Python，Go，Node驱动，ORM使用，JDBC使用。

#### 相关项目

- 友盟+DMP元数据库设计（PostgreSQL / MySQL）
- 友盟+cplus元数据库设计 (PostgreSQL)
- 友盟+oplus私有化版本（ODPS 迁移至 PostgreSQL）
- 友盟+UDP数据统一层：(通过PostgreSQL代理MongoDB与HBase访问 )
- 友盟Share业务与微博爬虫迁移数据库设计(MongoDB迁移至PostgreSQL)
- 其他杂项数据库设计：Oplus动线热力图，CNZZ运营数据大盘
- 论文：NPC2017, CCF-C会：Unified Access Layer with PostgreSQL FDW for Heterogeneous Databases





### 2. Web应用开发/后端开发: Advanced

- 熟练使用Python，Go，Javascript（node.js）开发后端应用。
- 理解网络与计算机系统底层原理，熟悉TCP/IP，HTTP等协议。能够只用标准库裸写web应用。
- 熟悉各类Web Framework与Web Serve，包括Go(http/fasthttp)，Node(express,koa,restify)，Python(tornado)，Nginx，Caddy。
- 丰富的（HTTP，RESTful, GraphQL）API设计开发经验，熟悉认证授权日志监控报警限流改写Mock等功能在各语言下的实现。
- 有API Gateway建设落地经验，了解Nginx、Kong、Tyk的原理、应用、部署与运维。
- 信息安全专业背景，了解各类密码学原理、工具。熟练使用OpenSSH。

#### 相关项目

- CPlus风控数据服务(Node,Go)
- CPlus后台(Node)
- CNZZ运营报表数据服务(Python)
- OPlus数据大屏服务后端(热力、动线、人脸识别)(Python,Node,C++)
- LBS圈人应用算法优化（Java）。
- 个人定制版的Markdown Render与Static Blog Generator，完美支持MD+LaTeX。（Go）
- 内部MD文档共享站点与个人网站。(Python,Node,Go) 
- API Gateway建设：方案Kong & 方案Tyk 部署落地与推广
- 各类内部便利命令行工具（openapi-cli，finplus-cli, oss-cli, ...）

### 3. Web信息抓取：Advanced

- 源码级深入Python爬虫框架scrapy，可以对其进行任意定制修改。
- 熟练掌握正则表达式、XPath，CSS Selector，定制解析规则。
- 熟悉爬虫设计、编写、部署、运维、数据清洗等工作。

#### 相关项目

- 应用知识库建设，收录苹果与安卓应用市场共计300万+应用的详细信息，Go裸http爬虫：[go-itunes-search](https://github.com/Vonng/go-itunes-search) 与 [go-android-search](https://github.com/Vonng/go-android-search)
- 设备知识库建设，收录中关村在线全部产品。(python-scrapy)，手机设备数据专项梳理。(scrapy)
- 汽车知识库建设，破解汽车之家反爬，梳理了所有车型的详细数据。（scrapy）
- 地理知识库建设，收录了某地图所有的POI数据。（Go）
- Go编写的简易爬虫框架：gospider

### 4. 前端/数据可视化

- 熟悉HTML，CSS，JS，能根据文档解决各类前端问题
- 熟悉各类常见前端基础类库：jquery，easyui，require，bootstrap, MathJax, highlight.js, react...
- 熟悉各类模板语言：jade，ejs，html/template
- 熟悉数据可视化的常用类库：echarts, D3.js
- 可以独立解决前后台GUI设计开发，可视化报表等前端相关问题。

#### 相关项目

- OPlus热力动线人脸识别，数据大屏前端，热点标注工具。
- CPlus统计报表前端，CPlus管理后台
- CNZZ运营报表前台
- 个人站点前端页面
- 其他各类内部系统的前后台，各类专项BI报表与数据分析报告。

### 5. 数据分析/AI

- 数学，统计学基础扎实，了解神经网络原理。
- 熟悉Python（pandas, numpy）与Matlab科学计算。
- 了解OpenCV的安装部署与简单应用
- 了解Tensorflow工作模型，简单应用过。
- 了解推荐系统基本原理，实现过简易ItemCF，UserCF推荐系统。

#### 相关项目

- 纯PostgreSQL推荐系统解决方案。
- OPlus大屏-视屏实时人脸识别（OpenCV,C++,Python）
- 个人玩具项目：自动扒谱、拍照解数独小应用。

### 6. POSIX运维/环境配置

- 熟悉Bash，熟悉Linux常用命令，个人Bash配置方案项目：
- 熟悉Docker的使用，Dockerfile的编写。
- 熟悉Mac的使用，熟悉Mac和Windows下各类软件。熟练使用各类IDE。

#### 相关项目

- 部署运维管理了一个240核1T内存的PostgreSQL集群
- MacOS下CapsLock改键方案：[Capslock](https://github.com/Vonng/Capslock)
- POSIX环境配置方案：[Configuration](https://github.com/Vonng/Configuration)

### 7. 其他

- 扎实的计算机、数学基础，信息安全专业背景。辅修过经济、政治、法律、心理学相关课程。
- 流畅英语口语，无障碍沟通。
- 了解802.11协议，负责Oplus-WiFi探针调试开发、测试、刷写、部署、售后、技术支持。
- 熟练使用C# Windows Form与WPF开发Windows应用，大学期间开发了各类Windows下Matlab GUI工具。
- 有一定的GIS应用开发经验
