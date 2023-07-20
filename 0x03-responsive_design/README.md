This repository contains the solutions for the "Responsive Design" tasks for the ALX Frontend course. Below are the details of each task along with the corresponding files and directories.
Task 0: Fix the hero banner
Description:

The hero banner background is not visible due to some changes in the article.html page in the previous project. The task is to fix the hero banner by updating some values in the 01-styles.css file.
Changes to be made:

    Inside the .hero-homepage class selector, update background-position property to 65% 8rem.
    Inside the selector targeting .section-inner class inside .section-hero class, update min-height property to 35vh.

Relevant Files:

    Directory: 0x03-responsive_design
    File: 01-styles.css
    File: 01-index.html

Task 1: Make the container flexible
Description:

Update the .container selector in the 02-styles.css file to make it flexible by changing the width to max-width.
Changes to be made:

    Inside the .container selector, update width property to max-width.

Relevant Files:

    Directory: 0x03-responsive_design
    File: 02-styles.css
    File: 02-index.html

Task 2: Fix layout issues
Description:

Add media queries to handle layout issues for different device sizes (extra large devices, desktop/large devices, tablet/medium styles, and mobile styles).
Changes to be made:

    In 02-1-styles.css file:
        Inside the /* Helpers section, target all images inside the main section and update their properties.
        Inside the /* Section Latest news section, add a new media query targeting the row inside section-latest-news.
        Inside the /* Grid section, at the end, add a new media query and update the properties for different classes.

Relevant Files:

    Directory: 0x03-responsive_design
    File: 02-1-styles.css
    File: 02-1-index.html

Task 3: Generate images with responsive breakpoints
Description:

Generate responsive images with different resolutions and art-direction using a tool. Replace the existing images with the newly generated responsive images.
Changes to be made:

    Generate responsive images using the provided tool and replace the existing <img> tags in the 03-index.html file.

Relevant Files:

    Directory: 0x03-responsive_design
    File: 03-index.html
    File: 03-styles.css

Task 4: Create the mobile icon and hide the menu
Description:

Create a clickable icon that shows and hides the navigation menu using pure HTML/CSS. Use input type checkbox to toggle the menu.
Changes to be made:

    Update the HTML file (04-index.html) to add an input with the class menu-btn and a label with the class menu-icon.
    Update the CSS file (04-styles.css) to add styles to handle the behavior of the menu when the checkbox is checked/unchecked.

Relevant Files:

    Directory: 0x03-responsive_design
    File: 04-index.html
    File: 04-styles.css

Task 5: Hamburger!
Description:

Create an "hamburger" icon using pure CSS.
Changes to be made:

    Update the CSS file (05-styles.css) to create the "hamburger" icon.

Relevant Files:

    Directory: 0x03-responsive_design
    File: 05-index.html
    File: 05-styles.css

Task 6: Add the behavior based on menu-btn state
Description:

Add behavior to the menu based on the state of the menu-btn checkbox.
Changes to be made:

    Update the CSS file (06-styles.css) to handle the behavior of the menu when the menu-btn is checked.

Relevant Files:

    Directory: 0x03-responsive_design
    File: 06-index.html
    File: 06-styles.css

Task 7: Make the font size responsive
Description:

Make the typography responsive by using media queries to change the font size based on the screen size.
Changes to be made:

    Update the CSS file (07-styles.css) to add media queries and change the font size accordingly.

Relevant Files:

    Directory: 0x03-responsive_design
    File: 07-index.html
    File: 07-styles.css

Task 8: Improve the "Works" section
Description:

Improve the "Works" section by making some changes to the CSS.
Changes to be made:

    Update the CSS file (08-styles.css) to target the .card-inner class inside .card-work class for max-width: 767px.

Relevant Files:

    Directory: 0x03-responsive_design
    File: 08-index.html
    File: 08-styles.css

Task 9: Improve the "Footer" section
Description:

Improve the "Footer" section by making some changes to the CSS.
Changes to be made:

    Update the CSS file (09-styles.css) to add media queries and change the padding and alignment of the footer content for different screen sizes.

Relevant Files:

    Directory: 0x03-responsive_design
    File: 09-index.html
    File: 09-styles.css

Task 10: Fix the top header background
Description:

Fix the top header background for better visual appearance.
Changes to be made:

    Update the HTML file (10-index.html) to add the class article-page to the body tag.
    Update the CSS file (10-styles.css) to target the .section-hero class inside .article-page class and update the margin-top and padding-top properties.

Relevant Files:

    Directory: 0x03-responsive_design
    File: 10-index.html
    File: 10-styles.css
