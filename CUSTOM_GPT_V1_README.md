# Human Experience Lab

Version: 1.0.0  
Status: Ready to use  
Primary language: Japanese

Human Experience Lab（HEL）は、AI時代のプロダクトデザイナーが、人間の行動・認知・感情・動機を理解し、その理解を再利用可能な設計原則へ変換するための学習・訓練ワークスペースです。

## 目的

最終目的は、UIを素早く作ることではありません。

> UIを考える前に「この人は、この状況で何を達成しようとしているのか？」と自然に考えられる Human Experience Architect へ成長すること。

HELでは次の循環を回します。

```text
Learn → Train → Reflect → Generalize → Apply
 学ぶ     練習する   振り返る      原則化する     実務へ適用する
```

## v1.0の範囲

v1.0は、Custom GPTで今すぐ訓練を始めることに集中します。

- JTBD思考訓練
- デザイン心理学との接続
- 行動設計の分析
- Aesthetic Judgment（審美判断）訓練
- セッションごとの評価と振り返り
- Research NoteとDesign Principleの生成

GitHub自動更新、長期ダッシュボード、100日分の完全カリキュラムは、実際の使用データを得てから追加します。

## ファイル構成

```text
Human_Experience_Lab/
├── README.md
├── ROADMAP.md
├── custom-gpt/
│   ├── CONFIG.md
│   └── INSTRUCTIONS.md
├── knowledge/
│   └── CORE_KNOWLEDGE.md
├── prompts/
│   └── PROMPTS.md
├── templates/
│   └── RESEARCH_NOTE_TEMPLATE.md
└── research-notes/
    └── README.md
```

## 10分でセットアップ

1. ChatGPTのWeb版で「GPTを作成」を開きます。
2. `custom-gpt/CONFIG.md` のName、Description、Conversation Startersを入力します。
3. `custom-gpt/INSTRUCTIONS.md` の内容を「指示」欄へ貼り付けます。
4. `knowledge/CORE_KNOWLEDGE.md` をKnowledgeへアップロードします。
5. Previewで `今日のHuman Experience Trainingを開始してください。` と入力します。
6. テストに合格したら、まずは非公開で保存します。

## 毎週の推奨運用

| 頻度 | セッション | 目安 |
|---|---|---:|
| 週2回 | JTBD / Psychology Training | 15〜20分 |
| 週1回 | Aesthetic Judgment Lab | 45〜60分 |
| 週1回 | Weekly Reflection | 15分 |

訓練後は、GPTに「Research Note形式で出力してください」と依頼し、`research-notes/` に保存します。

## 役割分担

- Human Experience Lab GPT: 問いかけ、訓練、批評、原則化
- あなた: 観察、仮説、判断、言語化
- Codex: Markdownの整理、索引化、重複の統合、将来のバージョン更新
- Product Designer OS: HELで得た原則を実案件へ適用

## v1.0の成功条件

- 迷わず訓練を開始できる
- GPTが講義より先にユーザーへ考えさせる
- 表面的な機能と深いJobを区別できる
- 各セッションから最低1つの学びまたは原則が残る
- 4週間後に自分の判断基準の変化を説明できる

## 更新方針

思いつきだけではInstructionsを増やしません。次のいずれかが起きたときに更新候補とします。

- 同じ失敗が3回以上繰り返される
- 既存の枠組みでは扱えないケースが複数現れる
- ユーザーの熟達により質問の難易度が合わなくなる
- 新しいモジュールの効果を実例で説明できる

詳細は `ROADMAP.md` を参照してください。

