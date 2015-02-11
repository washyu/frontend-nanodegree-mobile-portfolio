The changes I made were based on the suggestions on pagespeed insite.

- I loaded the styles using a script after the end of the page body.
- I removed the call to the google font and just used "Roberto"
- Moced the print and mobile styes to a seperate files and loaded them with media tags.
- Used gimp to compress the images on the main page.
- On the pizza page I cashed the document.body.scrolltop value oustside the for loop value instead of calling in in the for loop.
- Also since all the pizza are the same size in the background I calculated the size outside the for loop that sets the pizzas on the page.

