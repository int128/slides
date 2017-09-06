# Spring Boot on App Engine
## Hidetake Iwata
Sep 7, 2017

---
## Hidetake Iwata
Software Engineer at Tokyo

[@int128](https://github.com/int128)

---
## App Engine

[App Engine | Google Cloud Platform](https://cloud.google.com/appengine/?hl=ja)

[2016年半ば現在のGoogle App Engine](http://write.kogus.org/articles/Y2Rtpp)

[「メルカリ アッテ」を支える Google App Engine と Golang](https://speakerdeck.com/ttsuruoka/merukari-atute-wozhi-eru-google-app-engine-to-golang)

---
## App Engine Standard

✅爆発的な需要に追従できるインフラが揃っている
- Instance Auto Scale
- Datastore

✅12 factorで必要な機能が揃っている
- Memcache
- Task Queue
- Static Content CDN
- Log Monitoring

---
## App Engine of GCP

Service Accountで各サービスと連携できる
- Cloud Storage
- Cloud SQL
- Cloud Vision
- etc.

ログストリームはStackdriverに送られる

---
## App Engine Java

✅Pros
- IDEによるタイプセーフな開発
- 数多くのJVM言語やライブラリ（Kotlin, Scala, Groovy...）

⛔Cons
- WARのデプロイ（12 factorではJAR）
- 初回アクセス時のスピンアップに数秒（Goは1秒以内）

---
## Spring Boot

✅Pros
- 標準的な設定が揃っているのでドメインに集中できる
- エコシステムが整っている

⛔Cons
- 初回アクセス時のスピンアップが長い（一度起動すれば速い）

---
## 標準的なBoot Appと異なる点

- JAR実行は使えない。App Engine Dev ServerでWAR実行
- ログはSLF4J→Logback→標準出力→Stackdriver
- TaskQueueやMemcacheに依存するユニットテストではApp Engine Testingのヘルパクラスを利用

---
## Getting Started

- [SpringBoot HelloWorld for App Engine Standard](https://github.com/GoogleCloudPlatform/getting-started-java/tree/master/appengine-standard-java8/springboot-appengine-standard)
- [Spring Boot + Kotlin + App Engine](https://github.com/int128/appengine-spring-boot-starter)
