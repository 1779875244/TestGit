MineGame

Git使用简要说明

#本地文件夹点右键
#选择 git bash

#在本地克隆远程仓库
#git  clone  https://github.com/帐号/远程仓库.git
git  clone  https://github.com/cib2000/TestGit.git

#察看本地仓库状态
git status

#切换到远程仓库
#cd 远程仓库
cd TestGit

git status

#将工作区文件保存到缓存，准备进本地仓库
#git add  本地文件名
#  . 小数点表示当前路径（目录）
git add  .
git status


#将缓存中文件提交到本地仓库
git commit  -m  "本次提交说明（注释）"
git status

#取消最后一次提交
git  reset  HEAD^
git status

#取消最后三次提交
#git  reset  HEAD^^^
#或者命令git  reset  HEAD~3

#从本地仓库恢复到工作区
git  checkout  .
git  status

################################
#将本地仓库同步提交到远程仓库
git config --global user.name "github上面注册的帐户"
git config --global user.email "帐户对应的邮箱地址"

#察看远程仓库主机
git remote -v

#添加远程分支到本地
#git remote  add  origin https://github.com/帐号/远程仓库.git
git remote  add  origin https://github.com/cib2000/TestGit.git

#推送到远程仓库
git push

#有冲突时，强制推送
git push  -f


################################
#从远程仓库更新本地仓库
git pull


################################
#将远程仓库下载到本地全新文件夹 法2
#初始化本地仓库
git init

#git pull https://github.com/帐号/远程仓库.git
git pull https://github.com/cib2000/TestGit.git

/git/cib2000

/git/testgit



