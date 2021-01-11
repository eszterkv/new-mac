# new-mac

## system

- sign in to icloud
  - untick everything but icloud drive, photos and find my mac
- settings:
  - trackpad -> tap to click, scroll & zoom not natural
  - a11y -> pointer control -> trackpad options -> enable 3-finger drag
  - system preferences -> search for dns servers -> add dns server 1.1.1.1
- download and install latest version of Xcode from the Mac App Store.
- `xcode-select --install`

### app store
- bitwarden
- bear writer
- slack
- amphetamine

finder
- show path bar
- remove labels and clean up Sidebar

dock
- remove all non-needed things

ui settings
- hide desktop icons with  
  `defaults write com.apple.finder CreateDesktop false; killall Finder`
- make emojis faster using  
  `defaults write NSGlobalDomain NSAutomaticWindowAnimationsEnabled -bool false`
- disable animations:  
  `defaults write -g NSAutomaticWindowAnimationsEnabled -bool false`

[install go](https://golang.org/doc/install)

## cli

- get oh-my-zsh
- get homebrew:  
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"`

get stuff with brew:
```
brew install git
brew install node
brew install wget
brew install ack
brew install yarn
brew install vim
brew install ripgrep

# browsers
brew cask install firefox
brew cask install google-chrome

# others
brew cask install vlc
```

set zsh as default shell:
`chsh -s /bin/zsh`

- get nvm + install some node versions
- get howdoi
- setup /etc/hosts as per https://someonewhocares.org/hosts/

## services & tokens

### passwords & web
- log in to bitwarden, add to ff
- ublock origin

### git
- generate tokens, revoke unused
- get dotfiles
- put installed vim version aliased into .zshrc
- .gitconfig

### vercel
`vercel login`

## other stuff
```
# Disable the sound effects on boot
sudo nvram SystemAudioVolume=" "
```
- set up prey
