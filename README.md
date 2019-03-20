# helloworld
This is a first Android test!<br><br>
# 实验内容
*验证Activity的生命周期*
# 关键代码<br>
```
public class MainActivity extends AppCompatActivity {
    public static final String TAG = "Lifecycle";
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
    }
    @Override
    protected void onStart() {
        super.onStart();
        Log.d(TAG,"onStart");
    }
    @Override
    protected void onResume() {
        super.onResume();
        Log.d(TAG,"onResume");
    } @Override
    protected void onPause() {
        super.onPause();
        Log.d(TAG,"onPause");
    }
    @Override
    protected void onStop() {
        super.onStop();
        Log.d(TAG,"onStop");
    } @Override
    protected void onDestroy() {
        super.onDestroy();
        Log.d(TAG,"onDestroy");
    } @Override
    protected void onRestart() {
        super.onRestart();
        Log.d(TAG,"onRestart");
    }
}
```
# 实验截图
## 初始界面
![初始界面](https://github.com/smartflowers/helloworld/blob/master/pictures/initial.jpg)
## 退出程序
![主界面](https://github.com/smartflowers/helloworld/blob/master/pictures/home.jpg)
![控制台](https://github.com/smartflowers/helloworld/blob/master/pictures/PSD.jpg)
## 重启程序
![控制台](https://github.com/smartflowers/helloworld/blob/master/pictures/SR.jpg)
## 转入后台
![控制台](https://github.com/smartflowers/helloworld/blob/master/pictures/PS.jpg)
