# 背景圖片

在CSS中，`background-image`屬性讓你為給定的選擇器設置背景圖像，

如下所示。

```
.hero {
  background-image: url("https://s3.amazonaws.com/codecademy-content/projects/make-a-website/lesson-2/bg.jpg");
}
```
上面的CSS語法把位於`https://s3.amazonaws.com/codecademy-content/projects/make-a-website/lesson-2/bg.jpg`的圖像設給class屬性`hero`。

為了調整選擇的背景圖片的大小

如下所示，在下方使用`background-size`

```
.hero {
  background-image: url("https://s3.amazonaws.com/codecademy-content/projects/make-a-website/lesson-2/bg.jpg");
  background-size: cover;
}
```
在此，我們指定了我們想要的圖片完全覆蓋`.hero`類別的元素。

## 說明

1. 讓我們把背景圖片加到 Mystwood Publishing的首頁。

在`main.css`中，找到`.hero`類別選擇器。

使用語法插入背景圖片。

這個是超讚的圖片URL連結供你使用：`https://s3.amazonaws.com/codecademy-content/projects/make-a-website/lesson-2/bg.jpg`

記住，為了使背景圖片正常運作，你需要在屬性值加上`url`和`()`：


`background-image: url("https://s3.amazonaws.com/codecademy-content/projects/make-a-website/lesson-2/bg.jpg");`

然後記得圖片的URL包含`""`。

點擊執行並在瀏覽器中注意背景圖片被賦值給`.hero`的div。

2. 在瀏覽器中，

  //你應該會注意到背景圖片看起來關閉了。
  
  //我們可以使用屬性`background-size`讓圖片看起來更多。
  
  在`main.css`中`.hero`選擇器底下的`background-image`，
  
  添加`background-size: cover;`
  
  點擊執行並注意到瀏覽器中：
  
  更多有著`.hero`的原始圖片可被觀看。
  
 3. 最後，現在背景圖片覆蓋了整個`.hero`的div，
 
  可是其中的黑色字體使`h2`和`p`的可讀性降低。
  
  在`main.css`中，
  
  給`.hero`選擇器的`color`屬性值設為`#ffffff`，
  
  也就是白色的十六進位色碼。
