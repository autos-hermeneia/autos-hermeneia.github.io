
# Jekyll Starter with Journal / Notes / Library / Study / Contact

## How to use
1) Create a repo named `USERNAME.github.io` (or any repo for a project site).
2) Upload all files in this folder to the repo root and commit.
3) In Settings → Pages, set Branch = `main`, Folder = `/`.
4) Visit `https://USERNAME.github.io`.

## Write a post
- Create a Markdown file in `_posts` named `YYYY-MM-DD-title.md`.
- Add a front matter block at the top:
```
---
layout: post
title: "제목"
date: 2025-08-24 12:00:00 +0900
categories: journal   # or notes / study / books / films / songs / words
---
```
- Write your content below in Markdown.
- Images: put them in `assets/` and reference with `![](/assets/your-image.jpg)`.

## Category pages
- Journal: `/journal/`
- Notes: `/notes/`
- Study: `/study/`
- Library: `/library/` (aggregates books, films, songs, words)

## Privacy
- This starter contains only placeholders. You control all content.
