# Card and SZ Theme Cheat Sheet

## Card initiation
To start a card grid add card and grid classes, at least one general grid class is needed, eg. `grid-col-3` for 3 items per row. No breakpoints needed.

### Card class
| Class | Selector | Info |
|-------|----------|----- |
|`card` |general / individual | initiates a general or individual card |
|`card--marginless-layout` |general / individual | removes margins from img and card borders |
|`card--inverted-layout` |general / individual | inverts image and title, making it from top to bottom img > title > p > button |
|`class` |general / individual | info |

### SZ Themes

| Class  | Info |
|-------|----- |
| `card--sz-minimal-dark`|like the `card` class but in black |
|`card--sz-dark-theme`| purple and black|
|`card--sz-light-theme`| purple and white|

## Grid

| Class | Selector | Range |  Info |
|-------|----------|----- | ----- |
|`grid-col-#` |general / individual| 1 - 8 | specifies ammount of items per row |
|`double-size` |general / individual| N/A | doubles the size of the item according to the general/individual selector's number of items per row |
|`half-size` |general / individual| N/A | same as `double-size` but halfs it |
|`full-row` | individual| N/A | makes the element take 100% of the row |

	Grid Breakpoints

| Class | Selector | Range |  Info |
|-------|----------|----- | ----- |
|`grid-col-#-xs` |general / individual| 1 - 8 | up to 480px |
|`grid-col-#-s` |general / individual| 1 - 8 | up to 768px |
|`grid-col-#-m` |general / individual| 1 - 8 | up to 980px |
|`grid-col-#-l` |general / individual| 1 - 8 | up to 1279px |
|`grid-col-#-xl` |general / individual| 1 - 8 | 1280px + |