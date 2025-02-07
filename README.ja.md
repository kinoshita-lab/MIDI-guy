# MIDI野郎 by 木下研究所

MIDI野郎キットは、ワンチップGM音源IC、SAM2695を使った音源モジュールです。GM音源の127種類の音が出るほか、エフェクトやEQなども使えます。詳細は、[SAM2695のデータシート](https://www.dream.fr/pdf/Serie2000/SAM_Datasheets/SAM2695.pdf)を参考にしてください。

## Rev 2.1の変更点

- USB Type-Cに変更
- サイズをフリスクケースに合わせた
- TRS MIDI Type A/B 両対応
- マイコンなどから接続しやすいように UART INを追加(3.3V)

## キットの内容

- 部品実装済み基板
- 3.5mm TRS Jack x 2
- DIN <-> TRS 変換ケーブル (Type A)

## キット以外に必要なもの

- USB Cケーブル
- USB電源アダプターやPCなど、USBケーブルをつないで電源にできるもの
- MIDIケーブル
- MIDIを出力できるデバイス(MIDI キーボード、 PCとUSB MIDIインターフェースの組み合わせ、など)

## 組みたてかた

TRSジャックをはんだづけします。
ロットによって、1つの場合と2つの場合があります。

下図の○で囲んだ8カ所が、はんだづけされていれば完成です。
![how to solder](images/how_to_solder_rev2_1.png)  

## 使い方

- Power: USB電源アダプタからの電源をつなぎます。
- MIDI In: MIDI鍵盤や、MIDIインターフェースなどのMIDI信号をここに入力します。
- Audio Out: ここから音が出ます。ヘッドフォンを直接さすこともできます。

## 回路図などの詳細、不具合情報など

こちらにあります。
<https://github.com/kinoshita-lab/MIDI-guy>

## ケース
STL file を @maks さんが公開しています。 ありがとうございます!!
https://www.printables.com/model/1151667-case-for-a-midi-guy-pcb
