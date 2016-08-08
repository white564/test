# 基本コマンド

$ git init

gitの管理を始める


$ git status

いまのファイルの状態を確認する


$ git log

コミットの履歴を参照する(歴史を見る)


$ git diff

コミットとの差分を確認する(unstageなファイルとHEADを比較する)


$ git diff —cached

コミットとの差分を確認する(stagedなファイルとHEADを比較する)


$ git diff A B

AとBの差分を比較する。Bを省略するとHEAD(最新のコミット)になる。


$ git add -A

コミット対象にするファイルを追加する(staging)


$ git commit -m “コミットメッセージ”

メッセージ付きで現在のファイルの状況を保存する(commit)


$ git remote add origin プロジェクトのsshアドレス

githubのリポジトリとローカルを紐づける


$ git push -u origin master

最初だけ-uを使ってoriginにmasterをpushすることを明示する


$ git push

githubなどのリモートリポジトリに現在のファイルの状況を送る


$ git pull

githubなどのリモートリポジトリからファイルの状況を取ってきて適用する


# ブランチ編

$ git branch

ブランチのリストといまいるブランチを確認する


$ git branch ブランチ名

新しいブランチを作成する


$ git chechout ブランチ名

ブランチに移動する(checkout)


$ git merge ブランチ名

対象のブランチをいまいるブランチに取り込む


# プルリクエスト編

1. 新しいブランチを作ってチェックアウトする。

2. ファイルを編集する。

3. push -u origin ブランチ名

4. githubでopen pull requestボタンを押す

5. マージボタンを押してプルリクエストを取り込む


