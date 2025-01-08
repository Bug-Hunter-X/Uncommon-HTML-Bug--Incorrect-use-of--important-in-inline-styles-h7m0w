# Uncommon HTML Bug: Incorrect use of !important in inline styles

This repository demonstrates an uncommon bug related to the use of `!important` in inline styles within HTML.  The bug occurs because using `!important` directly within JavaScript to set an inline style can cause unexpected behavior, particularly in some browser versions. While `!important` is generally intended for CSS, using it in this context can lead to inconsistent rendering and override expected styles.

**Bug:** The provided HTML uses JavaScript to set the `display` style of a div to `none!important`. This is not standard practice and some browsers may fail to handle this correctly, leading to the div remaining visible despite the styling.

**Solution:** The solution demonstrates correct method of handling display: none via JavaScript.