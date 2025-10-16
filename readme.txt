--Readme document for *LEAH KANG*, *LEAHYK@uci.edu*--

A reminder on academic integrity, as described in the syllabus.

In general, the course staff expects that you will look at code and examples from many online resources as part of the assignments, particularly to resolve syntax and understand frameworks. We expect that you'll use other libraries you find, and will even require it in some assignments. These practices are often critical to the work of developers today. The best developers are adept at interpreting the examples they see, customizing them to their specific situation, and citing their sources so they can find them later. We expect you to do the same.

While learning from examples is encouraged, attempting to pass an existing project or example from the web as your own is not allowed. If you ever have a question about what is or is not appropriate, feel free to ask the course staff!

Talking to classmates about class material, assignment requirements, etc. is a great way to verify ideas and get feedback. But this distinctly does *not* permit attempting to pass off someone else’s code as your own. Talking over ideas and approaches is allowed, but the work that you produce and submit must be your own.

1. How many assignment points do you believe you completed (replace the *'s with your numbers)?

10/10
- 1/1 Readme
- 2/2 Basic HTML content
- 1/1 Basic CSS styling
- 1/1 Advanced feature
- 2/2 Responsive layout
- 1/1 Passes validation checks
- 2/2 Embraces spirit of the assignment

2. What (a) basic features, (b) CSS features, and (c) advanced features did you include in your portfolio?

(a) Basic features
    - Images with descriptive alt attributes
    - Appropriate headings and paragraph text
    - Links to external pages
    - Multiple pages, with appropriate navigation between them
    - Semantic HTML tags (footer)
    - Adding custom icons from Google Material Icons


(b) CSS features
    - Modifying padding and margins to indent content and enhance readability
    - Modifying link, text color, or other colors to be visually appealing
    - Adding custom fonts from Google fonts with fallbacks


(c) Advanced features
    - Creating a more complex page layout- navigation bar


3. Did you ignore any of the warnings or errors presented by the accessibility checker? If so, why does this not seem like an accessibility concern? If it's useful, you can consolidate your thoughts on multiple warnings/errors if the rationale is similar.
    Yes. I got the same/similar accessibility and CSS errors per each HTML file.

    Accessibility Errors:
    - 1.1.1 Non-text content, Alt text does not convey same info (index.html, about.html, personal.html)
        I ignored this because for example alt text like “Leah Kang standing and smiling at a beach.” is enough context.

    - 1.1.1 Non-text content, Alt not empty, image may be decorative (index.html, about.html, projects.html, personal.html, contact.html, sitemap.html)
        I ignored this because the logo is a Home page link and has an accessible name through aria and hidden text. My hobby and content images are meaningful as well.
   
    - 1.1.1 Non-text content, Alt not empty, Image may require long description (index.html, about.html, projects.html, personal.html, contact.html, sitemap.html)
        I ignored this because images are simple, long descriptions are not necessary.
   
    - 1.3.1 Info and Relationships, dir attribute / Unicode LRM/RLM may be required (index.html, about.html, projects.html, personal.html, contact.html, sitemap.html)
        All content is in English

    - 1.3.1 Info and Relationships, Visual lists may not be properly marked (index.html, about.html, projects.html, personal.html, contact.html, sitemap.html)
        My navigation is correctly marked as nav > ul > li > a, and grids are labeled with heading and paragraph.
   
    - 1.3.3 Sensory Characteristics (index.html, about.html, projects.html, personal.html, contact.html, sitemap.html)
        None of the actions rely on shape or color or position.
    
    - 1.4.1 Use of Color / 1.4.5 Images of Text (index.html, about.html, projects.html, personal.html, contact.html, sitemap.html)
        Images and logos don’t ask instructions by color. Alt text provides context. No important text exists within images.
    
    - 1.4.1 Use of Color, script may use color alone (index.html, about.html, projects.html, contact.html)
        The script's interaction does not depend on color. Links underline on hover/focus, and focus outlines are visible.
   
    - 2.1.1 Keyboard Accessibility (index.html, about.html, projects.html, personal.html, contact.html, sitemap.html)
        Buttons, details, and links are all keyboard-operable and focus outlines are visible.
    
    - 2.3.1 Flashes (index.html, about.html, projects.html, personal.html, contact.html)
        No flashing or fast visual changes. Motion is guided by user prefers-reduced-motion setting.
    
    - 2.4.1 Bypass Blocks (index.html, about.html, projects.html, personal.html, contact.html, sitemap.html)
        Each page has a “Skip to main content” link. Navigation links are inside a <nav> with a <ul>.
    
    - 2.4.2 Page Titled (index.html, about.html, projects.html, personal.html, contact.html, sitemap.html)
        All titles are page-specific and descriptive.
    
    - 2.4.4 Link Purpose
        All link labels are meaningful like “Projects,” “View Code,” “Send Email”.
    
    - 2.4.5 Multiple Ways (index.html, about.html, projects.html, personal.html, contact.html, sitemap.html)
        Sitemap.html exists in every footer.
    
    - 2.4.6 Headings and Labels (index.html, about.html, projects.html, personal.html, contact.html, sitemap.html)
        Heading follow proper hierarchy.
    
    - 3.1.2 Language Parts (index.html, about.html, projects.html, personal.html, contact.html, sitemap.html)
        Pages are in English
    
    - 3.2.3 Consistent Navigation (index.html, about.html, projects.html, personal.html, contact.html, sitemap.html)
        Navigation order and layout are consistent.
    
    - 3.2.4 Consistent Identification (index.html, about.html, projects.html, personal.html, contact.html, sitemap.html)
        No long quotations on any page. 

    CSS Validation Warnings:
    - -webkit-font-smoothing is a vendor extension (line 67)
        I ignored this because it improves text rendering on WebKit browsers and is standard practice.

    - -moz-osx-font-smoothing is a vendor extension (line 68)
        I ignored this because it helps text rendering.

    - ::-webkit-details-marker is a vendor extended pseudo-element (line 130)
        I ignored this because it's needed to style the navigation menu's play button icon.

    - The property clip is deprecated (line 147)
        I ignored this because it's widely supported and used for the .visually-hidden class.

    - -webkit-background-clip is a vendor extension (line 194)
        I ignored this because it's the standard way to create gradient texts, and only way through webkit.

    - -webkit-text-fill-color is a vendor extension (line 195)
        I ignored this because it's required to create gradient text effects and works with -webkit-background-clip.

    - The value text is deprecated (line 196)
        I ignored this because it's widely supported and necessary for gradient text. The newer alternative still requires the -webkit- prefix.

4. How long, in hours, did it take you to complete this assignment?
    - I worked on this assignment for around 15 or more hours.


5. What online resources did you consult when completing this assignment? (list specific URLs, describe queries to Generative AI, or use of AI-based code completion)
    - https://www.chatgpt.com (Types of queries: line between aesthetics and accessibility, how to create gradients in CSS, CSS/HTML vocabulary)
    - https://www.w3schools.com (CSS/HTML/Javascript formatting)


6. What classmates or other individuals did you consult as part of this assignment? What did you discuss?
    - Carson Truong (We discussed how we should format the readme for the final version's potential problems on the validation checker.)


7. Is there anything special we need to know in order to run your code?
    - N/A
