### web前端面试题
1.行内元素和块级元素<br>
>行内元素：<br>1.可以在排列在同一行。 <br>
            2.设置宽高和内外边距对它都没有效果。<br>
            常见：img、span、a、input、select。em、i、small....<br>

>块级元素：<br>1.总是排列在新行，独占一行。<br>
            2.块级元素可以包含行内元素和块级元素。<br>
            常见：div、p、h1-6、ul、li、ol、table、tbody、tr、td、form...<br>

> 转换：display：block<br>

2.列举不同的清除浮动的技巧，并指出它们各自适用的使用场景

>1.clear:both;//添加新元素

>2.overflow:hidden;//加在父级元素上

>3.:after方法和:before方法.//作用于浮动元素的父级

