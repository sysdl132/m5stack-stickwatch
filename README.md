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
const char* BUILTIN_WIFI_SSID      = "wifi_name";
const char* BUILTIN_WIFI_PASSWORD  = "wifi_password";

# APP Version

Latest version is  1.76-r3
V1.76-R3>>>Fix some bugs
V0.20>>>First create
