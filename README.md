##User Story

AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines


##Acceptance Criteria

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


1. All images on the page have been marked with the alt attributes to not only become accessible for those using screen readers, but also makes the site more visible on search engines.

2. In addition to the alt attributes, a couple of the structural elements have been rearranged to make for code that is more logical in terms of sequence, as well as adding a <header>, <footer>, <aside> and <section> semantic element to give proper, more readable structure to the code.

3. A proper title has been given to the webpage, giving it a professional look at first glance.

4. Many of the elements in the CSS file have been combined, resulting in a file that has about 50 less lines of code and is much less redundant, all while achieving the same results. This was done by grouping images with the same page attributes into one rule set, as opposed to multiple.

5. This README file has been added and composed to describe and explain the changes I've made.

6. There is one broken link on the header that I was unable to fix. Looking through the code, I couldn't find anything wrong or different from the other two links that was causing it to not scroll down on the page like the other 2 links. If there's a solution for this, please share in my assignment feedback!

##
I used the internet resource W3 schools (w3schools.com) to figure out which semantic elements to use for this code as well as where they are theoritcally placed.

I also would not have been able to finish this assignment without the help of one of my TA's William. THANKS WILLIAM <3