# Example_usingMITAppInventor_Drone_Controller
BLE通信でドローンをリアルタイム制御するAndroidアプリです。<br>
MIT App Inventor(Webベースのビジュアルプログラミング環境)で製作いたしました。<br>
BLE通信で必要なUUIDなどは私のドローンの設定値に固定されているため、このアプリをそのまま使用することはできません。<br>
MIT App Inventorで作成できる外観やUIの参考になればと思い挙げています。<br>

## 概要
BLE通信でドローンを制御するAndroidアプリ

## デモ
[動画リンクはこちら]

## 機能
- リアルタイム操縦（ロール・ピッチ・ヨー・スロットル）
- BLEを用いたbytes通信による低遅延制御
- 単ループ角度PID制御モードと二重ループ角度角速度制御(カスケード制御)モードの切り替え対応
- ゲイン定数のデフォルト値とチューニング値の切り替え対応

## ダウンロード
[APKはこちら](https://github.com/harukiayukawa-source/Example_usingMITAppInventor_Drone_Controller/releases/tag/v0-00(Test))<br>
[.aiaファイルはこちら]()<br>
(ダウンロード後、MIT App InventorのURLを開き、そこでインポートしてください)<br>
[MIT App InventorのURL]()


## 技術スタック
- MIT App Inventor
- Bluetooth Low Energy
- PID制御

## What is MIT App Inventor ?
- ブラウザ上でできる、アプリケーション開発ツールです。UIデザインとブロックによるプログラミングの両方ができます。
- RemoteXYや

## 工夫した点
- 
- 通信遅延の最適化
