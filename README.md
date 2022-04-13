# elrs_to_espnow

通过对 radiomaster zorro 的 elrs 2.4G固件 + backpack固件的修改，通过espnow，可以通过esp32 或者 esp8266，当作接收器。
无需其他硬件。比较早期版本，广播模式暂不支持多个配对。

# 当前支持

1.采用crsf协议，支持遥感数据回传。

2.内置http OTA

3.支持betaflight和inav（其他未测）支持crsf的协议的飞控

4.距离未测，没有实飞

5.esp32板子支持

# 未来展望

1.通过绑定模式，支持多个终端

2.支持EspNow中继，扩大遥控范围

3.中继支持蓝牙连接，可以回传遥感数据（支持地面站）

