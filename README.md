# NBM-Homework-01
<!--MY USER STORY -->
AS a web developer,
I WANT to refactor the html and css code of this website to optimize the functionality with the least amount of unneccesary code as possible
SO THAT I can learn write optimized code efficiently when creating my own websites while reinforcing my understanding of the fundamentals.

<!-- Supplied USER STORY -->
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines


<!-- Acceptance Criteria -->
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title


<!-- Step-by-Step Process explanation -->
I began this process by inspecting the abundance of div tags segregating off each unique section of the html code.

Then, I wrapped section classes "hero", "content", and "benefits" into a main tag so that I could improve accessibility when resizing for mobile and tablet devices.

From there, I began to research semantic alternatives that I could use to consolidate sertain sections and avoid an excess amount of div tags. 

With the div tag acting as a general use tag for dividing unique sections of code, I decided that a nav tag would be more effective for the "content" class as "search-engine-optimization", "online-reputation-management", and "social-media-marketing" acted as clickable buttons to navigate the user to a specific area of the page. 

From here I updated the div class="header" and div class="footer" to the semantics tags header and footer.

I added an alt tag to each of the images explaining what is being depicted in the photo provided.

The next step was to figure out how I could optimize the "benefits" class and eliminate the need for further div tags. While looking at the formatting of the original website, the "benefits" section seemed to act separately from the "content" which would explain its placement to the right of the screen. I chose to replace these div tags with article tags as an article tag is most commonly used to contain information that may be distributed independently from the rest of the site.


<!-- Deployment URLs for Application and Github -->
[deploymentApplication] (https://nathanmilburn.github.io/NBM-Homework-01/)
[deploymentRepository] (https://github.com/NathanMilburn/NBM-Homework-01.git)

