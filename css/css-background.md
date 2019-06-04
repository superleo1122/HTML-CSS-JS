# css背景
## 1. 设置背景颜色
background-color

## 2. 设置背景颜色
1. background-image:url()  图片大小没有标签大，会水平和垂直方向平铺
2. background-repeat
    1. repeat  默认，在水平和垂直方向平铺
    2. no-repeat  在水平和垂直方向都不平铺
    3. repeat-x  在水平方向上平铺
    4. repeat-y  在垂直方向上平铺
    + 在实际应用中可以使用repeat属性使得小图变大图，降低数据大小
3. background-position 背景图片位置
    1. 具体的方位名词
        1. 水平方向：left center right
        2. 垂直方向：top bottom center
    2. 具体的像素     
        100px,200px  具体的像素可以接收负数
4. background-attachment 关联方式
    1. scroll 默认值，会随着滚动条的滚动而滚动
    2. fixed  不会随着滚动条的滚动而滚动
        
## 3.背景属性缩写
background:背景颜色 背景图片 平铺方式 关联方式 定位方式
+ 这些属性任何一个都可以被省略        

## 4.背景图片与插入图片的区别
1. 背景图片不占位置，插入图片占位置
2. 背景图片有定位属性，插入图片没有定位属性
3. 插入图片比背景图片语义强，所有在企业开发中若需要被搜索引擎搜索，推荐使用插入图片。