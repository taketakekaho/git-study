# Gitの勉強
- git add コマンドで、リポジトリに変更情報を追加する
    - このことをステージングと言う
- git commit コマンドで、リポジトリのインデックスに追加された変更情報にコメントを付けてコミットできる
- git push コマンドで、ローカルのコミットをリモートのリポジトリに反映させることができる

## pull手順

```
>git pull origin gh-pages
>git remote  */リモートの情報を見る/*
```

## push手順

```
>git add *
>git status
>git commit -m "coment"
>git log
>git remote add origin git@github.com:taketakekaho/git-study.git
>git push -u origin master
```

## タグ

```
>git tag 1.0
>git push -tags origin master
```

## ブランチを作る

```
>git branch gh-pages  */branchのうしろにブランチ名/*
>git branch
>git checkout gh-pages
>git branch
gh-pagesブランチでコード変更
>git checkout master    */取り込みたいブランチに切り替え/*
>git merge gh-pages     */取り込むブランチからのマージ/*
```
