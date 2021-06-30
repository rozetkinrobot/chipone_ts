# Chipone Touch Screen

This repository contains a Chipone touch screen module, specifically for Chuwi vi10 and hi10 model lines.

This driver should be considered "complete, but unpolished".

I have adapted this driver for linux kernel versions 5.0.0+

# URLs
[Theme on 4pda](http://4pda.ru/forum/index.php?showtopic=692634)

[My profile on 4pda](http://4pda.ru/forum/index.php?showuser=5204805)

# Build and install instructions

0. Install git 
```shell
sudo apt install git
```

1. Clone this repo into your chuwi hi10/vi10:
```shell
git clone https://github.com/rozetkinrobot/chipone_ts.git
```
2. cd into directory:
```shell
cd chipone_ts\
```
3. Make for 
hi10:
```shell
make hi10
```
4. Install:
```shell
sudo make install
```
5. Copy icn8505-HAMP0003.fw into /lib/firmware/chipone/
```shell
sudo mkdir /lib/firmware/chipone && sudo cp icn8505-HAMP0003.fw /lib/firmware/chipone/
```

6. Reboot your chuwi :)

**P.S.** I highly recommend turning off auto-rotate.

# License
Source code in this repository is released under GNU GPL License.<br>
