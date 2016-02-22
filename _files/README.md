## 参考

* https://github.com/sh0/recfsusb2n
* http://arkouji.cocolog-nifty.com/blog/ktvfsusb2/
* http://d.hatena.ne.jp/katauna/searchdiary?word=recfsusb2n

## ビルド準備

```
apt-get install -y \
  make gcc g++ libboost-filesystem-dev libboost-thread-dev
```

## ./_files/

* 2445882.zip (パッチ)
* Makefile
* 89-tuner.rules (/etc/udev/rules.d/89-tuner.rules)
