## ctrl+shift+delete 清除缓存get√

### GitHub

#### 官方网址：Github.com

#### 2.1目的

借助GitHub托管项目代码

#### 2.2基本概念

##### 仓库（repository）

仓库用来存放项目代码，每个项目对应一个仓库，多个开源项目则有多个仓库

##### 收藏（star）

收藏项目，方便下次查看。仓库主页star按钮，意思为收藏项目的人数。

##### 复制克隆项目（Fork）

![image-20200201192830943](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200201192830943.png)

脚下留心：该fork的项目是独立存在的

#### 2.3基本概念2

##### 发起请求（pull request）

上图从右向左![img](file:///C:\Users\admin\AppData\Local\Temp\SGPicFaceTpBq\10548\01004C3E.png)李四发张三收张三同意可以合并

##### 关注（watch）

关注项目，当项目更新可以接受到通知

##### 事务卡片（issue）

发现代码bug，但是目前没有成型代码，需要讨论时用

#### 2.4基本概念3

##### GitHub主页

账号创建成功或点击网址导航栏github图标都可以进入github主页：该页左侧主要显示用户动态以及关注用户或关注仓库的动态；右侧显示所有的git库

##### 仓库主页

主要显示项目的信息，如：项目代码，版本，收藏/关注/fork情况等

##### 个人主页

个人信息：头像，个人简介，关注我的人，我关注的人，我关注的git库，我的开源项目，我贡献的开源项目等信息。

#### 2.5创建仓库/创建新项目

一个git库（仓库）对应一个开源项目

通过git管理git库

![image-20200201235945957](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200201235945957.png)

#### 2.6仓库管理

##### 新建文件(create newfile)

编辑文件:点开文件点笔即编辑- -

删除文件：编辑旁边点垃圾桶删除

删除编辑等都需要记录commit可以查看操作记录

##### 上传文件（upload dile)

可以拖动或选择

##### 搜索仓库文件（find file）

快捷键t

##### 下载/检出项目

![image-20200202001933304](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200202001933304.png)

### Git

官方下载地址太慢，从CSDN上找镜像网站下载https://npm.taobao.org/mirrors/git-for-windows/

#### Git工作区域

##### 工作区（working directory）

添加、编辑、修改文件等动作/新建修改

Git Repository（Git 仓库）

最终确定的文件保存到仓库，成为一个新的版本，并且对他人可见

##### 暂存区

暂存已经修改的文件最后统一提交到git仓库中

## 向仓库中添加文件的流程

ls显示文件

初始化    初始化只需要一次 git config --list查看信息

git config --global user.name 'BigStrawberry0225'

git config --global user.email '1157710179@qq.com'

mkdir创建新文件夹＋名字   pwd显示当前路径

创建仓库 

touch＋文件 例：touch a1.php 创建文件

cd＋文件名进入文件之后git init创建仓库

## 向仓库中添加文件

git status显示当前情况

git add ＋文件名  	//工作区加到暂存区   git status

git commit -m ‘提交描述’	//暂存区加到仓库

## 修改仓库文件

vi 文件名  			//修改文件

再提交就行了

## 删除仓库文件

rm -rf 文件名 		rm 文件名		////删除文件

git rm +文件			//从git中删除文件 

提交操作：	 git commit -m ‘提交描述’

# Git管理远程仓库

## 目的

作用、备份、实现代码共享集中化管理

## 将本地仓库提交到远程

git push![image-20200202213108655](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200202213108655.png)

## Git克隆操作

然后本地操作完了再提交回去

### 目的

将远程仓库（github对应的项目）复制到本地

### 代码

git clone 仓库地址

仓库地址去github仓库download中复制

# Github Pages 搭建网站

github pages仅支持静态网页

仓库里面只能是.html文件

## 个人站点

访问

https://用户名.github.io

## 搭建步骤

### 1）创建个人站点

新建仓库（仓库名必须是【用户名.github.io】）

### 2）新建文件

在仓库下新建文件index.html文件

## 项目站点

https://用户名.github.io/仓库名

## 搭建步骤

1）进入项目主页点击settings

2）在settings页面，点击【launch automatic page generator】来自动生成主题页面

3）新建站点基础信息设置

4）选择主题

5）生成网页

有一个分支哦 彩蛋一下看看自己还能不能找到 very easy



![image-20200226003821972](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20200226003821972.png)