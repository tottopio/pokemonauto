Nintendo SWitchをArduino Leonardoを使って自動化します

## 必要なもの
**ハードウェア**
- Arduino Leonardo

**ソフトウェア**
- Arduino IDE

**Arduino LeonardoのデバイスIDを書き換える**  
hardware/arduino/avr/boards.txt内のleonardoのvidとpidを設定している個所を書き換える。
~~~
leonardo.vid=0x0f0d
leonardo.pid=0x0092
~~~

### 自動孵化
ボックスに空きがある限り、ポケモンを孵化し続ける

### 自動ポケモン逃がし
1ボックス分のポケモンを全て逃がすスケッチ

### 自動レイドバトル
ボックスに空きがある限り、レイドバトルを続ける



## 参考
[【ポケモン剣盾】全自動で卵を孵化させる装置](https://www.youtube.com/watch?v=oXnQt_Mbyzk)  

