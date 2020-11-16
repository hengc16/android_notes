# imageView

### 属性

src属性

![](.gitbook/assets/image%20%2828%29.png)

scaleType 属性 里的fitXY 撑满当前宽高，（图片会被拉伸）

![](.gitbook/assets/image%20%2825%29.png)

![](.gitbook/assets/image%20%2827%29.png)

### 加载网络图片

用第三方库 glide

* 可以下jar包放lib里
* 使用gradle
* 使用maven

用gradle

```text
repositories {
  google()
  jcenter()
}

dependencies {
  implementation 'com.github.bumptech.glide:glide:4.11.0'
  annotationProcessor 'com.github.bumptech.glide:compiler:4.11.0'
}
```

网络请求权限

在AndroidManifest里声明权限

![](.gitbook/assets/image%20%2831%29.png)

