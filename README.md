# simulation_checkbox
纯css+css3模拟CheckBox选择框


概述总结：

1、需要一个宽为112px,高为54px，半椭圆，色值为ddd的选择框。

2、html结构为input的CheckBox属性，此标签隐藏，label展示样子

3、重点之一：CheckBox需要一个id名（只能是id,class不生效）,label的for属性名字跟input的ID名保持一致

4、css方面设定label的宽，高，圆角值，背景色值，显示为块元素，相对定位值，padding值，transition值

5、label需使用:after伪元素，模拟按钮开关，设定宽，高，背景色，圆角值，绝对定位值，left值，transition值

6、重点之二：伪元素未加content:'';html上不生效

7、:checked(css3选择器) 选择器匹配每个已被选中的 input 元素（只用于单选按钮和复选框）。

8、重点之三：.order-sure-rad input:checked + .checkBtn{background: #FF3F61;}此写法可以让CheckBox被点击时让同级label改变背景色值

9、transition: all .2s ease; all指的是所有属性都赋予过渡效果，过渡时间延续2s，ease表示过渡类型是平滑过渡
