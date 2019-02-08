README
===
Conky is a great system momitor, it can show what you want system information on desktop.

It just try in VMware with Ubuntu 18.04, maybe will try in other system, maybe ......

## install Conky
> sudo apt update
> sudo apt install conky-all

after install conky, you will get a default conky setting file at `/etc/conky/conky.conf`

## Use this repository
clone this repository, than copy file `.conkyrc` and path `.conky` to `~`

Try start in terminal, it should run
> conky &

## autorun on boot
1. find `startup Applications Preferences`
2. Add a new applications
    * Name: conky <anything OK>
    * Command: conky &

## more information
* [Conky variables](http://conky.sourceforge.net/variables.html)

* [Deviant Art Link](https://www.deviantart.com/?qh=&q=conky)

* [openDesktop Link](https://www.opendesktop.org/search?projectSearchText=conky)