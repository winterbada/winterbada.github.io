---
layout: single
title: "리눅스 우분투 세팅"
categories: linux
tag: ubuntu
---

#리눅스 설치후 세팅해야 할것들

1.소프트웨어 gufw(방화벽) 설치후 활성화

2.소프트웨어 센터 다운로드 주소 변경 ftp.daum.net

3.기본 업데이트(한글설치)

```
sudo apt-get upgrade
sudo apt-get update


sudo apt upgrade ibus-hangul
```

4.기본 코덱 설치

```
sudo apt install ubuntu-restricted-extras
sudo apt-get update
```

5.git 설치후 토큰 설정

```
sudo apt-git install git (패키지 리스트 업데이트)
sudo apt install git


git --version 


git config --global user.name [이름]
git config --global user.mail


git clone [url]


git init
git status

git add -A
git commit -m "메세지"
git push

git push -u origin master
git remote add origin [url]

git push origin main
username :
pass: [토큰입력]
```

6.그래픽 카드 드라이버 (독점) 설치

7.리듬박스 (플러그인-대체도구모음)
