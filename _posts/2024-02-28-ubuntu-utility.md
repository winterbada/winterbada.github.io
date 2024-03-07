---
layout: single
title: "우분투 각종 유틸 설치"
categories: linux
tag: ubuntu
---

### 그래픽 카드 확인 및 설치

```
lspci | grep -E "NVIDIA"

sudo ubuntu-drivers devices

sudo apt install nvidia-driver-535

nvidia-smi
```

### 방화벽 확인 및 설치

```
ufw --version

sudo apt install ufw

sudo systemctl enable ufw

sudo systemctl start ufw

sudo ufw status

sudo ufw enable

sudo ufw deny 22/tcp



```

### vim 설치 및 .vimrc 파일 설정

```
sudo apt upgrade vim


set si
set cindent
set shiftwidth=4
set tabstop=4
set ignorecase
set hlsearch
set ruler
set title
syntax on
filetype indent on
set number
set nocompatible
set mouse=a
set fileencodings=utf-8,euc-kr
set fencs=ucs-bom,utf-8,euc-kr
imap jk <Esc>
```

### 나눔 고딕 폰트 및 D2Conding 폰트 설치

- ~/.local/share/fonts 디렉토리에 폰트복사

```
sudo apt-get install fonts-nanum*

sudo fc-cache -f -v

fc-list | grep "D2Coding"
```

### cpu 온도 모니터링

```
sudo apt-get install lm-sensors

sudo sensors-detect

sensors
```

- clang, build-essential, cmus, curl, gnome-tweaks, gimp, kdenlive

- gnome-shell-extension-manager(blur my shell), htop

- python3-pip, python3-tk, ubuntu-restricted-extras

- usb-creator-gtk, neofetch