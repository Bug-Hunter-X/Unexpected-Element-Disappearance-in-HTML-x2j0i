# Unexpected Element Disappearance Bug in HTML

This repository demonstrates a subtle bug in HTML where a div element disappears after a button click and there's no way to make it reappear.  The issue stems from setting the `display` property to `none` without providing a mechanism to revert this change. This results in unexpected behavior for the user, who might think the content is lost.

## Bug Description
The `bug.html` file contains the buggy code. Clicking the button hides the div, and there is no way to show it again.  The solution file offers a way to fix this.