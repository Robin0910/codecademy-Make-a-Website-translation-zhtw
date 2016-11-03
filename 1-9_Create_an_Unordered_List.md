#創造無序清單

做得好！有了五種頁面元素，你已經能創造出有趣的網站！

另一個重要的HTML元素是**unordered list**(無序清單)。

在unordered list 裡面的物件參考了序列物件。

每個物件都是圓點狀，不是數字。

舉例：

* 一個清單物件

* 第二個清單物件

* 第三個清單物件

以下是清單的HTML程式碼：

```
<ul>
  <li>A list item</li>
  <li>A second list item</li>
  <li>A third list item</li>
</ul>
```
關於無序清單：

1. `ul`標籤創造了無序清單

2.`li`標籤包含每個清單物件

無序清單可以使用很多方法在網頁中組織內容。

在下方我們將要使用它建構網站的導航欄，常稱作**navbar**

##說明

1. 我們的navbar將要建立在公司標題下方，
 
   所以首先我們需要再`index.html`中按`enter`自`<body>`和`<h1>`空出幾行。

   第一步，我們要用`<h2>`標籤當作導航欄的標題。

   其中的文字是"Ollie"

   `<h2>Ollie</h2>`

   點Run繼續。

2. 在導航欄`h2`的下方創造無序清單。
   
   這個清單件需要有不同頁面供使用者瀏覽
   ```
   <ul>
     <li>sign up</li>
     <li>search bikes</li>
     <li>reserve a bike</li>
     <li>about us</li>
   </ul>
   ```
   在你插入了所有的清單物件後，不要忘記加上關閉`</ul>`標籤
   
   點擊Run在網頁瀏覽器觀看結果   


