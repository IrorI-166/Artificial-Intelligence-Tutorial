# Contribution Guide
オープンソース編集可能にするにあたり、コミット精度を統一するための指針です。

## GitHub Flowブランチルールに準拠します
GitHub Flowはmainブランチの直接のコミットを受け付けません。

## ドキュメントの修正・コードの修正
どちらも以下のフロー通過を原則とします。

1. Issueの作成
2. PullRequestの作成
3. Review
4. merge

### Issueの作成
似た内容、同じ内容のIssueが無いか確認の上、作成してください。
似た内容がある場合は、大枠としてマイルストーンを作成し、あなたのIssueと当該Issueを割り当ててください。

### PullRequestの作成
Issue作成完了後、PRを作成してください。
内容の明確化のため、作業ブランチ名をそのままPR名にしないでください。

### Review
PRのスコープが最適か判断した後、コードに修正点が無いことを確認します。

### merge
Review後、Squash and mergeでマージしてブランチをクローズします。