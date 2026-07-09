# Human Experience Lab

Human Experience Lab は、JTBD（Jobs To Be Done）を中心に、人間の経験・行動・意思決定を研究し、UX、サービス設計、プロダクト戦略へ接続するための学習リポジトリです。

このリポジトリは、Custom GPT「Human Experience Lab — JTBD Trainer」のKnowledge、および日々の研究ノートの保存先として使います。

## 目的

- JTBD思考を反復練習し、ケース分析の精度を上げる
- 顧客の「機能要求」ではなく「達成したい進歩」を捉える
- UX心理学、行動設計、サービス設計、プロダクト戦略を横断的に学ぶ
- 重要な学びをMarkdownで蓄積し、再利用可能なKnowledge DBにする

## Knowledgeの使い方

`knowledge/` 配下の資料は、Custom GPTが参照する初期Knowledgeです。各ファイルは、JTBD分析、インタビュー、評価、研究ノート作成の基準として使います。

まずは以下の順で読むことを推奨します。

1. `knowledge/00-overview.md`
2. `knowledge/01-jtbd-fundamentals.md`
3. `knowledge/02-jtbd-analysis-framework.md`
4. `knowledge/04-evaluation-rubric.md`

## Custom GPTとの関係

Custom GPT「Human Experience Lab — JTBD Trainer」は、以下の用途で使います。

- JTBDケース分析の壁打ち
- インタビュー質問の改善
- 研究ノートの添削
- Anti-patternの指摘
- プロダクト改善仮説への変換

GPTとの対話で得た学びのうち、再利用価値が高いものだけをGitHubに保存します。

## GitHubを学習DBとして使う理由

- Markdownで軽量に蓄積できる
- 差分管理により、思考の変化を追える
- テンプレート化しやすく、学習形式を揃えられる
- 将来、Custom GPTのKnowledge更新や検索対象として再利用しやすい

## 初期フォルダ構成

```text
Human_Experience_Lab/
├ README.md
├ knowledge/
├ JTBD/
│  ├ Fundamentals/
│  ├ Case_Studies/
│  ├ Interview_Practice/
│  ├ Service_Analysis/
│  ├ Failure_Analysis/
│  ├ Patterns/
│  ├ Anti_Patterns/
│  ├ Frameworks/
│  └ Exercises/
├ Design_Psychology/
├ Behavioral_Design/
├ Service_Design/
├ Product_Strategy/
├ Research_Notes/
├ Templates/
└ Codex_Workflows/
```

## 運用方針

- 毎回すべてを保存しない
- 「後から参照したい学び」「再利用できる型」「失敗パターン」「分析の改善」が出たときだけ保存する
- 1ファイル1テーマを基本にする
- ファイル名は日付と短いテーマ名で管理する
- Knowledgeは定期的に見直し、肥大化したら統合・分割する
