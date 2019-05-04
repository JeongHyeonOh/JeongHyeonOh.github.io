---
layout: post
title: "the First Penguin."
date: 2019-05-04 20:34:26
image: '/assets/img/'
description: '첫 깃헙 블로그 글 연습.'
main-class: 'jekyll'
color: '#B31917'
tags:
- jekyll
categories:
twitter_text: 'Put your twitter description here.'
introduction: 'Put your description here.'
---

처음 했던 실수들
1. _config.yml
 - url에 ""안감싸기
 - baseurl수정 안해서 css적용 안됐음
2. 파일명 형식 안지켜서 새로 포스팅한 페이지가 노출이 안됨
 - YYYY-MM-DD-FILENAME.MD <= 여기서 날짜를 잘못적음
 
3. 깃 커밋 및 푸시 방법
 - cd work folder
 - git status // 깃 상태 확인
 - git add * // 새로 만든 파일을 커밋 할 수 있게 해줌
 - git status
 -
 - git commit -m "commit comment"
 - git status
 - git remote -v //현재 리모트 저장소 확인, 커밋전 제대로 올리는 건지 확인
 - git push //git에 반영. 이제 수정한 내용이 보일것임

q1. 현재 시각 받아오는 방법이 있을 텐데?

따라해봅시다.

[jekyll-gh]: https://github.com/mojombo/jekyll
[jekyll]:    http://jekyllrb.com
