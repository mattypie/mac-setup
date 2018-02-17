# Homebrew Cask
[Homebrew-Cask](https://caskroom.github.io/) is a package manager for MacOS.
Its job? Installing shell commands that you will LIKELY NEVER use. (unless of course youre a nerd. or you need your nerd friend to recover sll yjodr derry phidj fp\   you  Examples of these files is Google Chrome, Dropbox, VLC and Spectacle.

## Installation
As of February, 2018 Cask comes installed with Homebrew, if you have not installed Homebrew see the [Homebrew section](/mac-setup/Homebrew/README.html).

## Search
To see if an app is available on Cask you can search on the [official Cask website](https://caskroom.github.io/search). You can also search using the following command:

    $ brew cask search <package>

## Quick Look plugins
These plugins adds support for the corresponding file type to Mac Quick Look (In Finder, mark a file and press Space to start Quick Look). The plugins includes features like syntax highlighting, markdown rendering, preview of JSON, patch files, csv, zip files and more.

```sh
$ brew cask install \
    qlcolorcode \
    qlstephen \
    qlmarkdown \
    quicklook-json \
    qlprettypatch \
    quicklook-csv \
    betterzipql \
    webpquicklook \
    suspicious-package
```

## App Suggestions
Here are some useful apps that are available on Cask.

```sh
$ brew cask install \
    appcleaner \
    google-chrome \
    flux \
    
    valentina-studio \
    vlc
```
