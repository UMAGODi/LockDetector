![banner](https://raw.githubusercontent.com/UMAGODi/LockDetector/main/pic/banner.gif)



## 現在の最新バージョン：1.0.2 (2020/12/18)

[New] 無変換 の無効化
[New] 変換 の無効化
[New] カタカナひらがなローマ字 の無効化
[Bug] いくつかのバグを修正



# 概要

CapsLock、NumLock、ScrollLock の状態変更をMS-IMEのように画面の中心に表示するソフトです。

また、押し間違いを防ぐために CapsLock、NumLock、ScrollLock、Insert のキーのリマップ(割り当て変更)も行えます。<br> ~~(ほぼこっちがメインのような気もするが)~~



# ダウンロード

##### 右のReleasesか[ここ](https://github.com/UMAGODi/LockDetector/releases)

##### 右上の緑のCodeからDownload Zipはしないように！！！！そこにはアプリケーションは入ってません！！！！！！！！



# インストール・アンインストール

#### インストール

zip展開して終わり

#### アンインストール

LockDetector.exe を消しておしまい



# 使用方法

* LockDetector.exeをダブルクリックなどで起動すると、タスクトレイ(画面右下の ^  ←これ) にアイコンが出ます。

* 以後はCapsLock、NumLock、ScrollLockの状態変更を検知して自動的に画面の中心に表示が出ます。アイコンの詳細は下の画像を参照してください。

* キー入力での状態変更のみ検知します。即ち、マウス操作やソフトウェアによる状態変更では表示はでません。

* 終了する際はタスクトレイアイコンを右クリックしてから「終了」を選択してください。

* **スタートアップを登録する際は、登録後にアプリケーションを移動しないでください。**
  **スタートアップ登録後にアプリケーションが移動するとスタートアップは機能しなくなります。**

* キーのリマップを行う場合は、タスクトレイアイコンを右クリックしてから「キーのリマップ」で選択してください。対応しているリマップは以下です。(個別に設定可能)

  | 元のキー                   | リマップ後のキー |
  | -------------------------- | ---------------- |
  | Shift + CapsLock           | Win + CapsLock   |
  | NumLock                    | Win + NumLock    |
  | ScrollLock                 | Win + ScrollLock |
  | Insert                     | Win + Insert     |
  | 無変換                     | 無効化           |
  | 変換                       | 無効化           |
  | カタカナひらがな｜ローマ字 | 無効化           |

  

  



#### アイコン説明

![desc](https://raw.githubusercontent.com/UMAGODi/LockDetector/main/pic/desc.png)



# 技術的なお話

SetWindowsHookEx の WH_KEYBOARD_LL と、keybd_event を使ってます。

アンチウイルスソフトが何をもってキーロガー判定にするのか分からないので一応



# ライセンスとか

二次配布はしないでください。もしする場合は私に確認をしてください。[連絡先](https://twitter.com/osashimi636825)(Twitter)

このソフトウェアを使用して何かしらの損害が発生しても作者は一切の責任を負いかねます。