# HSCanT

HSCanT 是一款USB转4路CAN FD工具，基于HPM5321芯片设计。

## 特性

- 支持4路CAN FD通道
- 每路CAN FD通道支持最高8Mbit/s的数据传输速率
- 支持上位机配置可选的120Ω终端电阻
- 每路通道均支持独立的TX、RX状态全彩LED指示
- 支持最高±58V的过压保护

## 致谢

感谢[RCSN](https://github.com/RCSN)大佬提供的思路，以及该项目的上下位机软件支持。

- 上位机：<https://github.com/RCSN/cangaroo_hpmicro_canfd_analyzer>
- 下位机：<https://github.com/RCSN/hpm_sdk_extra/tree/main/demos/cangaroo_hpmicro>
