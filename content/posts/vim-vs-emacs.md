---
title: "Vim vs Emacs"
date: 2018-08-18
toc: false
tags:
  - editors
  - vim
---

![Vim screenshot](/images/vim-screenshot.png)

I have used Vim on and off for the past few years, and since March
of this year I have taken to customizing Vim to make it a great
developer environment. Over the last month I started acquainting
myself with Emacs for the first time and I used it for a few weeks
as my main editor for web development.

## Vim wins

As of today, I still prefer Vim.

If I were to describe them both in the same sentence, I would say
this: "Vim does one thing and it does it well; Emacs does all of
the things."

1. Vim keeps me in the terminal, while Emacs feels like its own
thing even though it does include a terminal emulator.
2. Vim keeps me on the keyboard, and especially the home row
as much as possible.

When I first started using Emacs (gui), I liked how it played nice
with the mouse and the clipboard, and yet it also had a great
wealth of keyboard shortcuts. I found several of the shortcuts to
be quicker than the Vim equivalents, such as saving a file.
The wealth of context-specific modes seemed to also be a great
feature.

For pure editing, there is also something nice about have just a
single "mode" (in Vim speak). You don't always have to switch back
to normal mode to do a command or move around the file. But this
feeling did not last long. Just last week I found myself missing
the Vim interface, and so I started using "Evil Mode" in emacs.
"Evil" stands for Extensible Vi Layer for Emacs, and it is simply
a minor mode which changes the Emacs interface to emulate Vim as
closely as possible.

My initial thought was that I had discovered the perfect editor:
The best of Vim and Emacs in one delicious package. However, I
found myself constantly switching between Emacs and Vim modes for
different tasks, and also just having so many keyboard options
available at the same time seemed more daunting and confusing than
productive.

Yet the biggest issue I had with Emacs was that while using it,
I felt disconnected from the terminal. You can open a terminal
emulater within Emacs, but it is just a window within Emacs. Emacs
becomes the perspective from which you use the computer, and
anything you want to do has to be done in the Emacs way.

My favorite thing about Vim is that it shines as being just a
text editor. When I use Vim, I am really just using the terminal
and then opening Vim as needed. I can stay in Vim for a little
while if I want to using NERDTree to navigate the directory tree,
but I can also quit Vim, get some errands done in the terminal
and then open up Ranger or whatever else suits my fancy.

## What I have learned

My time using Emacs was well-spent, and I hope to keep it a
part of my application toolbox. What I plan on doing next is
adding some additional keybindings to my vimrc (actually the
neovim equivalent) inspired by Emacs to speed up my actions.

## My current Vim plugins

You can also find my entire vimrc file on
[Github](https://github.com/mclaybaugh/linux-setup)

1. Vim-plug (package manager)
2. vim-javascript (improved javascript syntax support)
3. vim-airline (looks awesome, esp. with patched fonts)
4. NERDTree (file navigation and manipulation)
5. indentLint (for indent guides with indents as spaces)
6. vim-closetag (quick HTML completion)
7. syntastic (syntax checking)
8. git-gutter, vim-fugitive (awesome git integration)
9. YouCompleteMe (autocomplete for days)
10. gruvbox (best colorscheme ever)
11. vim-sublime-monokai (another good colorscheme)

- UPDATE 2019-05-20: My vim plugins are different now, keeping this
for archival purposes
