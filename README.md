---
layout: home
title: GitHub Pages 끄적끄적
permalink: /
---

## Jekyll 이용하여 테마 적용하기

### 💻 macOS 에서 ruby 설치

>💡Silicon macOS에서 기본 설치 되어있는 Ruby를 확인해야한다. ``witch ruby``

1. `gem install jekyll` 를 프로젝트 디렉토리에서 진행
   - 기본 디렉토리 구조 `__layouts`, `__posts`, `__pages` 내용 확인
2. __zshrc__ 에 `chruby` 스크립트 경로 내용 추가
3. `jekyll` , `bundle`이 terminal 에서 정상적으로 동작하는지 확인
4. gitbook 테마를 적용
   - 현 테마 버전에 없는 csv, logger gem 추가
2. 페이지 업데이트 내용 확인
```shell
  bundle exec jekyll serve —livereload
``` 
- 통해 [127.0.0.1:4000](http://localhost:4000) 으로 변경 상황 확인

> Jeklly 디렉토리 구조 및 정의, 명명 규칙 https://jekyllrb-ko.github.io/docs/structure/
## 🌐 웹페이지

- __https://kangseokjoo.github.io__
## 수정된 내용 자동 반영
### gh-pages 브렌치, github Actions
### ~~npm i gh-pages~~ 
