# oh-my-posh-hacker-bubbles-theme

Customized shell prompt theme that I use.

![Screenshot from 2024-08-18 14-10-11](https://github.com/user-attachments/assets/3488a735-de2f-47ec-b4f4-2d58cc9e3f7e)

## Installation

Clone the repo, move `theme.omp.json` to some folder, e.g. `~/.config/oh-my-posh/themes/`:

```bash
mkdir -p ~/.config/oh-my-posh/themes
git clone https://github.com/Trent-Fellbootman/oh-my-posh-hacker-bubbles-theme.git
mv oh-my-posh-hacker-bubbles-theme/theme.omp.json ~/.config/oh-my-posh/themes/
```

Then add this to your .zshrc/.bashrc

```bash
# zsh
eval "$(oh-my-posh init zsh --config ~/.config/oh-my-posh/themes/custom.omp.json)"
# bash
eval "$(oh-my-posh init bash --config ~/.config/oh-my-posh/themes/custom.omp.json)"
```
