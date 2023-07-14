# x32micro - STM32F103CxT6, CH32V203C8T6 ProMicro size board

ProMicro サイズの STM32、CH32 など STM32F103CxT6 互換ピンアウト MCU 用 ProMicro 型開発ボード

<img src="photos/x32micro-v1.1.1-front.jpg" width="30%"> <img src="photos/x32micro-v1.1.1-back.jpg" width="30%"> <img src="photos/x32micro-v1.1.1-pcb.jpg" width="30%">

- BOOTH 販売ページ
- STM32F103 互換系
  - 回路図 Semantics [f103cxt6/x32micro-v1.1.1-semantics.pdf](f103cxt6/x32micro-v1.1.1-semantics.pdf)
  - PCB [f103cxt6/x32micro-v1.1.1-pcb.pdf](f103cxt6/x32micro-v1.1.1-pcb.pdf)

### Tested MCU

<!-- - STMicro: STM32F103C8T6 -->

- WCH: CH32V203C8T6
- STMicro: STM32F103C8T6

## X32Micro v1.1.1

[gerber](https://github.com/74th/x32promicro/releases/tag/1.1.1)

### 部品表 Parts List

CH32V203 はクリスタルなしでも動作します。
その場合 Y1、Y2、C2、C3、C9、C10 を未実装にしてください。

| Reference | Parts                                | Qty |
| --------- | ------------------------------------ | --- |
| R1,R2     | 0805 Register 5.1kR                  | 2   |
| R3        | 0805 Register 200R or 10kR           | 1   |
| R4        | 0805 Register 0R                     | 1   |
| R5,R6,R7  | 0805 Register 10kR                   | 3   |
| C1        | 0805 Capacitor 10uF                  | 1   |
| C2,C3     | 0805 Capacitor 12pF                  | 2   |
| C4        | 0805 Capacitor 2.2uF                 | 1   |
| C5-8      | 0805 Capacitor 100nF                 | 4   |
| C9,C10    | 0805 Capacitor 22pF                  | 2   |
| D1        | 0805 LED                             | 1   |
| Y2        | 3225 4Pin Crystal 8MHz               | 1   |
| Y1        | 3215 2Pin Crystal 32.768kHz          | 1   |
| U1        | SOT-89 3.3V 1A Regulator AMS1117-3.3 | 1   |
| U2        | MCU STM32V103C8T6                    | 1   |
| SW1,SW2   | Push Switch SKRPABE010               | 2   |
| J1        | USB 2.0 Type-C Socket                | 1   |

![parts](photos/x32micro-v1.1.1-parts-position.png)

## License

MIT
