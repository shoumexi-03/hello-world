# gitの説明

## gitとは
- gitとは分散管理型のバージョン管理システムである.
- 元々はオープンソースソフトウェア管理のためのソフトウェアであった.
- gitは変更履歴が残り, 変更した箇所に戻ることができる.
- 他人との共同編集を行うことが可能である. 

## gitの機能

- コミット
- レポジトリ
- ランチ


## gitのコマンド

### 設定,確認系
- git init<br>
  gitの初期化, 設定の開始
- git status<br>
  ワークツリーのステータスの表示
- git config<br>
  設定周りの確認, 変更
- git log<br>
  ログを表示<br>
  --onlineでコミットメッセージの1行のみの一覧を表示
- git diff<br>
  ファイルの差分を表示

### コミット系
- git add<br>
  ステージングエリアに追加
- git commit<br>
  コミットの実行

### 修正系
- git commit --amend --no-edit<br>
  コミットの修正
- git checkout<br>
  削除されたファイルの復旧,過去コミットの復元
- git reset<br>
  コミットのリセット
- git revert<br>
  "コミットの変更を打ち消す"コミット
- git rm
  ファイルとindex情報の削除


### リモート系
- git clone<br>
  レポジトリをコピー
- git pull<br>
  リモートレポジトリの同期
- git push<br>
  変更をアップロードする
- git request-pull<br>
  プルリクエスト: 変更依頼
- git remote<br>
  リモートレポジトリの設定

### ブランチ系
- gt branch<br>
  ブランチの作成
- git checkout<br>
  ブランチの切り替え
- git merge<br>
　ブランチの統合
-git clone <br>
  レポジトリをコピー
-git push<br>
  変更をアップロードする

  
