---
title: memo
date: 2015-07-06 08:54 UTC
tags: memo
---

# middlemanによる記事の投稿方法

## 環境構築

(事前にgit cloneでローカルに準備。以下作業はそのディレクトリにて行う。)

```
$ npm install -g bower
$ bundle i$ bundle update
$ bower install
```

## 記事の投稿方法

```
$ bundle exec middleman article {article-title}
# ・・・
# edit a# ・・・
$ bundle exec middleman build
$ bundle exec middleman deploy
# ・・・
# update repository
# ・・・
$ git add .
$ git commit -m 'commit message'
$ git push origin master''}
```

