# fragment

![](.gitbook/assets/image%20%2856%29.png)

![](.gitbook/assets/image%20%2842%29.png)

### 常用方法

![](.gitbook/assets/image%20%2836%29.png)

![](.gitbook/assets/image%20%2841%29.png)

返回视图文件，就像activity里oncreate方法里的setcontainedView一样

找到布局文件

![](.gitbook/assets/image%20%2859%29.png)

![](.gitbook/assets/image%20%2830%29.png)

当view创建完整之后，我们可以用这个方法。

拿到当前布局文件里的element



在container activity里管理fragment

创建fragment-&gt; 实例化fragment —&gt; 把fragment放入容器-&gt; 记得加commitAllowingStateLoss\(\);

![](.gitbook/assets/image%20%2833%29.png)

新版

![](.gitbook/assets/image%20%2852%29.png)

注意：！！！

这里getFragmentManger\(\) 改为getSupportFramentManager\(\)

