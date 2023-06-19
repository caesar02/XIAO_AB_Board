# XIAO_AB_Board
Klipperを前提としたABモーター駆動用ボードです。
ERCFを参考に作成しています。
https://github.com/Tircown/ERCF-easy-brd

XIAO または XIAO RP2040が使用可能です。

部品表
|基板上表示|名称|数|定数|参考|
|---------|----|--|----|---|
|C1,C2|積層セラミックコンデンサ|2|0.1μF 50v|https://akizukidenshi.com/catalog/g/gP-13582/|
|C3,C4|電解コンデンサ|2|100μF 50v|https://akizukidenshi.com/catalog/g/gP-06726/|
|J2,J3|XHコネクタ|2|3P|https://akizukidenshi.com/catalog/g/gC-12248/|
|J5|ターミナルブロック|1||https://akizukidenshi.com/catalog/g/gP-01306/|
|J7,J8|XHコネクタ|2|4P|https://akizukidenshi.com/catalog/g/gC-12249/|
|R1,R2,R3,R4,R6,R8|抵抗|6|10kΩ|https://akizukidenshi.com/catalog/g/gR-25103/|
|R5,R7|抵抗|2|100Ω|https://akizukidenshi.com/catalog/g/gR-25101/|
|U1|MCUボード|1|XIAO or XIAO RP2040|https://akizukidenshi.com/catalog/g/gM-17044/|

ピンアウト

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
|EN|PA11|gpio29|
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
