# weihumis   ios  app  install
1、制作plist文件
指定ipa包下载地址；
指定应用小图、大图下载地址；
指定开发者用户名、app版本号、安装提示语

2、plist需要用https协议，如果自由服务器不支持，可以上传到github等第三方服务器来下载plist文件
github创建项目
上传plist文件
（也可以吧ipa包、图片等也上传到github上，如果自己有服务器和公网ip，也可以放到自己服务器上）
点开文件，点击raw按钮生成plist文件下载地址
（https://raw.githubusercontent.com/zjn-helloWorld/weihuios/master/weihu.plist）

制作ios下载应用能识别的地址（加上前缀itms-services://?action=download-manifest&url=）
itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/zjn-helloWorld/weihuios/master/weihu.plist

3、制作二维码

4、用苹果原生浏览器下载plist安装ipa包

参考地址：https://segmentfault.com/q/1010000000623121
		  https://blog.csdn.net/Harvey_DHui/article/details/96099464