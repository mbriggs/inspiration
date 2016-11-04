# Inspiration

I wrote a small script to give me a message in emacs when I launched it that met the following constraints

 - is a one liner
 - is something I want to be reminded of when opening a code editor
 - is in some way profound

I thought it would be just a fun little thing, and it is, but I found that it gave me a disproportionate amount of joy every time I opened emacs. So I extracted this into a little fortune style script, for the purpose of integrating it into my shell.

## Installation

This requires some (any?) version of ruby to be installed.

Just put the script wherever, and call it. If you pass `--header`, it will add some newlines to pad stuff out.

To add to your shell, put it somewhere in your path, make sure its executable, and do `echo "inspiration --header" >> ~/.zshrc # or whatever shell init you use`

## Customization

open up the script and change the colors / decoration however you like

## Contributing

I highly welcome contributions, but will likely be a bit picky/arbitrary about what quotes I will accept, so please dont be offended if I dont merge. This is basically the simplest thing ever, so feel to fork / do whatever.
