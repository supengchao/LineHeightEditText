# LineHeightEditText

Fix edittext lineHeight and cursor effect when set lineSpacingExtra or lineSpacingMultiplier

## EditText vs LineHeightEditText

![EditText vs LineHeightEditText](https://raw.githubusercontent.com/hanks-zyh/LineHeightEditText/master/demo.gif)

## Usage

```groovy
compile 'com.hanks:lineheightedittext-library:1.0'
```

```xml
<com.hanks.lineheightedittext.LineHeightEditText
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:lineSpacingExtra="16dp"
    android:text="Hello World!\nHello World!\nHello World!"
    android:textSize="18sp"
    app:cursorColor="#ff0000"
    app:cursorHeight="21dp"
    app:cursorWidth="2dp"/>
```
