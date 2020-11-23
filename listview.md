# ListView

### 流程

* 创建ListViewActivity
* 画layout文件——》 activity\_listview
* 在mainacitivity里设置个跳转，可以点击跳转到listview activity
* 去listview layout 文件 写一个listview 布局  id=lv
* 去listviewActivity里找到lv，对其设置adapter
* 新建个adapter，重写getView 来觉得每个component 长什么样子
* 去新建一个layout文件，layout\_listItem -&gt; 画item的样子 注意id
* 改写adapter
  * 写constructor接收context, 赋值给mContext;
  * 写个静态class viewHolder 用来放item的控件
* 改写getview
  * 懒加载，如果convertview为空- &gt;找到控件,否则getTag（）
  * 给控件赋值
* 回到listviewactivity里设置adapter， 传入listViewAcitivity.this as context

写adapter 用baseadapter

![](.gitbook/assets/image%20%2867%29.png)

![](.gitbook/assets/image%20%2863%29.png)

创建list item的布局

![](.gitbook/assets/image%20%2866%29.png)



再回来写重写getview

![](.gitbook/assets/image%20%2865%29.png)

![](.gitbook/assets/image%20%2868%29.png)

最后回到listview activity 给他set adapter

![](.gitbook/assets/image%20%2862%29.png)

短按长按

![](.gitbook/assets/image%20%2860%29.png)

