git init

ls -la //查看

git status //查看檔案是否被更改

git add .  //將所有資料暫存

git commit -m "描述資料"

git remote add origin "https://github.com/age68573/WebAR.git"  //綁定

git push -u origin master 

<<<<<<< HEAD
=======

>>>>>>> gitlearn2
-----------------------------------------------------------------------------------
git pull origin master
git checkout -b age68573  //新增age68573分支
git checkout age68573     //進入age68573分支
git pull origin master
git add .
git commit -m "commit名稱"
<<<<<<< HEAD
git push origin master age68573 

-----------------------------------------------------
情境二: 以遠端為主:重拉pull　

git fetch --all                          #取得所有branch
git reset --hard origin/master  #放棄目前所有staging or unstaging 檔案, 還原成遠端版本origin/master
git pull origin master               #重拉
=======
git push origin master age68573 
>>>>>>> gitlearn2
