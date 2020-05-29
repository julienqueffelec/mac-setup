# mac preferences
- Trackpad > Tap to click
- Keyboard > Key Repeat > Fast
- Keyboard > Delay Until Repeat > Short
- Dock > Automatically hide and show the Dock


```sh
defaults write com.apple.dock autohide-time-modifier -int 0;killall Dock
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
 
