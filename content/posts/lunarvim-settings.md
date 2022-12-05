---
title: "Lunarvim Settings"
date: 2022-12-05T14:08:11-05:00
draft: false
---
### Retrieval Practice
As previous [mentioned](/posts/trying-a-new-editor/), I'm giving LunarVim a spin. To increase my chances of success, I want to document my settings and specific keybindings. Some of the settings can be Lunarvim specific and others that are plane Vim settings. I expect this post to evolve in the future, depending on my overall success with Lunarvim.


#### Search files/text
```vim
# File names
Leader + s + f 

# Text (live grep)
Leader + s + t

# File explorer
Leader + e

# Edit config.lua
Leader + L + c
```
Select results using `tab` and send them to the quick list using `crtl + q`.


#### Git
```vim
# Blame
Leader + g + l 
```

#### Terminal
```vim
# Integrated
Ctrl + \
```

#### LSP
```vim
# Definition
g + d

# References
g + r

# Implementation
g + I

# Signature
g + s

# Line info
g + l
```

#### Spellcheck
```vim
# Enable
:set spell spelllang=en_us

# Disable
:set nospell

# Move to the next/previous misspelled words
]s and [s

# Replace word over cursor
z=

# Add word to dictionary
zg

# Mark words as incorrect
zw
```

### References
The following links were used to gather the all of the above:
- [Lunarvim Configuration](https://www.lunarvim.org/docs/configuration)
- [Lunarvim keybindings](https://www.lunarvim.org/docs/configuration/keybindings)
- [Editing In Lunar Vim is Magic](https://blog.devgenius.io/editing-in-lunar-vim-is-magic-17-more-lvim-tips-and-tricks-598ba7f4f6d6)
