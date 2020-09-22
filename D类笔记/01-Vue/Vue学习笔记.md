# Vue

读音/vju:/，类似于view



![image-20200204033234547](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200204033234547.png)

## 属性

![image-20200220015541721](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200220015541721.png)

​	1）包含了el属性：该属性决定了这个vue对象挂载到哪一个元素上。例子：第一个Vue程序

​	2）包含了data属性：通常会存储一些数据

​			数据可以是我们直接定义也可以来自网络来自服务器加载

​	3）属性：methods，该属性用于在Vue对象中定义方法

## 指令

​	1）v-for指令：<li v-for="item in xxx">{{item}}</li>

可以理解为提取数组中各个元素并挨个输出，创建了数组元素个数个li

​	2）@click/v-on：click指令，该指令用在监听某个元素的点击事件，并且需要指定发生点即使，执行的方法。

### 第一个Vue程序，体验vue响应式

执行到22行创建vue实例，对原HTML进行解析和修改

在此之前显示原有HTML该有的东西

<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200204204057768.png" alt="image-20200204204057768" style="zoom: 50%;" />

<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200204204643539.png" alt="image-20200204204643539" style="zoom:50%;" />

<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200204204655630.png" alt="image-20200204204655630" style="zoom: 67%;" />

1·创建了vue对象

2·传入了一些options：{}

 	1）包含了el属性：该属性决定了这个vue对象挂载到哪一个元素上，上程序挂载到了id为app的元素上

​	 2）包含了data属性：通常会存储一些数据

​			数据可以是我们直接定义也可以来自网络来自服务器加载

### 第二个Vue程序，列表展示

v-for指令

<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200204211054965.png" alt="image-20200204211054965" style="zoom:50%;" />![image-20200204211144616](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200204211144616.png)

<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200204211154025.png" alt="image-20200204211154025" style="zoom:50%;" />![image-20200204211210586](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200204211210586.png)

<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200204211210586.png" alt="image-20200204211210586" style="zoom:50%;" />

### 第三个Vue程序，计数器

新的属性：methods，该属性用于在Vue对象中定义方法

新的指令：@click/v-on：click，该指令用在监听某个元素的点击事件，并且需要指定发生点即使，执行的方法

<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200204215156053.png" alt="image-20200204215156053" style="zoom:50%;" />

![image-20200220014343233](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200220014343233.png)

# Vue中的MVVM

View ViewModel Model

![image-20200220013343137](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200220013343137.png)

![image-20200220013921016](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200220013921016.png)

### vue的生命周期

生命周期：事物从诞生到消亡的整个过程

vue生命周期：自己看吧 created等等！

### 模板语法

webpack打包![image-20200302162633245](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200302162633245.png)

本地webpack   webpack开发时依赖 项目打包后不需要继续使用

![image-20200302174545803](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200302174545803.png)

![image-20200302180827439](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200302180827439.png)

步骤哈：

npm init

npm install

npm install webpack@xxxx --sava-dev

需要loader的时候去webpack官网找

![image-20200302231305909](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200302231305909.png)



es6转es5

![image-20200303232223693](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200303232223693.png) 

使用vue时

安装vue cnpm install --save vue

完事以后在webpack配置文件中配置vue compiler版本    不对的话调版本也行 多加一个plugin也行？

<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200304020851679.png" alt="image-20200304020851679" style="zoom:50%;" />

使用vue 组件化

打包html的plugin

<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200309021832701.png" alt="image-20200309021832701" style="zoom:50%;" />

<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200309023348780.png" alt="image-20200309023348780" style="zoom: 33%;" />

<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200309024303921.png" alt="image-20200309024303921" style="zoom: 33%;" />

将配置文件合并

<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200309031553495.png" alt="image-20200309031553495" style="zoom:50%;" />

<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200309044849386.png" alt="image-20200309044849386" style="zoom: 33%;" />

<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200309050033542.png" alt="image-20200309050033542" style="zoom: 67%;" />

<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200309050521947.png" alt="image-20200309050521947" style="zoom: 33%;" />

vue全家桶  VueCore+vue-router+vuex

ES(js)Lint   规范敲代码限制

<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200310201149529.png" alt="image-20200310201149529" style="zoom:50%;" />

<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200311003550715.png" alt="image-20200311003550715" style="zoom:50%;" />关掉ESLint



<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200311005945973.png" alt="image-20200311005945973" style="zoom: 67%;" />Vue程序运行过程

##### 后端渲染

![image-20200314162745767](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200314162745767.png)

##### 前后端分离

![image-20200314173543620](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200314173543620.png)

前端路由url和组件的关系

SPA页面 simple page application  单页面富应用 

SPA最主要的特点就是在前后端分离的基础上加了一层前端路由，前端来维护一套路由规则。

前端路由核心：改变URL，页面不进行整体的刷新

![image-20200314182010346](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200314182010346.png)



<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200314194411442.png" alt="image-20200314194411442" style="zoom:50%;" />

<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200314194531473.png" alt="image-20200314194531473" style="zoom:50%;" />![image-20200314230554749](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200314230554749.png)<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200314194531473.png" alt="image-20200314194531473" style="zoom:50%;" />![image-20200314230554749](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200314230554749.png)

<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200315001150595.png" alt="image-20200315001150595" style="zoom: 50%;" />

![image-20200317114250859](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200317114250859.png) 



VUE脚手架创建新项目

vue init webpack project_name

cnpm install vue-router --save  安装vue路由。--save是运行时依赖。

cnpm install axios --save 安装axios框架



vue状态管理图例

vuex中处理不能直接从组建改state 可以直接改mutations 可以进行跟踪出错方便调试 直接改state不行	actions处理异步操作	

<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200511151237432.png" alt="image-20200511151237432" style="zoom:67%;" />

vuex五个核心：state（状态）/mutation（方法）/actions（异步）/getters（类似计算属性，经过计算后显示而不是直接使用）/modules

mutation状态更新：vuex的store状态更新唯一方式：提交mutation



mutation相应规则：Vuex的store中的state是响应式的，当state中的数据发生改变时，Vue组件会自动更新。**前提：**在store中初始化好所需的属性

如果需要响应式用Vue.delete 或者Vue.set

![image-20200719133817437](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200719133817437.png)



module

![image-20200719150930941](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200719150930941.png)



Vue实战

vue create supermall 			vue脚手架3创建项目

git远程管理项目

![image-20200720145902035](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200720145902035.png)



## 新项目：

1.划分目录结构<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200722171118738.png" alt="image-20200722171118738" style="zoom:50%;" />

2.css文件引入<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200723023001280.png" alt="image-20200723023001280" style="zoom:50%;" />可以用cnpm install normalize.css  

base.css需要找一下

3.vue.config.js和.editorconfig文件  vue.config.js<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200723023210736.png" alt="image-20200723023210736" style="zoom:50%;" />

.editorconfig<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200723023234983.png" alt="image-20200723023234983" style="zoom:50%;" />

4.项目模块划分：tabbar->路由映射关系 也就是router中的path设置<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200723155553476.png" alt="image-20200723155553476" style="zoom:50%;" />





