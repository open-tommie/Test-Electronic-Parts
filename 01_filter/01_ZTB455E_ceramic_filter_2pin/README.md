# ZTB455E Ceramic Filter 2Pin

## Sammary (JPN: 概要)

JPN: AliExpressで購入した3つのZTB455EをNanoVNA VAA2 で計測した。

<img src="ZTB455E_2.jpg" width="200">

### 注意

・インピーダンス不整合で計測しているので、結果は参考程度の値です。

|部品|インピーダンス|
----|----
|ZTB455E |3kΩ(同様のMurata社セラミックフィルターから推定）| 
|NanoVNA |50Ω|


### CH0-DUT-CH1 (JPN: 透過特性)

JPN:S21 Gainがピークになる周波数(▼2)

<img src="CH0-DUT-CH1_ZTB455E_1_S21_S11Z.png" width="600">

|DUT No(JPN:テスト対象物)|Frequency| S21 Gain(dB) | 
----|----|----
|1 |439.960kHz| -1.651|
|2 |437.700kHz| -0.787|
|3 |434.480kHz| -0.605|

### CH0-DUT-GND

JPN:S11|Z| が最低になる周波数

|No|Frequency|
----|----
|1 |440.140kHz| 
|2 |437.740kHz| 
|3 |434.460kHz| 

|Test Item| Description|
----|----
|NanoVNA| NanoVNA SAA2|


## Schematic (JPN: 回路図)

TBD

## Screen Shot

<img src="CH0-DUT-CH1_ZTB455E_1.png" width="200">
<img src="CH0-DUT-CH1_ZTB455E_2.png" width="200">
<img src="CH0-DUT-CH1_ZTB455E_3.png" width="200">
<img src="CH0-DUT-GND_ZTB455E_1.png" width="200">
<img src="CH0-DUT-GND_ZTB455E_2.png" width="200">
<img src="CH0-DUT-GND_ZTB455E_3.png" width="200">


## etc
