# 動作環境
- 本体
  - Raspberry Pi 3 Model B+
- カメラモジュール
  - LABISTS カメラモジュール RPi Camera B01
```sh
$ lsb_release -a
No LSB modules are available.
Distributor ID:	Raspbian
Description:	Raspbian GNU/Linux 10 (buster)
Release:	10
Codename:	buster
```

# インストール
```sh
$ sudo apt update && sudo apt upgrade

# OpenCVをインストール
$ pip install opencv-python

# OpenCVに関連するライブラリをインストール
$ sudo apt-get install libhdf5-dev libhdf5-serial-dev libhdf5-103 libatlas-base-dev
```

