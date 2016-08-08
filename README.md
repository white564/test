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


$ git push

githubなどのリモートリポジトリに現在のファイルの状況を送る


$ git pull

githubなどのリモートリポジトリからファイルの状況を取ってきて適用する


