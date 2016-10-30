# xively-channel-service-client

Xively の 任意の Channel と MQTT publish/subscribe 通信をおこなうためのアプリケーションです。

# 0.利用方法
## 01.利用の前提
- 有効な Xively アカウントがあり、 有効な `Account ID` が利用出来る。
- 上記の Xively アカウントにおいて、 `device` が登録済みである。
- 上記の Xively アカウントをもちいて Webブラウザから [Xively CPM](https://app.xively.com/) にログイン可能である。または、API経由で
ログインできるように `API access token` を取得済みである。
  - `API access token` の取得は、[ログインAPI](http://developer.xively.com/reference#log-in) にて可能です。
  
