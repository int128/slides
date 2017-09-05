# Why Open Source Development?
## Hidetake Iwata
### Feb 13, 2015

---
## Hidetake Iwata
An Open Source Developer

[@int128](https://github.com/int128)

---
### Gradle SSH Plugin (&star;97)
* Gradle に SSH のコマンド実行やファイル転送を追加するプラグイン
* Groovy で書かれている
* 内部で JSch を利用

---
### Slack Docker (&star;18)
* Docker のイベントを Slack に通知する bot
* Node.js で動作する
* CoffeeScript で書かれている

---
### Gistnote (&star;8)
* Gist クライアントの Web サービス
* GitHub Pages にデプロイしている
* CoffeeScript で書かれている
* フレームワークに vue.js, page.js を採用

---
## Gradle SSH Plugin

https://gradle-ssh-plugin.github.io

---
### First release on Dec. 2012
* 2012年の秋頃から開発を始めた
* 個人のプロダクト

---
### Why?
* パフォーマンステストの自動化に取り組んでいた
* Jenkins上のGradleからサーバを操作する仕組みが欲しかった
* Capistranoでコマンドを書いていたけどビルドシステムと連携できないのが不満
* Gradleを使っているうちにDSLを拡張できることに気づいた
* じゃあプラグインにしよう

---
### Statistics
* 47 Releases (latest is v1.0.5)
* &star; 97 (GitHub)
* 2,508 View / 754 Users in last 30 days (Web site)
* 6,155 downloads in last 30 days ([Bintray](https://bintray.com/int128/maven/gradle-ssh-plugin/view#statistics))

---
## Why as Open Source?

* 良い物をクローズドにしておくのはもったいない
  * テクノロジーで世の中を良くしていきたい
* フィードバックループで価値あるプロダクトを作る
  * 公開すればフィードバックが得られる
* 自分の成果になる
  * 成果が自信につながる

---
## Collaboration
オープンソースのパワーはすごい

---
### 意外と多くの人がIssueやPull Requestをくれる
* Spockテストの追加 (Issue)
* sudoパスワードプロンプトのサポート (Pull Request)
* 多段SSHのサポート (Issue)
* Putty Agentのサポート (Pull Request)
* パスフレーズ付き秘密鍵のサポート (Pull Request)
* オフライン実行 (Pull Request/Issue)
* SOCKS/HTTPプロキシのサポート (Pull Request)
* ファイル転送の改善 (via Tweet)
* 後方互換性のサポート (Issue)

---
### 前向きなコメントが多い
* Thanks
* Awesome
* Great
* ～の機能があったらいいと思うよ

---
## Promotions
どうやってプロダクトを使ってもらうか

---
### ドキュメント大事
* プロダクトを使ってくれるユーザのよりどころ
* なるべくコード例を多く載せよう

---
### リリースノート大事
* アップデートしてくれるユーザのよりどころ
* マージしたPull Requestと紐付ける

---
### README大事
* 新規顧客獲得
* GitHubはリポジトリのトップページにREADMEが表示される
* README駆動開発

---
### リスティングサイトやリポジトリに登録する
* Gradle Plugin Registryに登録した
* リポジトリに登録するとユーザが使いやすくなる
  * Maven Central/Bintray
  * NPM
  * RubyGems

---
### 勉強会で発表する
* プロダクトを知ってもらう機会
* ひいては「自分」を知ってもらう機会

---
### ブログに書く
* たまに宣伝する程度でよさそう
* ニーズを持った人が見に来るとは限らないので、そこまで効果はないかも

---
## Difficulties
苦労しているところ

---
### GitHub Flowに慣れるまで少し時間が掛かった
* Pull Requestベースのレビューやディスカッション

---
### 英語のディスカッションが難しい
* 仕様を収束させるまでの説明力
* 何を言ってるか分からないこともある
* コミュ力

---
### モチベーションの維持が難しい
* 飽きる
* IssueやPull Requestなどのフィードバックが燃料
* 飽きないための対策として新しい技術を使う場にしてみる
* チップが欲しい

---
## Vision
今後やりたいこと

---
### Developer Productivity
開発者をサポートするツールを世の中にリリースしていきたい

* Continuous Integration/Delivery
* Pull Request driven development
* ChatOps
---
### from OpenSource to Work
Developer Productivityの仕事につなげていきたい


---
Thanks.
