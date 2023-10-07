# My config files for macOS

> Fish, Karabiner, Cursor

![](https://images.nikiv.dev/config-dark-23.png)

> Dark appearance.

![](https://images.nikiv.dev/config-light-23.png)

> Light appearance. Prefer to use light themes during day as it makes text more readable with natural light around.

You can see my top used apps, Safari extensions and Alfred workflows [here](https://github.com/nikitavoloboev/my-mac). I also explain how I use the apps in detail there.

<!-- ## File structure

- [fish](fish)
- [git](git)
- [karabiner](karabiner)
- [macos](macos) -->

## Clean install

1. Boot latest macOS version. Remember that username is the name you want the home folder to be (by default its first name & last name).
2. Go through [preferences](https://imgur.com/a/KoVAxFQ) & set everything up.
3. Download & install [apps I use](https://github.com/nikitavoloboev/my-mac).
4. Clone dotfiles & sync them.
5. [Sync settings](https://github.com/zenangst/Syncalicious) for apps I use.

## Setup & sync dotfiles

Take a look at [install](install) shell script. It will install [brew](https://brew.sh), [go](https://go.dev) & [mage](https://github.com/magefile/mage).

Run it with `./install`. As part of the script it will run `mage setup`. Take a look at [magefile.go](magefile.go) `Setup` function to see what it will do.

You can also run `mage` alone to see what commands you can run with descriptions of them.

In short, it will create appropriate symlinks pointing at files in `~/.dotfiles`. It is assumed that the dotfiles repo is placed there.

It will also install CLI tools & apps.

## Interesting dotfiles

[Here](https://wiki.nikiv.dev/unix/dotfiles) are dotfiles I got many ideas from and liked. I also mention [Nix configurations I liked](https://wiki.nikiv.dev/operating-systems/linux/nixos#nix-configs-nixos).

## Contribute

The tasks to do are outlined in [GitHub issues](../../issues) and in [todo.md](todo.md) (sorted by priority).

If issue/idea you have is not there, [open new issue](../../issues/new/choose) or [start discussion](../../discussions).

Any PR with code/doc improvements is welcome. ✨

Join [Discord](https://discord.com/invite/TVafwaD23d) for more indepth discussions on this repo and [others](https://github.com/nikitavoloboev#src).

### ♥️

[Support on GitHub](https://github.com/sponsors/nikitavoloboev) or look into [other projects](https://nikiv.dev/projects).

[![MIT](http://bit.ly/mitbadge)](https://choosealicense.com/licenses/mit/) [![Twitter](http://bit.ly/nikitatweet)](https://twitter.com/nikitavoloboev)
