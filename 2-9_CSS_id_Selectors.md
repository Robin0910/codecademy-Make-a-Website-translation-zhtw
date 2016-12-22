# CSS id 選擇器

現在背景已經變得很不一樣了！

在先前的練習中介紹了裝飾特定類別的HTML元素。

如果在設計網頁時需要一個`p`和其他的`p`不同樣式的HTML元素，要怎麼做？

舉例來說，要讓`a`和網頁中的其他元素不同，

你可以使用HTMLid 屬性：

`<a id="learn-code" href="https://www.codecademy.com">Click here to learn to code!</a>`

接著你可以使用`#`作為id選擇器的標示並定義他的規則。
關於使用id：

1. id只能使用一次，

  因為id分配的元素是獨立的。

2. id比class更特別，
  
  因此如果HTML元素同時使用id和class的話，
  
  id的優先級較高。
  
  在下方我們將會使用id選擇器來為網頁中單一的HTML元素設定不同的樣式。
  
## 說明

1. 在[7.font-siz]("https://github.com/cj10243/codecademy-Make-a-Website-translation-zhtw/blob/master/2-7_font-size.md")中，

  我們放大了`p`的`font-size`。
  
  我們卻又無意增加了網頁底部`© 2016 Mystwood Publisher`的大小
  
  我們可以屬用id來修正這個bug。
  
  在`index.html`中，
  
  找到上述提及的`p`，
  
  把id設為"footer":
  
  `<p id="footer">&copy; Mystwood Publishers Limited</p>`
  
  點及執行繼續。
  
2. 在`main.css`中，加上id選擇器。

  使用`#footer`作為id選擇器。
  
  ```
  #footer {
  }
  ```
  點擊執行繼續。
  
3. 設定`#footer`的`font-size`為`0.75rem`。

  點擊執行觀看瀏覽器的變化：
  
  "footer"段落現在被調為`0.75rem`。
