# rubyubuntu
how to use ruby on rails on Ubuntu

how to push code to github
1.rails newでプロジェクトを作成,git initでgit環境構築
Railsでプロジェクトを作成
rails new project_name
Railsプロジェクトを作成するGitコマンド
cd project_name
Gitを開始
git init
.gitignoreに.DS_Storeを追加
vim .gitignore
ファイルをコミット
git add .
git commit -m "initial commit"

2.Github websiteでrepositoryを追加
githubにログイン後、メニューより新規リポジトリを作成。
※「Initialize this repository with a README」にはチェックを入れずに Create repositoryをポチ。

3.リモートのリポジトリを追加
 Railsアプリのルートディレクトリにて、以下のコマンドを叩いてgithubにプッシュ。
 git remote add origin git@github.com:nigohiroki/project_name.git
 
 git pull origin master
 
 これで完了！
