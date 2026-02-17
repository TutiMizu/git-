# gh コマンド よく使うもの一覧

## 認証

| コマンド | 説明 |
|---|---|
| `gh auth login` | GitHubにログイン |
| `gh auth status` | 認証状態を確認 |
| `gh auth logout` | ログアウト |

## リポジトリ

| コマンド | 説明 |
|---|---|
| `gh repo list` | リポジトリ一覧 |
| `gh repo create <名前>` | 新規作成 |
| `gh repo clone <名前>` | クローン |
| `gh repo delete <名前>` | 削除 |
| `gh repo rename <新名>` | リネーム |
| `gh repo view <名前>` | 詳細表示 |
| `gh repo edit` | 設定変更（説明、公開/非公開等） |
| `gh repo fork <名前>` | フォーク |

## Pull Request

| コマンド | 説明 |
|---|---|
| `gh pr create` | PR作成 |
| `gh pr list` | PR一覧 |
| `gh pr view <番号>` | PR詳細 |
| `gh pr merge <番号>` | PRマージ |
| `gh pr checkout <番号>` | PRのブランチに切替 |
| `gh pr close <番号>` | PRを閉じる |

## Issue

| コマンド | 説明 |
|---|---|
| `gh issue create` | Issue作成 |
| `gh issue list` | Issue一覧 |
| `gh issue view <番号>` | Issue詳細 |
| `gh issue close <番号>` | Issueを閉じる |

## Gist

| コマンド | 説明 |
|---|---|
| `gh gist create <ファイル>` | Gist作成 |
| `gh gist list` | Gist一覧 |
| `gh gist view <ID>` | Gist表示 |

## リリース

| コマンド | 説明 |
|---|---|
| `gh release create <タグ>` | リリース作成 |
| `gh release list` | リリース一覧 |
| `gh release download <タグ>` | アセットダウンロード |

## その他

| コマンド | 説明 |
|---|---|
| `gh api <エンドポイント>` | GitHub APIを直接呼び出す |
| `gh browse` | ブラウザでリポジトリを開く |
| `gh status` | 通知・レビュー依頼等の状態確認 |

## よく使うオプション

- `--public` / `--private` : 公開/非公開指定
- `--yes` / `-y` : 確認をスキップ
- `--repo <owner/name>` : 対象リポジトリ指定
- `--limit <数>` : 表示件数
- `--json <フィールド>` : JSON形式で出力

詳しくは `gh help <コマンド>` で確認できます。
