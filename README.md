XMRIG CROT
Masukin command satu demi satu !!!

DOWNLOAD TERMUX
https://f-droid.org/repo/com.termux_118.apk


1.
```
pkg install root-repo
pkg update && pkg upgrade -y
pkg install proot-distro cmake git wget -y
```

2.
```
proot-distro install debian-oldstable
```

3.
```
proot-distro login debian-oldstable
```

4.
```
apt update && apt upgrade -y
```

5.
```
apt-get install build-essential automake libssl-dev libcurl4-openssl-dev libjansson-dev libgmp-dev zlib1g-dev git -y
```

6.
```
wget -q https://github.com/Rssxcv/xxx/blob/main/xmrig.tar.gz && tar -xvf xmrig.tar.gz && chmod +x xmrig
```

7. PILIH SC
>>> SC DEFAULT
```
./xmrig -a ALGOCOIN -o POOLLU -u WALLETLU -p x -t$(nproc --all)
```

>>> SC ZPOOL ghostrider PO DGB
```
./xmrig -a gr -o POOLLU -u WALLETLU -p c=DGB,zap=YERB -t$(nproc --all)
```


SILAKAN COLIKAWAN !!!!!
