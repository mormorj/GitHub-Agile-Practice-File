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