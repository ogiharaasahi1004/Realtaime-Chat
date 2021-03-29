# Realtime-Chat

## サービス概要

![realtime-chat トップ](https://i.gyazo.com/33338cc4841856b1e2b6faca8e4d7096.png)

普段言えないようなことも書き込める、自分だけのメモサービス。タスクリストとしても使える。

今だからこそ正直に感じている想いを投稿する、チャットを作成する。

どこにも吐き出すことが出来ない悩みが、人間誰しも有ると思う。

だからこそ、そんな思いを文字に起こして吐き出すことで、可視化してモヤモヤがスッキリできるから。

今の時代、苦しいときが多いから、１つずつ乗り越えていくために自分を見つめ直すツールになるといいと思う。

悩んでいる人を救えるツールになるといいと思う。

***
## 作る上で意識した事

一つ一つの機能自体はいたってシンプルなものばかりであり、画期的で面白みのある作品かどうかと問われればあまり自信はありません。

しかしながら、Rails最大の強みでもある「MVCアーキテクチャ」の概念にひたすら忠実に従い、何よりも基本を意識した構成を心掛けております。

## 制作したきっかけ

今の時代を生きている人なら感じる生き苦しい気持ちを、明確に吐き出さないと自殺など悲しい事件がたくさん起きてしまう。実際若者の自殺の件数が◯倍に増えていると知った。

だから同じ若者として救いたいし、そんなときに自分だけしかみられないサイトで自分を向き合ってハッキリと言語化することで、悩みは消えていくと考えました。プライベートを発信する時代がからこそ、このクローズドの空間に価値がある。

今まで誰も経験したことがない、このよな中の変化を飲み込まれるのではなく、波乗りする側になるためにも、自分をもっと向き合って分析してほしいと思いました。

あなたの人生はあなたしか変えられないからです。人生を変える人を１人でも多く生み出して、特に若者を救えたらいいと思う。

私も今までできないことにたくさん挑戦してきたので気持ちがとてもわかるのですが、挑戦する人はその日の試合のお話やチームの状況を、すぐ知りたいし、思いを共有したいし、ヒトと繋がりたい思いが非常に強いです。

禅のような、ゆっくり時間をとって、自分の心と向き合うことが一番の解決方法だと思います。

***
## 重視した点
- 自分の中にある、漠然としたモヤモヤ（悩み）を言語化してスッキリする、悩みを解決するをテーマの中心にしました。
- 僕もたくさん挑戦して、悩みができるのでわかりますが、未来が見えない漠然とした悩みが一番つらいものです。
- だからまず、顧客の皆さんの悩みを自分だけの空間で、安心して正直に想いを言語化することで、未来の希望への筋道が出てくると思ったから。
- 私みたいな挑戦したり、日常で悩んでいる人のリアルな悩みを自分と向き合うマインドフルネスで１人でも多く救いたいし、悩みを解決したい。
- サービス自体は、なるべくシンプルに作り、基本に忠実に作り、動作が軽いことを大切にしました。
- 悩みが解決したら、いいね機能で投稿を評価し合ったり、答えが出たことに喜んだり、想いを言語化するために、文字で投稿できるようにしました。
- 動作確認を、機能ごとと全体の動作確認も行う点をとても大切にしました。

　
## 技術内容
- フレームワーク:Ruby on Rails（ '5.2.2'）
- DB: 'mysql2', '>= 0.4.4', '< 0.6.0'
- DB：PostgreSQL (本番環境)
- バージョン管理:Git
- インフラ:Heroku
- Webサーバ:puma('3.11')
- スタイルシート:sass-rails', '~> 5.0'
- パスワードセキュリティ:'bcrypt', '~> 3.1.7'

***
## URL
https://realtime-chat-ogihara.herokuapp.com/

テストユーザーアカウント

メールアドレス：user@example.com
パスワード：password
***

# 開発環境
- Ruby  2.5.3
- Rails 5.2.2

***

# 実装した各種機能

『記事関連』
- 記事一覧表示機能
- 詳細表示機能
- 記事投稿機能
- 記事削除機能
- エラーメッセージ表示機能
- お気に入り機能（いいね機能）
- ヘージネーション機能（kaminari）

『ユーザー関連』
- ユーサー登録機能
- ロクイン/ログアウト機能
- ユーサーフォロー機能
- DBテーフルのリレーション機能
***

## トップページ（ログイン前）
![Realtime-Chat トップページ（ログイン前）](https://i.gyazo.com/ca117e9c6db8f6ca8e7cb9510b312ac0.png)

## トップページ（ログイン後）
![Realtime-Chat トップページ（ログイン後）](https://i.gyazo.com/54cdebe369d29841ed3e68a8982fec0d.png)

## ユーザー登録ページ
![Realtime-Chat ユーザー登録ページ](https://i.gyazo.com/b6ff55c14a9fcb6e4183f13b5720e5d0.png)

## 投稿一覧ページ
![Realtime-Chat 投稿一覧ページ](https://i.gyazo.com/b5928aadb6e25d806939714f13c6aada.png)

## 投稿一覧ページ 2
![Realtime-Chat 投稿一覧ページ 2](https://i.gyazo.com/36eb92259ebc70cba0246ea81c18c3b2.png)

## お気に入り一覧ページ
![Realtime-Chat お気に入り一覧ページ](https://i.gyazo.com/d2cdba55714a462bca2cec46a2de3a15.png)

## ユーザー詳細ページ
![Realtime-Chat ユーザー詳細ページ](https://i.gyazo.com/4892c87ec45aeda67e5c094ba4174a03.png)


# 作成者の自己紹介

新潟大学工学部 新３年　荻原朝飛（２０歳）

*将来の夢 : 地方に全力で貢献する、ユーザーに喜んでもらえるエンジニアになること。*

- 得意な分野: 
チーム活動、コミュニケーション、プレゼンテーション
- スキルセット: 
HTML/CSS、Ruby、JavaScript、Firebase、MySQL、Git、GitHub
- やりたいこと: 
ヒトとヒトが繋がれる場所を作りたかった。
- Ruby選んだ理由: 
まず、Webアプリケーション開発の知見と動的型付け言語の知見をつける。
- Goをやる理由: 
今、最も価値の高い静的型付け言語は「Go」だと思うから。
- 目標: 
静的型付け言語の知見とマイクロサービス方式での開発手法に関する知見をつけて、お客さまを喜んでもらえるエンジニアになる。

『想いが伝わると非常に嬉しいです！ありがとうございました！』

***

