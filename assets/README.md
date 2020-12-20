What: To edit the HTML of client, Horiseon, for accessibility. 

Why: 

Accessibilty enhances the breadth of an audience for any webpage. 

Accessibility means (at a minimum) making the HTML of a webpage legible to screen readers by replacing non-specific elements (such as <div>) with more descriptive tags; ie. Article, section, etc. 

These more descriptive elements are Semantic HTML, a feature of HTML5.

With images it is particularly important to add <atl> elements because these allow for screen readers to pick-up valuable information about what that image is trying to communicate. 

Additionally, this element allows for images to be understood by sighted users in the event that the proper image link is broken or simply fails to load.

How: 

For this document the most important adjustments were to change the abundant <div> elements to more specific, semantic elements that have been incorporated into HTML5.

First, the navigation bar contained a broken link to the Search Engin Optimization article. 

Correcting that by rewritting the correct link resolved this bug.

These sections lacked clarity in thier element for screen readers:

Search Engine Optimization

Online Reputation Management

Social Media Marketing

These sections are targeted and described by the navigation bar, these sections were renamed at <articles>.

Their purpose is to inform the user of the importance of these concepts when marketing a company online. 

Given thier purpose is to inform, renaming them as such is logical and thier palcment next to the company tools means they 'point to' the solution to a users needs.

Next, the images within these articles lacked an alt attribute.

Adding these to the img element after the src attribute allows for the defining of the image to a screen reader. 

Then, it was necessary to further define the <div> elements that contained the <article> to make them further comprehensible to screen readers as sepearate articles.

Moved the benefits panel infront of the content a, b, and c to correct formatting error.

Finally, identifying the footer as such signals to the user that the content has ended upon reaching the bottom of the page. 
