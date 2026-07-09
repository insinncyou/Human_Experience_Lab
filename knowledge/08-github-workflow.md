# GitHub Workflow

ChatGPT / Custom GPT / Codex / GitHub を使い、低コストで学習Knowledgeを蓄積するための運用フロー。

## 基本方針

毎回保存しない。会話ログをすべて保存すると、Knowledgeがすぐにノイズで埋まる。

保存するのは、次回以降の分析、教育、研究、プロダクト検討に再利用できる学びだけにする。

## 保存すべき学びの基準

- 同じ失敗を避けるためのAnti-pattern
- 何度も使える分析フレーム
- 良いケーススタディ
- インタビュー質問の改善例
- UXやプロダクト戦略に接続できる示唆
- 自分の理解が一段深まったメモ

保存しないもの:

- 一回限りの雑談
- まだ粗い思いつき
- 既存資料の単なる要約
- 長すぎるGPTログ

## Markdown生成フロー

1. GPTとの対話で分析する
2. 重要な学びだけを選ぶ
3. `Templates/` のテンプレートに沿ってMarkdown化する
4. タイトル、日付、タグを入れる
5. 事実、解釈、仮説を分ける
6. GitHubに保存する

## Codexで保存・commit・pushする流れ

1. Codexに「この学びを研究ノートとして保存して」と依頼する
2. Codexが適切なフォルダとファイル名を提案する
3. Markdownを作成または追記する
4. 差分を確認する
5. commitする
6. pushする

例:

```text
Research_Notes/2026-07-09-notion-student-jtbd.md
```

## 推奨フォルダ構成

```text
JTBD/
  Fundamentals/
  Case_Studies/
  Interview_Practice/
  Service_Analysis/
  Failure_Analysis/
  Patterns/
  Anti_Patterns/
  Frameworks/
  Exercises/
Design_Psychology/
Behavioral_Design/
Service_Design/
Product_Strategy/
Research_Notes/
Templates/
Codex_Workflows/
```

## commit messageルール

形式:

```text
<type>: <short summary>
```

例:

- `docs: add JTBD interview notes`
- `docs: add case study for Notion onboarding`
- `templates: update research note format`
- `knowledge: refine JTBD anti-patterns`

初期コミットのみ:

```text
Initialize Human Experience Lab knowledge base
```

## ファイル名ルール

### 研究ノート

```text
YYYY-MM-DD-topic-name.md
```

例:

```text
2026-07-09-notion-student-jtbd.md
```

### ケーススタディ

```text
service-name-jtbd-case.md
```

例:

```text
notion-student-jtbd-case.md
```

### パターン / Anti-pattern

```text
pattern-short-name.md
anti-pattern-short-name.md
```

## 将来拡張しやすい運用方針

- Knowledgeは短く保ち、詳細研究は `Research_Notes/` に置く
- テンプレートは `Templates/` に集約する
- 学習が進んだら、`Patterns/` と `Anti_Patterns/` に再利用可能な型を移す
- Custom GPTのKnowledge更新時は、古いファイルを削るのではなく、統合・要約してから差し替える
- 重要な概念はタグで横断検索できるようにする
