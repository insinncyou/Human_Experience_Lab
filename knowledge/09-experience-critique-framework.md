# Experience Critique Framework

Experience Critiqueは、人が接するあらゆる体験を、観察から再利用可能な原則まで分析・訓練するためのフレームワークである。対象はUIだけでなく、プロダクト、サービス、空間、接客、広告、AI対話、業務フローを含む。

## 目的と非目的

目的は、体験の評価を「好き／嫌い」から、文脈・証拠・因果・トレードオフにもとづく設計判断に変えることである。

非目的は、短時間でUI改善案を量産すること、心理学用語で判断を飾ること、単発観察から普遍的な真理を断定すること。

## Phase model

| Phase | ユーザーが行うこと | コーチの主な問い | 出力 |
|---|---|---|---|
| 0. Frame | 題材、利用者、場面、問い、証拠、時間を定める | 「どの一場面を扱う？何を理解したい？」 | Critique brief |
| 1. Observation | 解釈なしの事実を列挙する | 「カメラに映るように何が起きた？」 | Observations |
| 2. Interpretation | 意味づけを複数案で書く | 「この事実は他にどう読める？」 | Interpretations |
| 3. Critical Questioning | 根拠・比較・前提・反証を検査する | 「誰にとって？何と比べて？反例は？」 | Evidence gaps |
| 4. Hypothesis | 因果鎖と検証方法をつくる | 「何が、どのように、どんな結果へつながる？」 | Testable hypotheses |
| 5. Human mechanism | 必要なJTBD、心理、行動、システム制約を接続する | 「望む進歩は？摩擦・不確実性・フィードバックは？」 | Mechanism map |
| 6. Experience judgment | 方向性とトレードオフを比較する | 「何を優先し、何を失う？別案は？」 | Decision rationale |
| 7. Generalization / Application | 条件付き原則、反証条件、別場面への適用を書く | 「どこまで再利用でき、どこで壊れる？」 | Experience Principle and application candidate |
| 8. Knowledge capture | ノート化し、過去知識との関係を記録する | 「何を更新・限定・反証する？」 | Research Note |

Phaseは直線ではない。新しい証拠が出たらObservationまたはInterpretationへ戻る。解決策はPhase 6より前に決めない。

## Coaching protocol

- 訓練中は一度に一つの中心質問だけを出す。
- ユーザーの答えには、結論の正否よりも、事実と推論の分離・根拠・代替説明をフィードバックする。
- 二度詰まったらヒント、三度詰まったか明示的に求められたら短い例示を出す。
- 「改善案は？」を急がず、先に何が起き、誰が何を失い／得たかを確かめる。
- 個人の好みが出たら否定せず、観察根拠、文脈適合、トレードオフに翻訳する。
- 既知知識を使う場合は、出典・適用範囲・未検証部分を区別する。

## Capability rubric

各セッションで扱った能力だけを0〜5で評価する。合計点で競わせず、次の練習を決めるために使う。

| 能力 | 0–1: 入口 | 2–3: 実践 | 4–5: 成熟 |
|---|---|---|---|
| Observation | 評価や原因と混ざる | 主要事実を分離できる | 再確認可能な具体性と欠けた証拠を示せる |
| Critical Thinking | 最初の印象を採用する | 前提・比較・代替説明を問える | 反証条件と判断限界を自ら設計できる |
| Hypothesis / Causality | 原因を断定する | 因果鎖と確信度を書ける | 交絡・複数要因・検証法まで扱える |
| Human Psychology / Behavior | ラベルを貼るだけ | 根拠ある機序候補を置ける | JTBD・文脈・行動・倫理を整合させられる |
| Articulation | 曖昧な形容詞に留まる | 観察→影響を説明できる | 他者が検証・再利用できる言葉にできる |
| Design Decision | 改善案を一案で断定する | 評価基準とトレードオフを示せる | 代替案・システム影響・検証優先度を判断できる |
| System Thinking | 接点を単独で見る | 前後の行動・制約を見られる | 複数接点、運用、権限、長期結果をつなげられる |
| Generalization | 事例の感想で終わる | 条件付きの示唆を書ける | 適用境界・反証・既存原則との関係まで定義できる |

フィードバックは、`Strongest move`、`Main blind spot`、`One better reasoning move`、`Next challenge` の4点で返す。未実施能力は採点しない。

## Framework selection

| 問い | 主に使うもの | Experience Critiqueとの関係 |
|---|---|---|
| 人は何の進歩を求め、何に切り替えるか | JTBD | Phase 5で必要なときに使う |
| 人は何を意図しているか、AIはどう支援すべきか | Intent / AI-era Reframe | 体験の入口・制御・期待調整を評価する |
| 主張の根拠、前提、反証は何か | Critical Thinking | Phase 3〜4の必須技術 |
| 注意、理解、動機、摩擦、習慣はどう働くか | Human Psychology / Behavior Design | Phase 5の説明仮説として使う |
| 何をどの条件で設計すべきか | Design / Experience Decision | Phase 6でトレードオフを扱う |

一つのフレームワークを全問に強制しない。JTBDが不明ならJTBDへ戻り、根拠が足りなければ心理説明や設計提案を保留する。

## Anti-patterns

- 「ボタンが小さいから悪い」のように、文脈・行動結果・比較なしで結論を出す。
- 「ユーザーは迷うはず」のように、対象者の内面を観察事実として扱う。
- 「認知負荷」「損失回避」などの語を、証拠なしに原因とする。
- 美しさ・簡潔さを普遍的な価値とし、高リスク場面の説明可能性や回復可能性を落とす。
- AIが最初から分析・改善案・完成原則を出し、ユーザーの推論を代替する。
- 一つのケースで原則を確定し、既存ノートとの矛盾を消す。

## Principle format

`When [specific context and person], they need/want [progress or human need]. Therefore, the experience should [direction], while avoiding [risk/trade-off].`

必ず、適用条件、例外、根拠状態、検証すべき次のケースを併記する。
