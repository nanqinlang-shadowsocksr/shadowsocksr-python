## installation script
[![build](https://github.com/SuzukazeAoran/SVG/blob/master/build%20passing.svg)](https://github.com/nanqinlang-shadowsocksr/shadowsocksr-python)
[![language](https://github.com/SuzukazeAoran/SVG/blob/master/language-python-blue.svg)](https://github.com/nanqinlang-shadowsocksr/shadowsocksr-python)
[![author](https://github.com/SuzukazeAoran/SVG/blob/master/author-nanqinlang-lightgrey.svg)](https://github.com/nanqinlang-shadowsocksr/shadowsocksr-python)
[![license](https://github.com/SuzukazeAoran/SVG/blob/master/license-GNU3.0-orange.svg)](https://github.com/nanqinlang-shadowsocksr/shadowsocksr-python)

powered by nanqinlang  
`wget -N --no-check-certificate https://github.com/nanqinlang-shadowsocksr/shadowsocksr-python/releases/download/2.2/ssr-setup_2.2.sh && chmod +x ssr_setup_2.2.sh && bash ssr_setup_2.2.sh install`
wiki：https://www.nanqinlang.com/shell-ssr_setup.html  
releases：https://github.com/nanqinlang/shadowsocksr/releases
## memories
greatful thanks to @breakwa11
even if what a hatred somebody for breakwa11, things those who did are indeed too much  
still wish littlesister can hold a peaceful future, `thanks for your everything`  
respect her choice, `do change if you wanna change`  
there is no smoothing way, `to meet or not to meet, that's a fortune`
## the original program
according to the remain legacy by breakwa11
### Server
- Install
    apt-get install git / yum install git
    git clone https://github.com/shadowsocksr/shadowsocksr.git

If you clone it into "~/shadowsocksr"  
move to "~/shadowsocksr", then run:
    bash initcfg.sh

move to "~/shadowsocksr/shadowsocks", then run:
    python server.py -p 443 -k password -m aes-128-cfb -O auth_aes128_md5 -o tls1.2_ticket_auth_compatible

Check all the options via `-h`.

You can also use a configuration file instead (recommend), move to "~/shadowsocksr" and edit the file "user-config.json", then move to "~/shadowsocksr/shadowsocks" again, just run:
    python server.py

To run in the background:
    ./logrun.sh

To stop:
    ./stop.sh

To monitor the log:
    ./tail.sh
### client
* [Windows] / [macOS]
* [Android] / [iOS]
* [OpenWRT]

Use GUI clients on your local PC/phones. Check the README of your client for more information.

Documentation  
You can find all the documentation in the [Wiki]

License  
Copyright 2015 clowwindy

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at  
    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software  
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT  
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the  
License for the specific language governing permissions and limitations  
under the License.

Bugs and Issues

[Issue Tracker]  
[Android]:           https://github.com/shadowsocksr/shadowsocksr-android  
[Build Status]:      https://travis-ci.org/shadowsocksr/shadowsocksr.svg?branch=manyuser  
[Debian sid]:        https://packages.debian.org/unstable/python/shadowsocks  
[iOS]:               https://github.com/shadowsocks/shadowsocks-iOS/wiki/Help  
[Issue Tracker]:     https://github.com/shadowsocksr/shadowsocksr/issues?state=open  
[OpenWRT]:           https://github.com/shadowsocks/openwrt-shadowsocks  
[macOS]:             https://github.com/shadowsocksr/ShadowsocksX-NG  
[Travis CI]:         https://travis-ci.org/shadowsocksr/shadowsocksr  
[Windows]:           https://github.com/shadowsocksr/shadowsocksr-csharp  
[Wiki]:              https://github.com/breakwa11/shadowsocks-rss/wiki  
