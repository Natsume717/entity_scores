# entity_scores
predicateのentity_scoresに関するデータパックサンプルになります。

詳しくはブログ記事『[【マイクラ】entity_scoresでスコアボードの値を確認【predicate】](https://natsumake.com/predicate_entity_scores/)』を参考にしてください。

<h3>使い方</h3>

導入後、スコアボード（sample_score）が画面横に掲載されます。<br>
出てこない場合は```/reload```を実行してください。

```/execute if predicate sample:test run give @a diamond 1```を実行することで、検証できます。

また、スコアボードの値は<br>
```/scoreboard players set @a sample_score 1000```<br>
といった感じのコマンドを実行して変更してください。
