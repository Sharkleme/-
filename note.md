**页面布局排序**
页面整体布局
	从上到下,从外向里,从左向右,先写通用页面(头部,底部),在写特殊页面
css属性顺序重要性
	1,css属性书写顺序不对,可能会影响页面的布局(line-height和font连写冲突)
	2,方便程序员维护,一般会把布局属性,重要的属性放在前面,次要,点缀属性放在最后面
属性的书写顺序
	1,布局属性
		display  float position 
	2,盒子模型+背景
		width height background margin padding
	3,文本内容属性
		color font text-align line-height
	4,点缀属性
		border-radius 阴影效果text-shadow 光标小手
选择器使用
	推荐使用 类+后代选择器 ,一般选择器的层级不超过3个


**一些点**
小导航条a span a
大一点主要ul>li>a
字体颜色都一样，设置在父栏
把a变为块级元素

理解以便预测,预测以便控制