# japanese-toxic-dataset

ANLP2022「日本語有害表現スキーマの提案と評価」にて考案した日本語における有害表現を検知するためのスキーマとデータセットを提供しています。

リポジトリの構成は次の通りです。

- `schema_ja.md`: ラベリングスキーマ
- `data/subset.csv`: 「日本語有害表現スキーマの提案と評価」で利用したデータセットのサブセット


## データセットの詳細

`data/subset.csv`は次のカラムで構成されています。

|カラム名|説明|
|:-|:----|
|id|文章ID|
|text|文章|
|Not Toxic|有害レベル: Not Toxic|
|Hard to Say|有害レベル: Hard to Say|
|Toxic|有害レベル: Toxic|
|Very Toxic|有害レベル: Very Toxic|
|category_卑語|有害カテゴリ: 卑語|
|category_差別|有害カテゴリ: 差別|
|category_迷惑行為|有害カテゴリ: 迷惑行為|
|category_猥褻|有害カテゴリ: 猥褻|
|category_出会い・プライバシー侵害|有害カテゴリ: 出会い・プライバシー侵害|
|category_違法行為|有害カテゴリ: 違法行為|
|category_偏向表現|有害カテゴリ: 偏向表現|
|annotation_num|アノテータ数|
