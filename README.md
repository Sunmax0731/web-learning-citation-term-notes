# web-learning-citation-term-notes

Web学習・引用・用語抽出ノート は、ページ保存、引用クリップ、長文読書ノート、YouTube講座メモ、用語抽出、学習ハイライトをブラウザ上でまとめる。

## 何を解決するか

Webで学んだ内容がブックマーク、動画メモ、用語メモに分散し、復習しづらい。

## 差別化

ページ、動画、用語、引用を同じ学習ノートとして保存する。

## 公開先

- Chrome Web Store

## 現在の到達点

- core / validators / report / review-model / CLI に責務を分割済み
- Chrome拡張 Side Panel + local notes の最小実装または配布用骨格を同梱済み
- 代表シナリオ `samples/representative-suite.json` で正常系、必須項目不足、warning、混在バッチを自動検証済み
- 厳格 QCDS は Quality、Cost、Delivery、Satisfaction の全観点 S+ で評価済み
- docs ZIP は `dist/web-learning-citation-term-notes-docs.zip`

## 主要コマンド

```powershell
npm test
npm start
```

## 重要ドキュメント

- [要件定義](docs/requirements.md)
- [仕様](docs/specification.md)
- [設計](docs/design.md)
- [手動テスト](docs/manual-test.md)
- [厳格手動テスト追補](docs/strict-manual-test-addendum.md)
- [QCDS評価](docs/qcds-evaluation.md)
- [厳格QCDS metrics](docs/qcds-strict-metrics.json)
- [トレーサビリティ](docs/traceability-matrix.md)

## 参照したアイデアパック

- created_idea: `D:\AI\ChromeExtension\created_idea_002_web-learning-citation-term-notes`
- idea ZIP: `D:\AI\ChromeExtension\created_idea_002_web-learning-citation-term-notes\idea_002_web-learning-citation-term-notes.zip`
- PICKUP rank: 39
- Domain: ChromeExtension
