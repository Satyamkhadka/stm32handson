# Intro
 STM32 using platformio 
## info 

```shell
[env:stm]
platform = ststm32
framework = stm32cube
board = genericSTM32F103ZE

upload_protocol = stlink

monitor_speed = 115200

debug_tool = stlink

```
##  to run 
    clone this repo 
    pio run 
    pio run -t upload 
    pio run -t monitor (not working )