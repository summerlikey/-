# 笔记
git使用笔记  
# 同步远程仓库最新改动到本地
1.查看远程仓库地址 git remote -v  
2.从远程仓库获取最新版本到本地 git fetch origin master:temp  
3.比较temp文件和本地仓库又什么不同 查看不同 git diff temp  
4.确认后更新本地仓库  git merge temp  
# 个人网站
 进行项目主页 点击setting 点击change theme 访问用户名.github.io/仓库名/ 
 https://summerlikey.github.io/summer/

1. ## 首先查看当前远程仓库地址

```bash
git remote -v
```

从远程仓库获取最新版本到本地

```
git fetch origin master:temp
```

作用是将远程仓库的master分支下的代码下载到本地分支上面，更新完后可以去掉本地temp文件夹

比较temp与本地仓库

```
git diff temp #查看不同
```

确认后，更新本地仓库

```
git merge temp #更新本地仓库
```