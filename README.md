# 基于ssm框架的慕课书评网

前言：本文章仅为项目展示，无教学

描述：**基于前后端分离的开发模式，利用Mybatis-plus实现持久层敏捷开发，基于spring-task异步实现评论分数统计**

环境：java1.8，Tomcat9，

技术：**SSM，Mybatis-plus，Kaptcha，wangeditor，Spring Task****。**  **Druid连接池,jsoup html解析器,vue3/Axios/vant UI**   

vant vue3版本有赞前端团队

（1）首先，ssm就是Mybatis，Spring，Spring MVC的整合；

（2）MybBatis-Plus敏捷开发插件；

（3）结合项目实际，介绍谷歌的Kaptcha验证码组件；

（4）因为书评内容包括图文资料，为了能够在线编辑这些图文信息，引入了富文本编辑器wangEditor；

（5）Spring Task任务调度组件；

（6）Bootstrap UI前端框架入门；

（7）也通过文本材料，介绍了【如何基于阿里云实现短信验证】和【如何基于腾讯云的滑块验证码，实现前置的人机登录检查】；
————————————————

项目展示：![image](https://github.com/MapleDipX/imooc-reader/assets/133567178/ba4192d7-c2c4-40d8-947f-99a8dfb1e22b)
![image](https://github.com/MapleDipX/imooc-reader/assets/133567178/cc2fdf0d-e311-4057-9f91-0daf48f3e9d7)
![image](https://github.com/MapleDipX/imooc-reader/assets/133567178/337a629e-a8e2-4c2f-a2fd-6fd907e9934d)

登录页面:

![image](https://github.com/MapleDipX/imooc-reader/assets/133567178/a04002fb-c743-400d-96fb-1c1cc71c2760)
详情页：

![image](https://github.com/MapleDipX/imooc-reader/assets/133567178/889a59e9-e703-4597-aeb0-01016a07a4a5)
![image](https://github.com/MapleDipX/imooc-reader/assets/133567178/5b49f53b-774f-4637-9dc0-5ce75e0fd196)
![image](https://github.com/MapleDipX/imooc-reader/assets/133567178/35a43555-fc4d-4fed-aac1-61c5434b48f4)

管理页面：
![image](https://github.com/MapleDipX/imooc-reader/assets/133567178/2227ee66-fc2b-4311-9cdc-c81abec6812a)
新增：
![image](https://github.com/MapleDipX/imooc-reader/assets/133567178/9389651b-afd0-4e58-b56b-2a01d7476777)
修改：
![image](https://github.com/MapleDipX/imooc-reader/assets/133567178/4849dd15-7e1c-4a4e-926b-f7d1cc7d507a)
删除功能：
![image](https://github.com/MapleDipX/imooc-reader/assets/133567178/da8de9b0-2de0-44ee-99f4-eaf17236948e)








