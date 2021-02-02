# Finder

## Install Quick Look plugins

### Install QLMarkdown

```
brew cask install qlmarkdown
```

### Install QLStephen

```
brew cask install qlstephen
```

### Install QLColorCode

```
brew cask install qlcolorcode
```

### Install qlImageSize

```
brew cask install qlimagesize
```

## Configure Quick Look plugins

### See quarantine attributes

```
xattr -r ~/Library/QuickLook
```

### Remove quarantine attributes

```
xattr -d -r com.apple.quarantine ~/Library/QuickLook
```

## Configure Finder

### Show Library folder

```
chflags nohidden ~/Library
```

### Show path bar

```
defaults write com.apple.finder ShowPathbar -bool true
```

### Show status bar

```
defaults write com.apple.finder ShowStatusBar -bool true
```

### Always show column view

```
defaults write com.apple.finder FXPreferredViewStyle -string "clmv"
```

### Expand save panel by default

```
defaults write NSGlobalDomain NSNavPanelExpandedStateForSaveMode -bool true
defaults write NSGlobalDomain NSNavPanelExpandedStateForSaveMode2 -bool true
```

### Only show open applications in Dock

```
defaults write com.apple.dock static-only -bool true
```

