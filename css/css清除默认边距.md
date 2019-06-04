# 一、清除默认边距 (外边距和内边距)
## 1. 为什么要清除
在企业开发中为了更好的控制盒子的宽度和高度，以及计算盒子的宽高，编写代码之前第一件事情就是清空默认的边距。

## 2. 如何清除
1. 通配符选择器会遍历当亲啊界面的所有元素，性能低
     ```
     * {
         margin: 0;
         padding: 0;
      }
     ``` 

2. 使用如下这段代码
    ```
    body,div,dl,dt,dd,ul,ol,li,h1,h2,h3,h4,h5,h6,pre,code,form,fieldset,legend,input,textarea,p,blockquote,th,td{margin:0;padding:0}
    ```
   网址: 
   + https://yuilibrary.com/yui/docs/cssreset/
   + http://yui.yahooapis.com/3.18.1/build/cssreset/cssreset-min.css
   