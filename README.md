## Sublime Text 3 Config

Please find my Sublime Text 3 config herein. It exists mostly so that I can keep my preferences and packages synced across machines, but I'm pretty sure it'll be of use to most Sublime Text 3 users looking to jumpstart their config.

#### Prereqs

1. Ensure you have [package control installed](https://packagecontrol.io/installation)

#### Usage

```
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/
rm -rf *

# note the '.' that follows the repository address below.
# this tells git to copy the *contents* of the repo, rather
# than adding an entire subdirectory (`sublime_text_3_config`) within Packages/Users/
git clone https://github.com/vanderhoop/sublime_text_3_config.git .
```




