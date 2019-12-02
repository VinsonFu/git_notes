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

