# web字体和图标
font-family设置字体
font-family:"微软雅黑"
## 什么是web字体
用来解决用户电脑没有安装相应字体，强制让用户下载该字体
使用@font-face规则，制作一个新字体
```
@font-face{
    font-family:"good-family",
    src:url("good-family的链接")
}
```

web字体在网页中并不常见，但是为web图标带来了新契机
因为图标不像字体，它需要的数量不多，代码量很小