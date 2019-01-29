一、Git基本命令
1、Git init 
初始化当前目录为本地仓库
2、Git status 
查看当前的状态信息，有没有文件没有提交到缓存中，以及提交到本地仓库
    Git status -s 显示简短的信息
    Git status 显示详细的信息
3、Git add file
将文件加入到缓存中，此时使用Git status -s 查看到该文件已处于缓存中，且标记为A，如果改动该文件的花，再使用Git status -s 将会显示AM标识改动过，需要再次添加到缓存中Git add file 
4、Git commit -m '说明'
将缓存中的文件提交到本地仓库；
git commit -am '说明'
注意：全部文件为 tracked 才行，你新建了文件为 untracked 时，该命令不会执行。
5、Git push
将本地仓库的更新文件上传到远程仓库
