# メッセージ関連

## オブジェクト

| name          | type   | description |
| :---          | :---   | :---        |
| content       | string | メッセージコンテンツ |
| id            | string | メッセージID |
| clean_content | string | メッセージコンテンツからメンションを無効化したメッセージ |
| reference     | ?[MessageReference Object](/docs/v2/messages#Referenceオブジェクト) | メッセージの返信内容 |

## Referenceオブジェクト

| name       | type   | description |
| :---       | :---   | :---        |
| channel_id | string | チャンネルID  |
| guild_id   | string | サーバーID    |
| message_id | string | メッセージID  |

## メッセージを送信

`POST` `/messages`

Json payload

| name    | type                                          | description |
| :---    | :---                                          | :---        |
| author  | [Author Object](/docs/v2/users#オブジェクト)    | ユーザー      |
| channel | [Channel Object](/docs/v2/channel#オブジェクト) | チャンネル    |
| guild   | [Guild Object](/docs/v2/guild/#オブジェクト)    | サーバー      |
