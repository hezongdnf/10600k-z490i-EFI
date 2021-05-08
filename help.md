
### Mac登录界面显示其他用户

这是因为你之前打开以Root身份登录，只要关闭以Root身份登录就可以了。

在终端输入：
```
sudo defaults write /Library/Preferences/com.apple.loginwindow SHOWOTHERUSERS_MANAGED -bool FALSE
```
