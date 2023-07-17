Project Description: This project focuses on advanced CSS techniques to enhance the styling and layout of a web page. It covers various tasks such as image downloading, scrolling behavior, color customization, variable usage, font styling, box-sizing, link styling, section styling, grid styling, navbar customization, and more.
Tasks
Task 0: Let's get some images!

Type: Mandatory

Description: In this task, we need to download 10 high-resolution images from Unsplash that resemble the final product of our project. These images will also be used for a future project on Responsive Design. Additionally, we need to include 3 specific images (2 logos and a favicon) mentioned in the project description.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

Files:

    images/pic-about-01.jpg
    images/pic-work-01.jpg
    images/pic-work-02.jpg
    images/pic-work-03.jpg
    images/pic-article-01.jpg
    images/pic-article-02.jpg
    images/pic-article-03.jpg
    images/pic-person-01.jpg
    images/pic-person-02.jpg
    images/pic-person-03.jpg

Task 1: Effortless transitions when scrolling

Type: Mandatory

Description: When scrolling is triggered on the html element, we want the scroll behavior to be as fluid as possible.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: styles/1-style.css
Task 2: Do you know your color values?

Type: Mandatory

Description: Create specific CSS declarations based on styles/1-style.css:

    Set the foreground color value of the body to #161616.
    Set the foreground color value of all anchor elements to #161616.
    Set the display of all elements with the class visually-hidden to none.
    Set the foreground color of all elements with the class card-category to #D73953.
    Set the foreground color of all elements with the class section-tagline to #D73953.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: styles/2-style.css
Task 3: Reuse and repeat. A programmer's life should be simple with variables

Type: Mandatory

Description: Based on styles/2-style.css:

    Target the root element and define the following custom properties:
        color-primary set to #d73953.
        color-black set to #090909.
        color-white set to #ffffff.
        color-light-grey set to #f3f3f3.
        color-dark-grey set to #353535.
        text-color set to color-black.
    Revisit the section-tagline and card-category declarations and reset their color to color-primary.
    Revisit the body and anchor declarations and reset their color to text-color.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: styles/3-style.css
Task 4: Variables for storing certain font types

Type: Mandatory

Description: Based on styles/3-style.css:

    Target the root element and create 2 custom font-family properties: font-family-base and font-family-title.
        The first choice font should be set to "Helvetica Neue".
        The second choice font should be set to "Helvetica".
        The third choice font should be set to "Arial".
        The last choice font should be set to "sans-serif".
    Set the font-family of the body to font-family-base.
    Create a new declaration targeting all 6 levels of section headings and set their font-family to font-family-title.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: styles/4-style.css
Task 5: Variables for the font size

Type: Mandatory

Description: Based on styles/4-style.css:

    Target the root selector and create the following custom properties:
        font-size-small set to 1.2rem.
        font-size-medium set to 1.6rem.
        font-size-large set to 1.8rem.
        font-size-x-large set to 2.3rem.
        font-size-xx-large set to 4.8rem.
    Set the font size of all fonts in the html element to 62.5% of their normal size.
    Set the font size of fonts in the body to font-size-medium.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: styles/5-style.css
Task 6: Variables for the font-weight

Type: Mandatory

Description: Based on styles/5-style.css:

    Target the root element and create the following custom properties:
        font-weight-regular set to 400.
        font-weight-bold set to 700.
    Set the font weight of fonts in the body to font-weight-regular.
    Set the font weight of fonts in the headings to font-weight-bold.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: styles/6-style.css
Task 7: Integrating Google Fonts into the CSS file

Type: Mandatory

Description: Based on styles/6-style.css:

    Add Open Sans as the first choice font for font-family-base, with the previous fonts shifted down accordingly.
    Add Raleway as the first choice font for font-family-title, with the previous fonts shifted down accordingly.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: styles/7-style.css
Task 8: Defining line heights

Type: Mandatory

Description: Based on styles/7-style.css:

    Target the root element and create the following custom properties:
        line-height-small set to 1.2.
        line-height-base set to 1.5.
        line-height-big set to 1.8.
    Set the minimum height of line boxes in the body to line-height-base.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: styles/8-style.css
Task 9: Links are decorated by default, time to remove them

Type: Mandatory

