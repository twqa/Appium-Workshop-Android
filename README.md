# Appium-Workshop-Android
##Test Case

自动化安装微信，登陆，在置顶的对话框中输入“Appium Test” 并验证

##环境配置
###Genymotion Settings
ADB --> Android SDK
/Users/xxx/Library/Android/sdk

###Install ARM_Translation_Lollipop_20160402.ZIP

###SDK environment variable 

vim .bash_profile
```
export ANDROID_HOME=/Users/xxxx/Library/Android/sdk

export PATH=$ANDROID_HOME/platform-tools:$PATH

export PATH=$ANDROID_HOME/tools:$PATH
```

source ~/.bash_profile
验证方法： adb devices 

###Appium configuration
Platform version: 5.0.1 Lollipop (API Level 20)
Advance Andorid SDK path
Set app path

## 跑脚本前需要打开Genymotion虚拟机和Appium GUI并Lanuch，关闭Inspector



