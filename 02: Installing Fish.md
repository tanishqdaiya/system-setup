# Installing fish shell

## #1 Dealing with zsh

```bash
$ chsh -l # List all available shells
$ chsh -s /bin/bash # To switch to bash
$ rm -rf ~/.zshrc # Find and remove all the zsh files if you want with rm -rf command. You may need sudo as well.
$ reboot # Reboot your conmputer for the bash to take over
```

## #2 Installing Fish

How is bash?

```bash
$ pacman -S fish # To install fish. You may need sudo...
$ fish # To use fish. But you won't write it everytime!! SO?
$ chsh -l # Again, Listing all the available shells
$ chsh -s /bin/fish # To switch fish to your default shell.
$ reboot # Fish will take over from there.
```

## #3 Installing oh-my-fish

```bash
$ curl -L https://get.oh-my.fish | fish
```

## Reference Links

[fish-shell](https://fishshell.com/)

[oh-my-fish GitHub](https://github.com/oh-my-fish/oh-my-fish)

