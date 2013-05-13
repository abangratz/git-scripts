#git-scripts

A collection (\*cough\*) of git scripts I use in daily practice.

## git-interactive-branches

Used for deleting merged branches.

### Installation

You can use the Gemfile (via bundler) to install the gems needed. Manually, you want to install

- [Highline](http://highline.rubyforge.org/)
- [Main](https://github.com/ahoward/main) and
- [ruby-git](https://github.com/schacon/ruby-git)

via rubygems in every environment (gemset?) that you want to use it (or use the global gemset, if you know what you are
doing).

Example:

```
gem install highline
gem install main
gem install git
```


### Usage

Default is an interactive mode that shows you a menu where you can select a branch or
multiple branches that have been merged and delete them locally.

The other mode is `git interactive-branches --delete-merged` which deletes **all** merged branches immediately.

#LICENSE

ISC License :

Copyright (c) 2013, Anton Bangratz <anton.bangratz@gmail.com>

See [LICENSE](LICENSE) for details.
