# パッチノート

## v 1.1.1 ~ 1.1.3

### 修正(v 1.1.1 ~ 1.1.3)

- インポートができないバグが発生していたため修正を試みました。

### 追加及び変更(v 1.1.1 ~ 1.1.3)

- それぞれ、バージョンを上げました

## v 1.1.0

### 修正(v 1.1.0)

- recipes の format version を 1.12 に変更しました

### 追加および変更(v 1.1.0)

- 新しく `./recipes/furnace_wfbundle_bread` を追加しました。そのため、かまどで小麦粉の袋を焼くとパンがドロップします。[^1]
- 新しく `./texts/en_US.lang` を追加しました。これにより、日本語だけでなく英語もサポートされ、さらにそれ以外の言語の人も英語で遊ぶことができるようになりました。
- `./manifest.json` の version を [1,0,3] から[1,1,0] に変更しました。

[^1]:小麦をそのままパンにクラフトすると小麦一つに対してパン一つですが、一度小麦粉の袋にすることで小麦一つに対してパン二つを作成できます。ただし革が必要になります。

___

## v 1.0 以下について

これらのバージョンはバグが発生しており、正常にアドオンを楽しめません(v 1.0.3 はインポートも出来ません)。そのため、ここでは修正・追加・変更点を記載しません。
なお、v 1.0.0 に関しては、logからも削除されており、閲覧が不可能です。
