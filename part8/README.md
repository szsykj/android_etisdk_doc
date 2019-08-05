
#获取当前设备倒计时，查询设备获取，可能为null

```java
/**
* 获取当前设备的倒计时，查询设备获取
* @param did   设备的id
* @return
*/
void getTimerByDeviceId(int did, ResultCallBack<TimerModel> resultCallBack);
```

# 通过缓存查询设备的倒计时，可能为null
```java
/**
* 通过缓存查询设备的倒计时，可能为空
* @param did   设备的id
* @return
*/
TimerModel getTimerFromCache(int did);
```

#设置倒计时
```java
/**
* @param did            设备的id
* @param minute         要设置的倒计时长，单位为分钟
* @param open           是否是打开设备
* @param resultCallBack 回调
*/
void setTimer(int did, final int minute, boolean open, ResultCallBack<TimerModel> resultCallBack);
```

#停止倒计时
```java
/**
* 停止timer
*
* @param did
* @param resultCallBack
*/
void stopTimer(int did, ResultCallBack resultCallBack);
```

#缓存倒计时
```java
/**
* 缓存Timer
*
* @param timerModel 倒计时模型
*/
void saveTimer(TimerModel timerModel);
```

#清楚缓存的倒计时
```java
/**
* 清除设备的timer缓存
*
* @param did   设备的id
*/
void deleteTimer(int did);
```