Description: Based on styles/8-style.css:

    Style the anchor elements so that the text isn't decorated with anything.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: styles/9-style.css
Task 10: Centering the section titles

Type: Mandatory

Description: Based on styles/9-style.css:

    Create a new custom property section-header-align and set it to center.
    Just above the section-tagline declaration, create a new declaration targeting the class section-header.
        Set the horizontal alignment of that class with section-header-align.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: styles/10-style.css
Task 11: Add more styles to the section tagline

Type: Mandatory

Description: Based on styles/10-style.css:

    Create a custom property section-tagline-transform and set it to uppercase.
    Target the section-tagline class:
        Set the font family to font-family-title.
        Use the section-tagline-transform property to transform the text.
        Set the font weight to font-weight-bold.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: styles/11-style.css
Task 12: Adding more styling to the section title

Type: Mandatory

Description: Based on styles/11-style.css:

    Create the following custom properties:
        section-title-margin set to 0.
        section-title-color set to color-black.
    Just above the section-tagline declaration, create a new declaration targeting the section-title class:
        Set the font family to font-family-title.
        Set the font size to font-size-xx-large.
        Set the font weight to font-weight-bold.
        Use the section-title-margin to set the margin.
        Use the section-title-color to set the text color.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: styles/12-style.css
Task 13: Pseudo Classes

Type: Mandatory

Description: Based on styles/12-style.css:

    Ensure that the declaration targeting anchor elements only targets those containing a hyperlink.
    Directly after this declaration, target the visited state for the link:
        Italicize the text.
    Directly after the visited state, target the hover state for the link:
        Decorate the links with an underline when hovering.
    Directly after the hover state, target the active state for the link:
        Set the color of the background with the variable color-light-grey.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: styles/13-style.css
Task 14: Resetting the CSS stylesheet for browser consistency

Type: Mandatory

Description: Based on styles/13-style.css:

    Normalize your CSS file using necolas' normalize.css with the provided version.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: styles/14-style.css
Task 15: Add universal box-sizing

Type: Mandatory

Description: Based on styles/14-style.css:

    Just before the styling for html, add a universal box sizing rule.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: styles/15-style.css
Task 16: Styling the container

Type: Mandatory

Description: Based on styles/15-style.css:

    After the styles for .section-tagline, target the container class and set the following:
        Width of 960px.
        Evenly distribute the margins on both the left and right sides.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: styles/16-style.css
Task 17: Adding padding to sections

Type: Mandatory

Description: Based on styles/16-style.css:

    Create the following custom properties:
        section-padding set to 5rem 0.
        section-header-padding set to 0 0 3rem.
        section-body-padding set to 0 0 3rem.
        section-footer-padding set to 3rem 0 0.
        section-footer-align set to center.
        footer-padding set to 5rem 0 1rem.
    Just before the section-header declaration, target the section class and set the padding on all 4 sides to section-padding.
    Set .section-header's padding on all 4 sides to section-header-padding.
    Following the section-header declaration, target the section-body class, set the padding on all 4 sides to section-body-padding.
    Following the section-body declaration, target the section-footer class, set the padding on all 4 sides to section-footer-padding, and set the horizontal alignment with section-footer-align.
    At the end of your style file, target the footer class and set the padding on all 4 sides of the selected element with footer-padding.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: styles/17-style.css
Task 18: Customizing the navbar

Type: Mandatory

Description: Based on styles/17-style.css:

    Targeting the navbar-menu class, let it float to the right.
    For the nav class:
        Set the margin on all sides to 0.
        Set the padding on all sides to 0.
        The styling on the list should not use anything.
        Center align the text.
    For the nav-item class in nav class:
        Set the font family to nav-item-font-family.
        Set the boldness of fonts to nav-item-font-weight.
        Set the size of fonts to nav-item-font-size.
        Set the spacing between text characters to nav-item-letter-spacing.
        Set the display to nav-item-display.
        Set the margin on all sides to nav-item-margin.
    For the nav-link class in nav class:
        Set the display to block.
        Set the padding to half of the root element for top and bottom, and equal to the root element for left and right.
    While hovering over the nav-link class in nav class, set their foreground color value to nav-item-link-hover.
    Create the following custom properties:
        nav-item-font-family set to font-family-title.
        nav-item-font-weight set to font-weight-bold.
        nav-item-font-size set to font-size-medium.
        nav-item-letter-spacing set to 4% of the root element.
        nav-item-display to inline-block.
        nav-item-margin to 3 times the root element on the bottom and 0 elsewhere.
        nav-item-link-hover set to color-primary.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: styles/18-style.css
