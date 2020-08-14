#Forms in HTML

1.  If you're using an input element in a form, what attribute controls the behavior of that input?

The *type* attribute determines the behavior of the input.  This could be "text", or "input", etc.

2.  What element is used to create a dropdown list?

A dropdown list is created with a `<select>` element.  It will contain (nest) two more more `<option>` elements, the choices for the dropdown.

3.  If you're using an input element to send form data to a server, what should the `type` attribute be set to?

Use *type="submit"* to use a submit button that will send data to a server.  The text on the submit button can be changed to anything using the *value* attribute.

4.  What element is used to group similar form items together?

similar form items can be grouped using the `<fieldset>` element.  Within the fieldset, there is a label placed within `<legend>` tags.  Each input field will also have a `<label>`.

#Boxes and layout in CSS

1.  Describe the differences between border, margin, and padding.

* Border - The limits of a given box.  Every box has one, even if it is not visible.
* Margin - The margin sits outside the edge of a border.  It can surround a border.
* Padding - The space between a border and the content inside that border.

2.  For a CSS rule `padding: 1px 2px 5px 10px`, what sides of the content box does each pixel value correspond to?

* 1px - top
* 2px - right
* 5px - bottom
* 10px - left

3.  Describe the difference between block-level and inline elements.

Block-level elements will stack vertically and will be separated from surrounding text.  

Inline elements will flow horizontally and will be in the same line as the surrounding text.

4.  What is the role of fixed positioning, and why is z-index important in the scenario of using fixed positioning?

A *fixed* element will stay in the same position no matter what the user does.  Scrolling up or down will not move that element.  It will ignore other elements on the page and not affect their position.

5.  What is the difference between a fixed and liquid layout?

* Fixed - Elements do NOT change size as the browser window is resized.  They are fixed to an exact size.  Measurements are typically given in Pixels.
* Liquid - Elements and designs either stretch or contract as the window is reshaped.  The sizes are dynamic and responsive.  
