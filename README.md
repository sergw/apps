OS X Apps lists for quick installation and seamless migration

* `name.list.genarator.sh` — producer of ready list
* `name.list.generation.*` — instruction or producet of instruction for generation list manually
* `src-*` — just source list for generators

## Install all
[./install-all.sh](./install-all.sh)

## Lists of apps
```sh
ls | grep 'list$' | grep -v src
```
* [appstore.list](appstore.list)
* [brew-cask.list](brew-cask.list)
* [brew.list](brew.list)
* [npm.list](npm.list)
* [web.list](web.list)

## Generators of lists
```sh
ls | grep gen | grep -v README
```
* [appstore.list.generation.txt](appstore.list.generation.txt)
* [brew-cask.list.from.web.list.generation.sh](brew-cask.list.from.web.list.generation.sh)
* [brew-cask.list.generator.sh](brew-cask.list.generator.sh)
* [brew.list.generator.sh](brew.list.generator.sh)
* [npm.list.generator.sh](npm.list.generator.sh)
* [src-builtin.list.generation.txt](src-builtin.list.generation.txt)
* [src-installed.list.generator.sh](src-installed.list.generator.sh)
* [web.list.generator.sh](web.list.generator.sh)

## Alternatives

See also:
* [nerevar/dotfiles/osx](https://github.yandex-team.ru/nerevar/dotfiles/tree/master/osx)

## [TODO](TODO.md)
* Add sublime plugins
* Add gems
* Add pips

----
_Genarated by `README.md.genarator.sh`_
