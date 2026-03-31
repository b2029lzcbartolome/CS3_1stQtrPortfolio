1. Relative positioning allowed for the sidebar to be moved based on the left and top values.
2. When scrolling the page, the footer doesn't move due to it being fixed.
3. Absolute removes the element from the document flow, meaning other elements ignore it and fill it's spot up. This is different from Fixed since Fixed only makes the asset stay stationary.
4. If you swap the index values, the main content box will cover the notice. And since normally the notice box has a higher z-value, it will overlap the content box.

a. Static is the default position, Relative moves the element without affecting the other elements, Absoulute removes the element from the program flow, with elements acting like it's not there and floating based on parent coordinates, and Fixed reomves the element from flow and makes it stay in the exact same spot.
b. Absolute element looks up the histroy of the HTML to find it's parent coordinates. It positions itself next to the nearest ancestor with a position value, or defaults to the body window if there is none.
c. Fixed makes it so that the element is always at a specific coordinate, while sticky scrolls with the page until a certain point.
d. Some things I could do are to make the navigation bar fixed, use relative hover effects on links, and use sticky on a schedule element.