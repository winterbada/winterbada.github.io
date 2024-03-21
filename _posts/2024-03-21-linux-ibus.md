---
layout: single
title: "아치리눅스 한글입력 ibus"
categories: linux
tag: archlinux
---

### 한글 입력기 설치 순서

```
sudo vi /etc/locale.gen

```

- en_US.UTF-8 ko_KR.UTF-8 주석제거

### ibus 설치 및 설정파일 작성

```
sudo pacman -S ibus ibus-hangul

vi ~/.xprofile

작성하고 내용 입력

export GTK_IM_MODULE=ibus
export XMODIFIERS=@im=ibus
export QT_IM_MODULE=ibus

ibus-daemon -drx
```


