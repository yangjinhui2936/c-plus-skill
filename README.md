# c++
This project is used to summarize c++ knowledge.It includes basic grammar knowledge and application scenarios


#How to get this hub to local
## 将本地代码下载到本地
```shell
git clone https://github.com/yangjinhui2936/c-plus-skill.git
git remote add origon https://github.com/yangjinhui2936/c-plus-skill.git
 ```
### 设置ssh key
    ssh-keygen -t rsa -C "邮箱地址"
    将~/.ssh 目录下id_rsa id_rsa.pub 内容复制到 github中是SSH and GPG keys 中，需要新建New SSH key
    1. 测试是否成功连接GitHub
    `ssh -T git@github.com `
    2. 提示`git@github.com: Permission denied (publickey)`
      chmod 600 ~/.ssh/*
#### 添加修改并提交到github网站
```shell
git add .
git commit -m "commit content"
git push -u origin  //代码提交
git branch //可查看当前分支  如果显示main则是正确的

git remote -v   //查看远程地址
```