[![inicio.png](https://i.postimg.cc/hjN7tTPL/inicio.png)](https://postimg.cc/zbSfdLhv)
[![imgFiles.png](https://i.postimg.cc/W3dXyGHg/imgFiles.png)](https://postimg.cc/LYMtY1R8)
[![imgHola.png](https://i.postimg.cc/59wRW3tS/imgHola.png)](https://postimg.cc/K48NntB1)

### Requirements
- Neovim >= **0.9.0** (needs to be built with **LuaJIT**)
- Git >= **2.19.0** (for partial clones support)
- [LazyVim](https://www.lazyvim.org/)
- a [Nerd Font](https://www.nerdfonts.com/)(v3.0 or greater) **_(optional, but needed to display some icons)_**
- [lazygit](https://github.com/jesseduffield/lazygit) **_(optional)_**
- a **C** compiler for `nvim-treesitter`. See [here](https://github.com/nvim-treesitter/nvim-treesitter#requirements)
- for [telescope.nvim](https://github.com/nvim-telescope/telescope.nvim) **_(optional)_**
  - **live grep**: [ripgrep](https://github.com/BurntSushi/ripgrep)
  - **find files**: [fd](https://github.com/sharkdp/fd)
- a terminal that support true color and *undercurl*:
  - [kitty](https://github.com/kovidgoyal/kitty) **_(Linux & Macos)_**
  - [wezterm](https://github.com/wez/wezterm) **_(Linux, Macos & Windows)_**
  - [alacritty](https://github.com/alacritty/alacritty) **_(Linux, Macos & Windows)_**
  - [iterm2](https://iterm2.com/) **_(Macos)_**

### Instalacion

## usuarios con neovim instalado
1. En el caso que tengamos el directorio de nvim ya configurado hacemos un backup si queremos volver a la configuracion anterior que teniamos
```bash
mv nvim nvim.bak
```
2. Elimina cualquier configuración anterior y directorios de caché
```bash
rm -rf ~/.local/share/nvim
rm -rf ~/.local/state/nvim
rm -rf ~/.cache/nvim
```
## usarios sin neovim instalado
- Actualizacion del sistema segun en cual estes
  
1. instalar neovim
- debian
```bash
sudo apt-get install neovim
```
- Arch Linux
```bash
sudo pacman -S neovim
```
- hacemos el git clone en .config
```bash
https://github.com/Damixn31/nvim.git
```
  

