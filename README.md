
# MIKROTIK

# install mikrotik on vps
# نصب میکروتیک روی سرور مجازی

# نصب

```
curl -Ls https://raw.githubusercontent.com/Ptechgithub/Mikrotik/master/install.sh -o install.sh && chmod +x install.sh && ./install.sh
```

.

.
 
.

.

#install on Arvancloud 
# برای نصب روی سرورهای آروان از دستورات زیر استفاده کنید . دستورات را به ترتیب وارد کنید👇
#1

```
sudo wget https://download.mikrotik.com/routeros/7.10/chr-7.10.img.zip -O chr.img.zip
```

#2

```
sudo gunzip -c chr.img.zip > chr.img
```

#3

```
sudo dd if=chr.img bs=1024 of=/dev/vda
```

#4

```
sudo echo s > /proc/sysrq-trigger
```

#5

```
sudo echo b > /proc/sysrq-trigger
```
