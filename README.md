# AUR_Mirror
A Chinese Mirror of Source Files Required in AUR

## Introduction
This project helps to improve the download speed of source file that required when use AUR, based on the original PKGBUILD file, change the url and related stuff into [aliyun](https://mirrors.aliyun.com), [USTC](https://mirrors.ustc.edu.cn) and others.

## Installation

Append this repo into ```/etc/pacman.conf```

	[AUR_mirror]
	SigLevel = Optional TrustAll
	Server = https://github.com/skychan/AUR_Mirror
