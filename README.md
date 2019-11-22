# Machine setup instructions

Add Homebrew

And add XCode command line tools
xcode-select --install

Setting up dev environment
```bash
brew cask install iterm2
```

Setting up iTerm2 keybindings:
```
Profiles 
-> Open profiles... 
-> Edit profiles... (button) 
-> Keys (tab) 
-> Load Preset... (dropdown) 
->  Choose "Natural text editing". Done! :-)
```
[https://superuser.com/questions/357355/how-can-i-get-controlleft-arrow-to-go-back-one-word-in-iterm2]

To set color scheme:
[https://ethanschoonover.com/solarized/]

Then use
```
Profiles
-> Open profiles...
-> Colors (Tab)
-> Color Presets...
-> Import
-> Solarized Light
```

Font:
Hack: [https://github.com/source-foundry/Hack]

Install software:

Add .bash_profile to home directory
```
brew install git
brew install vim
brew install macvim
brew install fzf
brew install pyenv
brew install the_silver_searcher
brew install bash-completion
brew install ripgrep
```

git config setup:
git config --global user.name "Your Name Here"

# python environment
brew install readline xz

# as per https://github.com/pyenv/pyenv/wiki/Common-build-problems#requirements
sudo installer -pkg /Library/Developer/CommandLineTools/Packages/macOS_SDK_headers_for_macOS_10.14.pkg -target /
pyenv install 2.7.15
pyenv install 3.7.2

pip install --upgrade setuptools
pip install --upgrade pip

ruby environment
brew install rbenv ruby-build rbenv-default-gems rbenv-gemset

```

For Node.JS, use NVM, https://github.com/creationix/nvm

https://github.com/amix/vimrc

