[原创]字节全系App抓包

直接hook cronet协议 附Frida脚本

使用方法 先启动目标app再 frida -U -f 包名 -l 脚本路径

例子：frida -U -f com.ad2001.frida0x1 -l test.js(test.js是脚本的绝对路径)

先开脚本再用charles或者burp suite抓包就能看到cronet协议的传输明文了