Task 19: Grid styling and custom variables

Type: Mandatory

Description: Based on styles/18-style.css:

    Create the following custom properties:
        section-tagline-margin set to 0.
    Set the margins for the section-tagline class to section-tagline-margin.
    For all ul with the class row:
        Set 0 margins all around.
        No padding all around.
        The list should not have any default styles at all.
    For the col-1-3 class:
        Set the width to 33.33% of its parent.
        Float it to the left.
        Set its padding to half of the root element.
    For the col-1-2 class:
        Set the width to 50% of the parent.
        Float it to the left.
        Set its padding to half of the root element.
    For the footer-copyright class:
        No margins.
        Set the size of the fonts to font-size-small.
        Set the foreground color to text-color.
    For all ul tags in the footer, align the text to the right.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: styles/19-style.css
Task 20: Clear the context of the grid

Type: Mandatory

Description: Based on styles/19-style.css:

    Write a CSS rule that creates a new row after each instance of the class row with the following properties:
        No content.
        Displayed as a table.
        Do not allow any floating elements on either side.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: styles/20-style.css
Task 21: Simplify the col- selector

Type: Mandatory

Description: Based on styles/20-style.css:

    Select all classes that start with col-.
    Float them to the left.
    Set their padding to half of the root element.
    Remove references to these common properties for the individual col-1-3 and col-1-2 classes.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: styles/21-style.css
Task 22: Add a dark theme to sections

Type: Mandatory

Description: Based on styles/21-style.css:

    Style the data-section-theme="dark" with these rules:
        Redefine the custom property text-color to the color-white.
        Redefine the custom property section-title-color to color-white.
        Set the background to the variable color-black.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: styles/22-style.css
Task 23: Fix issues for dark theme

Type: Mandatory

Description: Based on styles/22-style.css:

    Style the footer-address class:
        Set the color of the text to the text-color property.
    Style the social-link class:
        Style it so that it renders as a block element.
    Style the social-link class that also selects the svg children:
        Fill in the color of the svg children with the text-color variable.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: styles/23-style.css
Task 24: Add background and hover state to services

Type: Mandatory

Description: Based on styles/23-style.css:

    Target card-title that is inside card that is inside card-item:
        Set the font weight to font-weight-bold.
        Set the font size to font-size-large.
    Target card-description that is inside card that is inside card-item:
        Set the font size to font-size-small.
    Target card-item that is inside card-container that is inside services:
        Set the display to grid.
        Set the grid template columns to repeat(4, 1fr).
    Target card-item that is inside card-container that is inside services that is being hovered over:
        Set the background color to color-primary.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: styles/24-style.css
Task 25: Add the button to the services section

Type: Mandatory

Description: Based on styles/24-style.css:

    Add a new CSS rule targeting the class button within the services class:
        Set the display to inline-block.
        Set the padding on all sides to 1rem.
        Set the margin on the bottom to 1rem.
        Set the font size to font-size-small.
        Set the font weight to font-weight-bold.
        Set the text color to text-color.
        Set the background color to color-primary.
        Set the border to none.
        Set the border radius to 1rem.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: styles/25-style.css
Task 26: Accessibility first!

Type: Advanced

Description: Based on styles/25-style.css:

    Create a class selector named visually-hidden that hides an element visually while keeping it accessible to screen readers.
        Set the display property to none.
        Set the visibility property to hidden.
        Set the overflow property to hidden.
        Set the position property to absolute.
        Set the width and height properties to 1px.
        Set the margin and padding properties to 0.
        Set the border property to 0.
    Apply the visually-hidden class to the logo-image class.
    Add a role attribute with the value presentation to the logo-image class.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: styles/26-style.css
Task 27: More specific CSS reset

Type: Advanced

Description: Based on styles/26-style.css:

    Add a specific CSS rule to reset the default styling for ol and ul tags.
        Set the list-style to none.
        Set the padding and margin to 0.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: styles/27-style.css
