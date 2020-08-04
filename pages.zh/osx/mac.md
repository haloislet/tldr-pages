# mac

> macOS 一些命令记录

- 开启任何来源:

`sudo spctl --master-disable`

- 关闭任意来源:

`sudo spctl --master-enable`

- 查看系统信息:

`system_profiler`

- 查询公网 IP:

`curl cip.cc`

- 开启 HIDPI

`sudo defaults write /Library/Preferences/com.apple.windowserver.plist \
DisplayResolutionEnabled -bool true`
