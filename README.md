
## QUESTION-1
Flexbox (Flexible Box Layout) is a modern CSS layout system designed to arrange items in a container, even when their size is unknown or dynamic. It makes it easier to build flexible and responsive layouts by allowing items to grow, shrink, and align properly inside a container.

Flexbox is considered better than traditional float or inline-block layouts because:

It makes alignment (both horizontal and vertical) much easier.

It avoids the common float issues like clearing and collapsing.

Items can automatically adjust their size to fill space.

The layout is more responsive and adapts well to different screen sizes.

It requires less CSS code and no hacks or clearfixes.

Overall, Flexbox simplifies layout creation and is widely used in modern web design for building clean, responsive, and flexible interfaces.






## QUESTION-3
In Flexbox, the main axis is the primary direction in which flex items are arranged within a container, while the cross axis is perpendicular to the main axis. The flex-direction property determines the direction of the main axis. Here's a breakdown: Main Axis: This is the direction in which flex items are placed. By default, it's a horizontal row (left to right). However, you can change it to a column (top to bottom) using flex-direction: column. Cross Axis: This axis is always perpendicular to the main axis. If the main axis is a row, the cross axis is a column, and vice versa.


## QUESTION-5
The flex property in CSS is a shorthand that sets how a flex item behaves in a flex container. It combines three properties into one line: flex-grow, flex-shrink, and flex-basis.

The syntax is:

flex: <flex-grow> <flex-shrink> <flex-basis>;

flex-grow controls how much the item will grow if there is extra space.

flex-shrink controls how much the item will shrink if there is not enough space.

flex-basis sets the initial size of the item before any growing or shrinking happens.

Examples:

flex: 1 means flex-grow is 1, flex-shrink is 1, and flex-basis is 0%. The item will grow and shrink as needed, starting from 0 size.

flex: 0 means no growing, can shrink, and starts at 0 size.

flex: auto means the item can grow and shrink and starts from its natural size.

flex: none means no growing or shrinking and uses the item’s natural size.

flex: 2 1 100px means the item grows twice as fast as others, can shrink, and starts at 100 pixels width.

If you write only one number like flex: 2, the browser treats it as flex: 2 1 0%.