# dev-photo-gallery
Photo gallery

## Expected output
![expected output](expected-output.png "Open book")

## Current link
[Page with error](https://anandrktm.github.io/dev-photo-gallery/) 


## Instructions
1. Find the errors
2. Fix the error
3. Share your solution on your repository's [github page](https://pages.github.com/)
4. Raise a PR with the fix.

## fixed errors:

1. Fix the array index for the quote array:
Change quote[Math.floor(Math.random()*4)] to quote[Math.floor(Math.random()*quote.length)] to ensure the correct array length is used.

2.Move div with id "container" inside the body tag:
The container div should be within the body, not the head.

3.HTML Doctype and Language Attribute:
No errors, but I added lang="en" to specify the language for better accessibility.

4. Removed the unnecessary async keyword from the window.onload function since there are no asynchronous operations in this function.

5. Added let to declare the image_url variable in the changeImage function. This prevents it from becoming a global variable.

6. Improved formatting and added line breaks for better readability and organization.

7.  I added an inline style to the img element inside the div with id="poster". The style attribute sets the width to 600px and the height to 400px, matching the dimensions of the layout image. 


