# operationWork

## git 基本コマンド  

- ブランチを切り替える  
`git checkout <切り替えるブランチ>`

- 新規ブランチをチェックアウトする  
ベースとなるブランチに移動  
`git checkout <ベースブランチ>`  
ブランチ作成  
`git checkout -b <新規ブランチ>`  

- リモートレポジトリの更新内容をローカルに取得し、現在のブランチに取り込む  
`git pull`
origin 上の <ブランチ>を、現在チェックアウトしているブランチに取り込む  
`git pull <origin> <ブランチ>`

- ステージング、コミット  
`git add -A`
`git commit`

- push  
ローカルブランチを、リモートレポジトリ「origin」上の同名のブランチに反映  
`git push <origin> <プッシュするローカルブランチ>`

- タグ作成  
`git tag -a <タグ名> -m '<コメント>' <コミットID>`

- git log  
`git log`
`git log --graph`

- リベース  
`git rebase master`
