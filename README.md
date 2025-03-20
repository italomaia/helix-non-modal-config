# Helix Non-Modal Config

I was never a big fan of editors like [vim](https://www.vim.org/) as they push you to build just too much muscle memory 
to be able to use them effectively. Recently neovim came around, trying to level the field 
and make the text based experience a bit friendlier. And now there is (Helix)[https://github.com/helix-editor/helix/].

It has some neat ideas that remind me of the (howl editor)[https://github.com/howl-editor/howl],
another project I enjoy, like the way it actively tries to help you do the right thing with auto-complete
suggestions as you type.

After giving it a few hours, it is clear to me the experience is interesting and I can see
myself being productive with it, but not how it currently is. The amount of mode switching
is just too high at the moment! I need to keep my eyes constantly at the bottom-left corner
to track which mode is active and which set of key-bindings do I need to have in my mind's
buffer.

## The Idea

This project is just a place to store the configuration makes me the most productive with Helix, which translates
to the following:

- one should have to remember as few key-bindings as possible
- modes should be switched as little as possible 
- keymap feels more natural: the most common behavior should have the simpler binding
- keybinding between modes is kind of similar

If this ressonates with you, give it a try. Most keymaps have a description either telling what
they do or why they exist.

## Installation

Given you have helix and curl installed:

`curl https://raw.githubusercontent.com/italomaia/helix-non-modal-config/refs/heads/main/config.toml -o ~/.config/helix/`