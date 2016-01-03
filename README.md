## Quick Intro

- This is a fork of only the `vim` utilities from the original [opensips]
project using the following Git `filter-branch` action:

```
git clone https://github.com/OpenSIPS/opensips && cd opensips
git filter-branch --subdirectory-filter utils/vim -- --all
```

- The objective is to make the Vim package managers such as [vundle] happy so
that one may just add the following line `.vimrc` to get [opensips]
configuration management support:

```
Bundle gsbabil/vim-opensips
```

- Original [opensips] installation instructions are still valid and can be
found in `INSTALL`


[opensips]: https://github.com/OpenSIPS/opensips  "OpenSIPS"
[vundle]: https://github.com/VundleVim/Vundle.vim "Vundle"
