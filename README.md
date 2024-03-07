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

## List of Errors

1.The`<div id="container">` is placed outside the `<body>` tag.
2.There is a semicolon at the end of the `img_bird` URL.
3.There is no necessary need of async keword
4.The `updateImage()` function is not correctly called when the page loads.
5.The random index generated in the `loadImage()` function should be between 0 and 4.
6.The `image_url` variable in the `changeImage()` function is not declared.
7.Images layout should be 600*400 size 



## Changes made


-Moved the `<div id="container">` inside the `<body>` tag.
- Removed the semicolon at the end of the `img_bird` URL.
- Correctly called the `updateImage()` function when the page loads.
- Used `quote.length` to generate a random index in the `loadImage()` function.
- Passed the `current_quote` variable to the `createHeading()` function.
- Declared the `image_url` variable using `let` in the `changeImage()` function.
- images layout should be 600*400 size
