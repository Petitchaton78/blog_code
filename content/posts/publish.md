---
title: "发布"
date: 2022-04-15T18:56:56+08:00
draft: false**
---

# 发布流程基本代码

## 1 创建新post，名称自选

cd blog_loveit

hugo new posts/daily_note_n.md

cd content/posts

./daily_note_n.md

Modify and save

## 2 生成可发布代码

cd blog_loveit

hugo -- generate public file （must in parent directory) 

## 3 git 同步

cd ../public

git add .

git commit -m "modify"

git push



