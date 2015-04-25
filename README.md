#MakerD3Printer
中文本土化的3D打印机控制系统 
编不下去， 好吧！我坦白，就是reprtier 的固件，我中文化了！ 
最新版0.9.2.3. 支持Arduino due 32位的主板。
还在用8位avr（mege2560） 吗？ 你落伍了。 汉化方法我会有时间就放出来来的，汉化不完全，Marlin固件我也会立马汉化，耐心等待。 

注意：

固件的设置方法就是到 http://www.repetier.com/firmware/v092/index.html 配置你的3D打印机，然后下载Configuration.h 到我的固件底下替换文件就是了。 

！！！！！！！！！！！！！！！！！！！！！！！！！！！！！！！！！！！！！！！！！！！！！！！！！！

再次说明： 
1. Arduino DUE 没有EEPROM ，所以配置固件时这个一定要禁用EEPROM。 
2. 将下载的Configuration.h 用记事本打开找到#define UI_LANGUAGE 改值为10，我设置的中文语言配置 希望你用得愉快！