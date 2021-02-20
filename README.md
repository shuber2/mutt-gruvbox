# A gruvbox color scheme for mutt and neomutt

## Description

[Gruvbox](https://github.com/morhetz/gruvbox) is a well designed, popular
colorscheme for vim. This is a port to mutt and neomutt, in which vim can act
as mail composer.

This is a replication of the repository
[here](https://git.sthu.org/?p=mutt-gruvbox.git;a=summary). The
[website](https://www.sthu.org/code/codesnippets/mutt-gruvbox.html) gives
further details and a screenshot, like this:

![screenshot](https://www.sthu.org/code/codesnippets/img/mutt-gruvbox.png)


## Usage

Download the files or clone the repo, e.g.

    cd ~/.mutt
    git clone https://git.sthu.org/repos/mutt-gruvbox.git gruvbox

Then source them in your `~/.mutt/muttrc`, e.g.

    source ~/.mutt/gruvbox/colors-gruvbox-shuber.muttrc
    # For neomutt also add this line:
    # source ~/.mutt/gruvbox/colors-gruvbox-shuber-extended.muttrc

The colorscheme is split into two files, where the latter also defines colors
for neomutt.

## License

GNU Lesser General Public License v3.
