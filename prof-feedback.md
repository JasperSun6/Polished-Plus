# Professor Feedback

## Week 2B ----------------------

Overall, great start! Great organization with your comments! A few small changes:

- the <h1> should be wrapped around the <img> inside the <header>, the "Community feel" heading should be an <h2>. The secondary line of text in the banner should be a <p>
- There should only be 1 <h1> per page. the headings in the Product Intro and Call to action banner should both be <h2>.
- Avoid using all caps text in HTML. If you want your text to look all caps, use CSS instead
- <p>© 2021 Algonquin College</p> --> <small>&copy; 2021 Algonquin College</small>
- The logos in the header/footer should be wrapped in an <a> linking to the home page

## Week 3 ----------------------

Great work! A few suggestions to clean up and simplify your code:

- You can simplify your button styles. You've created two separate classes and have duplicated a number lines of code. To simplify, create on `.btn` class that creates the basic button styles and then create a second `.btn-white` that changes to colour to white. This will help keep things consistent as well.
- The same concept can be applied to the banners as a whole. create a basic `.banner` class that applies basic styles like alignment, color, etc. Then use a secondary class to apply overrides for padding and image.
- Try and be more descriptive with your classes and avoid numbering classes. Instead of `.signUp1` and `.signUp2` use something like `.btn-teal` and `.btn-white` instead. That way someone looking at the code will understand what those classes do.