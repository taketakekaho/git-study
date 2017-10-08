# Gitの勉強
- git add コマンドで、リポジトリに変更情報を追加する
    - このことをステージングと言う
- git commit コマンドで、リポジトリのインデックスに追加された変更情報にコメントを付けてコミットできる
- git push コマンドで、ローカルのコミットをリモートのリポジトリに反映させることができる

##push手順

```
>git add *
>git status
>git commit -m "coment"
>git log
>git remote add origin git@github.com:taketakekaho/git-study.git
>git push -u origin master
```

##タグ

```
>git tag 1.0
>git push -tags origin master
```

