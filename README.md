# my-memo-divorce

Claude Code CLI と対話しながらメモを溜めるための個人プロジェクト。

## 使い方

```sh
cd ~/Documents/development/SalesforceDX/ClaudeCodeTrial/my-memo-divorce
claude
```

起動したら Claude に話しかけるだけ。

```
> 今日読んだ本の感想をメモして: 〜〜
> Salesforceの権限セット周りで気づいたことをメモ: 〜〜
> Salesforceについてメモしたやつ見せて
```

運用ルールは `CLAUDE.md` に書いてある。

## 構成

- `inbox.md` — 分類前の雑多なメモ（デフォルト書き込み先）
- `notes/` — テーマ別に整理されたメモ
- `CLAUDE.md` — Claude 用の運用ルール
