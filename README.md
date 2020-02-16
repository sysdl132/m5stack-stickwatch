![挂科](https://gitee.com/sysdl132/m5stack-stickwatch/widgets/widget_2.svg)

Language:English | [中文](https://github.com/sysdl132/m5stack-stickwatch/blob/master/README.md#%E4%B8%AD%E6%96%87%E7%89%88)

# English version

![](https://img.shields.io/github/forks/sysdl132/m5stack-stickwatch)

![](https://img.shields.io/github/stars/sysdl132/m5stack-stickwatch)

![](https://img.shields.io/github/issues/sysdl132/m5stack-stickwatch)

# m5stack-stickwatch

[Little changed on eggfly's stickwatch.](https://github.com/eggfly/StickWatch)

# NOTE
I think the power management system is not working...
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

Latest version is v1.4|v1.4 Fix some bugs|V0.20 First create

#URLs

index of M5Stick:
[click here](https://docs.m5stack.com/#/en/core/m5stick)

flash download tools v3.6.8:

[DOWNLOAD](https://www.espressif.com/sites/default/files/tools/flash_download_tools_v3.6.8_0.zip)

Language:[English](https://github.com/sysdl132/m5stack-stickwatch/blob/master/README.md#english-version) | 中文

# 中文版

# m5stack-stickwatch

[国内镜像](https://gitee.com/sysdl132/m5stack-stickwatch/tree/master)

[在eggfly的文件上略微改动。](https://github.com/eggfly/StickWatch)

# 注意
电池与温度系统无法正常运行。

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

最新：1.4|此版本：修复一些bug|0.20：第一个版本

# URL

设备数据：
[点我](https://docs.m5stack.com/#/zh_CN/core/m5stick)

flash download tools v3.6.8:

[下载](https://www.espressif.com/sites/default/files/tools/flash_download_tools_v3.6.8_0.zip)
