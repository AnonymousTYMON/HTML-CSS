# The Argleton Advertiser
The Argleton Advertiser has been around for a long time, and it was written using old HTML 4 which didn't have **article** and **section** elements. That means they used a lot of **div** elements everywhere. This makes it pretty tricky to read and harder to set the styles right.

## Make sure to use border-box for all questions this week
The question text won't mention it, but you should make sure there's a * { box-sizing: border-box; } at the top of **main.css** for all questions (remember to put it after any **@import** lines though!).

## Change the div elements into sections and articles
* The "snippets" and "headlines" class divs should be **section** elements instead (don't remove the classes).
* Each of the "article" class divs should be **article** elements instead since they are each separate articles.
* Leave the "column" class divs as they are; they're purely for styling so it's ok for them to be divs.
## Style the "column" class divs
* both columns should have **width** 260px and 6px of padding on all sides;
* put the columns next to each other with **inline-block**;
* give them a right-hand side border of 1px **solid** **rgb(200, 200, 200)**;
* make them line up at the top with **vertical-align**.
## Style the sections
* The "headlines" class section should have **width** 370px and 6px of padding on all sides.
* All **section** elements should be **inline-block** to put them on the same line;
* all **section** elements should have **vertical-align** set to top;
## Style the articles and their contents
* All the text in the articles should be **font-family**: **serif**;
* each article should have 10 pixels of padding on the bottom (to separate the articles);
* all headings and paragraphs in the articles should have no margins and 4px of padding on the top;

The result should look like this:
![alt text](https://groklearning-cdn.com/problems/hezYPrKv8hHkHECbTHyYjT/visual-diff.png)
