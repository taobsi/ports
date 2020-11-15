# Ports
My CRUX linux ports collection.

## Setup
```
curl -OO https://raw.githubusercontent.com/taobsi/ports/main/taobsi.{httpup,pub}
mv taobsi.{httpup,pub} /etc/ports
ports -u taobsi
```

```
echo prtdir /usr/ports/taobsi >> /etc/prt-get.conf
```
