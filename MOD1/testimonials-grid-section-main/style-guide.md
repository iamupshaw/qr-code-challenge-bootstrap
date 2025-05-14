# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

> 💡 These are just the design sizes. Ensure content is responsive and meets WCAG requirements by testing the full range of screen sizes from 320px to large screens.

## Colors

### Primary

- Purple 50: hsl(260, 100%, 95%)
- Purple 300: hsl(264, 82%, 80%)
- Purple 500: hsl(263, 55%, 52%)

### Neutral

- White: hsl(0, 0%, 100%)
- Grey 100: hsl(214, 17%, 92%)
- Grey 200: hsl(0, 0%, 81%)
- Grey 400: hsl(224, 10%, 45%)
- Grey 500: hsl(217, 19%, 35%)
- Dark blue: hsl(219, 29%, 14%)
- Black: hsl(0, 0%, 7%)

## Typography

### Body Copy

- Font size: 13px

### Font

- Family: [Barlow Semi Condensed](https://fonts.google.com/specimen/Barlow+Semi+Condensed)
- Weights: 500, 600

> 💎 [Upgrade to Pro](https://www.frontendmentor.io/pro?ref=style-guide) for design file access to see all design details and get hands-on experience using a professional workflow with tools like Figma.
.parent {
display: grid;
grid-template-columns: repeat(4, 1fr);
grid-template-rows: repeat(3, 1fr);
grid-column-gap: 0px;
grid-row-gap: 0px;
}
.div1 { grid-area: 1 / 1 / 3 / 3; }
.div2 { grid-area: 3 / 1 / 4 / 2; }
.div3 { grid-area: 1 / 3 / 3 / 4; }
.div4 { grid-area: 3 / 2 / 4 / 4; }
.div5 { grid-area: 1 / 4 / 4 / 5; }