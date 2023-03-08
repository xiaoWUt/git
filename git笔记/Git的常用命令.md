#### 设置用户签名（必须设置）

Git安装好之后要设置的，只要设置一次就好了，如果不设置将来提交代码时会报错的

~~~
//设置用户名
git config --global user.name 用户名
//例如 git config --global user.name wu


//设置邮箱
git config --global user.email 邮箱
//例如 git config --global user.email 1537327547@qq.com
~~~

设置好后可以去到Windows的家目录下找到当前所登录的账号下的**.gitconfig**文件中右击用编辑工具打开是否有刚才设置的用户和邮箱，有即设置

![](F:\第二次前端\git\git笔记\windows目录.png)

![](F:\第二次前端\git\git笔记\windows目录2.png)



#### 当前分支（master）默认分支

#### 初始化本地库

~~~
git init
~~~



#### 查看本地库状态

~~~
git status
~~~

#### 添加暂存区

~~~
git add 文件名
~~~

#### 删除暂存区的文件

~~~
git rm --cached 文件名
~~~

#### 提交本地库

~~~
git commit -m "日志信息" 文件名      //日志信息相当与版本号
~~~

#### 查看版本信息

~~~
//查看版本信息
git reflog

//详细查看版本信息
git log
~~~

![](F:\第二次前端\git\git笔记\版本号.png)

红箭头为版本号



#### 回退版本信息（版本穿梭）

可以穿梭已有的版本

~~~
git reset --hard 版本号
~~~

