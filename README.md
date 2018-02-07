# gittest

> common use
```c
git clone https://github.com/liu578/java_recruit.git
git add . //add all documents in pwd
git commit -m "updated commit" //submit to local repository
git push //upload to remote repository
```

>manual
```c
//git push <远程主机名> <本地分支名>  <远程分支名>
git push origin master：refs/for/master

git remote add origin https://github.com/liu578/java_recruit.git //name the remote repository address as origin
git push -u origin master //将本地的master分支推送到origin主机，同时指定origin为默认主机，后面就可以不加任何参数使用git push了 所以第一次push用-u 之后直接git push即可

git add README.md
git config --list //查看配置信息
git status //查看项目状态信息
git branch //查看项目分支
git checkout -b host//添加一个名为host的分支
git checkout master //切换到主干
git merge host //合并分支host到主干
git branch -d host //删除分支host
```

