# website 七分工作，三分学习。
1、Linux C编程一站式学习 https://akaedu.github.io/book/
2、The Scientist and Engineer's Guide to Digital Signal Processing http://www.dspguide.com/pdfbook.htm
3、C Tutorial https://www.tutorialspoint.com/cprogramming/index.htm
分享几款C代码review辅助工具 https://mp.weixin.qq.com/s/-7IAKYxUGUsXlsi-e8GZBw
4、Git 
从Git基础入手成为Git高手 https://mp.weixin.qq.com/s/T3mP2YGzI7WSUr3C9S8ltw
VS Code 中使用Git实践 https://mp.weixin.qq.com/s/PQwMcpDVhKTAci7WDjK9tQ
Git的常用姿势整理 https://mp.weixin.qq.com/s/neQz5JWfPEBDQUgl0huTjA
程序员必备的高效 Git 客户端 Fork https://mp.weixin.qq.com/s/J1AbKb6w3rCnP_HKtmRprQ
5、数据结构和算法
labuladong 的算法笔记 https://labuladong.github.io/algo/home/
labuladong https://www.zhihu.com/people/labuladong
6、工具与环境
VS Code
cmake 与make;
git，gitlab, gitee, github; fork, gitBash;
gdb, g++, gcc;
linux常用命令， vim使用命令
![image](https://github.com/yulinlinlynn/website/assets/94822885/459217fd-24ca-40a0-a541-67f8d41f5286)

7、git， gitBash 与gitLab 笔记
******** 拉代码********
git bash here //找到目标文件夹，删除.git 文件夹，右击选择
git clone https://adasgitlab.***.com/acur/acur101_ps_linux.git // 拷贝一份远程仓库，即下载一个项目。（复制粘贴gitlab地址）
ls //查看当前文件夹内容
cd acur101_ps_linux/    //进入master
git checkout user/alg_microDopplerDetect //进入分支 switch to a new branch
git log  // 查看历史提交记录
******* 发版本**********
git status //查看仓库当前状态，显示有变更的文件
git diff   // 查看所有改动，比较【暂存区】和【工作区】的差异
git diff fileName //查看具体文件改动
git checkout --fileName // 检出文件，将指定文件恢复到最新的提交状态，丢弃未提交的更改 （用于撤销不需要的修改）
git add  .    // 添加文件到【暂存区】
git commit  // 将【暂存区】内容添加到【本地仓库】中
git pull // 下载远程代码并合并
git push // 上传远程代码并合并
git fetch // 从远程获取代码库

***************  *************************
git init //初始化仓库

workspace：工作区
staging area：暂存区/缓存区
local repository：版本库或本地仓库
remote repository：远程仓库

git reset // 回退版本
git rm // 将文件从暂存区和工作去删除
git mv // 移动或命名工作区文件

git remote  //远程仓库操作

git blame  fileName  //以列表形式查看指定文件的历史修改记录

8、单元测试 https://mp.weixin.qq.com/s/VGpcSbgvUssYcYsc5Q7d-A

9、Kaggle https://www.kaggle.com/code/flaviobossolan/stratified-sampling-python

