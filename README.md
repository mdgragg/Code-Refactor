# Code-Refactor
Changed the <title> of the website to "Horiseon".

Deleted "./" in the css style.css path. It only needs ../ if it is located in folder outside where the HTML is.

Changed div around h1 and ul to nav

Added "id" for search-engine-optimization, so the list nav item would be linked.

Deleted classes for items that had id with the same name.
Then changed css to have # for id instead of . for the deleted classes.

Deleted /img as image tags shouldn't have close tags, just the self closing tags (>).
Moved any image classes before the image link.
Added alt text after the image link.

Changed unnecessary div tags to either header, main, section, or aside.

In css, deleted styles with duplicated styling. 1 style for h2, h3, and divs that have the same styles.

Condensed ".benefit-lead" ".benefit-brand", and ".benefit-cost" into 1 style because it's using the same style

Changed div class="footer" to footer tag

Added min-height: and changed the height: to auto for the blue boxes making them responsive.


