查看版本：

```
git --version
```

版本控制：实质上是管理文件夹

```
1.进入要管理的文件夹
	-  右键 git bash here
2.初始化
	- git init
3.检测当前文件夹下的文件状态【红色】
	- git status 
4.让git管理 + 生成版本【绿色】
	- git add .
	- git commit -m "初始化"
5.查看历史版本
	- git log
	
红色：新增文件或者修改文件  =》 git add .
绿色：git已经管理起来     =》 git commit -m "描述信息"
生成版本
```

补充：在commit前

```
个人信息配置：
git config --global user.name "zhaoxiaoa"
git config --global user.email "amanscorner@163.com"
```

git三大区域：

<img src="assets/image-20241217090903801.png" alt="image-20241217090903801" style="zoom:67%;" />



