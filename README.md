# Ma config sur Windows 10

Vous désirez savoir comment je configure Windows 10 pour mon usage personnel? Ou alors simplement comment configurer Neovim sur Windows 10! N'hésitez pas à regarder la série dès maintenant sur YouTube!

Lien vers la série: [lien](https://www.youtube.com/playlist?list=PLuWyq_EO5_ALS-X7aNbe_cv_aMMTY3ZrB)

## Episode 5

- [Nvim Docs](https://neovim.io/doc/user/provider.html)
- [CoC](https://github.com/neoclide/coc.nvim)
- [CoC Extensions](https://github.com/neoclide/coc.nvim/wiki/Using-coc-extensions)
- [Node](https://nodejs.org/en/)
- [Python](https://www.python.org/)

## Episode 4

- [Colorschemes](https://github.com/rafi/awesome-vim-colorschemes)
- [Onedark](https://github.com/joshdick/onedark.vim)
- [Airline](https://github.com/vim-airline/vim-airline)

## Episode 3

- Vim Settings
  - [Link](https://www.shortcutfoo.com/blog/top-50-vim-configuration-options/)
  - [Link](https://www.linode.com/docs/guides/introduction-to-vim-customization/)
  - [Link](https://linuxhint.com/important_vim_settings/)
- [Mappings](https://vim.fandom.com/wiki/Mapping_keys_in_Vim_-_Tutorial_(Part_1))

## Episode 2

- [Alacritty](https://github.com/alacritty/alacritty)
- [Vim-plug](https://github.com/junegunn/vim-plug)
- [Hack Font](https://github.com/source-foundry/Hack-windows-installer/releases/tag/v1.6.0)

## Episode 1

Installer Vim-Plug sur Win10

```bash
md ~\AppData\Local\nvim\autoload
$uri = 'https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
(New-Object Net.WebClient).DownloadFile(
  $uri,
  $ExecutionContext.SessionState.Path.GetUnresolvedProviderPathFromPSPath(
    "~\AppData\Local\nvim\autoload\plug.vim"
  )
)
```

- [Neovim](https://neovim.io/)
- [Neovim Nightly](https://github.com/neovim/neovim/releases/tag/nightly)
- [Alacritty](https://github.com/alacritty/alacritty)
