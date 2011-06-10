# Vesta: Your emacs Distribution

This is a distribution of emacs plugins intended to be run on the latest
Aquamacs release.

Vesta is clearly influenced by Carlhuda's Janus vim distribution.

I got into Emacs after leaving TextMate, and it took a lot of work to
get my setup even halfway decent. I want to record my trials and
tribulations and share them with you. Also I hope you contribute back
and we can all have a better Emacs experience.

My hope is that we can make this as useful and as easy to use as Janus.

*Please note that this README is ahead of the development right now and serves mainly as a TODO list.*

## Prerequisites

Vesta is built primarily for Aquamacs Emacs.

## Installation

0. `for i in ~/.emacs ~/.emacs.el; do [ -e $i ] && mv $i $i.old;
   done`
1. `git clone git://github.com/sfsekaran/vesta.git ~/.emacs.d`
2. `cd ~/.emacs.d`
3. `rake`

or

  `curl https://github.com/sfsekaran/vesta/raw/master/bootstrap.sh -o - | sh`

## Customization

Create `~/.emacs.local` for any local customizations.

If you want to add additional Emacs plugins you can do so by adding a `~/.vesta.rake` like so:

    emacs_plugin_task "haml-mode", "git://github.com/nex3/haml-mode.git"

## Updating to the latest version

To update to the latest version of the distribution, just run `rake` again inside your `~/.emacs.d` directory.

# Intro to Emacs

TODO

# Features

TODO
