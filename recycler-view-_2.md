# Recycler View \_2

### 横向滚动

流程

* 建horizontalViewActivity
* 画recycler view控件在activity布局
* 在activity里找到控件
* set linear layout manager
  * set orientation 改为horizontal
* set adapter
* 创建我们的adapter class



![](.gitbook/assets/image%20%2870%29.png)

### 网格视图

流程

* 建gridViewActivity
* 在布局里加recycler view控件
* 在activity里找到控件
* set grid layout manager
  * 传参 gradrecyclerviewactivity.this, 3
  * 这里的3  是指grid一行有几个item
* set adapter
* 创建我们的adapter class





