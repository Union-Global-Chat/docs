# メッセージ関連

## オブジェクト

| name          | type   | description |
| :---          | :---   | :---        |
| content       | string | メッセージコンテンツ |
| id            | string | メッセージID |
| clean_content | string | メッセージコンテンツからメンションを無効化したメッセージ |
| reference     | ?[MessageReference](/docs/v2/messages#返信オブジェクト) | メッセージの返信内容 |

## メッセージを送信

`POST` `/messages`

Json payload

| name    | type                                          | description |
| :---    | :---                                          | :---        |
| author  | [Author Object](/docs/v2/users#オブジェクト)    | ユーザー      |
| channel | [Channel Object](/docs/v2/channel#オブジェクト) | チャンネル    |
| guild   | [Guild Object](/docs/v2/guild/#オブジェクト)    | サーバー      |
