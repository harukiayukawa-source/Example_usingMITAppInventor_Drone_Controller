# Example_usingMITAppInventor_Drone_Controller
BLE通信でドローンをリアルタイム制御するAndroidアプリです。MIT App Inventorで製作いたしました。<br>
BLE通信で必要なUUIDなどは私のドローンの設定値に固定されているため、このアプリをそのまま使用することはできません。<br>
MIT App Inventorで作成できる外観やUIの参考になればと思い挙げています。<br>

## 概要
BLE通信でドローンを制御するAndroidアプリ

## 機能
- リアルタイム操縦（ロール・ピッチ）
- BLE通信による低遅延制御
- 単ループ角度PID制御モードと二重ループ角度角速度制御(カスケード制御)モードの切り替え対応
- ゲイン定数のデフォルト値とチューニング値の切り替え対応

## デモ
（動画 or GIF）

## ダウンロード
[APKはこちら](リンク)

## 技術スタック
- MIT App Inventor
- Bluetooth Low Energy
- PID制御

## 工夫した点
- 操作の安定性向上（expo導入）
- 通信遅延の最適化
