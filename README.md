# karabiner-hhkb-jis-underscore-to-backslash

HHKB(JP配列)使用時、`International1`キー（`_`キー、スラッシュキーの右隣）を押すと 通常は `_`（アンダースコア）が入力されますが、このキーを`\`（バックスラッシュ）に 動作を変更する[Karabiner-Elements](https://karabiner-elements.pqrs.org/) 用の Complex Modifications ルールです。

## 動作

| 操作 | 変更前 | 変更後 |
|---|---|---|
| `International1` 単独 | `_` | `\`（バックスラッシュ） |
| `Shift` + `International1` | `_` | `_`（変更なし） |

## 動作環境

- macOS
- HHKB(JP配列)など、`International1` キーを持つJIS配列キーボード
- Karabiner-Elements

※ 本ルールは「`option` + `International3`」キー入力を `\` として扱う環境を前提としています。
ご自身の環境で `option` + `International3` が `\` を出力しない場合は、動作しない可能性があります。

## 導入方法

1. [Karabiner-Elements](https://karabiner-elements.pqrs.org/) をインストールする
2. Karabiner-Elements を起動し、**Complex Modifications** タブを開く
3. **Add your own rule** をクリック
4. 元の内容を削除し、本リポジトリの `international1_to_backslash.json` の中身を貼り付けて保存する
6. 一覧に表示されたルールが **Enable** であることを確認する

## ライセンス

特に制限を設けません。自由に改変・利用してください。
