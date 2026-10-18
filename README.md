# gamma_neck_pcb

## 役割

砲塔と車体をつなぐスリップリングの受け口になる受動分配基板。マイコンは載せず、24V とCAN 2 系統、ゲームモジュール線を分配・パススルーする。

## 主要部品

| 部品 | 型番 | 用途 |
|---|---|---|
| 24V 出力コネクタ | AMASS XT30PW-F × 3 | 首モータ、P4 キャリアへの 24V 分配 |
| 6P コネクタ | JST PH S6B-PH-K × 2 | リング電源入力、Yaw モータ（MHF5005） |
| CAN コネクタ | JST PH S2B-PH-K × 5 | CAN1 × 3（首モータ）、CAN2 × 2（パススルー） |
| ゲームモジュール線 | JST PA B04B-PASK × 2 | パススルー |
| CAN 終端抵抗 | 120 Ω × 2 | CAN1 / CAN2 の終端 |
| 電源 LED | LED 3mm + 10 kΩ | 24V 通電表示 |

回路図は [gamma_neck.pdf](./gamma_neck.pdf)、部品表は [bom.csv](./bom.csv)、3D は [gamma_neck.step](./gamma_neck.step)。設計時の検討は [docs/](./docs/) に残している。

## ライセンス

© Rabbits Robotics、[CERN-OHL-P-2.0](./LICENSE)。
