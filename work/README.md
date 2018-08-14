## 哈哈
`哈哈` 
```
private void initFloatManager() {
        mFloatWindowManager = new FloatWindowManager.Builder(this)
                .setHotAreaLayout(R.layout.float_window_hot_area)
                .setClickLayout(R.layout.float_window_click_view)
                .setAnimAccLayout(R.layout.float_window_anim_view)
                .setInitializationCallback(new OnInitializedCallback() {
                    @Override
                    public void onInitialized() {
                        addFloatWindow();
                    }
                })
                .build();
        mFloatWindowManager.initialize();
    }
```
