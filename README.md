# thebelltower.github.io

Content for blog available at <https://thebelltower.github.io/>. Built using [Jekyll][jekyll].

[![Build Status](https://travis-ci.org/thebelltower/thebelltower.github.io.svg?branch=master)](https://travis-ci.org/thebelltower/thebelltower.github.io)

## Table of Contents

* [Setup](#setup)
* [Run](#run)
* [Writing Posts](#writing-posts)
* [Deploy](#deploy)
* [License](#license)

## Setup

* Fork from Github
    ```
    git clone https://github.com/thebelltower/thebelltower.github.io.git your-project-folder
    cd your-project-folder
    git remote rm origin
    git remote add origin your-repo-url
    ```

* Install [Homebrew](http://brew.sh/)
    ```
    ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
    ```

* Install Ruby
    ```
    rbenv install -s $(cat ./.ruby-version)
    gem update --system
    ```

* Install Ruby gems
    ```
    gem install bundler
    bundle install
    ```

## Run

`bundle exec jekyll serve`

If you update `_config.yml`, you must restart the server, else you can rely on live reload.

## Writing Posts

* Create a draft
    ```
    bundle exec jekyll draft "My new draft"
    ```

* Convert to post when done
    ```
    bundle exec jekyll publish _drafts/my-new-draft.md
    ```

* [Deploy changes](#deploy)

## Deploy

Update `master` branch, and let [Github Pages][gh-pages] and [Jekyll][jekyll] handle the rest.

## License

The following directories and their contents are copyright thebelltower. You may not reuse anything therein without my permission:

  * `_posts/`

All other directories and files are MIT Licensed.

[jekyll]: https://jekyllrb.com/
[gh-pages]: https://help.github.com/articles/what-is-github-pages/
