# vigil-diff

  watch git-diff's output with vim while you change files.

## requirements

  - [Vim](http://www.vim.org/)
  - [Git](http://git-scm.com/)
  - [inotify-tools](http://inotify-tools.sourceforge.net/)

## installation

  just copy `bin/vigil` somewhere into your `$PATH`

## usage

  open first terminal and

    cd /your/git/repo
    vigil-diff file-to-watch

  open second terminal and edit `/your/git/repo/file-to-watch`
  (using any `$EDITOR`)
