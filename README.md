# dev-photo-gallery
Photo gallery

## Expected output
![expected output](expected-output.png "Open book")

## Current link
[Page with error](https://anandrktm.github.io/dev-photo-gallery/) 


## Instructions
1. Find the errors
2. Fix the error
3. Mention the list of errors in your README.md file
4. Share your solution on your repository's [github page](https://pages.github.com/)
5. Raise a PR with the fix.




#Photo Gallary

This project is a simple photo gallary with the functionality to change the displayed image and accompanying quote.

## I Changed this things in this code and made to correct 

1. Moved the `<div id="container">` element from the from the `<head>` section to the `<body>` section to ensure correct HTML structure.
2. Removed the semicolon (`;`) at the end of the `img_bird` URL declaration to prevent syntax errors.
3. Updated the `loadImage` function to use `quote.length` instead of a hardcoded value (`4`) to ensure a random index within the bounds of the `quote` array.
4. Added a declaration for the `image_url` variable in the `changeImage` function to prevent potential errors when the select element's value is not `'book'` or `'layout'`.
5. Added the class `big-text` to the heading element and updated its font size to `20px` using css