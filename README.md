# flutter-build-ios
一键构建ios包，用于在没有苹果开发者证书的情况下将flutter项目打包成ipa文件，打包的ipa文件可以使用个人证书，企业证书进行签名分发，也可以使用各类苹果签名平台进行签名。
主要用于内部项目以及接活，一般为灰黑产类无法直接上架苹果商店的应用。

## 使用
默认输出为iphone.ipa文件
```shell
./ios.sh
```
也可以指定输出的ipa文件名
```shell
./ios.sh lalala
```
这样会输出lalala.ipa文件
