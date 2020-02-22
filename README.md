# ichiyasaGitSample
『いちばんやさしいGit&GitHubの教本』のサンプルプロジェクト

## 読書感想

・Chapter6 終了後、Chapter7 実施前に、以下のコマンドを実行
　してクリーンアップ（＝GitHubとmasterを同期）しておくこと。

$ git checkout master
$ git pull origin master

## その他

・電子書籍の目次ページから飛べない。（別途、ページ番号を印刷）
・git pull 実行時、SSHのパスワードの入力は必要。

## Git まとめ

I. レビュイー

@ローカル
a. $ git clone GitHub_repository_URL
b. $ cd reposirory_name
c. $ git status

01. $ git checkout -b branch_name
02. ファイル修正
03. $ git commit -am "コミットコメント"
04. $ git push origin branch_name

@GitHub
05. Create pull Request（master ← branch_name）


II. レビュアー

@GitHub
06. Start a review
07. Submit review 
08. Merge pull request


III. レビュアー

@ローカル
09. $ git checkout master
10. $ git pull origin master