# AstroNvim

## Install neovim

```
brew install neovim
```

To install homebrew on Linux, look [here](https://docs.brew.sh/Homebrew-on-Linux).

## Install AstroNvim

```
gh repo clone sebpretzer/AstroNvim ~/.config/nvim
```

## Install Dependencies

[nodejs](https://nodejs.org/en/download/):
```
brew install node
```

[Lua Language Server](https://luals.github.io/):
```
brew install lua-language-server
```

[nerdfonts](https://www.nerdfonts.com/font-downloads):
```
brew install --cask font-blex-mono-nerd-font
```

[ripgrep](https://github.com/BurntSushi/ripgrep):
```
brew install ripgrep
```

[lazygit](https://github.com/jesseduffield/lazygit):
```
brew install jesseduffield/lazygit/lazygit
```

[deno](https://deno.com/):
```
curl -fsSL https://deno.land/install.sh | sh
```

## In neovim

### Wait for AstroNvim to install packages

First, make sure you let all the installations take place. This should only be a moment or two.

### Authenticate GitHub Copilot

```vim
:Copilot auth
```
