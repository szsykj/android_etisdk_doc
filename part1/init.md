#SDK初始化

在application中初始化sdk后，使用sdk中对外提供的接口(具体接口使用参考demo实例)

```
public class SykjApplication extends Application {
    @Override
    public void onCreate() {
        super.onCreate();
        SYSdk.init(this);
    }
}
```