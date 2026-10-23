# kushuel（クシュ）｜AIを使った開発・研究の記録

2026年5月末から、AIを使った開発・研究に取り組んでいます。主な題材は、Path of Building（PoB）の調査、ゲームの試作、数学のLean 4形式化です。

私は目的・対象範囲・優先順位・結果の採否を決め、調査・実装・形式化などにAIを活用しています。詳しくは[人間とAIの役割](AI_USE.md)をご覧ください。

## 公開した成果

**指定したランク2の入力族に対する、n+8手の上界構成のLean 4形式化**

固定した操作モデルのもとで、すべての自然数n（0を含む）について、指定した入力族から目標の順序付きの組(x, y)へn+8手で到達する構成をまとめました。最短性は主張していません。

- [公開リポジトリ：acc-nplus8-lean](https://github.com/kushuel-pixel/acc-nplus8-lean)
- [投稿で参照する固定commit](https://github.com/kushuel-pixel/acc-nplus8-lean/tree/3ce25bf13b32d31e6989ab663a913b65779624e4)
- SAIR ACC Proof Track：**ACC-P000019**、**Partial result（部分成果）**
- 投稿タイトル：*A Lean 4 Formalization of an n+8-Move Upper Bound for a Rank-Two Family*

SAIR上での公開投稿を確認しています。投稿に表示される区分と完全性は著者の申告であり、プラットフォームによる検証済みという意味ではありません。第三者による独立再現と、人間専門家の査読は未確認です。

詳しい対象範囲は[数学の活動紹介](cases/math.md)に記載しています。

## 主な活動

| 活動 | 内容 |
|---|---|
| [Path of Building（PoB）の調査](cases/pob.md) | ゲーム『Path of Exile』向けの構成・性能検討ツールについて、計算や入力状態を調べた活動 |
| [ジャンケンゲーム](cases/janken.md) | 最初の習作と、ライフ制・対戦履歴を加えた「三手決闘」の試作 |
| [VLNの試作](cases/vln.md) | 本人にとって転機となったツール制作の経験 |
| [数学のLean 4形式化](cases/math.md) | 指定した入力族に対するn+8手の上界構成と公開資料 |

活動の時期は[活動年表](TIMELINE.md)にまとめています。

## 資料について

数学の証明コードと検証資料は、上記の公開リポジトリで配布しています。この一式には、活動紹介と参照先を収録しています。

資料の有無と確認範囲は[公開資料と確認範囲](REPRODUCIBILITY.md)、利用許諾は[公開範囲とライセンス](PUBLICATION_POLICY.md)をご覧ください。

更新：2026-10-24（日本時間）

Copyright 2026 kushuel
