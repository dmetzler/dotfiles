# Damien Metzler's dotfiles


## Heritage

First instanciation came from [Moncef Belyamani](https://www.moncefbelyamani.com/automating-the-setup-of-a-new-mac-with-all-your-apps-preferences-and-development-tools/)


## Requirements

 - [1password CLI](https://support.1password.com/command-line-getting-started/)
 - Command line tools for XCode : `xcode-select --install`
 - [Homebrew](https://brew.sh/)

## Steps

```shell script
eval $(op signin my.1password.com dmetzler@gmail.com) 
brew install chezmoi
chezmoi init --apply dmetzler
```

