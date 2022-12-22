# 认识终端、Shell、命令行
### 终端和Shell
- 终端，就是Mac上的Terminal.app，或者一些别的终端.
软件打开终端之后，我们进入的就是Shell
Shell的作用是将你输入的命令解释并执行。
### Shell的工作路径
- 查看命令前面，会有代表当前路径的地方。这说明，每条命令其实都是在某个文件夹下执行的。
### 常用命令
```
which <command> # 查看Shell如何解析这条命令
echo <String> # 原封不动的输出一个字符串
echo $SHELL # 输出一个变量的值，查看当前使用的Shell

pwd # 显示当前的工作路径 pirnt working directory
cd <dir> # 更改路径 change directory

ls # 列出当前路径下的文件和文件夹
ls -a # 列出当前路径下的所有文件和文件夹
open <file> # 使用默认程序打开文件
mkdir <folder_name> # 在当前目录下新建文件夹
touch <filename> # 在当前目录下创建纯文本文件
cat <filename> # 显示某纯文本文件的内容

mv/cp <origin_file> <dest_file> # 重命名/移动/复制文件
rm <file> # 删除文件（谨慎使用）
rm -rf <dir> # 删除文件夹（谨慎使用）

clear # 清除终端屏幕上的内容

```
```
⌃C # 结束当前命令
↑ # 调出上次执行的命令 还有↓
```