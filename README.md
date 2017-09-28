# iOS-Android-App-icon-Resizer-Bash-Script
mac terminal bash script using to make app size of app icon. support iOS and android
##  INSTALL
```

git clone git@github.com:heart/iOS-Android-App-icon-Resizer-Bash-Script.git
cd iOS-Android-App-icon-Resizer-Bash-Script
mv appicon /usr/local/bin/
cd ..
rm -rf iOS-Android-App-icon-Resizer-Bash-Script
sudo chmod 755 /usr/local/bin/appicon

```

##  HOW TO USE
###	runcommand
For the best result icon.png must be greater than or equal to 1024x1024 pixels.
```
appicon icon.png
```
![app icon resizer screen shot](https://github.com/heart/iOS-Android-App-icon-Resizer-Bash-Script/blob/master/screenshot/howtouse.jpg?raw=true)

###	result
![app icon resizer screen shot (iOS)](https://github.com/heart/iOS-Android-App-icon-Resizer-Bash-Script/blob/master/screenshot/result.jpg?raw=true)

![app icon resizer screen shot (Android)](https://github.com/heart/iOS-Android-App-icon-Resizer-Bash-Script/blob/master/screenshot/androidresult.jpg?raw=true)


## UNINSTALL SCRIPT
```
rm /usr/local/bin/appicon
```