---
original: 13ddf7db8cf4a7871df219c613e9a3de1d6898800e063530335cfbe20f8965e6
---

# 破坏性变更

这是一份可能破坏现有实现的网络身份协议（NIP）变更历史，按时间倒序排列。

| 日期        | 提交    | NIP      | 变更 |
| ----------- | --------- | -------- | ------ |
| 2024-07-31  | [3ea2f1a4](https://github.com/nostr-protocol/nips/commit/3ea2f1a4) | [NIP-45](45.md) | [444ad28d](https://github.com/nostr-protocol/nips/commit/444ad28d) 被撤销 |
| 2024-07-30  | [444ad28d](https://github.com/nostr-protocol/nips/commit/444ad28d) | [NIP-45](45.md) | NIP-45 被弃用 |
| 2024-07-26  | [ecee40df](https://github.com/nostr-protocol/nips/commit/ecee40df) | [NIP-19](19.md) | `nrelay` 被弃用 |
| 2024-07-23  | [0227a2cd](https://github.com/nostr-protocol/nips/commit/0227a2cd) | [NIP-01](01.md) | 事件应在 created_at 之后按 id 排序 |
| 2024-06-06  | [58e94b20](https://github.com/nostr-protocol/nips/commit/58e94b20) | [NIP-25](25.md) | [8073c848](https://github.com/nostr-protocol/nips/commit/8073c848) 被撤销 |
| 2024-06-06  | [a6dfc7b5](https://github.com/nostr-protocol/nips/commit/a6dfc7b5) | [NIP-55](55.md) | NIP 编号被更改 |
| 2024-05-25  | [5d1d1c17](https://github.com/nostr-protocol/nips/commit/5d1d1c17) | [NIP-71](71.md) | 'aes-256-gcm' 标签被移除 |
| 2024-05-07  | [8073c848](https://github.com/nostr-protocol/nips/commit/8073c848) | [NIP-25](25.md) | e-标签被更改为不包含整个线程 |
| 2024-04-30  | [bad88262](https://github.com/nostr-protocol/nips/commit/bad88262) | [NIP-34](34.md) | 'earliest-unique-commit' 标签被移除（改用 'r' 标签） |
| 2024-02-25  | [4a171cb0](https://github.com/nostr-protocol/nips/commit/4a171cb0) | [NIP-18](18.md) | 引用转发应使用 `q` 标签 |
| 2024-02-21  | [c6cd655c](https://github.com/nostr-protocol/nips/commit/c6cd655c) | [NIP-46](46.md) | 参数被字符串化 |
| 2024-02-16  | [cbec02ab](https://github.com/nostr-protocol/nips/commit/cbec02ab) | [NIP-49](49.md) | 密码首先被标准化为 NFKC |
| 2024-02-15  | [afbb8dd0](https://github.com/nostr-protocol/nips/commit/afbb8dd0) | [NIP-39](39.md) | PGP 身份被移除 |
| 2024-02-07  | [d3dad114](https://github.com/nostr-protocol/nips/commit/d3dad114) | [NIP-46](46.md) | 连接令牌格式被更改 |
| 2024-01-30  | [1a2b21b6](https://github.com/nostr-protocol/nips/commit/1a2b21b6) | [NIP-59](59.md) | 'p' 标签变为可选 |
| 2023-01-27  | [c2f34817](https://github.com/nostr-protocol/nips/commit/c2f34817) | [NIP-47](47.md) | 应遵守可选的过期标签 |
| 2024-01-10  | [3d8652ea](https://github.com/nostr-protocol/nips/commit/3d8652ea) | [NIP-02](02.md) | 列表条目应按时间顺序排列 |
| 2024-01-10  | [3d8652ea](https://github.com/nostr-protocol/nips/commit/3d8652ea) | [NIP-51](51.md) | 列表条目应按时间顺序排列 |
| 2023-12-30  | [29869821](https://github.com/nostr-protocol/nips/commit/29869821) | [NIP-52](52.md) | 'name' 标签被移除（改用 'title' 标签） |
| 2023-12-27  | [17c67ef5](https://github.com/nostr-protocol/nips/commit/17c67ef5) | [NIP-94](94.md) | 'aes-256-gcm' 标签被移除 |
| 2023-12-03  | [0ba45895](https://github.com/nostr-protocol/nips/commit/0ba45895) | [NIP-01](01.md) | WebSocket 状态码 `4000` 被 'CLOSED' 消息替代 |
| 2023-11-28  | [6de35f9e](https://github.com/nostr-protocol/nips/commit/6de35f9e) | [NIP-89](89.md) | 'client' 标签值被更改 |
| 2023-11-20  | [7822a8b1](https://github.com/nostr-protocol/nips/commit/7822a8b1) | [NIP-51](51.md) | `kind: 30000` 和 `kind: 30001` 被弃用 |
| 2023-11-11  | [cbdca1e9](https://github.com/nostr-protocol/nips/commit/cbdca1e9) | [NIP-84](84.md) | 'range' 标签被移除 |
| 2023-11-10  | [c945d8bd](https://github.com/nostr-protocol/nips/commit/c945d8bd) | [NIP-32](32.md) | 'l' 标签注释被移除 |
| 2023-11-07  | [108b7f16](https://github.com/nostr-protocol/nips/commit/108b7f16) | [NIP-01](01.md) | 'OK' 消息必须有 4 个项目 |
| 2023-10-17  | [cf672b76](https://github.com/nostr-protocol/nips/commit/cf672b76) | [NIP-03](03.md) | 'block' 标签被移除 |
| 2023-09-29  | [7dc6385f](https://github.com/nostr-protocol/nips/commit/7dc6385f) | [NIP-57](57.md) | 可选的 'a' 标签被包含在 `zap receipt` 中 |
| 2023-08-21  | [89915e02](https://github.com/nostr-protocol/nips/commit/89915e02) | [NIP-11](11.md) | 'min_prefix' 被移除 |
| 2023-08-20  | [37c4375e](https://github.com/nostr-protocol/nips/commit/37c4375e) | [NIP-01](01.md) | 具有相同时间戳的可替换事件应保留 id 最小的事件 |
| 2023-08-15  | [88ee873c](https://github.com/nostr-protocol/nips/commit/88ee873c) | [NIP-15](15.md) | 'countries' 标签被重命名为 'regions' |
| 2023-08-14  | [72bb8a12](https://github.com/nostr-protocol/nips/commit/72bb8a12) | [NIP-12](12.md) | NIP-12、16、20 和 33 被合并到 NIP-01 中 |
| 2023-08-14  | [72bb8a12](https://github.com/nostr-protocol/nips/commit/72bb8a12) | [NIP-16](16.md) | NIP-12、16、20 和 33 被合并到 NIP-01 中 |
| 2023-08-14  | [72bb8a12](https://github.com/nostr-protocol/nips/commit/72bb8a12) | [NIP-20](20.md) | NIP-12、16、20 和 33 被合并到 NIP-01 中 |
| 2023-08-14  | [72bb8a12](https://github.com/nostr-protocol/nips/commit/72bb8a12) | [NIP-33](33.md) | NIP-12、16、20 和 33 被合并到 NIP-01 中 |
| 2023-08-11  | [d87f8617](https://github.com/nostr-protocol/nips/commit/d87f8617) | [NIP-25](25.md) | 空 `content` 应被视为 "+" |
| 2023-08-01  | [5d63b157](https://github.com/nostr-protocol/nips/commit/5d63b157) | [NIP-57](57.md) | 'zap' 标签被更改 |
| 2023-07-15  | [d1814405](https://github.com/nostr-protocol/nips/commit/d1814405) | [NIP-01](01.md) | `since` 和 `until` 过滤器应为 `since <= created_at <= until` |
| 2023-07-12  | [a1cd2bd8](https://github.com/nostr-protocol/nips/commit/a1cd2bd8) | [NIP-25](25.md) | 支持自定义表情符号 |
| 2023-06-18  | [83cbd3e1](https://github.com/nostr-protocol/nips/commit/83cbd3e1) | [NIP-11](11.md) | 'image' 被重命名为 'icon' |
| 2023-04-13  | [bf0a0da6](https://github.com/nostr-protocol/nips/commit/bf0a0da6) | [NIP-15](15.md) | 不同的 NIP 被重新添加为 NIP-15 |
| 2023-04-09  | [fb5b7c73](https://github.com/nostr-protocol/nips/commit/fb5b7c73) | [NIP-15](15.md) | NIP-15 被合并到 NIP-01 中 |
| 2023-03-15  | [e1004d3d](https://github.com/nostr-protocol/nips/commit/e1004d3d) | [NIP-19](19.md) | `1: relay` 变为可选 |

2023-03-01 之前的破坏性变更尚未记录。

## 注意事项

- 如果不清楚某个变更是否具有破坏性，我们会将其列出。
- 日期是合并的日期，不一定是提交的日期。