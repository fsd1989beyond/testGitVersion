### 工程区域
- 版本库（Repository）  
    隐藏目录.git， 可以叫本地仓库
- 工作区(Working Directory)  
    日常工作的代码文件或者文档所在的文件夹
- 暂存区（Stage）  
    一般存放在工程根目录 .git/index 文件中，暂存区也可以叫索引
    
### 文件状态
- 已提交(commited)  
    该文件已安全的保存在本地仓库中了
- 已修改(modified)  
    修改了某文件，但还没有提交保存
- 已暂存(staged)  
    把已修改的文件放在下次提交时要保存的清单中
  
### 常用命令

- 工程准备 git init/git clone
- 查看工作区 git diff/ git status


- 增删改文件到暂存区 git add/git rm/git mv
- 提交更改的文件 git commit
- 推送到远端仓库 git push


- 查看日志 git log
 
- 分支管理 
    - 列出本地分支 git branch 
    - 新建分支 git checkout -b 
    - 删除分支 git branch -d 
    - 切换分支 git checkout
    - 跟新分支 git pull
    - 合并分支 git merge
- 撤销操作
    - 强制会退到历史节点 git reset
    - 回退本地所有修改到未提交的 git checkout    
- 分支合并 
    - 合并目标分支到当前分支 git merge/git rebase




### IDEA 中git
- 提交时中忽略某些文件
```
 1.新建一个changelist，名字为 忽略；
 2.提交代码时，选中想忽略的文件，右键 Move to Another Changelist，这时选择第一步已经建好的 忽略，下次再提交时，
   只要 Change list选择Default，就不会出现已经忽略的文件。
```

- 恢复本地文件为远端版本
  git checkout  LicenseAdaptLicense.java