git init

ls -la //查看

git status //查看檔案是否被更改

git add .  //將所有資料暫存

git commit -m "描述資料"

git remote add origin "https://github.com/age68573/WebAR.git"  //綁定

git push -u origin master 


-----------------------------------------------------------------------------------
git pull origin master
git checkout -b age68573  //新增age68573分支
git checkout age68573     //進入age68573分支
git pull origin master
git add .
git commit -m "commit名稱"
git push origin master age68573 