# GIT-DEMO

- Markdown 語法
    - https://hackmd.io/@eMP9zQQ0Qt6I8Uqp2Vqy6w/SyiOheL5N/%2FBVqowKshRH246Q7UDyodFA?type=book

### 練習 GIT 相關指令
---


重點指令
=
- git init
    - 初始專案
- git add .
    - U/A/M/D (控管模式)
- git checkout .
    - 恢復修改 (反悔簡易恢復)
    - 任一個 commit-object
- git commit -m "xxxxxxxx"
    - 暫存區 → 倉庫區
- git log / git status
- git chechout -b (新增+切換分支)
- git merge (合併分支)
- git reset --hard HEAD (commit-object)
- git reflog

### 雲端相關
- github 申請新的專案倉庫網址
- git remote add origin https://github.com/xxxxxxxxx/xxxxxxx.git
- git remote -v
- git push -u origin master (第一次遠端需要產生分支)
    - git push (第二次後，可直接push)
    - (使用 git commit --amend) git push -f [強制更新]

- 複製專案
    - git clone https://github.com/xxxxxxxxx/xxxxxxx

- 雲端同步專案到本地端
    - git pull