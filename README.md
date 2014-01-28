Responsive Email Template
=========================

Used for creating easy responsive email templates.

## Steps
  1. Create a new html file for your email
  2. Copy the "begin.html" contents into your file
  3. Copy the contents of the layout you want. E.g: if you want a 2 column layout, copy the contents of 2-column.html
  4. Look in your code for `<!-- Put Content Here -->` and replace with your email content.
      * For Images, copy "image.html" into your code where `<!-- Put Content Here -->` is located
  5. Once the layout has been achieved, copy the "end.html" contents into your file.
  6. Add styles as necessary to achieve the look you want. This will take time and adjustments, but shouldn't be too tough.


## Tips

* Use `<br>` tags for vertical spacing rather than padding or margin whenever possible. Padding and margin are a bit buggy on some email clients with tables and block level elements.
* Avoid semantic tags like `<h1> - <h6>, <p>, <em>`, etc. These tend to render a bit odd in some email clients when dealing with padding, margins, and line height. For instance, h1 tags are stripped in some email clients, and in microsoft web mail they are automatically given microsoft branded styles. Instead, use `<span>` tags with inline styles on all text.
