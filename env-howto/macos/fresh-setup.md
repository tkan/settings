# install

## automatically

1. [`brew`](https://brew.sh)

```bash
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

2. Packages (apps, utils etc.)

```bash
$ brew cask install iterm2 google-chrome firefox sublime-text postman java
$ brew install tmux bash bash-completion coreutils tree git python httpie nvm nginx
```

3. Node

```bash
$ mkdir ~/.nvm
$ nvm install node
$ brew install yarn --without-node
```

## manually

* [Sublime Text Package Control](https://packagecontrol.io/installation)

# tweak

## System Preferences

* "General" <- almost everything :)
* "Dock"
  * "Automatically hide and show the Dock" <- on
* "Mission Control"
  * "Automatically rearrange Spaces" <- off
* "Security & Privacy"
  * "General"
    * "Require password" <- immediately
    * "Show a message when the screen is locked" <- off
* "Displays"
  * "Display -> Automatically adjust brightness" <- off
  * "Night Shift -> Schedule" <- "Sunset to Sunrise"
* "Keyboard"
  * "Keyboard"
    * "Use F1, F2, etc. keys as standard function keys on external keyboards" <- on
    * "Modifier Keys... -> Caps Lock" <- `^` Control
    * "Customize Control Strip..."
    * "Shortcuts"
      * "Mission Control" (contradicts with Sublime Text, e.g. multicursor)
        * "Mission Control" <- off
        * "Application windows" <- off
        * "Show Dashboard" <- off
      * "Input Sources" <- `⌘Space`
      * "Spotlight" <- `⌃⌘Space`
  * "Input Sources"
    * Languages
      * - "U.S."
      * + "British"
      * + "Ukrainian - PC" 🇺🇦 (or better [`bandera-layout`](https://github.com/muromec/bandera-layout))
    * "Automatically switch to a document's input source" <- on
* "Trackpad -> Point & Click"
  * "Look up & data detectors"<- off
  * "Tap to click" <- on
  * "Tracking speed" <- faster (60%)
  * "Silent clicking" <- on
  * "Force Click and haptic feedback" <- off
* "Siri"
  * "Enable Siri" <- off
* "Date & Time"
  * "Clock -> Date options -> Show date" <- on
* "Accessibility"
  * "Display -> Reduce motion" <- on :star:

## Finder

* "Preferences"
  * "General -> New Finder windows show" <- home
  * "Sidebar" <- rearrange
  * "Advanced"
    * "Show all filename extension" <- on
    * "Keep folders on top when sorting by name" <- on

## iTerm2

* "Preferences -> Profiles"
  * "Colors"
    * "Color Presets..." <- "Dark Background"
    * "Basic Colors"
      * "Background" <- `#112233`
  * "Text"
    * "Change Font" <- "12pt Menlo Regular"
  * "Keys" (see [Use ⌥ ← and ⌥→ to jump forwards / backwards words in iTerm 2, on OS X](https://coderwall.com/p/h6yfda/use-and-to-jump-forwards-backwards-words-in-iterm-2-on-os-x))
    * "Left ⌥ Key" <- "Esc+"
    * "Key Mappings"
      * "⌥←"
        * "Action" <- "Send Escape Sequence"
        * "Esc+" <- "b"
      * "⌥→"
        * "Action" <- "Send Escape Sequence"
        * "Esc+" <- "f"

# setup

* [GitHub (SSH keys)](https://help.github.com/articles/connecting-to-github-with-ssh)