# 20190107

## 资源

https://www.imooc.com/learn/9

https://www.imooc.com/learn/36

https://www.imooc.com/learn/955

https://www.imooc.com/learn/949

https://www.imooc.com/learn/277

## 单词

direction 方向趋势
construct 建立
instance 情况例子
relative 相对的
absolute 绝对的
position 位置/安置
query 询问质疑

## 视野

MDN
win10内置linux
StackOverFlow
issue

## github

https://github.com/yujiangshui/A-Programmers-Guide-to-English.git (英语学习)

-----

# 石头 20190115

零  基础丶书目
1. linux   鸟哥的私房菜
2. js  JavaScript高级程序设计/JavaScript设计模式
3. css  CCS的秘密
4. 深入了解计算机系统

【80%】
壹  基本功丶练手（各4天）
1. 复制学校官网，做到百分百一样，注意：
（1）响应式设计
（2）父子元素的重叠和样式的继承
基本功很重要！！！这一个页面都不够练的，但至少得练好一个页面
2. 复刻一个页面（明天我找给你）

貳  入门丶技术基础
【66%】
1. 首先是前端数据交互的技术，分别使用三种技术ajax/fetch/axios实现快递100api接口的调用，注意理解什么叫“同步”和“异步”（关于前端的三种接口和100接口的使用方法自己百度搜）〔各2天〕

2. 然后是数据交互的进阶技术〔1-1-0.5-3天〕
【100%】
（1）自己在本地用express.js起一个后台服务，用chrome应用“postman”尝试和这个进程进行交互调试
【90%】
（2）再在本地用webpack开启前端进程和自己的后端进程进行交互
【100%】
（3）反复使用git的各种操作，至少包括〔add commit push fetch pull diff remote config〕
【】
（4）最后在自己的服务器上起一个后端进程，和自己本地的前端进程进行交互（会遇到跨域问题，百度一下怎么在后端解决跨域问题，顺便掌握一下跨域问题是什么，有哪些解决方式）

叁 接着是前端的老本行，页面设计〔各2天〕
（1）用bootstrap组件设计你的个人博客页面
（2）改用antd组件设计（请用上grid, Form, Pagination, DatePicker, Meaasge, Modal）

肆  入门丶前端工业化标准
（1）代码规范，在自己已有的项目上使用less，eslint（standard.js）
（2）尝试使用Angularjs、vuejs、reactjs，前两个都有比较清晰的中文文档，而且是完整的框架，最后一个只算得上是类库
（3）再次学习什么是webpack、gulp，什么是前端中的“编译、打包、混淆、自动化处理”
（4）有了高级程序设计大红书的基础以后，看ES6、7的新语法，学习手动配置babel
（3）React学习路径：把官方文档里的Todolist写出来，大致了解react组件的绑定原理和“生命周期”的概念，至少要能分清一个js请求写在同一个Class Component的不同地方都有什么区别
——在github或掘金或segment上搜一个尽量新且尽量简单的react项目，确保他能跑以后按他的一步一步抄一遍，了解state和props又有什么区别？什么情况下才会触发react树的更新，从而导致页面的局部渲染？——
——〔Redux〕抄一个尽可能精简的redux项目，百度一下什么是action, reducer, store，Container，了解一个数据请求在整个redux体系中是如何流动的，其中信息的承载方式发生了几次、怎样的变化？
——〔Router〕查看react router文档，先实现最基本的router，点击不同的按钮能够做到局部渲染不同的组件。接着抄一个Router项目，体会router的使用方式（因为其版本更迭快，尽量选最新版的，坑会少一点）
——〔dva〕dva是上述的集成体，用同样的流程学习甚至重写一下以前写过的项目，体验一下什么是router的动态加载

先到这儿，如果从头到尾都完成了，手上至少有3个自己的项目了，基本功也比较扎实了，你再扯一点计算机专业基本知识，起码一般的公司肯定要你。这一切的前提是，你不能浅尝辄止，看到标题就觉得自己差不多都会了然后就跳过。基本上每一项都有坑，如果哪项你没遇到坑那你得回去好好再实践几次。很多我没标进去的知识点只是因为太零碎了，但是只要踩坑就一定会遇到。