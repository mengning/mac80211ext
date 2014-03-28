mac80211ext
===========

extended mac80211


### Setup mac80211ext

* git clone https://github.com/mengning/mac80211ext.git in net/ of linux kernel source code
* add [source "net/mac80211ext/Kconfig"] below [source "net/mac80211/Kconfig"] in net/Kconfig
* add [obj-$(CONFIG_MAC80211EXT) += mac80211ext/] below [obj-$(CONFIG_MAC80211) += mac80211/] in net/Makefile
* make menuconfig and choose Networking support/Wireless/mac80211ext
* make
