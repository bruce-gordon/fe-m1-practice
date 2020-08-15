#Images in HTML (Chapter 5)

1.  In an image element, why is the `alt` attribute important?

`alt` contains text that describes the image.  This text can be read aloud by tools that assist visually impaired users, allowing them to know what is happening in the images on the site.

2.  What determines if an image element is inline or block?

The placement of the image tag within the rest of the code will determine if it is block or inline.  If placed before a <p> tag, for example, it will be a block above the paragraph.  

If the <img> is placed within the text, between two <p> tags, then the image will be inline with the text of the paragraph.

3.  What are the benefits of `jpg` or `png` image file formats?

*jpg* is best when images have multiple colors or complex color variants with many shades/pixels.
*png* is better when an image is FLAT, having large fields of a solid color or only 1-2 total colors.  Simple color fields without variations or shades.

#Images in CSS (Chapter 16)

1.  What is the benefit of specifying the height and width of images in CSS compared to specifying in the HTML?

You can "pre-set" certain sizes and give them names (small, med, large) in CSS, and then quickly apply those size names to the images in HTML so that you don't have to manually enter specific pixel sizes each time you add another <img>.

2.  What is an image sprite, and why is it useful?

A sprite is a single image that is used for multiple parts of an interface.  Because it is reused, the browser only needs to request that image once instead of requesting multiple images.
