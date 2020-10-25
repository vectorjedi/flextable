# Responsive Flex Table without Javascript

As the title already suggests, this is just a table built with Flexbox & pure CSS, no JavaScript at all.

## Features
This table makes use of the CSS ```scroll-snap-*``` and CSS Flexbox properties. If you want to learn more about these I'd suggest the links in **[Acknowledgments](#acknowledgments)**.
It also is operable with touch and keyboard: you can swipe the table columns horizontally, and tab'n'enter through the header anchors to jumpscroll smoothly to the next column.
Since this table uses anchor tags, you can even deeplink to the table column headers.

<p class="codepen" data-height="265" data-theme-id="dark" data-default-tab="css,result" data-user="vectorjedi" data-slug-hash="LYZWNXG" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Responsive CSS only Flex Table ">
  <span>See the Pen <a href="https://codepen.io/vectorjedi/pen/LYZWNXG">
  Responsive CSS only Flex Table </a> by Mo Beumers (<a href="https://codepen.io/vectorjedi">@vectorjedi</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

## Getting Started

This example is kept simple and agnosic. Like in the ol` days: pure HTML, pure CSS, no fuzz.
If you are going to use it, you might want to fit it to your needs by

- restructuring the CSS into SCSS or LESS
- replacing some CSS classes with utility classes of your favorite CSS framework
- refactoring the markup into the template language of your choice
- make a dynamic and/or reactive component for your desired JS framework out of it.

### Prerequisites

A few things you might consider when using this:

* Since the table has some elements using ```posision: sticky```, in the context it is placed in, it cannot take into account any ```position: absolute``` for offsets for example.
* The table width is relative to the page width on the mobile breakpoint. If you need gutter left and right, set the ```--padding``` variable.

### Using

The table has two CSS variables you can utilize:

```css
--padding: 30px; /* absolute padding to sides */
--tablecolumns: 3; /* the number of table columns minus left column
```

## Contributing

No need for contribution, just fork this repo or copy/download the code and have fun.
This repo will not be maintained further.

## Authors

- **Mo Beumers** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

- [CSS-TRICKS' awesome elaborate demonstration of scroll-snap](https://css-tricks.com/practical-css-scroll-snapping/)
- Also from [CSS-TRICKS, the best overview of Flexbox to date.](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [W3C Scroll Snap Model](https://www.w3.org/TR/css-scroll-snap-1/#overview)
- [Another great example of what can be achieved with scroll-snap](https://css-tricks.com/css-only-carousel/)
