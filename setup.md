# Mac Setup

## System Preferences

-   Dock & Menu Bar
    -   Show recent application in Dock - OFF
    -   Dock Size - INCREASE
-   Trackpad
    -   Secondary click - "Click in bottom right corner"
    -   Look up & data detectors - OFF
    -   Swipe betwen pages - OFF
-   Mission Control
    -   Show Desktop - "Right Command"
-   Keyboard
    -   Text
        -   remove replace/with
        -   Correct spelling automatically - OFF
        -   Capitalize words automatically - OFF
        -   Add period with double-space - OFF
    -   Shortcuts
        -   Mission Control - OFF
        -   Application Windows - Off
-   Spotlight
    -   TURN OFF - Bookmarks & History, Contacts, Conversion

## Install Apps

-   Mini Calendar (App Store)
-   XCode Command Line Tools
-   iTerm2 ([https://iterm2.com](https://iterm2.com/))
    -   `echo "PROMPT='%F{215}%n:%~ %%%f '" > ~/.zshrc`
    -   `echo '.DS_Store' > ~/.gitignore`
    -   `git config --global core.excludesfile ~/.gitignore`
    -   Preferences > Profile
        -   Colors > Color Presets > Visit Online Gallery > Chalkboard
        -   Window
            -   Transparency - 8
            -   Blur - Enable / 7
-   Homebrew: [https://brew.sh/](https://brew.sh/)
-   Rectangle (`brew install --cask rectangle`)
    -   Spectacle shortcuts
-   Fonts
    -   `brew tap homebrew/cask-fonts`
    -   `brew install --cask font-jetbrains-mono font-public-sans`
        -   iTerm2 > Preferences > Profiles > Text
            -   Font - JetBrains Mono, Use Ligatures

## Editor

-   `brew install vscodium`
-   Color Theme - Atom One Dark
-   copy contents of `vscode-settings.json` into Library > Application Support > VsCodium > User > `settings.json` (accessible via GUI through Workbench > Appearance > Color Customizations)

### Extensions

-   Color Highlight
-   Docker
-   DotENV
-   file-icons (colorless)
-   Formattting Toggle
-   Markdown Preview Github Styling
-   Prettier
-   Python

## Resources/References

-   https://github.com/tanho63/pc-setup/blob/main/macos-laptop.md
-   https://github.com/nguyenkvi/setup/blob/main/checklist.md
-   https://sebastiandedeyne.com/setting-up-a-global-gitignore-file/
