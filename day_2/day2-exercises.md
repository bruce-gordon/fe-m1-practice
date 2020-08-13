#HTML lists and links
1.  There are three main types of lists in HTML: ordered, unordered, and definition. What are their differences?

Ordered lists `<ol>` are *numbered*.
Unordered lists `<ul>` have *bullet points* instead of numbers and are in no particular order.
  -Both use list items `<li>`.
Definition lists `<dl>` consist of a list of words or terms and their respective definitions.
  -Terms are listed using a definition term `<dt>`.
  -A <dt> is paired with a `<dd>`, a which contains the defition or description of the term in the <dt> element.

2.  What is the basic structure of an element used to link to another website?

The link element uses the `<a></a>` tag.  Within the tag, start with the `href` attribute followed by the url for the link.  After the URL you also add the text that the user will see on the actual web page.  The href attribute and link URL both exist inside the opening <a> tag.  Example:
`<a href="http://www.google.com">Google</a>`

3.  What attribute should you include in a link to open a new tab when the link is clicked?

Use the `target` attribute with the following format (`target="_blank"`).  Example:
`<a href="http://www.google.com" target="_blank">Google</a>`

4.  How do you link to a specific part of the same page?
Use the `id` attribute to label sections of the page.  For example, a subheading for "more information" could be identified as "more_information" with the `id` attribute.  
`<h2 id="more_information">More information</h2>`
Then later on you can use the `<a>` tag to link to that id.  Inside the <a> tag you code `<a href="#textfromtheid">` followed by the text that will be visible in the link.  Example:
<a href="#more_information">More information</a>

#CSS chapters 10-12
1.  What is the purpose of CSS?

CSS changes how content appears.  It can determine color, size, style, etc.

2.  What does CSS stand for? What does cascading mean in this case?

*Cascading Style Sheets*  Cascading means that the rules we create in CSS have a hierarchy.  Each rule can overrule an earlier line of code.  If we code that the entire page should have black font, but then code that <h2> headings should be green, the headings will be green but all other font will still be black.

3.  What is the basic structure of a CSS rule?

A *selector* followed by a *declaration*.  The declaration, inside of curly braces, consists of a *property:* and a *value;*.

Example:

p {color: green;}

This will change the text inside of any paragraph to green.

*Specificity* also matters.  A more specific rule will override a less specific rule.

4.  How do you link a CSS stylesheet to your HTML document?

<link />, which includes href, type, and rel.

<link href="styles.css" type="text/css" rel="stylesheet" />

5.  When is it useful to use external stylesheets as opposed to using internal CSS?

External stylesheets are useful when creating a site with multiple pages.  This allows all pages on the site to use the same style rules, instead of having to re-code them on each page.  You can also easily change all pages at once if desired.  It also keeps your content code separate from your style code.

6.  Describe what a color hex code is.

A 6-digit code with numbers/letters that specifies a particular color. Preceded by a hashmark. It could look like:

`#ee45e8`

7.  What are the three parts of an HSL color property?

* Hue = color
* Saturation = percent of gray in color
* Lightness = percent of whiteness (0% is black, 100% is pure white)

8.  In the world of typeface, what are the three main categories of fonts? What are the differences between them?

* Serif = extra details and flourish on the ends of letters
* Sans-serif = no extra details, with only straight ends to letters like in arial
* Monospace = all letters have the same width, they take up the same Monospace

9.  When specifying font-size, what are the main three units used?
* Pixels - 16px is default
* Precentages - percent relative to 16 px, which is considered standard (100% = 16px)
* Ems - 1.0 em is equivalent to the width of an "m".  This can be set to smaller or larger than an "m".
