# slp-etr-pages

## how to install

```sh
$ npm install -g bower
$ bundle install
$ bundle update
$ bower install
```

## how to post an article

```sh
$ bundle exec middleman article {article-title}
# ・・・
# edit article
# ・・・
$ bundle exec middleman build
$ bundle exec middleman deploy
# ・・・
# update repository
# ・・・
$ git add .
$ git commit -m 'commit message'
$ git push origin master
```

