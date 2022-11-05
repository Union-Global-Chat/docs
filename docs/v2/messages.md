# メッセージ関連

## メッセージを送信

`POST` `/messages`

Json payload

| name    | type                                          | description |
| :---    | :---                                          | :---        |
| author  | [Author Object](/docs/v2/users#オブジェクト)    | ユーザー      |
| channel | [Channel Object](/docs/v2/channel#オブジェクト) | チャンネル    |
| guild   | [Guild Object](/docs/v2/guild/#オブジェクト)    | サーバー      |
