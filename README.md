# 003ssh图书馆管理系统源码

#### 介绍
```
本毕业设计运用了使用技术：spring mvc+spring+hibernate，数据库使用了当前较为流行的Mysql5.7。
根据本校图书馆的工作流程与实际的需求和特色，本系统需满足以下几个方面的要求：
1.对新书进行登记入库、下架管理；
2.对借书读者信息提供维护功能；
3.提供图书借书、续借、还书功能；
4.提供图书超期未还自动扣款功能；
5.提供数据导入功能。
共22张表
```

源码获取：[ **点此获取** ](http://www.shuyue.fun/?type=productinfo&id=114)

#### 环境需要
```
1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。
2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;
3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可
4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS；
5.是否Maven项目: 是；查看源码目录中是否包含pom.xml；若包含，则为maven项目，否则为非maven项目 
6.数据库：MySql 5.7版本；
```

#### 技术栈
```
1. spring mvc+spring+hibernate
2. JSP+easyUI+BootStrap+JQuery
```

#### 使用说明
```
1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；
2. 将项目中dbconfig.properties配置文件中的数据库配置改为自己的配置
3. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;
若为maven项目，导入成功后请执行maven clean;maven install命令，配置tomcat，然后运行；
4. 运行项目，输入localhost:8080/xxx 登录
5. 账户admin  密码123456
```

#### 注意事项
若jeecg中的jar包下载不成功时，需要在maven的setting.xml的文档中进行如下设置；
    <mirror>
            <id>aliyun</id>
            <name>aliyun Maven</name>
            <mirrorOf>*,!jeecg,!jeecg-snapshots</mirrorOf>
            <url>http://maven.aliyun.com/nexus/content/groups/public/</url>
        </mirror>

## 运行截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/194010_ed4fa082_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/194019_e040d424_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/194027_ce41b221_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/194034_ac395f5f_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/194043_dbb1f3df_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/194052_971e490c_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/194100_86db804d_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/194108_2a9a2cad_863230.png "屏幕截图.png")


