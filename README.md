# ADSU01 USB録音 音源再生モジュール

## USB録音 音源再生モジュールで手軽に効果音再生！
**USBで接続して簡単に音源を取り込みモジュール本体内に**  
**４曲合計９０秒まで保存、スイッチ入力を使用し簡単に出力可能！**  

![](https://bit-trade-one.co.jp/wp/wp-content/uploads/2015/09/8c66b6b374088d8c2a15d59aaad77cba.png)  

組み込み機器へ本製品を搭載することで、簡単に目的の音を出力することが可能です。  
また音質についても40kHz以上のサンプリング周波数を持ち、音声だけでなく音楽や効果音の再生も可能です。  
従来の音源モジュールのアナログ音質に満足できなかったユーザーにも安心しておすすめできる音質を持っています。  
またマイコンやArduino／RaspberryPi等の出力ピンからも制御可能でスイッチ入力による  
再生停止により制御可能で組み込み初心者にも安心の音源再生モジュールです。  

## 製品詳細は[こちら](https://bit-trade-one.co.jp/product/module/adsu01/)!

### 評価ボードセットのサポートサイトは[こちら](https://github.com/bit-trade-one/ADSU01TB_Sound_Player_Module_reference_board)!

## [マニュアル](https://github.com/bit-trade-one/ADSU01_Sound_Player_Module/blob/master/Manual/ADSU01_MANUAL_WEB.pdf)

## [PCアプリ](https://github.com/bit-trade-one/ADSU01_Sound_Player_Module/tree/master/App)

### [基板図](https://github.com/bit-trade-one/ADSU01_Sound_Player_Module/tree/master/Dimensions)

### [回路図](https://github.com/bit-trade-one/ADSU01_Sound_Player_Module/tree/master/Schematics)

## 製品仕様

### ピン配置

 
ピン番号|信号名|説明|I/O
:-|:-|:-|:-
1|+5V|5V入力、USBから電源供給しない場合に使います|
2|GND|GND|
3|GND|GND|
4|STATUS|再生状態を表示します（再生中はH）|O
5|STOP|停止（Lアクティブ）|I
6|PLAY4|4曲目再生（Lアクティブ）|I
7|PLAY3|3曲目再生（Lアクティブ）|I
8|PLAY2|2曲目再生（Lアクティブ）|I
9|PLAY1|1曲目再生（Lアクティブ）|I
10|GND|GND|
11|GND|GND|
12|AOUT|音声出力|O
13|PGC|NC（マイコン書込用）|IO
14|PGD|NC（マイコン書込用）|IO
15|GND|GND|
16|VCC|NC（マイコン書込用）|
17|MCLR|NC（マイコン書込用）|I
18|USB5V|USBから供給された5V|
19|D-|USB(D-)|IO
20|D+|USB(D+)|IO

＊ピン間2.54mm、ピン幅600mil

製品仕様  

【対応OS】  
日本語版OS: Windows10, Windows8, Windows7，Vista™搭載のDOS/Vパソコン  
【対応機種】USBポートを標準で持ち、パソコン本体メーカーが上記対応OS上でのUSBポートの動作を保証している機種。  
*(一部対応しない機種があります）NEC PC-9800、PC-9821シリーズには対応しておりません。*  
*設定アプリケーションソフトウェア導入のため別途インターネット環境が必要です。*  
【対応インターフェース規格】USB2.0(タイプminiBコネクタ) USBフルスピードモード  
【対応音源フォーマット】MP3 / WAV / AIFF / OGG / FLAC  
【音源再生仕様】サンプリング周波数：約40kHz　／　量子化ビット：8bit  
【本体寸法】W17.8×D39.3×H15mm  
【重量】　約5g  
【電源】　DC5V（USB電源可）  
【動作環境:温度】　0～45℃、湿度10～60％(結露なきこと）  
【生産国】Made in Japan  
【保証期間】お買い上げから6ヶ月間  
付属品  
 - USB録音・音源再生モジュール基板： 1台  
 - 取扱説明書 ： 1部  
 - 保証書：１部  
