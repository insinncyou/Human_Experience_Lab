# Human Experience Lab — Prompt Library v1.0

このファイルは、Human Experience Labを使う人のための操作メニューです。最初は全文を覚える必要はありません。

## 1. 今日の15分トレーニング

```text
今日のHuman Experience Trainingを15分で開始してください。
私に一度に一つだけ質問し、私が考えてから次へ進んでください。
最後に、強み・盲点・次の課題・Design Principleをまとめてください。
```

## 2. JTBDトレーニング

```text
身近な商品またはサービスを一つ選び、JTBDトレーニングを始めてください。
機能、タスク、機能的Job、感情的Job、社会的Jobを区別できるように質問してください。
答えは私が考えるまで提示しないでください。
```

## 3. 自分の分析をレビュー

```text
以下は私のJTBD分析です。
まず、良い点と弱い点を診断してください。
次に、一番重要な弱点を深掘る質問を一つだけしてください。

[ここに分析を貼る]
```

## 4. プロダクト分析

```text
[プロダクト名 / 機能] をHuman Experience Loopで分析したいです。
観察事実と仮説を混ぜず、Context、JTBD、Psychology、Behavior、Design Opportunity、AI-era Reframeの順に、私へ質問しながら進めてください。
```

## 5. Aesthetic Judgment Lab（画面なし）

```text
[プロダクト / 機能] を題材にAesthetic Judgment Labを始めてください。
最初にユーザー、タスク、ブランド意図、制約を確認し、評価基準を一緒に決めてください。
その後、見た目だけでなく設計思想が異なる3〜5案を文章で提示し、私に順位と理由を考えさせてください。
最後に私の判断へ反論し、Aesthetic Principleを一つ作ってください。
```

## 6. Aesthetic Judgment Lab（画像生成あり）

```text
[プロダクト / 機能] のAesthetic Judgment Labを始めます。
画像を作る前に、対象ユーザー、中心タスク、ブランド意図、使用環境、制約、評価基準を私と確定してください。
その後、情報階層・密度・インタラクションモデル・感情トーンが明確に異なる4方向のUIコンセプトを生成してください。
単なる色違いや既存ブランドの模倣にはしないでください。
```

## 7. 削る訓練

```text
この画面または構成から、核心のJobを損なわずに30%を削る訓練をします。
あなたが先に答えを出さず、削除候補を私に選ばせてください。
各判断について、情報階層、信頼、認知負荷、回復可能性への影響を問い返してください。
```

## 8. AIに自分の順位を反論させる

```text
以下が私のデザイン案ランキングと理由です。
別の経験豊富なDesign Directorの立場から、私の評価基準、盲点、個人的好みの混入を具体的に反論してください。
反論後、私に一つだけ再考の質問をしてください。

[ランキングと理由]
```

## 9. Research Noteを作る

```text
ここまでのセッションをResearch Noteにしてください。
観察、解釈、仮説、根拠、未検証点を明確に分けてください。
最後に、適用条件とリスクを含むDesign Principleを一つ作ってください。
```

## 10. 週次レビュー

```text
今週のResearch Notesをレビューしてください。
繰り返し現れたパターン、矛盾、根拠の弱い仮説、更新すべき判断基準を抽出してください。
来週は一つだけ、最も効果の高い訓練テーマを提案してください。

[今週のノートを貼る]
```

## 11. Design Principleの品質レビュー

```text
以下のDesign Principleをレビューしてください。
文脈の明確さ、人間の進歩、実装への過剰な具体化、トレードオフ、検証可能性の5点で評価してください。
完成文を先に書かず、改善のための質問を一つしてください。

[原則]
```

## 12. 直接教えてほしいとき

```text
今回は訓練ではなく解説モードで答えてください。
[テーマ] を、定義・なぜ重要か・具体例・よくある誤解の順に簡潔に説明してください。
```

## 13. CodexへResearch Noteを保存させる

```text
以下のHuman Experience Labセッションを、既存のRESEARCH_NOTE_TEMPLATE.mdに従って整理してください。
観察と仮説を分離し、曖昧な点を勝手に補完せず、Evidence statusを付けてください。
新しいResearch Noteとしてresearch-notes/YYYY-MM-DD-topic.mdへ保存し、必要ならREADMEの索引を更新してください。

[セッション内容]
```

## 14. Experience Critiqueを開始する

```text
Experience Critiqueを[15 / 30 / 60]分で開始してください。
題材は[UI / プロダクト / サービス / 空間 / 接客 / 広告 / AI対話]の[対象]です。
扱う場面は[誰が、いつ、どこで、何をしようとしているか]です。

AIは研究コーチとして、一度に一つだけ質問してください。答えや改善案を先に提示せず、Observation → Interpretation → Critical Questioning → Hypothesis → Human Psychology / Behavior → Experience Judgment → Generalizationの順に、必要な段階だけ進めてください。
事実、当事者の発言、解釈、仮説、既知知識を明確に区別し、各仮説には代替説明と検証方法を求めてください。
最後に、能力別フィードバック、Draft Experience Principle、既存Research Notesとの重複・矛盾・接続候補を含むResearch Noteを作ってください。
```

## 15. Experience CritiqueをResearch Noteへ保存する

```text
以下のExperience Critiqueセッションを、Templates/EXPERIENCE_CRITIQUE_RESEARCH_NOTE_TEMPLATE.mdに従ってResearch Noteへ整理してください。

- 曖昧な内容を補完せず、Observation / Reported / Interpretation / Hypothesis / Known knowledgeを分離する
- 仮説ごとにEvidence status、Confidence、Alternative explanation、How to test or falsifyを残す
- Experience Principleには適用条件、例外、トレードオフ、検証状態を付ける
- Research_Notes/を検索して、重複・補強・限定・矛盾候補をKnowledge connectionsへ記録する
- 新規ファイルはResearch_Notes/YYYY-MM-DD-short-topic.mdとして保存する

[セッション内容]
```
