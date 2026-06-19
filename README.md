# One Pager Project

[top](#one-pager-project) | [learning target](#learning-target) | [requirements](#requirements) | [instructions](#instructions) | [FTW: For the Win](#for-the-win)

## Learning Target: 
Students will be generate a **one pager** web project devoted to a topic of choice (a business, historical event or person, how to instructional page, travel destination, or something similar). This page will apply a variety of common HTML elements and apply basic CSS techniques to apply fonts and colors.

[top](#one-pager-project) | [learning target](#learning-target) | [requirements](#requirements) | [instructions](#instructions) | [FTW: For the Win](#for-the-win)

## Requirements:
NOTE: for the course outcome related to `HTML` and `CSS`, your score will be calculated using the pytest tests.
### HTML Requirements
* Your one-pager must be named `index.html`
* Must ***use appropriate headers*** according to semantic reasoning
* Must have at least ***two sections*** each labeled ***with an appropriate header***.
    - should be level 2 headings.
    - sub headings (level 3) are allowed, but only if you are breaking up a section into sub-sections 
* Must have at least six paragraphs in all (try to not put them all in one section).
* Must pass HTML Validation (test your page using the [w3c validator](https://validator.w3.org/))

### CSS Requirements
* Must ***use CSS*** as a style tag or external stylesheet to add styles.
    - ***You may NOT use the style attribute***
* ***Use a [Google Font](https://fonts.google.com/)*** (not default font)
    - Only 1 font-family is required
    - The font should be readable (avoid fancy and highly stylized fonts)
* ***Colors*** (background and foreground) ***must be applied*** to the page
    - add it to the `body` or `html` tag.
* Make sure it ***passes the [CSS Validator](https://jigsaw.w3.org/css-validator/)***
* Make sure it is readable (using a readable font and a high color contrast)

### For The Win (FTW)
Please meet the following requirements in order to score a 4/4 in each of the following course outcomes:
* "Develop Static Websites...":
    - Add 1 3rd section, which means you will need to have...
        + at least 3 `h2` tags in all
        + at least 9 paragraphs in all
    - Break up each section with a break tag (at least 2 in all)
    - Make a font-pairing using Google fonts (see [Top 50 Google Font Pairings [Handpicked by Pro Designers]](https://www.pagecloud.com/blog/best-google-fonts-pairings))
    - Pick a color palette for your page (from a site such as [coolers.co](https://coolors.co/) or  [Color Hunt](https://colorhunt.co/))
    - Change the color on your headings (`h1` and `h2`) (so they are not the same as your normal text)
    - There is a maximum paragraph width set in `em`s or `rem`s 
    - Make sure any color combinations meet **Color Contrast at a Level AAA**
        + Most text must meet **Normal Level AAA**
        + Large text may meet **Large Level AAA**
        + According to the [Color Contrast Checker](), *"Large text is defined as ...**18.66px and bold or larger**, or ...**24px or larger**."*
* "Apply Design Principles..."":
    - Make sure the colors are from a color palette and they look good.
    - Make sure the colors meet color contrast (see above).
    - Make sure text is readable, and the fonts do not compete with the theme of the content.
    - Make sure text is readable, and the paragraphs are not too wide.
    - Make sure paragraphs are not centered text

### Design Requirements:
Note: these requirements will be scored directly by your teacher.
* Above all, ***text must be readable*** (both through the font-face as well as in the use of high contrast colors)
* Use of fonts (no more than 2) and colors match the content of the site.
* All paragraphs of text are broken up into smaller chunks of text and  left-aligned or justified (NOT centered).
* The only text that may be centered is the headings (`h1` and/or `h2`)
* Typography follows most guidelines of the [Practical Typography Summary of Key Rules](https://practicaltypography.com/summary-of-key-rules.html) especially font size, line spacing, and line length.
* Layout is balanced without any irregular gaps that call attention to themselves. Any images should be floated so the text wraps around it.

[top](#one-pager-project) | [learning target](#learning-target) | [requirements](#requirements) | [instructions](#instructions) | [FTW: For the Win](#for-the-win)

## Instructions:
Once you have accepted the assignment and have a copy of your repo...
1. Open your project in VSCode.
2. Create a file named `index.html` in the project folder.
3. Add the basic HTML code to `index.html`
4. Select a topic to explore where you have access to content (you do not have to write your own content).
    - choose a topic that you can break up into at least three sub-categories.
    - I recommend a favorite topic of yours that you are interested in or pick a unit of study that you have for another class.
5. In the body of `index.html` add the headers you plan to use.
    - Add a title using the most important heading tag.
    - In the `head` section, be sure to provide the same title in the `<title>` tag.
    - Add a sub-title (using the appropriate heading tag) to title each of your sections.
6. In each section add several paragraphs.
    - Each paragraph should be short and scannable.
    - One concise thought per paragraph.
    - No more than 4 sentences per paragraph.
    - Try including several single-sentence paragraphs.
    - Do NOT use `<br>` tags to "create" paragraphs (instead surround each paragraph with a '<p>' tag).
7. Add a `<style>` tag to the head.
8. In the `style` tag, target and style all content using a global selector.
    - change the font using either a ***font stack*** or use a ***[Google font](https://fonts.google.com/)***
    - Find and apply a good, high-contrast color combination for the background and text color
        + colors should go well with the selected topic
        + colors should have a really high contrast
        + use the [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/) (the higher the contrast number the better - aim for 8 or higher)
9. Target and style the headers.
    - I recommend targetting all possible selectors as one.
    - Use another color for the text than you did in step 8.
    - All headers smaller than 18.7px must pass at Normal AA level
        + Headers at least 18.7px or larger may pass at Large AA level and still pass.
10. As you work on your page, be sure to commit and push your changes using the following commands:
    - `git add *`
    - `git commit -m "concise explanation of what you did"`
    - `git push origin main`
11. When you push your changes, check the repo to see if you passed tests.
12. Once you've passed all tests, you will receive a green check and a 4/4 on the GitHub Classroom assignment.
13. To turn in your assignment, take a screen capture of the final product as seen on a browser and turn that in.
    - Your teacher can see if you passed all tests
    - You will then receive a grade based on the scoring categories (see [scoring categories](#scoring-categories))

[top](#one-pager-project) | [learning target](#learning-target) | [requirements](#requirements) | [instructions](#instructions) | [FTW: For the Win](#for-the-win)

## Scoring Categories
Your project will receive a score based on the final criteria:
* HTML requirements
    - you meet all requirements related to the HTML
    - you have no validator errors
* CSS requirements
    - you meet all requirements related to CSS
    - you have no CSS validator errors
* Content & Design
    - You meet or surpass content requirements
    - Your choice of fonts and colors are readable and help the content

[top](#one-pager-project) | [learning target](#learning-target) | [requirements](#requirements) | [instructions](#instructions) | [FTW: For the Win](#for-the-win)

### For the Win...
To get a 4 (above & beyond), you will want to...
* Go above & beyond the list of requirements
* Add additional styles and markup without breaking validation reports
* Demonstrate solid understanding of scannable text
* Make effective and pleasing design decisions (use a space, readability, etc.)

[top](#one-pager-project) | [learning target](#learning-target) | [requirements](#requirements) | [instructions](#instructions) | [FTW: For the Win](#for-the-win)