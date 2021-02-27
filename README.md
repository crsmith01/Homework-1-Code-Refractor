# Homework-1-Code-Refractor

<!-- Description -->
In this assignment, I addressed accessibility via the code, committing messages to say what had been done along the way, so other team members would know what changes had been made.
1. To start, all 7 images need to be visiable and have alternative text (none had alternative text, and only 3 images appeared to at the start). A simple iCloud fix addressed the missing images. Alt text for the 3 in the aside was a bit tricky.
2. Title changed from “website” to “Horiseon Homepage”.
3. The source code's generic HTML elements were changed to semantic HTML elements (i.e. changing )
4. Links must work. Online Reputation Management and Social Media Marketing did from the start, and addingin an id to the Search Engine Optimization section meant it did as well.
5. The most time-consuming aspect of this assignment was making the code dry. The properties of many of the elements was the same, so it could be conslidated. For instance, .search engine optimization img, .online rep man img, and .social media marketing img can be put together as img (since they all had max-height set to 200px). The same could be done with h2 for those three (since margin and font-size are the same), .benefit, .benefit h3, and .benefit img.  It looked wonky at times when the HTML did not coordinate wtih the changed css terms.
6. The final step was deploying to GitHub. 


<!-- Screenshot -->
Screenshots of the finished page can be seen here: (./assets/images/screenshot-part-1.png) and (./assets/images/screenshot-part-2.png)

<!-- Code -->
The deployed application can be found via this link: https://crsmith01.github.io/Homework-1-Code-Refractor/.