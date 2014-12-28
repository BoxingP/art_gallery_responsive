##Responsive Web Page

###Becoming Responsive
```sh
target ÷ context = result
```

###Flexible Grid
####Flexible Font
use <strong style="color:green">em/rem</strong> as unit of font-size
```sh
h1 {
  font-size: 2em;
}
```
####Fluid Grid
  * change <strong>pixel</strong> to <strong style="color:green">percentage</strong>
  * grid system

###Flexible Images
```sh
img {
  max-width: 100%;
}
```

###Media Queries
####Media type
all, screen, print...
```sh
<link rel="stylesheet" href="style.css" media="screen">
```
```sh
@media screen {}
```

####Media query
```sh
@media only screen and (max-width: 640px) {
  img {
    max-width: 100%;
  }
}
```

####Viewpoint
```sh
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```

####Retina
```sh
@media only screen and (-webkit-min-device-pixel-ratio: 2) {}re
```

##Reference
###Readings
[responsive-web-design](http://alistapart.com/article/responsive-web-design)
###Tools
  * [responsive view](http://responsive.is/)
  * [grid generator](http://gridpak.com/)
