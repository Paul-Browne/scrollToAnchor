# scrollToAnchor
A simple, pure javascript animation that scrolls the page to anchors
works on all `<a href="#somewhere">somewhere</a>` in the page, as long as the first character in the string is a hash.
Then the body will scroll to that point in the page when the link is clicked

The time taken to scroll to the point is a function of the distance from the current point in the page, to the target. So the further away the point, the longer it takes, with a minimun of 1 second for distances less than 500 pixels and a maximum of 2.5 seconds for distances of greater than 2500 pixels.
