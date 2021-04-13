# アプリ名　
**YourDiary**

# 概要
日常的に使うことが期待されるカレンダーアプリに、より日常で使えるような機能を追加したアプリケーション

# 本番環境
https://diary-mochikibi-app.herokuapp.com
ID/Pass
* ID: admin
* Pass: 2222

ログイン情報（テスト用）
* Eメール : test@com
* パスワード: a1a1a1

# 機能紹介
**todoリスト**
<img width="1439" alt="スクリーンショット 2021-03-23 16 53 52" src="https://user-images.githubusercontent.com/78133205/114600935-e0e1f480-9ccf-11eb-9cd8-2a3ae0ea8176.png">

やるコトリストでは、その日行いたいことをリストにまとめることができ、計画的な行動をサポートします。
また、やるコトの状態を現在取り組んでいるのか、これからなのか、終わったことなのかで変更できるので、整理がしやすいです！

**日記投稿**
<img width="1440" alt="スクリーンショット 2021-03-23 16 56 00" src="https://user-images.githubusercontent.com/78133205/114601710-ca886880-9cd0-11eb-9f8b-a407ded6d6aa.png">
毎日の出来事を記録して、思う存分思い出を保存できます。
日にち検索機能がついているので、すぐに探している思い出を見つけることができます！

**カレンダー**
<img width="1440" alt="スクリーンショット 2021-03-23 16 56 46" src="https://user-images.githubusercontent.com/78133205/114601664-bc3a4c80-9cd0-11eb-8d8e-c34c85bc2584.png">
カレンダー機能では、登録した予定をわかりやすく見ることができます。
予定を選択すると、その予定に登録したメモ書きを確認することができます。

**天気予報**
<img width="1439" alt="スクリーンショット 2021-03-23 16 57 06" src="https://user-images.githubusercontent.com/78133205/114602204-4bdffb00-9cd1-11eb-9ad7-f55c76379a6a.png">
あなたの現在の位置情報を元に、1週間分の三時間ごとの天気を確認することができます。
※ブラウザでの位置情報取得の許可が必要です

#　工夫した点
* todoリストでは、ボタンを押すたびに状態が変わる機能をajaxを用いて実装した。
* javascript、jqueryを用いて位置情報を取得した。
* ウェルカムページをjavascriptを用いて実装した。
* cssはsassを用いて実装した。

# 使用技術（開発環境）
## バックエンド
ruby, ruby on rails

## フロントエンド
HTML,sass,javascript,jquery,ajax

## データベース
MySQL,SequelPro

## ソース管理
Github, Github Desktop

## アプリケーションサーバー
heroku

##　エディタ
VScode

# 課題や今後実装したい機能

* スマホ画面制作（レスポンシブ対応）
* 予定登録などの非同期通信の実装




