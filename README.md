# Git  
  
- 初始化資料夾  
```
git init
```
- 加載    
```
git add .   
```  
- 自動pull並更新至最新(git pull+git fetch)
```
git pull -r
```
- 創建節點    
```
git commit -m "describe"   
```
- 新增連結  
```
git remote add <name> <url>
```
- 推上git   
``` 
git push <連結名稱> <分支名稱>
``` 
- 若無法推上(要求先pull)  可使用   
```
git push -f <連結名稱> <分支名稱>  
```
- 創建SSH KEY  
```
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```
>> 未來可使用SSH連線，即可不用輸入帳號密碼

- 更改連結branch
```
git branch -m <branch>
```
- 切換branch分支
```
git switch <branch_b>
```
- 追蹤遠端分支(下次使用可直接輸入git push)
```
git push -u origin <branch>
```
- 若出現modified: <dir> (modified content, untracked content)  

```
git rm -rf --cached <dir>
```
- clone 資料夾(指定branch)
```
git clone <repo URL> -b <branch name>
```
- 排除某項程式
```
git add -u
git reset -- main/dontcheckmein.txt
```
- pull檔案(但不想改變現有工作)
```
git stash
git pull
git stash pop
```
