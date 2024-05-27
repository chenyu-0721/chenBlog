---
title: hexo筆記
date: 2024-05-25 03:01:13
tags:
  - hexo
  - 筆記
---

## 創建新的 md 檔

```
hexo new '檔名'
```

## 創建新的 page tags

```
hexo new page '連結名字'
exanple：" hexo new page about"
```

## 啟動專案

```
hexo serve
```

## Git

1. git -v <!-- 看 git 版本-->
2. npm install hexo-deployer-git --save
3. 到 github 上 new 一個專案
4. 到 \_config.yml 找到 deploy 並把下方的資訊複製貼上 repo 是指 git 的網址
   repo 的網址是 git 專案的網址

```

deploy:
type: git
repo: https://github.com/chenyu-0721/chenBlog
branch: gh-pages
message: "update"

```

5. 到 \_config.yml 大概是第 16 行
   這是指 網址 要打上去 https://使用者.github.io/專案名稱

```
# URL
## Set your site url here. For example,
if you use GitHub Page, set url as 'https://username.github.io/project'

url: https://chenyu.github.io/chenBlog
```

6. git clean
7. git deploy
8. 就大功告成了
