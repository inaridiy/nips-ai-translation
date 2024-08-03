---
original: 13ddf7db8cf4a7871df219c613e9a3de1d6898800e063530335cfbe20f8965e6
---

# 破壊的変更

これは、既存の実装を潜在的に破壊するNIPの変更履歴で、新しい順に記載されています。

| 日付        | コミット    | NIP      | 変更内容 |
| ----------- | --------- | -------- | ------ |
| 2024-07-31  | [3ea2f1a4](https://github.com/nostr-protocol/nips/commit/3ea2f1a4) | [NIP-45](45.md) | [444ad28d](https://github.com/nostr-protocol/nips/commit/444ad28d) が元に戻された |
| 2024-07-30  | [444ad28d](https://github.com/nostr-protocol/nips/commit/444ad28d) | [NIP-45](45.md) | NIP-45が非推奨となった |
| 2024-07-26  | [ecee40df](https://github.com/nostr-protocol/nips/commit/ecee40df) | [NIP-19](19.md) | `nrelay`が非推奨となった |
| 2024-07-23  | [0227a2cd](https://github.com/nostr-protocol/nips/commit/0227a2cd) | [NIP-01](01.md) | イベントはcreated_atの後にidでソートされるべき |
| 2024-06-06  | [58e94b20](https://github.com/nostr-protocol/nips/commit/58e94b20) | [NIP-25](25.md) | [8073c848](https://github.com/nostr-protocol/nips/commit/8073c848) が元に戻された |
| 2024-06-06  | [a6dfc7b5](https://github.com/nostr-protocol/nips/commit/a6dfc7b5) | [NIP-55](55.md) | NIP番号が変更された |
| 2024-05-25  | [5d1d1c17](https://github.com/nostr-protocol/nips/commit/5d1d1c17) | [NIP-71](71.md) | 'aes-256-gcm'タグが削除された |
| 2024-05-07  | [8073c848](https://github.com/nostr-protocol/nips/commit/8073c848) | [NIP-25](25.md) | e-タグがスレッド全体を含まないように変更された |
| 2024-04-30  | [bad88262](https://github.com/nostr-protocol/nips/commit/bad88262) | [NIP-34](34.md) | 'earliest-unique-commit'タグが削除された（代わりに'r'タグを使用） |
| 2024-02-25  | [4a171cb0](https://github.com/nostr-protocol/nips/commit/4a171cb0) | [NIP-18](18.md) | 引用リポストは`q`タグを使用すべき |
| 2024-02-21  | [c6cd655c](https://github.com/nostr-protocol/nips/commit/c6cd655c) | [NIP-46](46.md) | パラメータが文字列化された |
| 2024-02-16  | [cbec02ab](https://github.com/nostr-protocol/nips/commit/cbec02ab) | [NIP-49](49.md) | パスワードが最初にNFKCに正規化された |
| 2024-02-15  | [afbb8dd0](https://github.com/nostr-protocol/nips/commit/afbb8dd0) | [NIP-39](39.md) | PGPアイデンティティが削除された |
| 2024-02-07  | [d3dad114](https://github.com/nostr-protocol/nips/commit/d3dad114) | [NIP-46](46.md) | 接続トークンのフォーマットが変更された |
| 2024-01-30  | [1a2b21b6](https://github.com/nostr-protocol/nips/commit/1a2b21b6) | [NIP-59](59.md) | 'p'タグがオプションになった |
| 2023-01-27  | [c2f34817](https://github.com/nostr-protocol/nips/commit/c2f34817) | [NIP-47](47.md) | オプションの有効期限タグが尊重されるべき |
| 2024-01-10  | [3d8652ea](https://github.com/nostr-protocol/nips/commit/3d8652ea) | [NIP-02](02.md) | リストエントリは時系列順であるべき |
| 2024-01-10  | [3d8652ea](https://github.com/nostr-protocol/nips/commit/3d8652ea) | [NIP-51](51.md) | リストエントリは時系列順であるべき |
| 2023-12-30  | [29869821](https://github.com/nostr-protocol/nips/commit/29869821) | [NIP-52](52.md) | 'name'タグが削除された（代わりに'title'タグを使用） |
| 2023-12-27  | [17c67ef5](https://github.com/nostr-protocol/nips/commit/17c67ef5) | [NIP-94](94.md) | 'aes-256-gcm'タグが削除された |
| 2023-12-03  | [0ba45895](https://github.com/nostr-protocol/nips/commit/0ba45895) | [NIP-01](01.md) | WebSocketステータスコード`4000`が'CLOSED'メッセージに置き換えられた |
| 2023-11-28  | [6de35f9e](https://github.com/nostr-protocol/nips/commit/6de35f9e) | [NIP-89](89.md) | 'client'タグの値が変更された |
| 2023-11-20  | [7822a8b1](https://github.com/nostr-protocol/nips/commit/7822a8b1) | [NIP-51](51.md) | `kind: 30000`と`kind: 30001`が非推奨となった |
| 2023-11-11  | [cbdca1e9](https://github.com/nostr-protocol/nips/commit/cbdca1e9) | [NIP-84](84.md) | 'range'タグが削除された |
| 2023-11-10  | [c945d8bd](https://github.com/nostr-protocol/nips/commit/c945d8bd) | [NIP-32](32.md) | 'l'タグの注釈が削除された |
| 2023-11-07  | [108b7f16](https://github.com/nostr-protocol/nips/commit/108b7f16) | [NIP-01](01.md) | 'OK'メッセージは4つの項目を持つ必要がある |
| 2023-10-17  | [cf672b76](https://github.com/nostr-protocol/nips/commit/cf672b76) | [NIP-03](03.md) | 'block'タグが削除された |
| 2023-09-29  | [7dc6385f](https://github.com/nostr-protocol/nips/commit/7dc6385f) | [NIP-57](57.md) | オプションの'a'タグが`zap receipt`に含まれた |
| 2023-08-21  | [89915e02](https://github.com/nostr-protocol/nips/commit/89915e02) | [NIP-11](11.md) | 'min_prefix'が削除された |
| 2023-08-20  | [37c4375e](https://github.com/nostr-protocol/nips/commit/37c4375e) | [NIP-01](01.md) | 同じタイムスタンプの置換可能なイベントは、最も低いidのイベントを保持すべき |
| 2023-08-15  | [88ee873c](https://github.com/nostr-protocol/nips/commit/88ee873c) | [NIP-15](15.md) | 'countries'タグが'regions'に名称変更された |
| 2023-08-14  | [72bb8a12](https://github.com/nostr-protocol/nips/commit/72bb8a12) | [NIP-12](12.md) | NIP-12、16、20、33がNIP-01に統合された |
| 2023-08-14  | [72bb8a12](https://github.com/nostr-protocol/nips/commit/72bb8a12) | [NIP-16](16.md) | NIP-12、16、20、33がNIP-01に統合された |
| 2023-08-14  | [72bb8a12](https://github.com/nostr-protocol/nips/commit/72bb8a12) | [NIP-20](20.md) | NIP-12、16、20、33がNIP-01に統合された |
| 2023-08-14  | [72bb8a12](https://github.com/nostr-protocol/nips/commit/72bb8a12) | [NIP-33](33.md) | NIP-12、16、20、33がNIP-01に統合された |
| 2023-08-11  | [d87f8617](https://github.com/nostr-protocol/nips/commit/d87f8617) | [NIP-25](25.md) | 空の`content`は"+"とみなされるべき |
| 2023-08-01  | [5d63b157](https://github.com/nostr-protocol/nips/commit/5d63b157) | [NIP-57](57.md) | 'zap'タグが変更された |
| 2023-07-15  | [d1814405](https://github.com/nostr-protocol/nips/commit/d1814405) | [NIP-01](01.md) | `since`と`until`フィルターは`since <= created_at <= until`であるべき |
| 2023-07-12  | [a1cd2bd8](https://github.com/nostr-protocol/nips/commit/a1cd2bd8) | [NIP-25](25.md) | カスタム絵文字がサポートされた |
| 2023-06-18  | [83cbd3e1](https://github.com/nostr-protocol/nips/commit/83cbd3e1) | [NIP-11](11.md) | 'image'が'icon'に名称変更された |
| 2023-04-13  | [bf0a0da6](https://github.com/nostr-protocol/nips/commit/bf0a0da6) | [NIP-15](15.md) | 異なるNIPがNIP-15として再追加された |
| 2023-04-09  | [fb5b7c73](https://github.com/nostr-protocol/nips/commit/fb5b7c73) | [NIP-15](15.md) | NIP-15がNIP-01に統合された |
| 2023-03-15  | [e1004d3d](https://github.com/nostr-protocol/nips/commit/e1004d3d) | [NIP-19](19.md) | `1: relay`がオプションに変更された |

2023-03-01以前の破壊的変更はまだ文書化されていません。

## 注意事項

- 変更が破壊的かどうか明確でない場合は、リストに含めています。
- 日付はコミットの日付ではなく、マージされた日付です。