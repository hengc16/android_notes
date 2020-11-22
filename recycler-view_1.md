# Recycler View\_1

### 介绍

![](.gitbook/assets/image%20%2838%29.png)

![](.gitbook/assets/image%20%2844%29.png)

### 流程

* 建一个recycler view activity
* 在layout里创建控件
* 在activity里找到控件，做跳转
* 在新建一个activity 为linear recycler view activity 用来演示 linear 版的recycler view
* 在layout里创建recycler view 控件
* 在linear rec view activity 里找到声明控件。
* 开始使用这个recycler view
  * set layoutmanager 可以有各种布局管理器，这次演示linearlayoutmanager
  * setadapter， 
* 写adapter类，继承recyclerview.adapter
  * 写一个内部类，linearViewHolder 继承于RecyclerView.viewHolder
  * 并把这个内部类写到recyclerView.adapter&lt;linearAdapter.linearViewHolder&gt; 泛型
  * 去画一个布局
  * 写构造方法获取context
  * 在oncreate里new一个viewholder，传入item布局的view当参数
    * 通过LayoutInflater.from\(context\).inflate\(R.layout.layout\_linearItem, parent,false\) 来得到view
  * 改写linearViewHolder
    * 找到控件
  * 改写onbindview holder
    * 通过holder的属性得到控件，对其进行更改。
* 回到activity里，set我们建好的adapter

