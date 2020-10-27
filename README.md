### Repository for [https://avras.github.io/cryptodocs](https://avras.github.io/cryptodocs)

Steps for updating the site

1. `git checkout master`
1. `mdbook build`
1. `git checkout gh-pages`
1. `cp -r book/* .`
1. `rm -r book/*`
1. `git commit -am"Commit message"`
1. `git push`