# 一、文字属性
## 1.规定文字样式
1. font-style
    1. normal 正常的
    2. italic 倾斜的

## 2.规定文字粗细
1. font-weight
    1. bold 加粗
    2. bolder 比加粗还要粗
    3. lighter 细线，默认
    4. 100

## 3.规定文字大小
1. font-size
    1. 30px    
    
## 4.规定文字字体
1. font-family
    1. 字体名  中文一定要用双引号或者单引号
    2. 字体名，字体名    
注意：中文字体都可以处理英文，英文字体不能处理中文，所以要想让英文和中文显示不同字体，需要将英文字体放前面，中文字体放后面。

## 简写格式
+ font: style weight size family;
+ style和weight可以省略，但size和family不可省略。style和weight位置可以交换，size和family不可互换。

# 二、文本属性
## 1.文本装饰属性
1. text-decoration
    1. underline 下划线
    2. line-through 删除线
    3. overline 上划线
    4. none 什么都没有，最常见用途为去掉超链接的下划线

## 2.文本水平对齐的属性
1. text-align
    1. left
    2. right
    3. center

## 3.文本缩进的属性
1. text-indent
    1. 2em em是单位，一个em代表缩进一个文字的宽度
    
# 三、颜色属性
1. color
    1. red  英文单词
    2. rgb(255,0,0)  rgb
    2. rgba(255,0,0,0.1)  rgba  a代表透明度，为0到1
    3. `#FF0000`  十六进制
    4. `#F00`    十六进制缩写