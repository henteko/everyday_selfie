# Everyday Selfie
毎日自撮りして自己管理

lunchdで自動起動してます  

upload_selfie内のYOUR_ACCESS_TOKENは自分のGyazoのaccess_tokenを入れてください  
everyday_selfie.plist内もいい感じに編集してください  

# Install

everyday_selfie require [imagesnap](https://github.com/rharder/imagesnap).
```sh
$ git clone git@github.com:henteko/everyday_selfie.git
$ cd everyday_selfie/
$ brew install imagesnap
$ vim upload_selfie # Edit the YOUR_ACCESS_TOKEN(Gyazo)
$ vim everyday_selfie.plist # Edit the /path/to/everyday_selfie
$ mv everyday_selfie.plist ~/Library/LaunchAgents/everyday_selfie.plist
$ launchctl load ~/Library/LaunchAgents/everyday_selfie.plist
```
