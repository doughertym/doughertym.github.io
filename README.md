# doughertym.github.io

## Tools & Resources

* [GitHub Action - Jekyll Actions](https://github.com/marketplace/actions/jekyll-actions)
* [Minimal Mistakes Jekyll theme](https://github.com/mmistakes/minimal-mistakes)

## Run Locally

```
[doughertym.github.io]-> docker run --rm -v "${PWD}:/srv/jekyll" -p 4000:4000 -it jekyll/jekyll:builder bash
```

```
bash-5.0# bundle config set --local path 'vendor/bundle'
bash-5.0# bundle install
bash-5.0# bundle exec jekyll serve -s docs/ --verbose --host 0.0.0.0 --watch
```
