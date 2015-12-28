# Command
Useful command line for daily code.


文件说明：
imagesetGenerator.sh
把png格式的图片，以1/3,2/3的比例批量压缩图片，并生成Xcode中imageset的格式，拖入文件夹中即可识别。
详细说明可以参考：http://www.cocoachina.com/ios/20151120/14314.html

imagesetToolbar.sh
按照苹果官方文档的建议生成指定像素的图片  @2x:44x44 @3x:66x66

imagesetTabbar.sh
按照苹果官方文档的建议生成指定像素的图片  @2x:50x50 @3x:75x75

imagesetAppIcon.sh
按照苹果官方文档的建议生成指定像素的图片 @2x:120x120 @3x:180x180  appStore:1024x1024

以上主要针对iphone，如果是ipad的话需要另外个性，具体可以参考：
https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/MobileHIG/IconMatrix.html#//apple_ref/doc/uid/TP40006556-CH27-SW1



/* Mac下无权限执行Shell命令的处理方法
新建一个test.sh，内容：
#!/bin/bash
echo 'hello world'

保存，运行如下命令：
chmod +x test.sh 
./test.sh
*/