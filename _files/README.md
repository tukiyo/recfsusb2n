## 参考

* https://github.com/sh0/recfsusb2n
* http://arkouji.cocolog-nifty.com/blog/ktvfsusb2/
* http://d.hatena.ne.jp/katauna/searchdiary?word=recfsusb2n

## ./_files/

* 2445882.zip (パッチ)
* Makefile
* 89-tuner.rules (/etc/udev/rules.d/89-tuner.rules)

## build

```
apt-get install -y \
  make gcc g++ libboost-filesystem-dev libboost-thread-dev

git clone https://github.com/tukiyo/recfsusb2n
cd recfsusb2n/src
unzip ../_files/2445882.zip
cp -a ../_files/Makefile .
make
```

