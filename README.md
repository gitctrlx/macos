# macOS Dev Environment

Terminal configuration for Rust / Git / Blockchain developers.

## Quick Start

```bash
# 1. Copy Ghostty config
cp -r .config/ghostty ~/.config/

# 2. Append zsh config
cat .zshrc >> ~/.zshrc && source ~/.zshrc
```

## Ghostty Terminal

**Font**: Maple Mono NF CN (15pt) — install separately  
**Theme**: Kanagawa (auto light/dark)  
**Opacity**: 95%

### Key Features

- **Quick Terminal**: `Ctrl + `` ` global dropdown terminal
- **Option as Alt**: Vim/Tmux keybindings support
- **Clipboard Protection**: Prevents malicious paste injection

## Zsh Plugins

Requires [Oh My Zsh](https://ohmyz.sh/):

| Plugin | Description |
| ------ | ----------- |
| `git` | Aliases & completions |
| `rust` | Rust toolchain support |
| `zsh-autosuggestions` | History suggestions |
| `zsh-syntax-highlighting` | Syntax highlighting |

### Install Third-Party Plugins

```bash
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```