Task 28: Card Background Images

Type: Advanced

Description: Based on styles/27-style.css:

    Add background images to the .card-image class in card-container.
        Use the following image URLs:
            ../images/pic-about-01.jpg
            ../images/pic-work-01.jpg
            ../images/pic-work-02.jpg
            ../images/pic-work-03.jpg
            ../images/pic-article-01.jpg
            ../images/pic-article-02.jpg
            ../images/pic-article-03.jpg
            ../images/pic-person-01.jpg
            ../images/pic-person-02.jpg
            ../images/pic-person-03.jpg
    Set the background size to cover.
    Set the background repeat to no-repeat.
    Set the background position to center.

Note: Make sure the image URLs are correctly specified relative to the CSS file location.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: styles/28-style.css
Task 29: Custom favicon

Type: Advanced

Description: Based on the provided favicon.ico file, place it in the appropriate location in your project directory so that it serves as the favicon for your website.

Repo: alx-frontend

Directory: 0x02-CSS_advanced

File: favicon.ico

30. Fix the works section
mandatory
Based on styles/29-style.css

Target card-outer within the card-work

Relatively position the element
Hide any overflow
Target the image inside card-image inside card-work

The height of these elements should be 30rem
The width of this element should be 100%
Property: object-fit, Value: cover
Vertically align to the bottom
Target card-inner inside card-work

Absolutely position the element
Vertically position with -0.1rem on the top
Horizontally position the element with -0.1rem on the left
Horizontally position the element with -0.1rem on the right
Set the z-order to 1
Target card-inner when card-work is hover

Set the background color to this value: rgba(0, 0, 0, 0.7)
Target card-title inside card-work

Center align the text
Margins all around should be 0
Opacity should be set to its lowest value
The height of the selected elements should be 100%
The position should be relative
Target the link inside card-title and card-work

Make sure elements display as blocks
Text should not be decorated
Padding on the top should be 45%
Create the after pseudo elements of the link (inside card-title and card-work)

Absolutely position the selected elements
Set the top, right, left, and bottom positions to be 0
The content property of these elements should have an empty value
Target card-title when card-work is hover

The opacity of these elements should be set to the value of 1
Does not have to pass w3c

Repo:

GitHub repository: alx-frontend
Directory: 0x02-CSS_advanced
File: styles/30-style.css

31. Add quotes decoration on testimonials
mandatory
Target the card-quote that is inside the card-testimonial

Style it so that the position is relative to its parent
Target the before pseudo-element of card-quote that is inside the card-testimonial

The content should be set to the value \201C
Absolutely position the selected elements
The vertical position of the selected elements should be -4.5rem
The horizontal position from the left should be -1rem
The foreground color of the selected elements should be set to #efeded
The size of fonts should be 10rem
The z-order should be set to -1
Does not have to pass w3c

Repo:

GitHub repository: alx-frontend
Directory: 0x02-CSS_advanced
File: styles/31-style.css
  
32. Incorporating transitions
mandatory
Create some custom properties

Name: transition-duration, Value: .3s
Name: transition-cubic-bezier, Value: cubic-bezier(0.17, 0.67, 0, 1.01)
Add transformations on the card work

Target the card-image when card-work is hover

Use the transform property to apply a scale transform with a value of scale(1.2)
Target the card-outer when card-work is hover

Use the transform property apply a scale transform to make the elements shrink. Use scale(0.95)
Add animations on the navigation items

Inside .nav .nav-link::before

Use the shorthand property transition and have it use the value of var(–transition-duration) var(transition-cubic-bezier)
Animate the button background

In the hover state of the button class

The duration of the transition should be set to the variable transition-duration
The transition effect should be applied to the color and background-color properties (transition-property)
Add transitions on the card works

Inside card-work:hover .card-image

Use the shorthand property transition and have it use the value of var(–transition-duration) var(transition-cubic-bezier)
Inside .card-work .card-inner

Use the shorthand property transition and have it use the value of var(–transition-duration) var(transition-cubic-bezier)
Does not have to pass w3c

Repo:

GitHub repository: alx-frontend
Directory: 0x02-CSS_advanced
File: styles/32-style.css
