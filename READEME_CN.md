# Hidekeyboard
## 摘要 
仿照iOS实现点击非输入框区域 软键盘隐藏 一款使用超简单的轻量级库

## 英文文档
[View English Documents](https://github.com/yingLanNull/HideKeyboard)

## 动画
![1](https://github.com/yingLanNull/HideKeyboard/blob/master/show/show.gif)

## 下载APK体验
[Download Demo](https://github.com/yingLanNull/HideKeyboard/blob/master/show/demo-debug.apk)

## 使用方法
### 步骤 1
#### Gradle 配置
```
dependencies {
    compile 'com.yinglan.keyboard:hidekeyboard:1.0.3'
}
```

### 步骤 2

#### 代码

```
		HideUtil.init(this);
```

```
{
	 @Override
     protected void onCreate(Bundle savedInstanceState) {
         super.onCreate(savedInstanceState);
         setContentView(R.layout.activity_main);
         HideUtil.init(this);
     }
}

```
## 注意

```
	该实现使用了Activity顶层布局android.R.id.content的OnTouchListener监听,重写此监听需注意。
```

## 开源协议

    Apache License Version 2.0

