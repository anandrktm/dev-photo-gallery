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

1. Language Specification:
Added lang="en" to the <html> tag to specify the document's language as English.

2. Image Styling:
Added an inline style to the <img> tag within the #poster div to set its width to 600 pixels and height to 400 pixels, ensuring a consistent size for displayed images.

3. Removed Unnecessary Async Keyword:
Removed the unnecessary async keyword from the window.onload function as there were no asynchronous operations within the function.

4. Array Index Correction:
Corrected the array index in the loadImage function to use quote.length instead of a hardcoded value (4) to ensure the function works correctly for any number of quotes in the array.

5. Variable Declaration:
Added let before the declaration of the image_url variable within the changeImage function to ensure it is properly scoped and does not pollute the global scope.

6. Semicolon Correction:
Removed the unnecessary semicolon from the end of the img_bird declaration to maintain consistency with the other variable declarations.
Console Log Information:

7. Updated console log messages for better clarity and consistency.

8. Inline Styling for Image:
Added an inline style to the img tag within the #poster div to set its width to 600 pixels and height to 400 pixels, ensuring a consistent size for displayed images.