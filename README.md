# Ma config sur Windows 10

Vous désirez savoir comment je configure Windows 10 pour mon usage personnel? Ou alors simplement comment configurer Neovim sur Windows 10! N'hésitez pas à regarder la série dès maintenant sur YouTube!

Lien vers la série: [lien](https://www.youtube.com/playlist?list=PLuWyq_EO5_ALS-X7aNbe_cv_aMMTY3ZrB)

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

Lien(s):

- [Neovim](https://neovim.io/)
- [Neovim Nightly](https://github.com/neovim/neovim/releases/tag/nightly)
- [Alacritty](https://github.com/alacritty/alacritty)
