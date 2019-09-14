# ValidateEmail
检测大量邮件的工具

![operationGuide](https://ftp.bmp.ovh/imgs/2019/09/195e730ddf0ac060.gif)

---

邮件检测服务大多数都有每小时的检测限制，使用起来很不爽。

使用了 http://tool.chacuo.net/mailverify 的邮件检测服务，它没有每小时的次数限制，只是会提示不要调用太频繁。程序内做了延时处理来避免调用频繁的问题。

对于检测失败的邮箱，会做一定次数的重试，默认10次，可以在网页里做修改.

---

本地开发的环境是osx和chrome，需要禁用安全策略以实现跨域。其他浏览器没有尝试。

For mac
```bash
open -n /Applications/Google\ Chrome.app/ --args --disable-web-security --user-data-dir=/Users/luchen/Documents/MyChromeDevUserData
```

For win
```
chrome.exe --user-data-dir="C://MyChromeDevUserData" --disable-web-security
```