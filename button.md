# Button

### 跳转

声明button， 找到btn，加listener，调转到制定activity。

![](.gitbook/assets/image%20%2814%29.png)

### 字体大小，颜色

![](.gitbook/assets/image%20%286%29.png)

![](.gitbook/assets/image%20%284%29.png)

### 自定义背景形状

在drawable里new有一个root element 为shape的drawable resource file

![](.gitbook/assets/image%20%287%29.png)

![](.gitbook/assets/image%20%2822%29.png)

### 自定义按压效果

创建一个drawable resource file， 使用root element为selector

![](.gitbook/assets/image%20%2816%29.png)

### 点击事件

Toast 为界面弹出提示信息， 注意带参数view

![](.gitbook/assets/image%20%2811%29.png)

为button设置onClick触发点击事件。showToast

![](.gitbook/assets/image%20%288%29.png)

![](.gitbook/assets/image%20%285%29.png)

### 更常用的点击事件方法

在onclick里去override指定button对象的onclick触发， 而不是在xml里写onClick 去调用某个函数

![](.gitbook/assets/image%20%2813%29.png)

