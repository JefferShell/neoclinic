## 项目简介

本项目使用neo4j作为关系图谱数据库，旨在追踪疫情之间的关系，并进行溯源分析。项目自带一份完整的数据库，包括患者、常住地、路径实体等，可有效解决分析疫情来源的问题。

**注意：**使用前务必读一下README.md文件，里面有初始化数据方法。


## 主要功能

- 正常登录注册功能，无问题
- 登录首页是全国疫情地图，根据疫情严重程度标注了疫情的深浅
- 右侧tab表示了每个城市的地址，点击只会查找对应城市的人
- 进入对应城市后，可以查找图谱关系，和对应途径地，比如你要搜途径哪里的，直接搜就可以看到谁去过


## 技术架构

- 框架：django
- 数据库：neo4j
- 前端展示：echarts
- 数据库驱动：py2neo


## 使用说明

1. 检查项目依赖，并确保安装所有依赖。
2. 启动项目并访问首页。
3. 登录或注册。
4. 在地图上选择一个城市，以查找该城市的疫情情况。
5. 在城市页面中，搜索道路名以找到相关路径和提及该道路的乘客。


## 联系方式

微信号：zt745324325