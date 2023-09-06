# HTML & CSS Review

## Overview

This exercise is to assess where you all individually stand at the beginning of the term. I encourage you to complete each task on your own but I am open to you working together so long as each student fully understands what they are submitting.

Reference the screenshot of the styled page to double check it matches your work. I have provided screenshots in both pdf and png format. 

We will review the exercise together next class.


## Creating files and organizing project

1. Fork this repository and clone down to your local environment using Github Desktop. Remember that you will not be able to easily move this project once cloned so pick a location where it can stay. Example: dsn1713 --> week 1 folder.
2. Create a CSS file named `style.css` and place it in a `css` folder.
3. Link the new css file to your `index.html`.
4. Embed two Google fonts (listed below) in the `<head>` of your html:
  - Wix Madefor Display `ExtraBold 800`
  - Nunito `Regular 400`
5. Organize images that will be displayed on your web page into their own `images` folder.
6. Review all filenames and confirm they are using proper naming conventions.
7. Commit and push up your work to GitHub to confirm all is working as it should.
8. On Github, adjust the repository settings to enable GitHub pages. Settings --> Pages --> Under Branch choose main --> Save. This is the link you will submit to Brightspace.


## HTML related tasks

Now we're ready to update the HTML. Content has been placed in the index.html file but you are to apply the html tags.

1. Assign appropriate regions to your content
  - `header`
  - `nav`
  - `main`
  - `footer`

2. Assign semantic html to your content. Consider what each individual piece of content is, and which html element should be used to give more meaning to the content. There are cheatsheets on Brightspace to help you out. **Remember that all pieces of content must use an html tag.**

3. Apply accessibility features where required (ex. landmark roles, alt attribute, aria-label, etc..)


## CSS related tasks

Apply styling to elements to match the provided design. There are screenshots of the page in the root directory (pdf and png).

1. Select `*` and apply `box-sizing: border-box;`

2. Select `body`
  - Set the default font family to be `Nunito`
  - Set the text color to `#fff`. This is the most common color on the page for text but I would wait to apply this until all background colors are in place so that you can see the text.
  - Set line height to `1.5`

3. Create a class for `wrapper` and add the class to the appropriate html elements so that it is used to contain the content in the middle of the page. This would ideally be applied to each section since the hero image spans the full width of the page.
  - Set a max width of `1200px` for the wrapper.
  - Center the content in the middle of the page using the `margin` property.

4. Update CSS to reflect design provided using properties covered last term
  - Heading (h1-h3) font sizes (remember to set as rem).
  - Background colors, font colors, etc..
  - Color values used in the layout: #7251B5, #DEC9E9, #6647A6, #fff and #000
  - Notice the text-shadow on the heading in the hero banner.
  - Change employee images to grayscale using the `filter` property. 
  - Margin and padding

5. Use Grid property for a minimum of one element.

6. Use Flexbox property for a minimum of one element.



## Validate your work

1. Validate your HTML [here] (https://validator.w3.org/#validate_by_input)

2. Validate your CSS [here] (https://jigsaw.w3.org/css-validator/#validate_by_input)



## How to submit your assignment

Submit a link to your GitHub page for this repo to the appropriate Brightspace assignment.

Ex. https://wendywarren.github.io/html-css-review/

This is worth marks in the rubric so please submit to your webpage on Github and NOT your repo (with code).