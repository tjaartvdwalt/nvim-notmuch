# Notmuch for (Neo)Vim

This plugin started of as a fork of the Vim plugin shipped with Notmuch, with some bugs fixed to make it work for modern vim systems. Hopefully it will grow into something great.

## Why yet another Notmuch plugin?

The vim plugin shipped with Notmuch has several problems:

- It does not use the Vim 8 package system
- The Makefile hardcodes the installation directory as `~/.vim` which makes it incomatible with Neovim
- When you show search results it shows a Ruby `Mail::Field.new` deprecation warning
- I find it difficult to contribute to software that uses mailing lists for issue tracking


## Project goals

- Compatibility with Neovim, and Vim 8
- Remove external dependencies
