# 버튜버 데뷔 프로젝트 블로그

GitHub Pages(Jekyll, minima 테마) 블로그. 로컬에 Ruby가 없어도 GitHub가 빌드한다.

## 게시 방법

1. 이 폴더를 저장소로 올린다.
   - 사용자 사이트: 저장소 이름을 `BudongJW.github.io` 로 하면 https://budongjw.github.io/ 에 열림 (`_config.yml` 의 `baseurl: ""`)
   - 소속사 조직 사이트: GitHub 조직을 만든 뒤 `<조직>.github.io` 저장소, `url` 을 `https://<조직>.github.io` 로
   - 프로젝트 사이트: 다른 이름의 저장소면 `baseurl: "/<저장소 이름>"`
2. 저장소 Settings > Pages > Source를 **Deploy from a branch**, `main` / `/ (root)` 로 설정. push할 때마다 GitHub가 Jekyll로 빌드해 게시(보통 1~2분)

## 글 쓰기

`_posts/YYYY-MM-DD-영문-제목.md` 파일을 만든다. 파일 이름의 영문 제목이 주소가 된다.

```markdown
---
layout: post
title: "글 제목"
date: 2026-12-01 21:00:00 +0900
categories: [devlog]
---

본문
```

| 페이지 | 파일 |
|---|---|
| 프로젝트 소개 | `about.md` |
| 방송 소프트웨어 목록 | `software.md` |
| 참여 안내(소속 모집) | `join.md`. 신청서 링크는 모집이 열릴 때 추가 |
