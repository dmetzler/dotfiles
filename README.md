# Damien Metzler's dotfiles


## Heritage

First instanciation came from [Moncef Belyamani](https://www.moncefbelyamani.com/automating-the-setup-of-a-new-mac-with-all-your-apps-preferences-and-development-tools/)


## Requirements

 - [1password CLI](https://support.1password.com/command-line-getting-started/)

## Steps

```shell script
eval $(op signin my.1password.com dmetzler@gmail.com) 
sh -c "$(curl -fsLS git.io/chezmoi)" -- init --apply dmetzler
```

