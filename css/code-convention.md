#CSS规范:
1. 文件分类: 通用类; 业务类;(文件归档, 把css文件分为通用类和业务类)
    * 通用类: 公用样式, 第三方库, 自定义UI控件;
    * 业务类: 专辑, 歌手, 排行榜; 各自的业务样式放到各自的文件夹中;
* 文件规范
    * 文件引用:
        * 行内样式: 不推荐; 只有特殊情况才用, 如: 页面加载时就需要隐藏的,可以加入style="display: none;";
        * 外联引入: 使用link标签引入一些公用样式文件;
        * 内联引入: 当前页的特定样式可以放在head->style中;
        * 避免在CSS中使用@import, 它会引起页面重新渲染等性能问题;
    * 文件本身:
        * 文件名由小写字母和中划线组成;
        * 编码统一使用 UTF-8;
* 注释规范
    * 块状注释: 统一缩进, 在被注释对象之上;注释内容包括: 作者信息, 创建时间,(修改时间, 修改人), 模块功能说明;
    * 单行注释: 文字两端需空格,在被注释对象之上;
    * 行内注释: 文字两端需空格, 在分号之后;
* 命名规范
    * 分类命名: 布局样式 g- 开头, 模块样式使用 m- 开头;
    * 命名格式: 所有选择器命名(包括样式)都采用小写;长度适中:权衡长度和可读性;
    * 语义化命名: 以内容语义命名;
* 书写规范:
    * 单行与多行: 统一采用单行;(编辑器设置自动换行, 一般不会出现横向滚动条)
    * 空格与分号: 缩进采用4个空格, 规则内一个空格隔开; 保留最后一个属性值的分号;
    * 属性顺序: 根据属性的重要性按顺序书写;显示属性->自身属性->文本属性和修饰属性;
    * Hack方式: 统一各浏览器的Hack方式, IE6 "_property:value", IE6/IE7 "*property:value", 不要滥用Hack(无法解决时再用Hack);
    * 值格式: 统一属性值(color使用十六进制形式"#fff", url不使用引号"url(icon.png)");