# ValidateEmail
检测大量邮件的工具

![operationGuide]](https://github.com/cclc/ValidateEmail/ValidateEmailOperation.gif =642x418)

邮件检测服务大多数都有每小时的检测限制，使用起来很不爽。

使用了 http://tool.chacuo.net/mailverify 的邮件检测服务，它没有每小时的次数限制，只是会提示不要调用太频繁。

对于检测失败的邮箱，会进行一定次数的重试，默认10次，可以在网页里做修改.