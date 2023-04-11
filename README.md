<!--
 * @Date: 2023-03-27 11:36:17
 * @LastEditors: xzz
 * @LastEditTime: 2023-04-11 14:12:19
-->
#### 框架说明

###### 此框架基于webpack5, 使用vue3搭建,实现v3插件开发者开发阶段,编译完成自动刷新页面的功能,开箱即用!

> 已配置好插件所有必需的入口文件(background,content,inject,popup,manifest)
>
> node运行环境版本: 18.13.0    刷新原理:  websocket监听发送消息

##### 已配置好的依赖:

> * webpack5
> * vue3.2
> * pinia
> * jquery
> * scss
> * 自动引入组件及vue相关依赖

###### 开箱即用功能:

> * 常用功能函数promisify封装(fetch, array, object, dom... )
> * chrome常用API封装promisify(storage, communication between content and background, tabQuery, download...)