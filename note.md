# 1. html标签
    (1) p标签, button标签, a标签
    (2) a标签的属性, href, target
# 2. button CSS
    写button的css样式
    (1) hover, transition, shadow, opacity
    (2) class属性, 给button打标签
    (3) css 通过 <.标签> 调用某一个button, 明细设计这个button的样式
    (4) css属性必须;结尾
# 4. chrome devtool & CSS box model
    (1) 打开chrome devtools, 定位某一个element, 获取别人页面上的css元素参数
    (2) rapidtables.com/convert/color/hex-to-rgb.html
        rgb 16进制和10进制 转换
    (3) css box model
        a. button外面的margin
        b. button里面的margin, 是围绕文本, 键入join my channel超界了, 设置button里面的margin, 叫做padding
        c. 通过开发工具, 设置button的margin, padding,\
        d. 如果现在button的样式是height或width, 调整button的文本可能会超界. 解决方法是不要height, width, 替换成padding top | bottom | left | right 
    (4) button默认是里面的文本对齐的, 通过vertical-align让button顶部对齐
# 5. text style
(1) 设置文本的字体, 大小, 加粗, 斜体
(2) 对齐方式
(3) 整体字符串的宽度, 高度
(4) html entity html的特殊字符
(5) <p>默认有margin=14px, 通过margin参数调整
(6) 合并相同的字体配置，把字体从class中抽出来，放在<p>里
(7) 在.class里面设置的style，优先级高于，p selector里面定义的
(8) 插入>，在html里面有可能产生歧义，所以插入 &#62
(9) 字体设置下划线, 仅对个别的字体设置下划线.
a. <strong>元素, <u>元素, <span>元素
b. 可以为span单独做class
c. <p>里面设置了一堆空格, 但是html页面合并了, 不显示.解决方法是在<span>的class里面设置margin
# 6. html structure
 