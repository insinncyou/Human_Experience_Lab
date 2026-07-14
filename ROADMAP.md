# Human Experience Lab Roadmap

## Product definition

Human Experience Labは、Human Experience Architectへ成長するためのAI学習・訓練・研究システムです。

Custom GPTは対話入口、Markdownは持続する知識資産、Codexは整理・更新役、Product Designer OSは実務適用先です。

## Current release: v1.0 — Start Training

Goal: その日から15分の訓練を開始できること。

Included:

- Custom GPT configuration
- Released Instructions
- Core Knowledge
- Prompt library
- Research Note template
- JTBD / Psychology / Behavior / Aesthetic Judgment modes

Exit criteria:

- Preview acceptance testを通過
- 4週間で最低8回の短時間訓練
- Aesthetic Judgment Labを最低4回実施
- Research Noteを最低4件保存
- 同じ運用上の失敗が3回以上発生した箇所を特定

## v1.1 — Calibrate from Use

Trigger: v1.0を2〜4週間使用し、実際の失敗パターンが確認できたとき。

Candidates:

- 質問難易度の調整
- スコア基準の校正
- セッション時間別の短縮フロー
- Research Note出力の改善
- 冗長または重複するInstructionsの削減

v1.1に入れないもの:

- 使用実績のない大規模な学問モジュール
- 自動化のためだけの複雑な外部連携

## v1.2 — Knowledge Operations

Trigger: Research Noteが10件以上蓄積し、検索・重複・索引の問題が現れたとき。

Candidates:

- Knowledge index
- Design Principle registry
- Codex整理プロンプトの強化
- 月次レビュー
- Backlog / Decisions / Changelog

## v2.0 — Curriculum and Progress System

Trigger: 継続運用が確認され、訓練の習慣よりも難易度設計が次のボトルネックになったとき。

Candidates:

- 12週間または100日カリキュラム
- レベル別課題
- 成長ダッシュボード
- Academy / Trainer / Researchの明確な分離
- Behavioral Economics、Cognitive Science、Anthropologyの拡張

## Version-up decision rule

バージョンアップは、次の順に判断します。

1. 実際のセッションを観察する
2. 繰り返す問題を特定する
3. 原因がInstructions、Knowledge、Prompt、運用のどこにあるか分ける
4. 最小の変更を提案する
5. Previewで回帰テストする
6. 理由と変更点を記録してリリースする

メジャーバージョンは、目的・ユーザー体験・主要ワークフローのいずれかが変わる場合にのみ上げます。

## First four weeks

### Week 1

- GPTをセットアップ
- Previewテスト
- JTBD Trainingを2回
- Aesthetic Judgment Labを1回

### Week 2

- Product Analysisを1回
- JTBD Reviewを1回
- Aesthetic Judgment Labを1回
- Research Noteを2件保存

### Week 3

- 異なる業界を題材に2回訓練
- Aesthetic Judgment Labで画像生成を1回使用
- 自分の判断への反論を記録

### Week 4

- 週次ノートをまとめてレビュー
- 繰り返し現れた強みと盲点を抽出
- v1.1候補を最大3件に絞る
- Instructionsの変更前に、問題が再現するかPreviewで確認

