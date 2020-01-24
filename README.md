# IOSPolling
An open source library used for long polling in IOS


# Things to do before using the SDK

Build libcurl for iOS development.
This script will generate static library for armv7 armv7s arm64 i386 and x86_64.

please download libcurl from here: http://curl.haxx.se/download.html


Usage

```
curl -O https://curl.haxx.se/download/curl-7.64.0.tar.gz 
tar xf curl-7.64.0.tar.gz
cd curl-7.64.0
curl https://raw.githubusercontent.com/sinofool/build-libcurl-ios/master/build_libcurl_dist.sh |bash
```
*Note* - You can use the latest version
