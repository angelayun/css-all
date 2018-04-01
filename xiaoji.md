* content中，当使用attr()获取标签属性名的时候，千万不要添加引号!
* 加号+其选择相邻的后面的兄弟节点，而弯弯号~是全部后面的同级节点元素。
* IE对小数像素采取取整的策略，类似于Math.floor()方法，就算你大小为11.999999像素，最后还是显示11像素文字的大小（已测试）；而Firefox等一些浏览器则采取四舍五入的策略，类似于Math.round()方法，11.4像素就表现为11像素，11.5像素就表现为12像素
* 只有一个元素属于inline或是inline-block（table-cell也可以理解为inline-block水平）水平，其身上的vertical-align属性才会起作用。
* IE6/IE7浏览器下的vertical-align的百分比值不支持小数line-height。
* 类似于display:block; float:left;的CSS代码超过95%的情况是没有道理的(display:block是多余的)
* 浮动破坏了正常的line boxes
* line boxes的高度是由其内部最高的inline boxes的高度决定的
* 绝对定位的元素脱离了文档流，而浮动元素依旧在文档流中；同处于文档流中的文字实体不会与浮动元素重叠，而会与绝对定位元素重叠。