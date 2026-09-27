# 自己紹介

- 電気電子工学を学んでいる学生です。
- **組み込み・制御**を中心に開発しています（マイコンのプログラム、モーター・サーボの制御、センサー、シリアル／CAN 通信）。
- 好きな言語は C/C++ です。

## 作ったもの

> ほとんどのリポジトリは非公開です。

### MarineRobot — 水中ロボット
- Teensy でスラスター4基を制御（ESC への出力が急に変わらないように変化量を制限）
- DJI DT7 プロポでの手動操縦（DBUS 信号を解読）と、あらかじめ決めた手順での自動航行
- ESP32-CAM で水中映像を録画
- MATLAB のシミュレーター：深さと向きの自動保持（PID）、水の流れ・ケーブルの引っ張り・スラスター故障などの外乱を再現

### Tanekon — CanSat ローバー（種子島ロケットコンテスト）
- カプセルの中で待機し、気圧の変化で放出を判断して、ゴールまで自律走行するローバー
- GPS による誘導、IMU で転倒を検知して起き上がる処理、色検出によるカメラ誘導
- RoboMaster M2006 モーターを CAN 通信で動かし、タイマー割り込みで PID 制御（Teensy / Spresense）

### H8/3052F の硬貨カウンター — 組み込みシステムの授業
- PC 側で Web カメラと OpenCV（HSV で色を絞り込み、ハフ変換で円を検出）を使って硬貨を数える
- 結果をシリアル通信（Win32 API、9600bps）で H8/3052F に送る
- H8 が ITU の PWM（周期 20ms）でサーボを動かし、枚数に応じてお辞儀させる

### Raspberry Pi 4 への移植
- マイコン用の制御プログラムを Raspberry Pi 4 の C++ に移植中
- スラスターの PWM は pigpio、モーター制御は SPI の CAN コントローラーから Linux の SocketCAN に置き換え

## 使える言語

<img src="https://skillicons.dev/icons?i=c,cpp,py" /> <img src="https://img.shields.io/badge/VHDL-1f425f?style=for-the-badge" height="48" alt="VHDL" /> <br /><br />
