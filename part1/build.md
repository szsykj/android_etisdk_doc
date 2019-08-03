# build.gradle 配置
build.gradle 文件里添加集成准备中下载的dependencies 依赖库。  
```
implementation (name:'SykjSmartSdk_v1.0.0, ext:'aar')

implementation 'com.squareup.retrofit2:retrofit:2.4.0'
implementation 'com.squareup.okhttp3:logging-interceptor:3.11.0'
implementation 'org.eclipse.paho:org.eclipse.paho.client.mqttv3:1.2.0'
implementation 'org.eclipse.paho:org.eclipse.paho.android.service:1.1.1'
implementation 'com.tencent:mmkv:1.0.10'
implementation 'org.greenrobot:eventbus:3.1.1'
implementation 'com.google.code.gson:gson:2.8.3'
implementation 'org.litepal.android:java:3.0.0'
implementation 'com.aliyun.dpa:oss-android-sdk:+'

implementation 'com.jakewharton:butterknife:8.8.1'
annotationProcessor 'com.jakewharton:butterknife-compiler:8.8.1'
```