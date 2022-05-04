# Banner Layout Cheat Sheet

A 3x3 grid for positioning information within a banner.

## Classes:
```css
/* main class */
.banner

/* item spanning */
.grid-col-span-#
.grid-row-span-#

/* item positioning, individual selector */
.grid-item-#-top-left
.grid-item-#-top-middle
.grid-item-#-top-right
.grid-item-#-middle-left
.grid-item-#-middle-middle
.grid-item-#-middle-right
.grid-item-#-bottom-left
.grid-item-#-bottom-middle
.grid-item-#-bottom-right

/* Overlay themes, works on container */
.overlay-theme-glass
.overlay-theme-glass-mucho-glass
.overlay-theme-glass-less-glass

/* Overlay themes, individual selectors */
.grid-item-#-overlay-theme-glass
.grid-item-#-overlay-theme-mucho-glass
.grid-item-#-overlay-theme-less-glass
```

## Creating a new banner

To create a new banner using this banner system, please follow the next steps:

1. Create a new block in Magento, name it, and give it an identifier
2. Add a new Banner on a Row level
3. Add the desired background image
4. Edit the Banner
- Make sure to have Cover selected in the Background Size option
- Add the whatever text you are adding into the Message Text box in the Content section. Each paragraph will result in a grid item, giving the flexibility of moving paragraphs around the iamge.
5. Create a new page and add your new block to it!