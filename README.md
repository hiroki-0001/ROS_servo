# ROS_servo
## 2020 robot system homework 2

rosとpigpioを用いてサーボモータを動かします。

---
## 動作環境

### OS : ubuntu 20.04 server

### ROS : Noetic

---
## 使用したもの

・ [Raspberry Pi4 model B 4GB](https://akizukidenshi.com/catalog/g/gM-14778/)　× 1

・ [Futaba S3003 (サーボモータ)](https://www.rc.futaba.co.jp/servo_air/analog/s3003.html) × 1

   [*S3003のデータシート](http://www.es.co.th/schemetic/pdf/et-servo-s3003.pdf)
   
・ [オスメスジャンパーピン](https://akizukidenshi.com/catalog/g/gC-08934/) × 3

---
## 回路図

---
## デモ動画

---
## インストール方法

### 本パッケージ

```sh
$ cd ~/catkin_ws/src
$ git clone https://github.com/Hiroki-Noguchi0001/ROS_servo.git
$ cd ~/catkin_ws
$ catkin_make
$ source ~/.bashrc
```

### pigpio

[こちらのサイトを参考しました](http://abyz.me.uk/rpi/pigpio/download.html)

```sh
$ wget https://github.com/joan2937/pigpio/archive/master.zip
$ unzip master.zip
$ cd pigpio-master
$ make
$ sudo make install
```
unzipがインストールされていない場合は
```sh
$ sudo apt install unzip
```
でインストールしてください。

---
## 使用方法


---
## ライセンス

### ROS : [BSD 3-Clause](https://github.com/Hiroki-Noguchi0001/ROS_servo/blob/master/LICENSE)

### pigpio : [The Unlicense](https://github.com/joan2937/pigpio/blob/master/UNLICENCE)
