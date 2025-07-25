# Google Web Design Clone

https://github.com/user-attachments/assets/5df5cef2-58ab-4fd9-bcee-0400717279c5

# Key Takeaways
- I wrote this project in about 1 hour with a lot of Googling :) I didn't use AI for this one. Then, I realized that sometimes memorization of the fundamentals and key concepts is still valuable because it will save me so much time Googling and finding the resources that I truly understand, while I can spend time focusing on the styling of the website.
- Important concepts I think I should learn by heart are: centering the whole webpage, pushing a `div` to the bottom, and styling `input` and `button` components, like using box shadow
- If you Google stuff, make sure to check that the solution you're using from StackOverflow or other sources follows the latest or modern syntax. When in doubt, just check MDN documentation.
## Center Webpage
There are different ways to center a webpage. For this project, I use flexbox (flexible box layout), which is a layout method to **arrange items in rows or columns in a 1D layout**. I used the following properties to center the webpage: 
- `display: flex`: defines a flex container (parent)
- `flex-direction: column`: makes the elements stacked vertically.
- `justify-content: center`: defines the alignment along the main axis. This will automatically assign space from the left and right of the page so that all elements are centered horizontally.
- `align-items`: defines how the items are laid out along the cross (vertical) axis. 
- `text-align: center`: sets the **inline-level** content to be centered horizontally.
- `height: 100%`: creates a responsive height for different screen sizes so that when the parent container's height changes, the element's height will automatically adjust to remain 100% of its parent.

## Margin vs. Padding
A box has 4 different components:
- Content: what's inside the box (like the content inside a `div` element)
- **Padding**: the inner space between the content and the border of the box
- Border: the perimeter of the box (can be visible or invisible)
- **Margin**: the outer space surrounding the box.

The key difference between padding and margin is that the former defines the space within a box, and the latter controls the whitespace outside the box. I used margin to define the space between the items and the edges of the screen, and the space among items.

## Other Styling Techniques
- `line-height: 24px`: sets the height of a line box, which controls the vertical distance between lines of text within an element.
- `box-shadow: <length> | <length> | <length> | <color>`: the length property defines the offset length of the shadow (2 <= length <= 4). The first two lengths are the offsets along the x and y axes, while the third is the `blur-radius`, defining the blur's size.
- `input[type="text"]:focus`: defines the style of the input field when we click on it
- `position: absolute`: sets how an element is positioned in a document. The element is positioned relative to the nearest positioned ancestor 
- `list-style-type: none`: remove the bullet points of the list items
- `display:inline-block`: all elements will be flowed to be on a single line, or I can use `inline-flex`, which is the modern syntax.

## Useful Resources
[1] https://css-tricks.com/snippets/css/a-guide-to-flexbox/#aa-flexbox-properties

[2] https://webflow.com/blog/padding-vs-margin

[3] https://developer.mozilla.org/en-US/docs/Web/CSS/line-height

[4] https://developer.mozilla.org/en-US/docs/Web/CSS/line-height

[5] https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow

[6] https://developer.mozilla.org/en-US/docs/Web/CSS/display
