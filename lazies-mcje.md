# 怠惰部マイクラ鯖
身内向けマイクラ鯖の情報。
たまに技術メモとかも書くかも。

## サーバーアドレス
discordチャンネル `#minecraft` のトピックに記載されたでアクセスできます。

## 統合版・Java版の連携
現在、このサーバーは Java Edition と Bedrock Edition の両方から接続できます。

自分のアカウントを連携したい場合は以下の手順から。

1. 接続用サーバーに行く
   - 統合版・Java版の両方で `link.geysermc.org` のサーバーに接続する
   - ログインできたら、どちらかの端末で `/linkaccount` とコマンドを実行する
   - 4桁の数字が出てくるので、もう一方の端末で `/linkaccount 0000` のように4桁の数字を入れたコマンドを実行する
   - サーバーから自動的に切断されたらOK
2. いつも通りログインする
   - 統合版のサーバー追加から、アドレスはいつものやつ、ポートは `19132` を指定して接続できる

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
- サーバーの自動再起動スクリプト
- サーバーの自動バックアップスクリプト
- 今までのワールドを振り返ることができるようなマルチバース鯖
  - [MultiVerse](https://www.spigotmc.org/resources/multiverse-core.390/) とか [MultiWorld](https://www.spigotmc.org/resources/multiworld.2124/) とか
  - 導入済み
  - 今度の改善
    - プレイヤーが任意にワールドを移動できるようにする
    - 過去のワールドをなるべく漁っておく