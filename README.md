# image-playground
Image -Processing in Python

The Python Pillow library is a fork of an older library called PIL. PIL stands for Python Imaging Library, and it’s the original library that enabled Python to deal with images. PIL was discontinued in 2011 and only supports Python 2. To use its developers’ own description, Pillow is the friendly PIL fork that kept the library alive and includes support for Python 3.

There’s more than one module in Python to deal with images and perform image processing. If you want to deal with images directly by manipulating their pixels, then you can use NumPy and SciPy. Other popular libraries for image processing are OpenCV, scikit-image, and Mahotas.

My Pngs
![bulbasaur](https://github.com/satoshimasterbilly/image-playground/assets/70892776/d2c7ead1-26b3-4f05-bbf1-eb574ddc1cf3)


![charmander](https://github.com/satoshimasterbilly/image-playground/assets/70892776/9440c330-e4e2-4928-8ccb-8e99062582a8)


![pikachu](https://github.com/satoshimasterbilly/image-playground/assets/70892776/a509f56a-d3fe-4829-85b5-2527b1f6b4be)


![squirtle](https://github.com/satoshimasterbilly/image-playground/assets/70892776/d1beb64c-f5d6-41ac-a5e7-46c16e969c5b)

However, Pillow remains an important tool for dealing with images. It provides image processing features that are similar to ones found in image processing software such as Photoshop. Pillow is often the preferred option for high-level image processing tasks that don’t require more advanced image processing expertise. It’s also often used for exploratory work when dealing with images.

Pillow also has the advantage of being widely used by the Python community, and it doesn’t have the same steep learning curve as some of the other image processing libraries



Code:
```
from PIL import Image, ImageFilter

img = Image.open('./astro.jpg')
img.thumbnail((400, 400))
img.save('thumbnail.jpg')


print(img.size)
```
<meta charset=“utf-8”>
<meta name=“viewport” content=“width=device-width”>
<link rel=“stylesheet” href="https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.css“>
<link href=”https://fonts.googleapis.com/css?family=Raleway|Rubik:400" rel=“stylesheet”>
<link rel=“stylesheet” type=“text/css” href=“main.css”>
<title>Header and Footer</title>


<header>
<img src="https://i.imgur.com/GCNudvW.jpg" alt=“Global Travel”>
<h1>Global Travel Blog</h1>
<h2>Mother Earth</h2>
</header>
<footer>
<div class=“wrapper”>
<small>©2019 <strong>Awesome Company</strong>, All Rights Reserved</small>
<nav class=“footer-nav”>
<a href="#">Back to Top</a>
<a href="#">Terms of Use</a>
<a href="#">Privacy</a>
</nav>
</div>
</footer>


header h1 { // selecting header and h1 tags
font-family: ‘Rubik’, sans-serif; // used fonts, if not available first one will use next one
font-size: 1.25rem; // font size 1rem = 16px => font-size=16*1.25
color: #555; // color
margin: .67rem 0; // margin around the element
}

footer {
background: url(’http://i.imgur.com/f4jGhSF.png') repeat center; // we can set the footer background with CSS as well
display: table; // element will behave like a table element
width: 100vw; // 100% of the viewport width
height: 8rem; // 8*16px
text-align: center; // text align
padding: 1rem; // space around elements
font-family: ‘Arial’, sans-serif; // used fonts
font-size: .875rem; // font size
}
