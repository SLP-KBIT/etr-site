# slp-etr-pages

## how to deploy at first

need bower.

```sh
$ bundle install
$ bundle update
$ bower install
$ bundle exec middleman build
$ bundle exec middleman deploy
```

## how to post an article

```sh
$ bundle exec middleman article {article-title}
# ・・・
# editting
# ・・・
$ bundle exec middleman build
$ bundle exec middleman deploy
```

