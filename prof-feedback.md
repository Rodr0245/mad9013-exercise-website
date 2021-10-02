# Professor Feedback

## Week 2B ----------------------

Overall, great start! A few small changes:

- the <title> should be the name of the website: Polished+
- the logo bar should be its own separate <section>
- You should avoid typing in all caps on the web, it is bad for accessibility. Right in normal sentence case and then we can style it later with CSS to make it all caps.
- Change the <footer> tag on the "Join now..." banner to a <section>. A <footer> tag in this case works as it is acting as the conclusion of the main content. However, it's possible that this Call to Action banner could be reused somewhere else on the site and may not always be the conclusion of the page content, so a <section> is more universally appropriate.
- The logos in the header/footer should be wrapped in an <a> linking to the home page

## Week 3 ----------------------

Great work! A few suggestions to simplify your code:

- You can simplify your button styles. You've created two separate classes and have duplicated a number lines of code. To simplify, create on `.btn` class that creates the basic button styles and then create a second `.btn-white` that changes to colour to white. This will help keep things consistent as well.
- The same concept can be applied to the banners as a whole. create a basic `.banner` class that applies basic styles like alignment, color, etc. Then use a secondary class to apply overrides for padding and image.

Loving the super swanky button hovers! 🤘