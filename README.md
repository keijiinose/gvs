# 前庭電気刺激(GVS)実験用

前庭電気刺激(GVS)の実験用リポジトリ．

耳の後ろ辺りに電極パッドを貼り付けて電流を流すと加速度を感じます．

PC -(SPI)-> AVR -(SPI)-> DAC -> OPアンプ(LMC662CN) -> MOSFET -> DC昇圧回路 -> 電極パッド

![構成](circuit/diagram.png)


## 回路


![回路図](circuit/circuit.png)

(circuit.ce3 はBSch3V用です)


- AVR ATMEGA88 (秋月)
- D/Aコンバータ MCP4922 (秋月)
- MOSFET 2SK3234 (秋月)
- OPアンプ LMC662CN TODO: 別のに置換予定
- DC-DC昇圧回路 (aitendo) http://www.aitendo.com/product/6872
- 電極パッド (amazon) http://www.amazon.co.jp/dp/B0002ERMBE


## ファームウェア

TODO

## Oculus Rift

...

## 課題メモ

- 色々
- 昇圧回路は非絶縁なので複数同時に使えない

## License:

- MIT License

