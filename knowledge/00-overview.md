# Human Experience Lab Overview

## 目的

Human Experience Lab は、人がなぜ特定の行動を選び、どのような進歩を求めてサービスやプロダクトを使うのかを研究するための学習環境である。

中心に置く考え方は JTBD（Jobs To Be Done）である。単なるニーズ調査ではなく、ユーザーが置かれた状況、葛藤、代替行動、切り替えの瞬間を読み解き、UX・サービス設計・プロダクト戦略へ接続する。Experience Critiqueは、UIに限らない体験を観察・因果・原則として分析し、この人間理解を設計判断へつなぐ訓練である。

## JTBD Trainer GPTの役割

Custom GPT「Human Experience Lab — JTBD Trainer」は、以下の役割を持つ。

- JTBD分析の練習相手
- ケーススタディの構造化支援
- インタビュー設計のレビュー
- 分析のAnti-pattern指摘
- 研究ノートの添削
- プロダクト改善仮説への変換支援
- Experience Critiqueのソクラテス式コーチング

GPTは「正解を出す先生」ではなく、問いを深め、分析の粗さを可視化するトレーナーとして使う。

## 学習対象領域

- JTBD
- UX心理学
- 行動設計
- サービスデザイン
- プロダクト戦略
- リサーチ設計
- インサイト抽出
- 顧客理解と価値提案
- Experience Critique（観察、批判的思考、因果推論、設計判断、一般化）

## 学習レベル設計

### Level 1: 基礎理解

JTBDの用語、Jobの種類、代替行動、Struggleを理解する。

### Level 2: ケース分析

実在サービスや自分の体験をJTBDフレームで分解する。

### Level 3: インタビュー設計

過去の具体的行動を引き出す質問を設計し、仮説ではなく事実から分析する。

### Level 4: 戦略応用

分析結果をUX改善、価値提案、ポジショニング、プロダクトロードマップに接続する。

### Level 5: 知識体系化

学びを研究ノート、パターン、Anti-patternとして蓄積し、再利用可能なKnowledge DBにする。

## GPTとの基本的な練習方法

1. 具体的なサービス、体験、またはユーザー行動を1つ選ぶ
2. GPTにJTBD分析を依頼する
3. `Situation`、`Trigger`、`Desired Progress`、`Alternative`、`Struggle` を確認する
4. GPTにAnti-patternを指摘させる
5. 改善した分析を研究ノートとして保存する

例:

```text
Notionを使う大学院生のJTBDを分析してください。
特に、Evernoteや紙のノートではなくNotionに切り替える瞬間を重視してください。
```

## Experience Critiqueの基本練習方法

1. UI、サービス、空間、接客、広告、AI対話などから、観察可能な一場面を選ぶ
2. ObservationとInterpretationを分けて記録する
3. 根拠、代替説明、反証条件を問い、因果仮説をつくる
4. 必要なときだけJTBD、心理、行動、システム制約を説明仮説として使う
5. トレードオフを含むExperience PrincipleをDraftとして書く
6. 既存Research Notesとの重複・矛盾・接続候補を確認して保存する

詳細は `knowledge/09-experience-critique-framework.md` を参照する。

## GitHubをKnowledge DBとして使う方針

GitHubには、すべての会話を保存しない。保存するのは、次回以降も使える学びだけである。

保存対象:

- 良いJTBD分析
- 失敗した分析と修正内容
- インタビュー質問集
- ケーススタディ
- 繰り返し出てくるパターン
- プロダクト改善に使える示唆

保存しないもの:

- 単発の雑談
- まだ検証されていない思いつき
- 既存資料の軽い言い換え
- 再利用しにくい長文ログ
