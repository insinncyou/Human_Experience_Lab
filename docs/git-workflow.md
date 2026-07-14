# Git ワークフロー

この文書は、Human Experience Lab で変更履歴を安全かつレビューしやすく保つための標準手順です。

## 基本方針

- `main` は常に共有可能な状態に保ちます。
- `main` へ直接コミットまたは push しません。
- 1 ブランチ、1 Pull Request、1 目的を原則とします。
- コミットには、その目的に必要なファイルだけを含めます。
- Pull Request をレビューしてから `main` へ統合します。

## 1. `main` を最新にする

```bash
git switch main
git pull --ff-only origin main
```

`--ff-only` を使うことで、意図しないマージコミットを避けます。作業中の変更がある場合は、先にコミットするか安全に退避してください。

## 2. 作業ブランチを作る

```bash
git switch -c <type>/<short-description>
```

推奨する接頭辞は次のとおりです。

| 接頭辞 | 用途 | 例 |
| --- | --- | --- |
| `docs/` | 文書の追加・更新 | `docs/add-interview-guide` |
| `feat/` | 新しい知識領域や仕組み | `feat/add-service-blueprint` |
| `fix/` | 誤りやリンク切れの修正 | `fix/jtbd-reference-link` |
| `chore/` | リポジトリ運用・保守 | `chore/repository-template` |

ブランチ名は小文字の英数字とハイフンを使い、内容が推測できる短い名前にします。

## 3. 変更を確認する

作業中は、意図したファイルだけが変更されているか確認します。

```bash
git status --short
git diff
```

生成物、認証情報、個人情報、顧客の秘密情報が含まれていないことも確認してください。

## 4. 対象ファイルだけをコミットする

```bash
git add path/to/file-a.md path/to/file-b.md
git diff --cached
git commit -m "docs: add interview research notes"
```

`git add .` や `git add -A` は、無関係な変更まで含める可能性があります。原則としてファイルパスを明示してください。

コミットメッセージは、次の形式を推奨します。

```text
<type>: <変更内容を表す短い命令形>
```

よく使う type は `docs`、`feat`、`fix`、`chore`、`refactor` です。1 コミットには、後から単独で説明・取り消しできるまとまりを含めます。

## 5. ブランチを push する

初回は upstream を設定します。

```bash
git push -u origin <branch-name>
```

2 回目以降は `git push` で更新できます。

## 6. Pull Request を作る

Pull Request テンプレートに沿って、次を記載します。

- 変更の目的と背景
- 主な変更点
- 影響するディレクトリや Knowledge
- 実施した確認
- レビュアーに見てほしい点

レビュー中に追加コミットを push すると、同じ Pull Request に反映されます。履歴を書き換える force push は、共同作業者と合意した場合を除き避けてください。

## 7. `main` の更新を取り込む

レビュー中に `main` が進んだ場合は、最新状態を取り込み、競合を解消して確認します。

```bash
git fetch origin
git rebase origin/main
```

共有済みブランチを rebase する場合は、共同作業者への影響を確認してください。rebase に不慣れな場合は、レビュアーまたはメンテナーに相談します。

## マージ後

Pull Request のマージ後はローカルを更新し、不要なブランチを削除します。

```bash
git switch main
git pull --ff-only origin main
git branch -d <branch-name>
```

リモートブランチの削除は、Pull Request の設定または GitHub 上で行います。

## 困ったとき

- 意図しないファイルを staged にした場合: `git restore --staged <file>`
- 変更内容を確認したい場合: `git diff` または `git diff --cached`
- 競合が発生した場合: 競合箇所を理解してから解消し、不明点があれば作業を止めて相談する

履歴を消す操作や force push は、影響を理解できないまま実行しないでください。
