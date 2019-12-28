# Robosys2019
Raspberry pi3 を使用したデバイスドライバの作成
## 作成したドライバについて
### 使用方法
```
sudo make
sudo insmod myled.ko
echo [コマンド] > /dev/myled0
```
### コマンド
+ 0 : 1つ目のLEDのみを点灯する
+ 1 : 2つ目のLEDのみを点灯する
+ 2 : 3つ目のLEDのみを点灯する
+ 3 : 順番に点灯する（できなかった）
+ 4 : すべてのLEDを点灯する
+ 5 : すべてのLEDを消す
