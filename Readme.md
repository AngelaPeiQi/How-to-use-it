# 标题
    Github入门使用教程

## 一、建库与提交

* 1、准备工作：
  * 注册github账号；
  * 电脑上安装git bash；
* 2、依次点击 "Repositories"，"New"，输入"Repository name" 和 "Description(optional)"，点击"Create repository"，即可创建一个空白仓库；
* 3、在桌面（或者任意你想要的问题），打开cmd；
* 4、从服务器上克隆一个库：git clone https://github.com/AngelaPeiQi/Exercise.git ，执行这个命令后，目录下会多一个文件夹；
* 5、在克隆的空白文件夹里编辑or放入你想要的文件，例如：编写一个README.md文件；
* 6、查看当前仓库状态：git status
* 7、添加你想要的提交的文件，例如：：git add README.md
* 8、提交到本地仓库，git commit -m "提交信息"  提交信息最好能体现修改了什么；
* 9、提交到远程仓库，git push ，这一步需要输入github的用户名和密码；
* 10、设置用户名，config --global user.name "你的用户名"
* 11、设置邮箱，config --global user.email "你的邮箱"

## 二、删除

### 删除库
* 进入需要删除的仓库中，找到"Settings"，即仓库设置；
* 在仓库设置里拉到最底部，找到"Danger Zone"即危险区域；
* 点击"Delete this repository"，即可删除该仓库；

### 删除仓库里的某个文件or文件夹
* 将github上的仓库，克隆到本地；
* 在本地文件夹中打开cmd；
* 查看此文件夹下的文件和目录：dir
* 删除本地仓库文件：git rm 文件名
* 删除本地文件夹：git rm -r 文件夹名
* 在终端中提交本次修改：git commit -m "备注"
* 把删除的文件恢复到最新版本：git checkout
* 将本地内容推送到远程仓库：git push

## 三、README语法

* https://blog.csdn.net/qq_31796651/article/details/80803599
  
* 预览：
  * Vscode中安装插件：Markdown All in one
  * 快捷键：ctrl + shift + V

## 四、其他小技巧

* github访问慢问题的解决：https://zhuanlan.zhihu.com/p/93436925