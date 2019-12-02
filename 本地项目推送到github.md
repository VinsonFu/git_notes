### 1.版本库创建

1.创建一个版本库非常简单，可以使用git bash也可以使用tortoiseGit。首先，选择一个合适的地方，创建一个空目录

2.使用GitBash创建

在当前目录中点击右键中选择Git Bash来启动。

创建仓库执行命令：

$ git init

3.也可以使用TortoiseGit创建

使用TortoiseGit时只需要在目录中点击右键菜单选择“在这里创建版本库”，一般不勾选“制作纯版本库(没有工作目录)”

4.版本库创建成功，会在此目录下创建一个.git的隐藏目录

### 2.添加文件到本地仓库

1.在版本库所在的目录中创建一个mytest.txt文件，并写一些内容

2.右击mytest.txt文件，选择TortoiseGit->添加，之后该文本文件变为带"+"号的图标

### 3.提交文件

右击带"+"号的文件，选择Git提交，日志内容必须填写：新增mytest.txt文件，单击提交

#### 1.在github上创建仓库

右上角"+"->New repositort，填写Repository name：mytest。点击“create repository”按钮仓库就创建成功了

#### 2.同步到远程仓库

同步到远程仓库可以使用git bash也可以使用tortoiseGit

##### 使用git bash

1.在本地仓库所在的目录点击右键选择“Git Bash Here”，启动git bash程序。

2.然后在git bash中执行如下语句：

git remote add origin https://github.com/VinsonFu/mytest1.git

git push -u origin master

3.输入自己的github账号与密码以连接到github

