activity主要代码：
@Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Log.i("MainActivityLife","调用onCreate()");
    }
    @Override
    protected void onStart() {
        super.onStart();
        Log.i("MainActivityLife","调用onStart()");
    }
    @Override
    protected void onResume() {
        super.onResume();
        Log.i("MainActivityLife","调用onResume()");
    }
    @Override
    protected void onPause() {
        super.onPause();
        Log.i("MainActivityLife","调用onPause()");
    }
    @Override
    protected void onStop(){
        super.onStop();
        Log.i("MainActivityLife","调用onStop()");
    }
    @Override
    public void onDestroy() {
        super.onDestroy();
        Log.i("MainActivityLife","调用onDestroy()");
    }
    @Override
    public void onRestart(){
        super.onRestart();
        Log.i("MainActivityLife","调用onRestart()");
    }
    结果截图：
    helloworld：
    https://github.com/linyu0119/helloworldactivity/blob/master/app/images/2.png
    activity生命周期：
    https://github.com/linyu0119/helloworldactivity/blob/master/app/images/1.png
