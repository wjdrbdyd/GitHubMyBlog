---
layout: post
current: post
cover:  assets/built/images/git-logo.png
navigation: True
title: Git Error 해결 
date: 2022-01-06 00:53:00
tags: [git-study]
class: post-template
subclass: 'git-study tag-git-study'
author: wjdrbdyd
---

github 디렉토리 아래 실행

1. 초기화
```git-study
$ git init
```
2. 원격 저장소 설정
```git-study
$ git remote add origin [git address]
```
3. gitgub 업로드
```git-study
$ git add .
$ git commit --m "message"
$ git push origin main  
```
4. error 발생 

-원인 : 충돌로 인해 푸쉬 불가?
```git-study
$ git push origin +main
```
실행시 push 성공.

