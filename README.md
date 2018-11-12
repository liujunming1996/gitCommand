# git 命令
### 创建新的本地仓库
``` bash
    $ git init
```
### 提交历史,显示所有记录
``` bash
    $ git log
```
### 显示指定文件的所有修改
``` bash
    $ git log -p <file>
```
### 谁，在什么时间，修改了文件的什么内容
``` bash
    $ git blame <file>
```

### 创建新的本地分支
``` bash
    $ git branch dev
```
### 切换到dev分支
``` bash
    $ git checkout dev
```
### 将分支合并到当前
``` bash
    $ git merge release
```
### 将当前版本重置到分支中
``` bash
    $ git rebase release
```
### 退出重置
``` bash
    $ git rebase --abort
```
### 解决冲突后继续重置
``` bash
    $ git rebase --continue
```