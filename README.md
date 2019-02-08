# Nali

## Installation

```bash
$ ./configure
$ make
# make install
```


## Usage

`Nali` required related packages installed. For example, in order to use `nali-dig` and `nali-nslookup` you need to have `dig (dnsutils)` installed.

```
$ nali [IP] # Get IP Geolocation Informatiuon
$ ... | nali # Parse IP from other commands' output
$ nali-update # Update QQWry.Dat From QQWry Mirror
$ nali-ping # The same as 'ping | nali'
$ nali-dig # The same as 'dig | nali'
$ nali-traceroute # The same as 'traceroute | nali'
$ nali-tracepath # The same as 'tracepath | nali'
$ nali-nslookup # The same as 'nslookup | nali'
```

![](https://i.loli.net/2019/02/08/5c5d68e6a6bfd.png)

## Copyright

The original version of `Nali` was made by `<https://www.surfchen.org/nali>`, optimized by [Meteoral](http://liuqingwei.com/). What you are looking at now is a fork version of `Meteoral/Nali` modified by [SukkaW](https://skk.moe), who is maintaining a [qqwry-mirror](https://qqwry.mirror.noc.one) and add that mirror to `Nali`.
