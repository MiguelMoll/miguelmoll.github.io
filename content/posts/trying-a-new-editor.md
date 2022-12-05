---
title: "Trying a New Editor"
date: 2022-12-05T12:17:50-05:00
draft: false
type: post
---

### Status Quo
Vim was the first editor (excluding IDEs) I ever used about 10 years ago. I've tried [many](https://www.gnu.org/software/emacs/) [editors](https://kakoune.org/) since but I've stuck with the Vim family and currently settled on [Neovim](https://neovim.io/).

The Neovim ecosystem has evolved nicely over time with plugins treating it as a first class citizen. 

I've tried to use graphical editors such as [VScode](https://code.visualstudio.com/) with much success. It almost took over as my daily editor. But I keep drifting back to Vim.

### Yet Another Editor
Unfortunately my nvim config has turned into a hodgepodge of settings that I forget over time. And honestly some of these I don't want to "manage". That includes when using languages that I haven't configured manually yet.

I've recently discovered [LunarVim](https://www.lunarvim.org/) and so far I'm really happy with it. I could be oversimplifying, but I see LunarVim as a Neovim distro/flavor with opinionated defaults. With so many plugins/settings right from the beginning, it's been nice to see it "just work".

That's not to say LunarVim doesn't have a config file. It's more so taking advantage of various [LSP](https://github.com/williamboman/mason.nvim), linters, formatters automatically for the respective file type.

A personal benefit here is that LunarVim uses Lua. So does vanilla Neovim but start from scratch with Lua is calling to me. Maybe I can finally learn it at a basic level.

I do want to give a shoutout to [NvChad](https://nvchad.com). Very similar concept but from my understanding it needs a bit more upfront configuration to get started. But I do want to keep an eye on it.

### Conclusion
So far I'm happy and impressed with LunarVim. I want to try to use stock LunarVim as possible but we'll see how it goes.
