# 添加添加Div區塊

現在我們已經知道HTML元素中的巢狀與父子關係

讓我們來看看其他應用在真正網站中的觀念。

Div區塊包圍在其他元素的外面來分配頁面。

這一堆被包圍的元素可以彼此獨立組織、移動和裝飾。

`div`常常被使用在`Class`的屬性

以下範例：

```
<div class="main">
 ...
</div>
```

注意：...代表省略的程式碼

在下面，我們將會用`div`來配置整個網頁

## 說明

1. 首先，我們會用`div`與其中的class屬性`container`在`body`...`</body>之中

```
<div class="container">
...
</div>
```

所有你之前練習的HTML元素都會在`<div class="container">`之中

1. the navbar h2
2. the navbar ul
3. the company heading h1
4. the tagline h3
5. the paragraph
6. the video

確定`/div`至少要在`</video>`下方

執行後注意HTML元素已被轉換於瀏覽器中。

2. navbar h2 and ul 在其他的`div`之中並給她class屬性`nav`

你可以使用以下的程式碼當作提示指引：

```
<div class="nav">
  <h2>Ollie</h2>
  <ul>
    <li>sign up</li>
    <li>search bikes</li>
    <li>reserve a bike</li>
    <li>about us</li>
  </ul>
</div>
```

執行。

注意navbar(導航欄)有了黃色的背景了

3.  最後，把`h1`，`h3` 、`p`和`video`包進第三個有著class屬性`main`的`div`

可以隨意使用以下程式碼當作指引：

```
<div class="main">
  <h1>Ollie Bike Sharing</h1>
  <h3>Share Your Pedals with the World.</h3>
  <p>Easy-to-use, free bike sharing now available in 27 cities.</p>
  <video width="320px" height="240" controls>
    <source src="https://s3.amazonaws.com/codecademy-content/projects/make-a-website/lesson-1/ollie.mp4" type="video/mp4">
  </video>
</div>
```

最後總共有三個`div`在這個頁面：

屬性`container`的`div`包含`nav`和`main`屬性的`div`
執行

`main.css`檔有中的屬性`container`、`nav`和`main`的`div`改變了葉面中的元素

如果你很好奇的話，可以探究`main.css`

這在之後可成會提到





