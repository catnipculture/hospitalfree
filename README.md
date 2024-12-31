> #### 作者主页：[舒克日记](https://blog.csdn.net/cativen)
>
>  简介：Java领域优质创作者、Java项目、学习资料、技术互助
>
> <b><font color=red>文中获取源码</font></b>

# 项目介绍

本医疗报销系统分为管理员还有用户两个权限

管理员可以管理用户的基本信息内容，可以管理公告信息以及公告的租赁信息，能够与用户进行相互交流等操作，

用户可以查看报销单信息，可以查看公告以及查看管理员回复信息等操作。



# 环境要求



1.运行环境：最好是java jdk1.8,我们在这个平台上运行的。其他版本理论上也可以。 

2.IDE环境：IDEA,Eclipse,Myeclipse都可以。推荐IDEA; 

3.tomcat环境：Tomcat7.x,8.X,9.x版本均可 

4.硬件环境：windows7/8/10 4G内存以上；或者Mac OS; 

5.是否Maven项目：是；查看源码目录中是否包含pom.xml;若包含，则为maven项目，否则为非maven.项目 

6.数据库：MySql5.7/8.0等版本均可；





# 技术栈



运行环境：jdk8 + tomcat9 + mysql5.7 + windows10

服务端技术：SpringBoot + MyBatis + Vue + Bootstrap + jQuery





# 使用说明





1.使用Navicat或者其它工具，在mysql中创建对应sq文件名称的数据库，并导入项目的sql文件； 

2.使用IDEA/Eclipse/MyEclipse导入项目，修改配置，运行项目； 

3.将项目中config-propertiesi配置文件中的数据库配置改为自己的配置，然后运行；





# 运行指导

idea导入源码空间站顶目教程说明(Vindows版)-ssm篇：

http://mtw.so/5MHvZq 

源码看好后直接在网站付款下单即可，付款成功会自动弹出百度网盘链接，网站地址：[http://www.codegym.top](http://www.codegym.top/)

其它问题请关注公众号：**IT小舟**,关注后发送消息即可，都会给您回复的。若没有及时回复请耐心等待，通常当天会有回复



# 运行截图



![img](https://img-blog.csdnimg.cn/img_convert/5163cf02ee095995e07a9f1c7b5e8b7d.png)





![QQ浏览器截图20240904215207](https://img-blog.csdnimg.cn/img_convert/9e0dcde46e52c7ee2f571e8c59d08765.png)

![springboot211基于springboot医疗报销系统的设计与实现0](https://img-blog.csdnimg.cn/img_convert/a714e9cea32df3a4ef1f5c8a96435362.png)

![springboot211基于springboot医疗报销系统的设计与实现1](https://img-blog.csdnimg.cn/img_convert/7a6ed59b25f667b9b321305d042c05aa.png)

![springboot211基于springboot医疗报销系统的设计与实现2](https://img-blog.csdnimg.cn/img_convert/eaa8597ea5c1dae8667a464c450893b2.png)

![springboot211基于springboot医疗报销系统的设计与实现3](https://img-blog.csdnimg.cn/img_convert/71ba2e21a6e3c0cb98751b4205e7bf57.png)

![springboot211基于springboot医疗报销系统的设计与实现4](https://img-blog.csdnimg.cn/img_convert/7f22f66e54834bbb49c512b987efed71.png)


### 代码

```java
	public List<DingdanxinxiVO> selectListVO(Wrapper<DingdanxinxiEntity> wrapper) {
 		return baseMapper.selectListVO(wrapper);
	}
	
	@Override
	public DingdanxinxiVO selectVO(Wrapper<DingdanxinxiEntity> wrapper) {
 		return baseMapper.selectVO(wrapper);
	}
	
	@Override
	public List<DingdanxinxiView> selectListView(Wrapper<DingdanxinxiEntity> wrapper) {
		return baseMapper.selectListView(wrapper);
	}

	@Override
	public DingdanxinxiView selectView(Wrapper<DingdanxinxiEntity> wrapper) {
		return baseMapper.selectView(wrapper);
	}
```


