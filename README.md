# Mac init

- [ ] Login to iCloud
- [ ] Login to Messages and Facetime

## System preferences

### Dock
- [ ] Adjust size
- [ ] Activate zooming
- [ ] Auto-hide

### Mission control
- [ ] Deactivate arrange spaces based on usage
- [ ] Deactivate dashboard

### Security
- [ ] Ask for password immediately

### Keyboard
- [ ] Key repetitions : fastest
- [ ] Delay : one before fastest
- [ ] Enabled enhanced dictation (twice Fn)
- [ ] Shorcuts : use `⌥ Space` for Spotlight

### Trackpad
- [ ] Right tap with two fingers
- [ ] Tap to click
- [ ] Movement speed : second to fastest
- [ ] Enable App exposé

### Sound
- [ ] Show volume in menu bar

### iCloud
- [ ] Deactivate desktop & documents in iCloud
- [ ] Enable back to my back
- [ ] Enable localize my mac

### App Store
- [ ] Enable automatic updates
- [ ] Download updates in backgroup
- [ ] Always ask for password

### Bluetooth
- [ ] Show in menu bar

### Share
- [ ] Name : `[DCMaxxx,Maxime] - [Machine]`
- [ ] Share screen
- [ ] SSH

### Date and time
- [ ] Use 24h format
- [ ] Display week-day
- [ ] Hide date

## App Store
- [ ] Pipfier
- [ ] Easy APNS provider
- [ ] Fantastical 2
- [ ] BetterSnapTools
- [ ] Keynote, Number, Pages
- [ ] Tweetbot
- [ ] TheUnarchiver
- [ ] Xcode
- [ ] EasyRes
- [ ] Slack

# CLI

## Shell
- [ ] Oh-my-zsh ([link](https://github.com/robbyrussell/oh-my-zsh))
  - [ ] Clone dotfiles in `~/.oh-my-zsh/custom` ([link](https://github.com/DCMaxxx/dotfiles))
  - [ ] Use the theme `agnoster` in `~/.zshrc`
- [ ] Powerline fonts ([link](https://github.com/powerline/fonts))
- [ ] Homebrew ([link](https://brew.sh/index_fr.html))
- [ ] Git alias : `[alias] (\n\t) branchname = rev-parse --abbrev-ref HEAD`

## iTerm2
- [ ] brew cask install iterm2
  - [ ] Colors/colors preset : `Solarized Dark`
  - [ ] Change cyan bright to a real cyan
  - [ ] Text/font : `12pt Meslo LG M DZ Regular for Powerline`
  - [ ] Keys : `⌥ [left,right]` : `Send escape sequence [b,f]`
- [ ] brew install wget

## Ruby
- [ ] brew install rbenv
  - [ ] Install latest ruby version
- [ ] brew install rbenv-gemset

## Cask
- [ ] brew cask install google-chrome
- [ ] brew cask install gitup
- [ ] brew cask install atom
- [ ] brew cask install puush
- [ ] brew cask install vlc
- [ ] brew cask install provisionql

## Customize macOS
- [ ] Faster Mission Control animations :
  - Command : `defaults write com.apple.dock expose-animation-duration -float 0.1 && killall Dock`
  - Rollback : `defaults delete com.apple.dock expose-animation-duration && killall Dock`
  - [Source](http://osxdaily.com/2012/02/14/speed-up-misson-control-animations-mac-os-x/)

# Productivity apps configurations

## Finder
- [ ] Open documents with new window
- [ ] Sidebar : Airdrop, Applications, iCloud Drive, Desktop, Documents, Downloads
- [ ] Top bar : Back/Next, Path, Format, Actions, Share, Search
- [ ] Folders : Always present by icon, Sort by name, Show informations, Use as defaults
- [ ] Desktop : Text position right, Show informations, Spacing two before last

# Dock
- [ ] Finder, Mail, Slack, Messages, iTunes, Xcode, Gitup, iTerm

## Mail
- [ ] Display accounts bar
- [ ] Rename accounts
- [ ] Keep open to download archived mails

## Slack
- [ ] Log in

## Alfred
- [ ] brew cask install alfred
  - [ ] Activate Powerpack
  - [ ] Launch at login
  - [ ] Use `⌘ Space`
  - [ ] Set locale to France
  - [ ] Features : deactivate all web searches but `google`, `maps`, `wiki`
  - [ ] Clipboard : keep plain text 7 days, images 24 hours.
  - [ ] Appearance : Alfred macOS, options: hide hat, hide menu bar icon,
  - [ ] Workflows
    - [ ] Colors ([link](http://www.packal.org/workflow/colors))
    - [ ] Emoji finder ([link](http://www.packal.org/workflow/emoji-finder))

## Xcode
- [ ] Login to personnal / pro account
- [ ] Behaviors ([link](./xcode/behaviors/))
- [ ] Theme : Solarized dark ([link](https://github.com/skywinder/xcode-themes))
- [ ] Trim whitespaces, including whitespaces only lines
- [ ] Cut / duplicate line(s) ([link](./xcode/shortcuts))

## Safari
- [ ] AdBlockPlus ([link](https://adblockplus.org))
- [ ] RES ([link](https://redditenhancementsuite.com))
- [ ] JSONAce ([link](https://github.com/jjlharrison/JSONAce))
- [ ] Back/prev, sidebar, space, pipfier, abp, search bar, share, download


## Other apps
- [ ] Fantastical2
  - [ ] Open & follow setup (hide notifications for calendar, reminders...)
  - [ ] Show in status bar
  - [ ] Hide in dock
- [ ] BetterSnapTools
  - [ ] Hide from dock
  - [ ] `⌘⌥⌃ [<-,->]` : half screen left/right
  - [ ] `⌘⌥⌃ Enter` : full screen
- [ ] Tweetbot : Login
- [ ] EasyRes : Start at login
- [ ] Chrome : Login
- [ ] Gitup : Install cli
- [ ] puush : Login

## macOS
- [ ] Control center : Today, Fantastical, Weather, Tomorrow
- [ ] Menu bar : puush, easyres, sound, wifi, bluetooth, fantastical, clock, battery (percentage), spotlight (cause you can't remove it...)

# Background downloads

- [ ] Open Photos, let it download iCloud library
- [ ] Perform macOS upgrades if needed
- [ ] (opt) Open and close every single app, because most have a welcome screen and you don't want to be bothered by it when you'll need the app.
