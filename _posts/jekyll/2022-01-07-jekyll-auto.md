---
layout: post
current: post
cover:  assets/built/images/jekyll-logo.png
navigation: True
title: Jekyll 강좌(1) - Jekyll 기본 
date: 2022-01-06 00:53:00
tags: [jekyll]
class: post-template
subclass: 'post tag-jekyll'
author: wjdrbdyd
---

1. jekyll compile
```jekyll
$ bundle exec jekyll serve

2. git add -> commit -> push
```jekyll
$ git add . # 현재 디렉토리 파일 add
$ git commit --m "message" # 커밋 및 메시지 내용
$ git push [-u origin main] 
```
3. travis key 암호화
```jekyll
travis login --pro --github-token [본인 계정 토큰]
travis encrypt --add env --override --com GITHUB_TOKEN=[토큰 키]
```
