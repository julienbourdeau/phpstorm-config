# phpstorm-config

This is my global configuration for [PhpStorm](https://www.jetbrains.com/phpstorm/),an IDE for PHP.

# Installation

Before you do this, make sure PhpStorm is not running, or it will overwrite your changes.

Use the following commands to go to the config directory, remove some default directories, and pull the files from my repository:

```bash
cd ~/Library/Preferences/WebIde80

# remove the files and folders that are in this repository
rm -r codestyles/
rm -r colors/
rm -r fileTemplates/
rm -r inspection/
rm -r keymaps/

# pull this repository
git init
git remote add origin git@github.com:julienbourdeau/phpstorm-config.git
git fetch
git checkout -t origin/master
```


## Subdirectories of the config folder

Directory | Contents
----------|---------
codestyles | Code Style settings (Editor > Code Style)
colors | Colors & Fonts settings (Editor > Colors & Fonts)
fileTemplates | File and Code Templates (Editor > File and Code Templates)
filetypes | File Types (Editor > File Types)
inspection | Inspection profiles (Editor > Inspections)
keymaps | Keyboard shortcuts (Appearance & Behavior > Keymap)
templates | Live templates (Editor > Live Templates)

# Credits

Thanks to [@nicwortel](https://github.com/nicwortel/phpstorm-ide-config) for original idea and research.
