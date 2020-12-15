绑定本地仓库到GitHub：

1.进入文件夹
2.将文件夹初始化为git仓库：
  git init
3.查看当前git仓库有无绑定的远程仓库：
  git remote -v
4.没有，则可以绑定:
  git remote add origin 仓库地址
  若绑错，则移除绑定：
  git remote remove origin
5.绑定完成，即可提交（三部曲）