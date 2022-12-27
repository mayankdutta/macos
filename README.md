# macos tips

#### Show Desktop
`defaults write com.apple.finder CreateDesktop true && killall Finder`

#### Hide Desktop
`defaults write com.apple.finder CreateDesktop false && killall Finder`

#### Memory saver
- daily disk
- grand perspective
- finder -> cmd+shift+g -> type'~/Library/Caches' -> delete em'
- preference->disk->first aid
- Freeing up all the RAM before using heavy software: `sudo purge`

#### Uninstaller 
- clean my mac (paid)
- app cleaner

#### mini Tiling app
- rectangle

#### Video player 
- IINA

#### Fan
- fanny 

#### Battery
- battery health

#### Display
###### prefernce->accessiblity->display
- tick reduce motion
- tick reduce transparrency


#### Mission control
- better to unmark all of em' 


#### Keyboard
- you might want to **max** the `key repeat` & `Delay until repeat` in the keyboard section. 

#### Telegram
- Insert `~/Library/Group Containers`, press Enter. This directory will open. 
- Then find the directory `*.keepcoder.Telegram`, go into it, next to `account-*`, next to postbox

#### Full screen shortcut 
- fn + f


#### EMFILE too many files open js error
- `ulimit -n` (to view your current limit) 
- `ulimit -n 1024` (to expand the limit, it will be temproary, restarting your session will restore the default value)
- Adding the `ulimit -n 10240` statement to your bash profile using `sudo nano .bash_profile` makes it permanent. 


