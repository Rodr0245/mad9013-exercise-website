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

## Week 4 ----------------------

Code Quality: 2.5/3
Design: .75/1
File Organization & Commits: 1/1
Total: 4.25/5

- Make sure to review your CSS to insure it is neat and organized, including:
  - remove empty lines inside of CSS rules
  - there should be a space between the selector and the opening curly bracket `{`
  - there should be a space between each ruleset
  - double check indentation
- Make sure to apply the `Ubuntu` font across the entire site!
- Apply base consistent margin to all heading and type like in our in class tutorial: `margin: 0 0 1.5rem;`
- You should include a base style for all `<a>`

## Week 5 ----------------------

Code Quality: 1/3
Design: .5/1
File Organization & Commits: 1/1
Total: 2.5/5

- You should be working in a mobile first responsive headspace. Start with mobile and get it perfect before the using media queries to adjust the layout for the large screen sizes. You layout is not responsive.
- Use the `.container` class we created in class to help create a more consistent layout. You have created new containers which are inconsistent and that unnecessarily recreate the same code, which is inefficient.
- Avoid setting fixed widths, margins, and paddings to move elements around. This causes your layout to be rigid and inflexible. Notice how some stuff is sticking off the side of the screen? This is the reason
- Use `float: right;` to align things to the right instead.
Part 2 is incomplete.

## Week 6 ----------------------

Code Quality: 2.75/3
Design: .75/1
File Organization & Commits: 1/1
Subtotal: 4.5/5

Late pentaly: -30%;

Total: 3/5

- instead of setting a large amount of paddings on the sides of the header and footer, use our `.container` class to keep a consistent max-width and centering

## Week 7 ----------------------

Code Quality: 2.5/3
Design: 1/1
File Organization & Commits: 1/1
Subtotal: 4.5/5

Late Penalty: -30%

Total: 3/5

- `<h4 class="split-header">The polished+ platform</h4>` should be `h2` to follow proper heading structure
- content should be ordered for mobile reading, (text, image, text, image, etc.) and then reordered on large screen sizes.

## Week 9 ----------------------

Code Quality: 2/3
Design: .75/1
File Organization & Commits: 1/1
Subtotal: 3.75/5

Late Penalty: -30%

Total: 2.25/5

- Missing `thead`. Should contain a `tr` with the Basic, Premium, and Ultra content, but not the pricing info. That should be in a separate `tr` in the `tbody`
- `<span class="dollarSign">$</span>` --> `<sup class="dollarSign">$</sup>`
- `td` should not have scope. Only `th` should have scope.
- Class of `.row` is redundant as you could just target the `tr` which represents rows
- You should avoid writing in all caps in HTML as it is bad for accessibility and SEO. Instead, you should write in normal sentence case and use `text-transform: uppercase;` to make the text appear all caps.
- `button` should be `<a class="btn">`
- Font size should not be reduced

## Week 9 ----------------------

Code Quality: 2.5/3
Design: 1/1
File Organization & Commits: 1/1
Subtotal: 4.5/5

Late Penalty: -30%

Total: 3/5

- All `input` need a `label` with text content in it. This is important for accessibility. To visually hide the labels, use the `screen-reader-text` styles discussed in class.