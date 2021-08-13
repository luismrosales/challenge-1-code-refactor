# challenge-1-code-refactor


## acceptance criteria
* Acceptance Criteria
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title

## code refactor to acceptance criteria
### index.html
* the title was changed.
* added an <a> attribute to the <h1> in the header, this allows you tp go back to the main page when clicked.
* an "id" attribute was added to the div so when the link is clicked, it takes us to the desired section.
* an "alt" was added to the image, so it fits the acceptance criteria.
* a footer tag was added to the bottom to identify where the footer is.
### Css.style
* a color of pink was added to the "seo" span to add contrast and meet the acceptance criteria.
* styled the footer to look similar to the header
