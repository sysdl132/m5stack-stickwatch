# English version

# m5stack-stickwatch

Little changed on eggfly's stickwatch.

# NOTE

Required settings:
M5Stack-Core-ESP32, QIO, 80MHz, No OTA (Large APP), 921600, Verbose//
Required libraries:
ESP32:
     | u8g2lib
     | m5stack
     | BLE
     | Wifi(built-in)

Required change-code:
in "config.h":

```
const char* BUILTIN_WIFI_SSID      = "wifi_name";
const char* BUILTIN_WIFI_PASSWORD  = "wifi_password";
```

# APP Version

Latest version is  1.76-r3|V1.76-R3>>>Fix some bugs|V0.20>>>First create

#URLs

index of M5Stick:
[click here](https://docs.m5stack.com/#/en/core/m5stick)

# 中文版

# m5stack-stickwatch

在eggfly的文件上略微改动。

# 注意

所需设置：
M5Stack-Core-ESP32, QIO, 80MHz, No OTA (Large APP), 921600, Verbose//
所需库：
源于ESP32：
    | u8g2lib
    | m5stack
    | BLE
    | wifi(built-in)
    
更换此处代码：  
在“config.h”：
```
const char* BUILTIN_WIFI_SSID      = "wifi名字";
const char* BUILTIN_WIFI_PASSWORD  = "wifi密码";
```

# 版本

最新：1.76-r3|此版本：修复一些bug|0.20：第一个版本

# URL

设备数据：
[点我](https://docs.m5stack.com/#/zh_CN/core/m5stick)
