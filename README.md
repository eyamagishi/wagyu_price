# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
*リモートリポジトリ →ネット上にあるファイルやディレクトリの状態を記録する場所

*ローカルリポジトリ →PC上にあるファイルやディテクトリの状態を記録する場所

## プッシュとマージの違いは何でしょうか？
*プッシュ →現在のローカルのブランチの内容をリモートのブランチに上げるという意味のコマンド

*マージ →別のブランチの作業内容をブランチに取り込むコマンド

## コミットとプッシュの違い
*コミット →変更履歴を残す、セーブする。

*プッシュ →リモートにローカルブランチを反映させること

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
一目で変更内容がわかるようなコミットメッセージにする

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
プルリンククエストでマージするメリットは、複数のローカルでした変更した内容がリモート上でマージするかどうか選択することができる。それによってバグの発生を避けている。


## コンフリクトを起こしてしまった場合、どう対処すべきですか？
*先にマージされた変更内容を取り込む *後にマージようとしている変更内容を取り込む *どちらの変更内容も取り込む
