# AstroNvim

## Install neovim

```
brew install neovim
```

To install homebrew on Linux, look [here](https://docs.brew.sh/Homebrew-on-Linux).

## Install AstroNvim

Optionally, you can backup your current nvim configuration:

```bash
mv ~/.config/nvim ~/.config/nvim.bak
```
or purge it:

```bash
rm -rf ~/.config/nvim && \
rm -rf ~/.local/share/nvim && \
rm -rf /tmp/nvim.user && \
rm -rf ~/.local/state/nvim && \
rm -rf ~/.cache/nvim && \
rm -rf /etc/xdg/nvim && \
rm -rf /usr/local/share/nvim && \
rm -rf /usr/share/nvim
```

Then, clone the AstroNvim config into your nvim configuration directory:

```bash
gh repo clone sebpretzer/AstroNvim ~/.config/nvim
```

## Install Dependencies

[nodejs](https://nodejs.org/en/download/):

```bash
brew install node
```

[Lua Language Server](https://luals.github.io/):

```bash
brew install lua-language-server
```

[nerdfonts](https://www.nerdfonts.com/font-downloads):

```bash
brew install --cask font-blex-mono-nerd-font
```

[ripgrep](https://github.com/BurntSushi/ripgrep):

```bash
brew install ripgrep
```

[lazygit](https://github.com/jesseduffield/lazygit):

```bash
brew install jesseduffield/lazygit/lazygit
```

[deno](https://deno.com/):

```bash
curl -fsSL https://deno.land/install.sh | sh
```

## Open neovim

```bash
nvim
```

### Wait for AstroNvim to install packages

First, make sure you let all the installations take place. This should only be a moment or two.

### Authenticate GitHub Copilot

```vim
:Copilot auth
```
