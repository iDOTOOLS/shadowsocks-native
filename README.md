#Build ShadowSocks native libs
Make sure you have installed Android NDK.


##Build
```
ndk-build
```

##Copy to the Android project
Copy the lib folders in `/libs` to `$ANDROID_PROJECT/app/src/main/assets`





## OPEN SOURCE LICENSES

* shadowsocks-libev: [GPLv3](https://github.com/shadowsocks/shadowsocks-libev/blob/master/LICENSE)
* tun2socks: [BSD](https://github.com/shadowsocks/badvpn/blob/shadowsocks-android/COPYING)
* redsocks: [APL 2.0](https://github.com/shadowsocks/redsocks/blob/master/README)
* OpenSSL: [OpenSSL](https://github.com/shadowsocks/openssl-android/blob/master/NOTICE)
* pdnsd: [GPLv3](https://github.com/shadowsocks/shadowsocks-android/blob/master/src/main/jni/pdnsd/COPYING)
* libev: [GPLv2](https://github.com/shadowsocks/shadowsocks-android/blob/master/src/main/jni/libev/LICENSE)
* libevent: [BSD](https://github.com/shadowsocks/libevent/blob/master/LICENSE)