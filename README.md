### Quick start guide


Jekyll is a Ruby Gem that can be installed on most systems.

#### Requirements

* [Ruby](https://www.ruby-lang.org/en/downloads/) version 2.4 or above, including all development headers (ruby version can be checked by running `ruby -v`)

## Instructions

1. Install a full [Ruby development environment](https://jekyllrb.com/docs/installation/)
2. Install Jekyll and [bundler](https://jekyllrb.com/docs/ruby-101/#bundler) [gems](https://jekyllrb.com/docs/ruby-101/#gems)
```
gem install jekyll bundler
```
3. Copy / clone current jekyll site from [github](https://github.com/zak905/site) to current directory.
```
git clone git@github.com:zak905/site.git .
```
4. Build the site and make it available on a local server
```
bundle exec jekyll serve
```
6. Now browse to [http://localhost:4000](http://localhost:4000){:target="_blank"}
