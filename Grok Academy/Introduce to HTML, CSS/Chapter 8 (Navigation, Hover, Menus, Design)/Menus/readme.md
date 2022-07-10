# Drop out of sight
This recipe sharing site has too many options in the menus and they're cluttering up the page! We're going to build a drop-down menu to only show the options when needed.

## Keeping the drop-down lists out of the way
* Add **position**: **absolute**; to the **nav** > **ul** > **li** > ul elements (The lists inside the menu list) so they appear over the top of other elements.
## Add :hover styles
Make the top level li list items change background colour to **rgb(121, 185, 211)** when hovered;
make the drop-down li list items change background colour to **rgb(185, 211, 121)** when hovered;
## Hiding and showing the drop-downs
* Add **display**: **none**; to the inside **ul** list elements (The lists inside the other list) so they disappear.
* Add **display**: **block**; to the inside **ul** list elements (The lists inside the other list) but only when the **li** element is hovered on so they appear again! (Hint, use this selector: **nav** > **ul** > **li**:**hover** > **ul**).

The result should look like this when not hovering over anything:
![alt text](https://groklearning-cdn.com/problems/FHY5c4JVkivpd7ZqLj2Fg9/screenshot.png)
And like this when hovering:
![alt text](https://groklearning-cdn.com/problems/fsc3oPRv6mCs9YK3uWKRKC/screenshot-hover1.png)
