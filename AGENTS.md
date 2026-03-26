# AIコーディングエージェント向けのガイドライン

AIコーディングエージェント向けのガイドラインを記載します。

## 動作環境

ローカル環境でGitHub CLIが動作することを前提としています。

## 使用言語

ユーザーへの回答や、各種アウトプットに、日本語を使用します。

## Git運用

- `feature/` から始めるブランチ名とします
- コミット前に差分を確認し、複数の関心が混在している場合は、変更単位ごとに別々にコミットします
- コミットメッセージは、変更内容と目的が第三者に伝わるように記載します

## GitHub PR作成

GitHubのPR作成を指示された場合は、以下の方針でPRを作成します。

- タイトルは開発対象のIssueと同じとします
- PRの説明を変更内容と目的が第三者に伝わるように記載します
- `Resolves` の記法を用いて開発対象のIssueと紐づけます
- assigneeに実装者を指定します

## はてなブログのCSSテンプレート

- <https://github.com/hatena/Hatena-Blog-Theme-Boilerplate/blob/master/scss/boilerplate.scss>
- https://github.com/hatena/Hatena-Blog-Theme-Boilerplate/blob/master/scss/lib/_core.scss
- https://github.com/hatena/Hatena-Blog-Theme-Boilerplate/blob/master/scss/lib/_variable.scss

はてなブログで利用可能なセレクターなどについては、リンク先を確認してください。
