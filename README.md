# Git  
  
- 初始化資料夾  
```
git init
```
- 加載    
```
git add .   
```  
- 創建節點    
```
git commit -m "describe"   
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
git commit -M <branch>
```
-追蹤遠端分支(下次使用可直接輸入git push)
```
git push -u origin <branch>
```
