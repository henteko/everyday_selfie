# Everyday Selfie
毎日自撮りしてgoogle photosで自己管理

lunchdで自動起動してます  

# Install

everyday_selfie require [imagesnap](https://github.com/rharder/imagesnap).
```sh
$ git clone git@github.com:henteko/everyday_selfie.git
$ cd everyday_selfie/
$ brew install imagesnap
$ vim selfie # Edit the /path/to
$ vim everyday_selfie.plist # Edit the /path/to/everyday_selfie
$ cp everyday_selfie.plist ~/Library/LaunchAgents/everyday_selfie.plist
$ launchctl load ~/Library/LaunchAgents/everyday_selfie.plist
```
