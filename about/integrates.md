---
layout: about
---

- 更新 2013/03/02

Stormから，キューやデータベースを利用することができる．

Stormの[spout](http://nathanmarz.github.com/storm/doc-0.7.1/backtype/storm/spout/ISpout.html)は，新たなキューを簡単に接続することができる．
キューを接続するサンプルは以下の４つがある．

1. [Kestrel](https://github.com/nathanmarz/storm-kestrel)
2. [RabbitMQ / AMQP](https://github.com/Xorlev/storm-amqp-spout)
3. [Kafka](https://github.com/nathanmarz/storm-contrib/tree/master/storm-kafka)
4. [JMS](https://github.com/ptgoetz/storm-jms)

同様に，Stormをデータベースにつなげるのも簡単である．
いつもどおりデータベースとの接続をopenして，read/writeができる．Stormではデータベースの並列化，パーティショニング，成功しなかった時のリトライ，なども扱うことができる．
