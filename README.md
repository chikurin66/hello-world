# hello-world

—————1st time—————
# レポジトリ名と同じにする必要はないが，同じにしておくと便利
mkdir “directly name”

cd “directly name”

echo “ #’repository name’” >> README.md

# イニシャライズ？
git init

git add .

git commit -m “first commit”

# “repository name”.git
git remote add origin https://github.com/chikurin66/“repository name”.git

# リモートからローカルにレポジトリ内容を引っ張ってくる．
git pull -u origin master

〜〜〜作業〜〜〜

# だいたい“git add . ”でいい．全てのファイルを追加する
git add [ . / ( file_name ) ]

# テキストを書いてローカルのレポジトリに書き込む
git commit -m “txt”

# リモートにレポジトリの内容をアップする
git push origin master



—————2nd or more—————

# リモートからローカルにレポジトリ内容を引っ張ってくる．
git pull origin master

〜〜〜作業〜〜〜

# だいたい“git add . ”でいい．全てのファイルを追加する
git add [ . / ( file_name ) ]

# テキストを書いてローカルのレポジトリに書き込む
git commit -m “txt”

# リモートにレポジトリの内容をアップする
git push origin master
