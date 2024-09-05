# CSS positioning

[CSS-Tricks - Almanic of all CSS items to use](https://css-tricks.com/almanac/)

[position - CSS: Cascading Style Sheets | MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/position)

[Position | CSS-Tricks](https://css-tricks.com/almanac/properties/p/position/)

[W3Schools.com](https://www.w3schools.com/css/css_positioning.asp)

## Introduction

To get a container to use flexbox, you assign it to `display flex`

[Guide to flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

```jsx
.container {
    display: flex;
}
```

You have two axis that you are displaying your content as (see image folder)

### Common Flexbox Patterns: The Layouts of the Land

- **Centering Content**: Like finding the perfect spot for your tent under the stars, centering content is a breeze with Flexbox. Just set `justify-content` and `align-items` to `center`, and watch your content align perfectly within its container.
- **Equal Distribution**: Distributing space in Flexbox is like evenly spacing out tents in an open field. Use `justify-content: space-around` or `space-between` to give your Flex Items equal breathing room, ensuring a harmonious layout.
- **Responsive Columns**: Flexbox shines in creating responsive designs, much like how a campsite adapts to the terrain. By setting `flex-wrap: wrap` on a container, Flex Items flow into a new row when the space becomes too narrow, ensuring your layout remains accessible on any device.
- **Vertical Stacking**: Sometimes, the best way to arrange your camp is in a vertical stack, especially when space is limited. By changing the `flex-direction` to `column`, Flex Items stack on top of each other, creating a neat, orderly layout that scales beautifully.

Justify content and align items is your new best friend (see image folder)

## CSS Grid

see image folder

## Intro

[W3Schools.com](https://www.w3schools.com/CSS/css_grid.asp)

[CSS Grid Layout Guide | CSS-Tricks](https://css-tricks.com/snippets/css/complete-guide-grid/)

### CSS Grid Basics: Columns, Rows, and Gaps

At the core of CSS Grid are three fundamental concepts: **columns**, **rows**, and **gaps**.

- **Columns and Rows**: Picture your webpage as a city block, with columns and rows forming the streets and avenues. CSS Grid enables you to define these pathways, creating a framework for your content to live within. By setting the `display` property to `grid` on a container, you're laying out the grid lines, ready to house your content buildings.
- **Gaps**: No one likes a cramped city. Gaps (or gutters) are the green spaces, the parks between buildings, providing breathing room for your content. With CSS Grid, you can easily set these gaps, ensuring your content is legibly spaced and aesthetically pleasing.
