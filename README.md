# umflint-lab
Test lab for UMFlint

What branding considerations did you consider when implementing the
component?
First, I wanted to use a UM-acceptable font. Based on the style guide, I chose Open Sans and linked to it from Google Fonts.
Next, I had to use the correct colors. The left section is the yellow/blue gradient, so it moves from UM-approved yellow to UM-approved blue. I wouldn't normally recommend a gradient, but if that's what the client wants I'm happy to deliver.

What accessibility considerations did you consider when implementing the
component?
The mockup had two likely contrast accessibility issues. "Johnny Wolverine" and "Professor of Computer Science" both did not contrast with the background (a common issue with gradients). To compensate, I made both white. This passed the WAVE accessibility test. Also, I made sure to structure the content with proper h1 and h2 heading levels.
The page does have three errors from the accessibility test - the three social media links. Still, these image links have alt tags and should be read just fine by screen readers. 

When implementing the responsive nature of the component what
considerations did you take into account?
The main consideration was how the left column of the mockup will respond on mobile. I wanted the columns to stack on mobile, but not before. So I made the breakpoint bootstrap's "sm" to stack on mobile. It worked well. Also the 'headshot' image had to respond, so just added the 'img-fluid' class. Otherwise, the content moved seamlessly from mobile to desktop.

Other notes:
- I added id tags to all the elements that should be linked to the faculty database.
- I also made the research interests buttons. If this were a real-world scenario, the client could click on the research interest and then see others with the same research interest.
