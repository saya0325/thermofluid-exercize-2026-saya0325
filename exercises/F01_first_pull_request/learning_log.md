# F01 学習ログ

## 予想と結果

- 変更した箇所：student_greeting関数のTODO１を"Hello, $(normalized_name)!"に変更し，名前をsaya0325にした．
- 期待した表示と実際の表示：Hello, saya0325!

## 自分のテスト

- 自分で選んだ入力と期待値（実名は不要）：入力：@test F01FirstPullRequest.student_greeting("  Julia  ") ==
        期待値："Hello, Julia!"
- 保証すること・保証しないこと：空白を除去すること・特殊文字に対応していること
- 実行コマンドと結果：julia --project=. -e 'using Pkg; Pkg.test()'・すべてのテストをパスした．
Test Summary:             | Pass  Total  Time
F00 environment preflight |   87     87  3.8s
Test Summary:         | Pass  Total   Time
F00 course CLI wiring |    9      9  10.1s
Test Summary:  | Pass  Total  Time
F01 / tests.jl |    3      3  0.1s
     Testing ThermofluidExercise tests passed

## つまずきと判断

- つまずき、その対処と理由（なければ「なし」）：別のディレクトリにファイルが混在したことで，書き換えたものがどのファイルにあたるのかわからなくなってしまった．複製されてしまった分を消去したことと，正しいパスを指定したこと．単一で済むものをむやみに複製してしまったことで混乱したため．また正しいパスが指定できていなかったため．
- 配布済み必須テストが保証することと、自作テストの入力・期待値を選んだ理由：空白の時にエラーを返すこと．理由は特になし

## AI利用・出典

- 依頼内容（利用なしの場合は「利用なし」）：
- 重要な提案：
- 採用・修正・却下と理由：
- 外部素材の出典、変更点、利用条件（なければ「なし」）：


## 理解度チェック・LETUS提出

- 対応する授業ID：F01
- LETUS提出日：
- 提出済み確認：
- 理解できた点：ディレクトリ指定の方法
- 残った疑問：メインとブランチの違い．ブランチはどこに作られたのか．
- 対話全文はLETUSへ提出し，このリポジトリには含めていない：
