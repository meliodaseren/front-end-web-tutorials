
### Pixels

You've probably noticed the unit of [pixels](https://en.wikipedia.org/wiki/Pixel), or `px`, used in websites. Pixels are used to size content to exact dimensions. For example, if you want a div to be exactly 500 pixels wide and 100 pixels tall, then the unit of `px` can be used. Pixels, however, are fixed, [hard coded](https://www.google.com/search?q=hard+coding) values. When a screen size changes (like switching from landscape to portrait view on a phone), elements sized with pixels can appear too small, overflow the screen, or become completely illegible.

### Em

Incorporating relative sizing starts by using units other than pixels. One unit of measurement you can use in CSS to create relatively-sized content is the em, written as `em` in CSS.

Historically, the em represented the width of a capital letter M in the typeface and size being used. That is no longer the case.

Today, the em represents the size of the base font being used. For example, if the base font of a browser is 16 pixels (which is normally the default size of text in a browser), then 1 em is equal to 16 pixels. 2 ems would equal 32 pixels, and so on.


### Rem

The second relative unit of measurement in CSS is the rem, coded as `rem`.

Rem stands for root em. It acts similar to em, but instead of checking parent elements to size font, it checks the root element. The root element is the `<html>` tag.

Most browsers set the font size of `<html>` to 16 pixels, so by default rem measurements will be compared to that value. To set a different font size for the root element, you can add a CSS rule.

---

## Review

* Content on a website can be sized relative to other elements on the page using *relative measurements*.
* The unit of `em` sizes font relative to the font size of a parent element.
* The unit of `rem` sizes font relative to the font size of a root element. That root element is the `<html>` element.
* Percentages are commonly used to size box-model features, like the width, height, borders, padding, or margin of an element.
* When percentages are used to size width and height, child elements will be sized relative to the dimensions of their parent (remember that parent dimensions must first be set).
* Percentages can be used to set padding and margin. Horizontal and vertical padding and margin are set relative to the width of a parent element.
* The minimum and maximum width of elements can be set using `min-width` and `max-width`.
* The minimum and maximum height of elements can be set using `min-height` and `max-height`.
* When the height of an image or video is set, then its width can be set to `auto` so that the media scales proportionally. Reversing these two properties and values will also achieve the same result.
* A background image of an HTML element will scale proportionally when its `background-size` property is set to `cover`.

Relative units of measurement are a first step towards incorporating responsive design in a website. When combined with more advanced responsive techniques, you can create a seamless user experience regardless of a device's screen size.
