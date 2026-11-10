# Assignment 10: Responsive & Accessible CSS Layout

Harrison Martin, ATLS/CSCI 3150

**Google Fonts (extra credit):** I imported two Google Fonts: Hanken Grotesk for the body text and Fraunces for the headings.

## Findings

I updated my Assignment 7 CSS so the three parts of the page (Basic HTML Animals, Looking at lists and Advanced HTML Animals) sit side by side in a three-column CSS Grid, and each part stacks its content with Flexbox. Without media queries, the three columns kept getting narrower as I shrank the browser window. Below 900px the columns were too thin to read comfortably, and below 640px the text was only a few words per line. I added two media queries. Below 900px the grid changes to two columns, and below 640px it changes to one column. Increasing the text size to 200% and 400% had the same effect as narrowing the window: the zoomed page switched to two columns and then one, so the text reflowed instead of getting cut off.

The HTML passes the Nu validator with no errors or warnings. [Add your outline, WAVE and screen reader results here.]
