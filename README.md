# new-mac

## prep

- Download and install latest version of Xcode from the Mac App Store.
- `xcode-select --install`

## ui
- icloud sign in

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

brew cask install iterm2

# browsers
brew cask install firefox
brew cask install google-chrome

# others
brew cask install vlc
```

set zsh as default shell:
`chsh -s /bin/zsh`

- get nvm + install some node versions
- put installed vim version aliased into .zshrc
- .gitconfig
- setup /etc/hosts as per https://someonewhocares.org/hosts/

## services & tokens

### git
generate tokens, revoke unused

### vercel
`vercel login`

## other stuff
```
# Disable the sound effects on boot
sudo nvram SystemAudioVolume=" "
```
