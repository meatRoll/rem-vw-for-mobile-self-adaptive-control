# 基于rem与vw的移动端自适应解决方案

采用`rem`和`vw`结合的方案，能够避免单独使用`rem`时需要绑定`window`的`resize`等事件，也能够避免单独使用`vw`或`vh`这种视口单位时，无法限定最大最小值的尴尬。

文件基于`sass`编写，如果不想用`sass`，可安装`webpack`的`px2rem-loader`进行`rem`的转换。

> 这个方案是[华仔](https://github.com/web-Wind)在掘金小册上面发现的，在这里整理下来防止遗忘。
