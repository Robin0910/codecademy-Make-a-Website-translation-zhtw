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

在CSS中，class選擇器可以以`.`來識別。後跟類名，

如下所示：

```
.header {
  color：#ffffff;
}
```

這段code結果讓帶有`class="header"`且為div的子元素，將具有`#ffffff`（白色）的字體顏色。

在下面，我們將使用CSS class選擇器來一次為多個HTML元素設置樣式。

1. 網站時常使用不只一個字型

在`index.html`中，`h2`和`p`包含在具有`class="hero"`的`div`中。

在`main.css`中，添加.hero類選擇器的屬性，將font-family更改為“Trebuchet MS”，使用Helvetica和sans-serif後備。您可以使用以下代碼作為指南：

。英雄 {
  font-family：'Trebuchet MS'，Helvetica，sans-serif;
}}

重要信息：在main.css中，使用.hero選擇器可以看到兩個屬性，padding和margin。我們將在單元III，CSS邊界和間距中介紹這些。

單擊運行以在Web瀏覽器中查看您的更改。

注意如何帶有類英雄的div的子元素現在出現在Trebuchet MS字體中。
