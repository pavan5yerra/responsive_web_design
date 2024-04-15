

### Inline Elements:
    >- Inline elements are elements that do not start on a new line and only take up as much width as necessary. Examples of inline elements include <span>, <a>, <strong>, and <em>.

### Block-Level Elements:
    >- Block-level elements, on the other hand, start on a new line and take up the full width available to them. Examples of block-level elements include <div>, <p>, <h1> through <h6>, and <ul>.

### Block Margins on Inline Elements:

 ***When you apply block-level margins (top, bottom, left, right) to an inline element:***

>- Top and Bottom Margins:  The top and bottom margins will push surrounding content away vertically as if the inline element has a      block-like presence. The content below the inline element will be pushed down by the top margin and up by the bottom margin.
>- Left and Right Margins:  Left and right margins won't have any effect on inline elements. Inline elements can't have horizontal margins like block-level elements.

***Example: Let's say you have an inline <span> element with block-level margins applied to it:***

        <span style="margin-top: 20px; margin-bottom: 20px; background-color: yellow;">
        This is an inline element with block margins.
        </span>

### In the above example:

>- The margin-top and margin-bottom will push the surrounding content away, creating space above and below the <span> element.
>- The background color yellow is just to make the inline element visible. Normally, inline elements don't have a visible background or border, but they can have margins.