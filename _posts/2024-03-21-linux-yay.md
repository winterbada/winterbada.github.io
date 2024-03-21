---
layout: single                
title: "아치리눅스 yay 설치" 
categories: linux             
tag: archlinux                
---

#### 아치리눅스 yay 설치 및 사용법

```
sudo pacman -S --needed git base-devel


git clone https://aur.archlinux.org/yay.git

cd yay

makepkg -si

```

- yay --version 버전확인

- yay -S 설치

- yay -Rns 삭제 의존파일포함

- yay -Sua AUR 패키지 업데이트

- yay -Ss [패키지명] 검색

- yay -Qe 설치된 패키지 확인

- yay -Syu 전체 패키지 업데이트


