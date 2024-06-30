# mpv-plugin-bookmark
#### mpv plugin to record your playing history for all videos in a folder. and you can choose resume to play next time.<br>
this is the light version, if you also want it loading play list automatically, switch to [master branch for of the original repo](https://github.com/yozorayuki/mpv-plugin-bookmark/tree/master).

###### Usage
* copy `bookmark.lua` script to `~/.config/mpv/scripts/`
* you can config the value of `save_period` which means how many seconds the it will save play progress. quit and puse also trigger saving<br>
the config file's path is `~/.config/mpv/lua-settings/bookmark.conf` , you may need to create it, for example:
```
save_period=30
```
###### Note:
This is a fork from the awesome [original repo](https://github.com/yozorayuki/mpv-plugin-bookmark/tree/light) to support remembering the last position for multiple videos. 
