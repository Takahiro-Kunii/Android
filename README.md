# Android
adbとか

```
adb devices
adb -s 356655112239232
adb kill-server
adb start-server
```

### adb承認キーの削除

Android実機に繋ぐときに出る「USB接続を許可しますか」が出なくて困った時に試す。

> del C:\\Users\\{User Name}\\.android\\adbkey.*
