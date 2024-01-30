# My Rust OS

[Philipp Oppermannのブログシリーズ](https://os.phil-opp.com/ja/)を参考にして実装したRust OSです。

## 機能

現在、このOSには以下のような基本的な機能が実装されています:

- VGAテキストバッファへの出力
- 割り込み処理（キーボード入力）
- ヒープメモリアロケーター
- 協調的タスク実行

## ビルドと実行

```bash
# リポジトリをクローンする
git clone https://github.com/nakamurau1/rust-os

# リポジトリに移動
cd rust-os

# QEMUでOSを起動
cargo run
```
