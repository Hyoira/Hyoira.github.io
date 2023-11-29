# 怠惰部マイクラ鯖
身内向けマイクラ鯖の情報。
たまに技術メモとかも書くかも。

## サーバーアドレス
discordチャンネル `#minecraft` のトピックに記載されたでアクセスできます。

## プラグイン説明

### インベントリ整理 ClickSort v1.6.1
[ClickSort 1.6.1](https://www.spigotmc.org/resources/clicksort.27021/)

#### できること
- アイテム枠を操作することでインベントリなどのアイテムを整列できる

#### カスタマイズ
- ソート操作方法の変更
  - `/clicksort click <single | double | none>` で変更
  - `single`(スロットをシングルクリックでソート)、`double`(スロットをダブルクリックでソート)、`none`(ソート操作なし)
- ソート種類の変更
  - `/clicksort sort <id | name | group | value>` で変更
  - デフォルトは`id`(アイテムIDで整列)
- 上記の変更はShift+左右クリックでもできるが、それが煩わしい場合は無効にできる
  - `/clicksort shiftclick`で本機能の有効/無効を切り替える

### チャットのローマ字変換 LunaChat
[LunaChat](https://www.spigotmc.org/resources/lunachat.82293/)

#### できること
- チャットに入力したローマ字を日本語に変換してくれる


## ツール
### Chunker - 公式のワールド変換ツール
[Chuinker](https://learn.microsoft.com/ja-jp/minecraft/creator/documents/chunkeroverview)




## 今後導入したいもの
- Bedrock EditionとJava Editionの両方から入れるようにする
  - [GeyserMC](https://geysermc.org/) とか [Floodgate](https://wiki.geysermc.org/floodgate/setup/) を使う
- サーバーの自動再起動スクリプト
- サーバーの自動バックアップスクリプト
- 今までのワールドを振り返ることができるようなマルチバース鯖
  - [MultiVerse](https://www.spigotmc.org/resources/multiverse-core.390/) とか [MultiWorld](https://www.spigotmc.org/resources/multiworld.2124/) とか
  - 導入済み
  - 今度の改善
    - プレイヤーが任意にワールドを移動できるようにする
    - 過去のワールドをなるべく漁っておく