# リファレンス

## ベースURL

https://ugc.renorari.net/api

## バージョン

v2に関することしかかれていません。

## Responseベース

`data`では結果が渡されます。

| name    | type    | description    |
| :--:    | :--:    | :--:           |
| success | boolean | 成功したか      |
| status  | int     | ステータスコード |
| message | ?string | エラーメッセージ |
| data    | json    | データ          |

## 認証

ヘッダー

```
Authorization: Bearer {Token}
```
