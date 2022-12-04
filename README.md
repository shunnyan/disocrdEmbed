# disocrdEmbed
PMMP-->Discordでサーバーの情報とかを出すやつ

## 動作環境
PMMP 4.0

## なんだこれは
pmmpのサーバーの情報をdiscordでﾎﾟｫﾝ!するプラグインの簡易版です。

## どう使うんだこれは
このプラグインのMainファイルに
```
public static $webhookurl_main = "";
```
っていうのが大分上に書かれてるんでその""にdiscordで作ったWebhookのURLつっこんで
起動したらあとは勝手にやります()

### Webhookとはなんぞや
Discordが提供してくれているURLでメッセージ送る奴
やり方は調べてね

### 動いたらこんな感じになるよ的な
![例](https://user-images.githubusercontent.com/80146606/205473066-7cba4b43-9dc9-4eb8-9516-025d43916f3b.png)

## 注意
・途中でWebhookURL変わった！っていう人はこのプラグインのコンフィグファイルがあるから消してね。

・サーバーステータスにERRORって出てるんだが？ -> サーバーが意図しない方法で停止されたからだと思う(つまり再起動で解決)

・コード汚いのは元が私用だったからっていうのがあるから許してね:-:

## 何で作ったん
配布なかったからってのと、使いたい人多そうだったから。