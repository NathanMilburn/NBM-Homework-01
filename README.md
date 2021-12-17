# NBM-Homework-01
MY USER STORY

AS a web developer,

I WANT to refactor the html and css code of this website to optimize the functionality with the least amount of unneccesary code as possible

SO THAT I can learn write optimized code efficiently when creating my own websites while reinforcing my understanding of the fundamentals.

SUPPLIED USER STORY

AS A marketing agency

I WANT a codebase that follows accessibility standards

SO THAT our own site is optimized for search engines


<!-- Step-by-Step Process explanation -->


I began this process by inspecting the abundance of div tags segregating off each unique section of the html code.

From there, I began to research semantic alternatives that I could use to consolidate sertain sections and avoid an excess amount of div tags. 

<!-- Image of semantic tag changes in first section -->

With the div tag acting as a general use tag for dividing unique sections of code, I decided that a nav tag would be more effective for the "content" class as "search-engine-optimization", "online-reputation-management", and "social-media-marketing" acted as clickable buttons to navigate the user to a specific area of the page. Upon updating to nav tags, I noticed that one of the buttons labeled "Search-engine-optimization" was not functioning correctly. I found the cause of this to be a missing ID tag to link the nav tag to the specific section.

![header/nav-changes](assets/images/Header-Nav-Corrections.png "Refactored div tags for accesibility")

From here I updated the div class="header" and div class="footer" to the semantics tags header and footer.

I added an alt tag to each of the images explaining what is being depicted in the photo provided.

![alt-tag-changes](assets/images/divtag-semanticchange-altattributes.png "Added alt tags and segregated SEO sections")

The next step was to figure out how I could optimize the "benefits" class and eliminate the need for further div tags. While looking at the formatting of the original website, the "benefits" section seemed to act separately from the "content" which would explain its placement to the right of the screen. I chose to replace these div tags with article tags as an article tag is most commonly used to contain information that may be distributed independently from the rest of the site.

![benefits-class/article-tags](assets/images/benefitsclass-refactoring-articletag.png "Refactored benefits class with article tags")



Refactored Website
<!-- Images of refactored website -->

![Refactored Top of Site](assets/images/Homework-01-TOPSITE.png "Top of Website")
![Refactored Bottom of Site](assets/images//Homework-01-BOTTOMSITE.png "Bottom of Website")

<!-- Deployment URLs for Application and Github -->
[deploymentApplication](https://nathanmilburn.github.io/NBM-Homework-01/)
[deploymentRepository](https://github.com/NathanMilburn/NBM-Homework-01.git)

