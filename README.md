# LevenshteinDistance
レーベンシュタイン距離計算 JavaScript版

### レーベンシュタイン距離とは？

２つのワードにおける編集距離のこと。

→ 編集・追加・削除それぞれについて１ポイントとし、合計のポイント数のこと。

#### example

`こうたい` と `こうじ` の編集距離

1. `こうたい` の `い` を削除　→　`こうた`
2. `こうた` の `た` を `じ` に編集 `こうじ`

上記より、レーベンシュタイン距離は　__2__


### 参考にしたアルゴリズム

https://mathwords.net/hensyukyori
