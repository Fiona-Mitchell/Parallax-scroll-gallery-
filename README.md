# Parallax-scroll-gallery-
Different approach to  parallax background &amp; image gallery

I used 
<img width="1046" alt="Screen Shot 2020-07-03 at 19 04 57" src="https://user-images.githubusercontent.com/47756305/86490685-28f6e280-bd60-11ea-9187-b8af3473df20.png">

Here is how I created this very simple parallax effect:
```
parallax {
  background-image: url(../images/mountain-background.jpg);
  height: 100%;
  background-attachment: fixed;
  background-position: center;
  background-repeat: repeat-y;
  background-size: cover;
}

.container-index {
padding: 0;
position: relative;
background-color: #ccdbd8;
}

.column-index {
  flex: 25%;
  max-width: 30%;
  padding: 0 4px;
}

.column-index img {
  margin-top: 8px;
  vertical-align: middle;
  width: 100%;
}

.row-index {
  display: flex;
  flex-wrap: wrap;
  padding: 0 20px;
  justify-content: center;
}
```
