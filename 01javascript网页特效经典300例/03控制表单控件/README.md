### 遍历表单的所有控件
### 实例描述
表单中的控件用来于用户进行交互,为了获取用户的输入,开发人员必须知道如何获取这些控件,并知道怎么操作他们,例如批量修改控件的样式或说明等,本例将展示如何遍历表单下的控件

### 实现代码如下链接所示
[遍历表单的所有控件](遍历表单的所有控件.html)

### 运行效果如下图所示
![](http://i.imgur.com/y88QOtb.gif)

### 具体分析
在document下内置了一个数组变量forms，它表示的是当前网页下的所有表单,本例代码首先通过该数组的第一个元素即获得了网页唯一的一个表单元素,然后通过表单form下的elements变量获得所有控件,最后通过所有控件的value属性获得他们的值，并进行拼接和展示

