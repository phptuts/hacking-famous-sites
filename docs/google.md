# Hacking Google

To get start with the hacking / google developer tools go [tools](google.md).

## Changing the background

```css
background-color: blue;
```

## Changing to a custom color

```css
background-color: rgb(230, 0, 230);
```

## Background Image

```css
background-image: url(https://www.goodfreephotos.com/cache/other-photos/backgrounds/blue-watercolor-background_800.jpg?cached=1522546278);
```

## Background Image Size

```css
background-image: url(https://www.goodfreephotos.com/cache/other-photos/backgrounds/blue-watercolor-background_800.jpg?cached=1522546278);
background-size: 100px;
```

## Background Image No Repeat

```css
background-image: url(https://www.goodfreephotos.com/cache/other-photos/backgrounds/blue-watercolor-background_800.jpg?cached=1522546278);
background-repeat: no-repeat;
background-repeat: repeat-x;
background-repeat: repeat-y;
```

## Backgroud Image Cover

```css
background-image: url(https://www.goodfreephotos.com/cache/other-photos/backgrounds/blue-watercolor-background_800.jpg?cached=1522546278);
background-size: cover;
```

## Multiple Background Images

```css
background-image: url(https://www.goodfreephotos.com/cache/other-photos/backgrounds/blue-watercolor-background_800.jpg?cached=1522546278),
  url(https://the-public-domain-review.imgix.net/blog/2020/zoom-backgrounds/zoom-batch-1-banner.jpg?fit=max&w=1200&h=850);
background-size: 100px 100px;
background-repeat: repeat-x, repeat;
background-repeat: repeat-y, repeat-x;
```

## Blend Image with Color

```css
background-color: #3ab1cc;
background-blend-mode: luminosity;
background-image: url(https://www.goodfreephotos.com/cache/other-photos/backgrounds/blue-watercolor-background_800.jpg?cached=1522546278);
background-size: cover;
```

## Blend Image with Another Image

```css
background-image: url(https://www.goodfreephotos.com/cache/other-photos/backgrounds/blue-watercolor-background_800.jpg?cached=1522546278),
  url(https://the-public-domain-review.imgix.net/blog/2020/zoom-backgrounds/zoom-batch-1-banner.jpg?fit=max&w=1200&h=850);
background-blend-mode: exclusion;
background-size: cover;
```

## Making the page the rotate

```css
transform: rotate(72deg);
```

## Making the page rotate along an axis

```css
transform: rotateX(0deg);
transform: rotateY(0deg);
transform: rotateZ(0deg);
```

## Making Scalling a web page

```css
transform: scale(1.5);
```

## Skewing the webpage

```css
transform: skewX(100deg);
```

## Using Clip Path

### Circle

```css
clip-path: circle(81px);
```

### Ellipse

```css
clip-path: ellipse(234px 64px at 44% 27%);
```

## Mouse Cursors

```css
cursor: nesw-resize;
```

## Mouse Cursor Image

```css
cursor: url(https://s3-us-west-2.amazonaws.com/s.cdpn.io/9632/heart.png),
  pointer;
```

## Resources

- [Background Css](https://www.w3schools.com/cssref/css3_pr_background.asp)
- [Transform 2D](https://www.w3schools.com/css/css3_2dtransforms.asp)
- [Transform 3D](https://www.w3schools.com/css/css3_3dtransforms.asp)
- [Mouse Curosors](https://www.w3schools.com/cssref/pr_class_cursor.asp)
- [Clip Path](https://developer.mozilla.org/en-US/docs/Web/CSS/clip-path)
- [Image Cursors](https://stackoverflow.com/questions/18551277/using-external-images-for-css-custom-cursors)
