# mac preferences
- Trackpad > Tap to click
- Keyboard > Key Repeat > Fast
- Keyboard > Delay Until Repeat > Short
- Dock > Automatically hide and show the Dock

##### Autohide dock
```sh
defaults write com.apple.Dock autohide-delay -float 0 && killall Dock
```

##### Show all files
```sh
defaults write com.apple.finder AppleShowAllFiles YES
```

##### Installing brew

```sh
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

 ##### Installing xcode-select (CLI tools):

```sh
xcode-select --install
```
 
##### Installing git

```sh
brew install git
```
##### Installing Spotify

```sh
brew cask install spotify
```

##### Installing Spotify

```sh
brew cask install visual-studio-code
```

##### Install [zsh](https://github.com/robbyrussell/oh-my-zsh/):

```sh
brew install zsh
```

##### Install [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions/):

```sh
brew install zsh-autosuggestions && \
echo "source /usr/local/share/zsh-autosuggestions/zsh-autosuggestions.zsh" >> ~/.zshrc
```

##### Install [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh/):

```sh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```


##### Install [node](https://nodejs.org/) (Node via [Homebrew](https://brew.sh/)):

```sh
brew install node
```

##### Install [yarn](https://yarnpkg.com/):

```sh
brew install yarn
# brew install yarn --without-node
```

##### Upgrade [npm](https://www.npmjs.com/):

```sh
npm i -g npm@latest
```

##### Install Dropbox:

```sh
brew cask install dropbox
```

##### Install Google Chrome:

```sh
brew cask install google-chrome
```

##### Install Hyper

```sh
brew cask install hyper
```


 
