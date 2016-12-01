# 連結樣式表

看看這個網頁瀏覽器。技術上來說，這就跟先前練習的例子相仿。

它也包含了完全一樣的HTML元素和內容。

但少了什麼？
這個先前使用設計網站的CSS居然沒有被連結！

`<link>`連結CSS檔到HTML檔，所以CSS的效果才會發生作用。

以下是關於`link`的範例

`<link rel="stylesheet" type="text/css" href="main.css"/>`

關於`link`

1. `link`有三種屬性：

    -`rel`：指定現在的檔案和將被連結檔案的關係，在此例中，`rel`的屬性是stylesheet。
    
    -`type`：指哪一種檔案被連結過去。
    
    -`href`：提供檔案的URL方便連過去。
    
    
 2. 就像`<img>`一樣，`<link>`也是self-closing，他不需要closing tag。
 
 3. 在上述的範例，main.css是外部的樣式表。
 
    使用外部樣式表是目前最受歡迎的方式。
    
    把CSS寫在行內也是另外一種方法。
    
##說明

1. 讓我們使用`<link>`連結`index.html和main.css

在index.html的`head`裡面，插入`<link>`連結`index.html`和`main.css`

使用上述的片段程式碼作為提示。

點擊Run並注意在瀏覽器中的效果：

1. `main.css`現在已連結到`index.html`

2. 現在main.css的CSS已經套用效果到`index.html`的HTML了。
