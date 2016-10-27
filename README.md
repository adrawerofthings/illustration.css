# illustration.css

Front-end design patterns for adding illustrations onto websites. A work in progress.

## persistent ornamentation

Given that many users dislike large, clunky, persistent navigation bars, why not consider replacing it with some **persistent ornamentation**? As with persistent navigation, the trick is to make sure that it doesn't get in the way. I like to use non-square images with transparent "holes" – and to keep it small, especially on mobile.

For example, see the plants at the bottom of [my personal blog](http://notebook.hongkonggong.com):

![Screenshot from notebook.hongkonggong.com](screenshots/persistent-ornamentation.gif)

Needless to say, if a website already has a persistent navigation bar, there probably isn't any room left for further ornamentation.

### css properties

```
position: fixed;
width: 100%;
background-image: url("../image.ext");
background-position: bottom center;
background-repeat: repeat-x;
bottom: 0;
```

N.B. `height` varies depending on the image and screen size.