# Ma config sur Windows 10

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
