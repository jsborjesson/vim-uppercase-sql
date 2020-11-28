# vim-uppercase-sql

Many people follow the convention of writing SQL keywords in upper case. Few
people enjoy using shift or caps lock to do it. This plugin fixes that.

![demo of writing sql query with automatically upper cased keywords](demo.gif)

## Installation

Using [vim-plug](https://github.com/junegunn/vim-plug) (or other similar package manager):

```vim
" put this in your ~/.vimrc, then run :PlugInstall
Plug 'jsborjesson/vim-uppercase-sql'
```

## Usage

Install it and forget about it. When you type an SQL keyword in an SQL file, it
will be automatically uppercased as you type, and it is smart enough to not
uppercase stuff in comments or strings.
