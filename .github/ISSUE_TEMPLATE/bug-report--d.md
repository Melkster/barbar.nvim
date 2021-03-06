---
name: Bug report :D
about: Create a report to help us improve
title: ''
labels: ''
assignees: ''

---

Preamble (you can delete this section):
 - Are you using a RECENT BUILD of neovim 0.5?
 - If not, rebuild it now before reporting the issue.

**Description**

A clear and concise description of what the bug is.

**To Reproduce**

init.vim:

```vim
let $PLUGIN_DIRECTORY = '~/.config/nvim/bundle'
set runtimepath^=$PLUGIN_DIRECTORY/nvim-web-devicons
set runtimepath^=$PLUGIN_DIRECTORY/barbar.nvim

" Set your options here
let bufferline = {}
```

Steps to reproduce the behavior:
1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. See error

**Screenshots**
If applicable, add screenshots to help explain your problem or to capture error messages.

**Informations**
Neovim version: xxx
