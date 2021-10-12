# Mantra

Mantra is a CLI for previewing [mandoc](https://mandoc.bsd.lv/) manual pages with live auto-reload in a pager.

## Installation

Dependencies:

- [`entr`](http://eradman.com/entrproject/) (for watching file changes)
- [`less`](https://www.greenwoodsoftware.com/less/) (Less is the only supported pager at the moment)
- [`tmux`](https://github.com/tmux/tmux/wiki) (for scripting pager interactions)

```sh
make all
PREFIX=/usr/local make install
```

## Usage

```sh
mantra style.9
```
