# tweet-bot-by-python
Python版のTweetBotです。<br>
Twitter時代に作成したのでXではありません。<br>
[Developer Portal](https://developer.twitter.com/en/portal/dashboard)<br>

```
pip install tweepy
import tweepy

pip install PyYAML
import yaml
```

## 使い方
tweet_list.txtに記載された内容を呟きます。<br>
上記URLからdeveloper登録をし、各種キーを取得した上でkeys.ymlに転記してください。<br>
タスクスケジューラやcronで定期的に実行させるとbotのような運用が可能になるはず。
