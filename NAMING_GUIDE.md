# Character and model naming guide

この文書は、キャラクター名・プレイヤー表示名・技術的なモデル名を区別するための推奨事項です。

ライセンス条件そのものは [Tomiya Character License v1.0](LICENSE) を参照してください。

## キャラクター名とモデル名は別

キャラクター／プレイヤープロフィールの名前や画像と、技術的なモデル成果物の名称は別に扱えます。

例:

```text
Player profile
  name: Wise Misk / 賢者ミスク
  image: Wise Misk artwork

Model artifact
  name: My-Misk-Tune-2B
  base: Qwen...
  derived_from: official/default model
  publisher: community author
```

公式モデルを使用しながら、プレイヤー表示名や画像だけ変更することもできます。

## コミュニティモデル

ファインチューニング、追加学習、変換などを行ったモデルには、元モデルと区別できる独自の技術名を付けることを推奨します。

例:

- `My-Misk-Tune-2B`
- `GameFox-2B`
- `Alice-RPG-Adapter`
- `GameFox-2B — fine-tuned from Wise Misk`

次のような由来表記も問題ありません。

- “fine-tuned from Wise Misk”
- “Wise Misk-derived”
- “based on the default Wise Misk model”

## キャラクター素材

Rim、gohon、賢者ミスクその他の対象キャラクター素材は、原則として Tomiya Character License v1.0 に従います。

ライセンス上、キャラクター名や設定の変更も可能です。

ただし、改変版やコミュニティ版を公式版であるかのように表示してはいけません。

## Official / Community の区別

アプリやモデルカタログでは、可能なら次の情報をプレイヤー表示名とは別に管理することを推奨します。

- official / community
- publisher
- base model
- derivation / provenance
- artifact hash

これにより、自由な改変や再利用を妨げずに、公式成果物とコミュニティ成果物を区別しやすくなります。
