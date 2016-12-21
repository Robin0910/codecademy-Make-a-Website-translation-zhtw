# CSS選擇器

到目前為止，我們只能使用CSS選擇HTML元素的標籤名稱。

然而，我們可以使用class選擇器來定位目標HTML元素。

參考下面的HTML：

```
<div class =“header”>
  <h2>標題</ h2>
  <p>段落</ p>
</ div>
```

在這裡，`div`是父元素，`h2`和`p`是子元素。

CSS樣式套用於`header`的class選擇器，也會自動套用`h2`和`p`。

再次複習[父元素和子元素](https://github.com/cj10243/codecademy-Make-a-Website-translation-zhtw/blob/master/1-10_Parent_and_Child_Elements.md)。

在CSS中，class選擇器的語法為`.`，其後加上class名稱，

如下所示：

```
.header {
  color：#ffffff;
}
```

這段code結果讓帶有`class="header"`且為div的子元素，將具有`#ffffff`（白色）的字體顏色。

在下面，我們將使用CSS class選擇器來一次為多個HTML元素設置樣式。

## 說明

1. 網站時常使用不只一個字型

在`index.html`中，`h2`和`p`包含在具有`class="hero"`的`div`中。


在`main.css`中，為class選擇器`.hero`添加屬性，

把`font-family`設為`Trebuchet MS`，

記得加上備用字型`Helvetica`、`sans-serif`。

你可以使用以下的code作為指引：

```
hero {
  font-family: 'Trebuchet MS', Helvetica, sans-serif;
}
```

重要：在`main.css`的兩個屬性padding(內距)和margin(外距)，

 are seen with the .hero selector.      

我們會在Boundaries and Spacing提到

點擊執行並在瀏覽器觀看結果。

注意有著`class="hero"`的`div`以`Trebuchet MS`字型顯示
