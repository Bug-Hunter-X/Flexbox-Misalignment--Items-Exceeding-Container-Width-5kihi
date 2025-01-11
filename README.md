# Flexbox Misalignment Bug
This repository demonstrates a bug related to flexbox layout in CSS.  When the total width of flex items exceeds the container's width, some browsers exhibit unexpected behavior (misalignment or collapse) rather than the expected wrapping or overflow.

## Bug Description:
The provided CSS uses `flex` to space items evenly. However, if the combined width of items exceeds the container's width, the layout breaks in some browsers. This demonstrates a need for careful consideration of the relationship between item width and container width in flexbox designs. 

## Solution:
The solution involves using CSS `flex-wrap: wrap;` to allow items to wrap onto multiple lines when they exceed the container's width, thus resolving the misalignment issue. 