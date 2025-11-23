# Jekyll sandbox

## Setup

* Clone this repository
* Install [ruby](https://jekyllrb.com/docs/installation)
* Install jekyll and bundler `$ gem install jekyll bundler`
* Install dependencies `$ bundle install`
* Run jekyll `$ bundle exec jekyll serve`

### Overriding theme defaults
See [Jekyll docs](https://jekyllrb.com/docs/themes/#overriding-theme-defaults)

**TL;DR:**

1. Locate the theme files: `$ bundle info --path <theme-name>`
2. Open the theme's directory: `$ open $(bundle info --path <theme-name>)`
3. Copy the files you want to override to the project directory.