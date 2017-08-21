# GitHub-Agile-Practice-File

一、設定遠端存儲庫
(1)
git remote add origin
透過 git remote 指令手動加入一個「遠端儲存庫」
這個 origin 名稱是在 Git 版本控管中慣用的預設遠端分支的參照名稱，主要目的是用來代表一個遠端儲存庫的 URL 位址。
(2)
事後修改
git remote set-url origin https://github.com/mormorj/GitHub-Agile-Practice-File
二、下載存儲庫的東西 pull(拉東西下來)
git pull origin master
將線上GitHub Repository裡習Master Branch複製到電腦資料夾

三、
(1)創造一個新的Branch: git checkout -b "Kenny's_Branch"
(2)查看目前的branch: git branch
(3)換回master: git checkout "master"   (不要把東西存在master上)
(4)git commit -m "Commit的名稱"
    git log 看一下commit的檔案
(5)git push origin "Branch名稱"