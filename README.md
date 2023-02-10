# XIAO_AB_Board
Klipperを前提としたABモーター駆動用ボードです。
ERCFを参考に作成しています。
https://github.com/Tircown/ERCF-easy-brd

XIAO または XIAO RP2040が使用可能です。

ピンアウトは以下の通りです。

A Motor
|Function|XIAO|XIAO RP2040|
|--------|----|-----------|
|EN|PA2|gpio26|
|STEP|PA4|gpio27|
|DIR|PA10|gpio28|
|UART|PB8|gpio0|
|UART Address|0|0|

B Motor
|Function|XIAO|XIAO RP2040|
|--------|----|-----------|
|EN|PA2|gpio29|
|STEP|PA7|gpio2|
|DIR|PB9|gpio1|
|UART|PB8|gpio0|
|UART Address|1|1|

ENDSTOP
|Function|XIAO|XIAO RP2040|
|--------|----|-----------|
|A-MIN|PA5|gpio4|
|B-MIN|PA6|gpio3|

I2C
|Function|XIAO|XIAO RP2040|
|--------|----|-----------|
|SDA|PA8|gpio6|
|SCL|PA9|gpio7|
