# 安装,配置git
 - macOS自带Git，使用下方命令查看Git的版本
```
git --version
```
用更新版本的Git，需要使用Homebrew进行安装，这里不多说，因为自带的版本版本已经足够了

- 添加Git用户名和邮箱
```
## 查看
git config user.name
git config user.email

## 修改
git config --global user.name <your name>
git config --global user.email <your email>
```
 - 创建版本库,在某个文件夹下执行：
 ```
 git init
 ```

# git的使用
- git的基本命令符：

  - 工作区→暂存区
  ```
  git add <file> 
  ```
  - 暂存区→本地版本库
  ```
  git commit -m "messege"
  ```
  ```
  注：<message>记录你这次commit修改的主要内容。使用英文或中文都可以，个人推荐使用英文
  ```
  - 查看日志
  ```
  git log
  ```  
  - 查看每个区的状态
  ```
  git status
  ```
  - gitignore
  ```
  touch .gitignore
  vim .gitignore
  ```
  ```
  注：vim添加好要屏蔽的后缀后：
    1.按esc退出编辑
    2.：wq   保存并退出，(不要问我为啥知道的)
  ```

# 远程仓库
- 连接远程仓库
```
查看SSH 公钥：cat ~/.ssh/id_rsa.pub

如果没有需要先使用命令ssh-keygen -o生成
```
- 将本地仓库上传到代码托管平台\
1.先连接git的仓库(具体不多讲)\
2.用命令上传项目
```
git push
```