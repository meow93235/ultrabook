# SmartScreen User Guide

SmartScreen is a web-based screening service.
Content across multiple displays and locations can be controlled remotely with Jujue, @Smartscreen bot, or ubot on Node-Red control.
Simply send images, Youtube videos, and urls from your Telegram-app.


## Command set for the SmartScreenbot


| Command | Function | 
| -------- | -------- | 
|/pin | device pairing | 
|/drop|drop files on your pairing devices|
|/youtube|enter keyword of youtube to play media|
|/miki|upload file(s) to miki storage|
|/jujue|Jujue command interaction|
|/status|get status of pairing device|
|/post|post subtitle to the screen|
|/flow|trigger flow “format” DDN: trigger ID screen
|/rc| remote control button|
|/view| get snapshot from IP cam|
|/help| See all the commands|

## SmartScreen setting
1. Access SmartScreen through URL: smartscreen.tv
![](https://i.imgur.com/tIxNcIu.png)
* If you are using a Linux device, SmartScreen can be downloaded from snapcraft. 

2. Click the button on the top-left corner  to reach "Setting". Here you can name your device and add tags.

3. Don't forget to click "save" after you make any changes.
![](https://i.imgur.com/rZDwqYD.png)


4. Click "SmartScreen" to exit back to the Home Page.

## Operation process
1. Make sure SmartScreen is already turned on and online.
2. Open your Telegram-app and search for @SmartScreen bot.
3. Key in "/help" to see all commands.
![](https://i.imgur.com/yAfFu94.jpg)

4. Key in "/pin" to set the SmartScreen display(s) to be connected. Enter your SmartScreen name or tag. 

5. Send your content (photo, video, file or url, ect.). If you'd like, you can also add a caption to it. 
* If @SmartScreen bot pings back “Dropped”, your content should be successfully displayed on your SmartScreen display!
![](https://i.imgur.com/79dAUEf.jpg)


* If it shows “DDN off”, it means you are not connected to your SmartScreen display. 
![](https://i.imgur.com/9xzqiqJ.jpg)

  - If you want to drop video through command /pin, make sure that you have already turned your video into mp4 file.
