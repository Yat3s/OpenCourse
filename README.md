# OpenCourse
A course of android project in iMooc.  
开源项目（OPEN）教程源码。

## BB in first / 写在前面
  该项目主要为慕课网的实战项目源码，该项目将会把每节课的视频讲解的源码分成一个branch，学员查看该节课的源码只需要checkout出该branch即可。
  
## Outline / 概要
  该项目主要是一个多人众包生成的演播平台，简而言之就是多人参与讨论同一个话题的文字直播平台。该项目将会从：`项目Idea--》项目PRD的撰写--》UI设计稿的设计思路--》项目初始架构思想--》功能编码--》测试部署上线`六个步骤讲解，其中前三个步骤将会简要的做概要总结，其中着重讲解：`项目初始架构思想--》功能编码--》测试部署上线`这三个步骤，课程将不仅仅会让学员了解一个Android项目从0-1的过程，而且还更加注重编码规范，设计理念，架构思想等多个范畴，让学员真正的能够享受到写一个好的代码，一个好的架构所带来的乐趣，并且能够让用户学会如何高效率的开发，享受编程的乐趣。
  ![image](https://cloud.githubusercontent.com/assets/14801837/20389581/3c874980-ad05-11e6-8963-fba44c7cece6.png)


## Catalogue / 目录
>
* **项目概要**
  * 项目简介和整体项目构建思路
    * 我们将开发一个什么样的玩意
    * 如何设计出一份好的文档
    * 从PRD中看到所有UI图的映射关系
    * 着手一个新的项目该注意哪些点
  * 项目构建所需
    * 将会用到的知识点
    * 将会用到的第三方框架
    * MVVM结构的设计思路
    * 功能模块的分包理念
    * RxJava/Retrofit/DataBinding的简要介绍
* **基础底层搭建**
  * 搭建一个好的基层对一个项目是多么重要
  * 工欲善其事必先利其器
  * Gradle的优化和加速
  * Global全局的基础搭建
  * Common通用层的基础搭建
  * Network网络层的基础搭建
  * Model模型层的基础搭建
  * View(Activity/xml)视图层的基础搭建
* **项目功能**
  * 授权相关
    * 授权设计思路
    * 如果做一个好玩又优雅的登录注册功能
  * 主流功能
    * 主流Feed的设计
    
## Architecture / 项目架构
![image](https://cloud.githubusercontent.com/assets/14801837/20388753/57605444-ad01-11e6-8895-6469ca80bd52.png)

其中说明几点：
- 自上向下不能存在任何依赖关系，从上而下或者同层可以存在依赖关系。
- 同层级如果能够依靠Dagger解耦就尽量解耦。
- 其中Application层将按照功能视图相关、CustomView、Service进行分包。
- 现在的package也将按照这个结构进行分包。


## Development / 开发相关
介绍一个版本的完整开发流程，以及日常Bug的反馈
![image](https://cloud.githubusercontent.com/assets/14801837/20388870/d1637b2c-ad01-11e6-81f2-19b270cd04b3.png)


