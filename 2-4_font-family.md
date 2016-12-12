# 字型

而增強網站的外觀最有效率的方式就是改變自形

在CSS中，改變字型要使用`font-family`屬性

```
h1 {
  font-family: Georgia, serif;
}
```

在上述的例子中，`h1`選擇器的屬性`font-family`被設值為`Georgia`，

然後`serif`被設為備用字型，

在瀏覽氣未支援第一種字型的情況下

備用字型會被拿來使用

##說明

1. 名為The Mystwood Publishers 網站能被更有設計感的字型改善

在`main.css`中，在`h1`選擇器中

在`{ }`中，添加：

`font-family: Palatino, 'Palatino Linotype', serif;`

執行後注意"Mystwood Publishers Ltd"的改變

現在的字型變成`Palatino`了。
