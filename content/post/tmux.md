+++
date = "2016-11-25T17:25:22-08:00"
slug = "2016/11/25/tmux-and-vim"
image = ""
share = true
draft = false
tags = [
  "tmux",
  "vim",
  "technology",
]
menu = ""
author = "Byron Mansfield"
title = "Tmux and Vim"
comments = true

+++

If you've ever worked with me or happened to pair program with me or maybe just stepped over to my desk to show me something, you probably know I love tmux and vim, and if you do not use them, you probably don't know how to use my termainl. And even if you do, you probably don't know my personal setup. This segment is just a little rant about why I love them both, and love them paired together. I also get commonly from co-workers "I don't know how to use your terminal bro". It's always too much to walk them through it when your trying to work through an issue. Hopefully this post will leave those individuals with a little more of an understanding of whats going on with my terminal bro.

Here is an example of my tmux and vim setup looks like.

![tmux and vim](/static/images/tmux-and-vim.png "tmux with vim")

Lets start basic. Since becoming a vagabond I have a mac because they make a nice portable laptop and I can rely on it and not have to waste time trying to configure linux to do things mac does out of the box. It makes me sad, but this is how it is. So with that said,

iTerm2 + Oh-my-zsh

Nothing crazy going on here, but just thought I'd call it out. Now, moving on to zsh config.

This one seems to throw more people off than I expected, which comes to sorta as a surprise to me, but hey, I'll still point it out.

I have my own custom prompt. You can find it in my dotfiles repo.

Another one I've seen people jump back an inch out of surprise and then lean in to see it closer.

I run archey at the beginning of ever fresh session. I can't help it. I miss Arch. It also evals some of my gpg and ssh keys to keychain.

Ok, now that we got the basic context, lets move on to more interesting things, like TMUX, because I pretty much always live inside a tmux session.

I've remapped the leader to be Ctrl A like screen. It's more intuitive to me than the default Ctrl B. I've customized the status bar quite a bit. I use plugins to manage my session and back it up, so that I can restore it.

Here is one that gets under some of my co-workers skin. I have disabled the mouse support. Bwahahaha. I love when they get frustrated over that. I have to comment on why, because I always get asked. Because I HATE REACHING FOR THE MOUSE! I key bind everything I can to vi bindings. I even use vimium to make browsing the web more keyboard driven.

Because it's a tileing window manager for your terminal, and I love vim, I've remapped all of the splitting of windows and panes, as well as navigating them more vim like. The default way is so painful. Now things are starting to feel like home.

I've probably bored you to death with my tmux explination, I guess lets move on to vim.

All the basics are there that you would expect, set numbers, set syntax, mapped my leader to comma, some other sane settings. Here is my favorite that I get like "Why the hell would you do that?". I remapped my arrow keys to be more useful because you shouldn't be using arrow keys in vim. Or at least that is my belief. Call me old school or whatever. Stay on homerow. End of story. They now just move things around. This is useful for quickly indenting a visual block and such.

I have some nice plugins like nerdtree, youcompleteme, rainbow parentheses. The coolest thing I've done is a little ctags trick with git + tag bar. I can now have a birds eye view of the files types, functions, methods, etc, and jump to them quickly and easily.

Think that is it for now. I'll try to add more to this post later.
