# x32micro - STM32F103CxT6, CH32V203C8T6 ProMicro size board

ProMicro サイズの STM32、CH32 など STM32F103CxT6 互換ピンアウト MCU 用 ProMicro 型開発ボード

- BOOTH 販売ページ
- 回路図 Semantics [x32micro-v1.1.1-semantics.pdf](x32micro-v1.1.1-semantics.pdf)
- PCB [x32micro-v1.1.1-pcb.pdf](x32micro-v1.1.1-pcb.pdf)

## X32Micro v1.1.1

### 部品表 Parts List

| Reference | Parts                                       | Qty |
| --------- | ------------------------------------------- | --- |
| C1-C3, C6 | 0805 Capacitor 100n                         | 4   |
| C4        | 0805 Capacitor 10u                          | 1   |
| C5        | 0805 Capacitor 2.2u                         | 1   |
| C7, C8    | 0805 Capacitor 12p                          | 2   |
| C9, C10   | 0805 Capacitor 22p                          | 2   |
| R1        | 0805 Resister 200                           | 1   |
| R2        | NC or 0805 Resister 10k for BOOT0 Pull Up   | 1   |
| R8        | NC or 0805 Resister 10k for BOOT0 Pull Down | 1   |
| R6-R7     | 0805 Resister 10k                           | 2   |
| R3        | 0805 Resister 0 R                           | 1   |
| R4, R5    | 0805 Resister 5.1k                          | 2   |
| D1        | 0805 LED                                    | 1   |
| J1        | USB2.0 Socket                               | 1   |
| JP1       | Jumper BOOT SW Pull Up / Down               | 1   |
| SW1, SW2  | SW Push                                     | 2   |
| U1        | MCU STM32V103C8T6                           | 1   |
| U2        | SOT-89 Regulator AMS1117-3.3                | 1   |
| Y1        | 3215 Oscillator 32.768k                     | 1   |
| Y2        | 3225 Oscillator 8M                          | 1   |

- CH32V203 など BOOT0 を Pull Up し、BOOT スイッチで GND に繋ぎたい場合
  - R2 を実装してください
  - R8 は未実装 NC にしてください
  - JP1 の中央のランドを △ マークにジャンパしてください
- STM32F103 など BOOT0 を Pull Down し、BOOT スイッチで 3V3 に繋ぎたい場合
  - R2 は未実装 NC にしてください
  - R8 を実装してください
  - JP1 の中央のランドを + マークにジャンパしてください
