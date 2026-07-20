# CSS Beginner Cheat Sheet

This cheat sheet contains the most commonly used CSS properties for beginner web developers.

---

# 1. Text Properties

| Property | Common Values | Description | Used On |
|----------|---------------|-------------|---------|
| color | red, blue, green, black, white, gray | Changes the text color | All text elements |
| text-align | left, center, right, justify | Aligns text horizontally | Headings, paragraphs, div |
| text-decoration | none, underline, overline, line-through | Adds or removes text decoration | Links, headings, paragraphs |
| text-transform | uppercase, lowercase, capitalize | Changes letter case | Text |
| text-indent | 20px, 40px | Indents the first line | Paragraphs |
| line-height | 1.5, 2, 30px | Controls spacing between lines | Paragraphs |
| letter-spacing | 1px, 2px, 5px | Space between letters | Text |
| word-spacing | 2px, 5px | Space between words | Text |
| white-space | normal, nowrap, pre | Controls text wrapping | Text |
| text-shadow | 2px 2px gray | Adds a shadow to text | Headings |

---

# 2. Font Properties

| Property | Common Values | Description | Used On |
|----------|---------------|-------------|---------|
| font-family | Arial, Verdana, Georgia, Times New Roman, Courier New | Changes font style | Text |
| font-size | 12px, 16px, 20px, 24px, 2rem | Changes font size | Text |
| font-weight | normal, bold, lighter, 100-900 | Changes text thickness | Text |
| font-style | normal, italic, oblique | Makes text italic | Text |
| font-variant | normal, small-caps | Small capital letters | Text |

---

# 3. Background Properties

| Property | Common Values | Description | Used On |
|----------|---------------|-------------|---------|
| background | red, #fff, url(image.jpg) | Shorthand background property | Any element |
| background-color | red, blue, yellow | Background color | Any element |
| background-image | url(image.jpg) | Background image | Any element |
| background-repeat | repeat, no-repeat, repeat-x, repeat-y | Repeats image | Any element |
| background-position | center, left, right, top, bottom | Positions image | Any element |
| background-size | cover, contain, 100%, auto | Image size | Any element |
| background-attachment | scroll, fixed | Background scroll behavior | Body |

---

# 4. Border Properties

| Property | Common Values | Description | Used On |
|----------|---------------|-------------|---------|
| border | 2px solid black | Complete border | Any element |
| border-width | 1px, 2px, 5px | Border thickness | Any element |
| border-style | solid, dashed, dotted, double, groove, ridge, inset, outset, none | Border appearance | Any element |
| border-color | red, blue, green | Border color | Any element |
| border-radius | 5px, 10px, 50% | Rounded corners | Buttons, images, cards |

---

# 5. Margin Properties

| Property | Common Values | Description | Used On |
|----------|---------------|-------------|---------|
| margin | 20px | Outside spacing | Any element |
| margin-top | 20px | Top margin | Any element |
| margin-right | 20px | Right margin | Any element |
| margin-bottom | 20px | Bottom margin | Any element |
| margin-left | 20px | Left margin | Any element |
| margin-auto | auto | Centers block elements | Containers |

---

# 6. Padding Properties

| Property | Common Values | Description | Used On |
|----------|---------------|-------------|---------|
| padding | 20px | Inside spacing | Any element |
| padding-top | 20px | Top padding | Any element |
| padding-right | 20px | Right padding | Any element |
| padding-bottom | 20px | Bottom padding | Any element |
| padding-left | 20px | Left padding | Any element |

---

# 7. Size Properties

| Property | Common Values | Description | Used On |
|----------|---------------|-------------|---------|
| width | 100px, 100%, auto | Element width | Any element |
| height | 200px, auto | Element height | Any element |
| max-width | 1200px, 100% | Maximum width | Images, containers |
| min-width | 200px | Minimum width | Containers |
| max-height | 500px | Maximum height | Images |
| min-height | 200px | Minimum height | Containers |

---

# 8. Display Properties

| Property | Common Values | Description | Used On |
|----------|---------------|-------------|---------|
| display | block, inline, inline-block, flex, grid, none | Controls display behavior | Any element |
| visibility | visible, hidden | Shows or hides while keeping space | Any element |
| overflow | visible, hidden, auto, scroll | Controls overflowing content | Containers |

---

# 9. Position Properties

| Property | Common Values | Description | Used On |
|----------|---------------|-------------|---------|
| position | static, relative, absolute, fixed, sticky | Positioning method | Any element |
| top | 10px | Distance from top | Positioned elements |
| right | 10px | Distance from right | Positioned elements |
| bottom | 10px | Distance from bottom | Positioned elements |
| left | 10px | Distance from left | Positioned elements |
| z-index | 1, 100, 999 | Stack order | Positioned elements |

---

# 10. Flexbox (Preview)

| Property | Common Values | Description |
|----------|---------------|-------------|
| display | flex | Enables Flexbox |
| flex-direction | row, column | Direction of items |
| justify-content | center, space-between, space-around, flex-start, flex-end | Horizontal alignment |
| align-items | center, flex-start, flex-end, stretch | Vertical alignment |
| gap | 10px, 20px | Space between items |

---

# 11. List Properties

| Property | Common Values | Description |
|----------|---------------|-------------|
| list-style-type | disc, circle, square, decimal, none | Bullet style |
| list-style-position | inside, outside | Bullet position |
| list-style-image | url(image.png) | Custom bullet image |

---

# 12. Table Properties

| Property | Common Values | Description |
|----------|---------------|-------------|
| border-collapse | collapse, separate | Merges table borders |
| border-spacing | 5px, 10px | Space between cells |
| empty-cells | show, hide | Displays empty cells |
| caption-side | top, bottom | Caption position |

---

# 13. Cursor Properties

| Property | Common Values | Description |
|----------|---------------|-------------|
| cursor | pointer, text, wait, help, move, crosshair, not-allowed | Mouse cursor appearance |

---

# 14. Opacity

| Property | Common Values | Description |
|----------|---------------|-------------|
| opacity | 0, 0.25, 0.5, 0.75, 1 | Controls transparency |

---

# 15. Common CSS Units

| Unit | Meaning | Example |
|------|---------|---------|
| px | Pixels | width: 300px |
| % | Percentage | width: 100% |
| em | Relative to parent font size | font-size: 2em |
| rem | Relative to root font size | font-size: 1.5rem |
| vw | Viewport Width | width: 50vw |
| vh | Viewport Height | height: 100vh |
| auto | Browser calculates automatically | margin: auto |

---

# 16. Common Color Formats

### Named Colors

```
red
blue
green
black
white
gray
orange
yellow
purple
pink
brown
```

### HEX

```css
#FF0000
#0000FF
#00FF00
#000000
#FFFFFF
```

### RGB

```css
rgb(255,0,0)

rgb(0,255,0)

rgb(0,0,255)
```

### RGBA

```css
rgba(255,0,0,0.5)
```

---

# Beginner's Most Used CSS Properties

These are the properties you'll use in almost every webpage:

- color
- background-color
- font-family
- font-size
- font-weight
- text-align
- width
- height
- margin
- padding
- border
- border-radius
- display
- position
- overflow
- cursor
- opacity

Learning these properties first will allow you to build clean and attractive webpages before moving on to more advanced CSS topics.