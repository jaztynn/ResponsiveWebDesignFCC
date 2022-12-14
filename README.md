# Responsive Web Design Project Documentation
Link: https://jaztynn.github.io/ResponsiveWebDesignFCC/ 
- CAT PHOTO APP
  - learnt HTML
  - only used HTML, no CSS
  - learnt about headings (h1, h2, etc.), unordered list, figure & figcaption, ordered list, section, fieldset, legend, input, button, form, main & footer (both are descendants of body)
  - title in head will contain name of tab
- CAFE MENU
  - learnt basic CSS
  - first exercise to use css, learnt to use link element in head
  - learnt div and attributing class
  - used url() for background-image
  - font-family is used to change font
  - .class{} and element{}
  - commas can be used to attribute style to multiple things at once
  - use to /*comment*/
  - can change style of a hyperlink with a{}, a:visited{}, a:hover{}, a:active{}
- COLORED MARKERS
  - learnt CSS colors
  - played around with class attribute a lot in div
  - can use shorthand margin: vertical-value horizontal-value;
  - played with linear-gradient: angle is 180deg by default, can have as many colours as you want, and it will be evenly distributed. separate with commas. put percentage after the colour of how much you want it to cover;
  - box-shadow: top right bottem left colour;
  - color can use rgb/rgba(x,x,x,[alpha in decimal]), hsl/hsla(hue[degree around colour wheel],saturation[%],lightness[%],[alpha in decimal]), #------/#-------
  - display: inline-block; makes block element act like in-line element
- REGISTRATION FORM
  - learnt HTML forms
  - fieldset, label with for attribute, for in label must match id attribute in input
  - input type default is text, can be email, number, radio, checkbox, image
  - required attribute makes field mandatory
  - select element is the dropdown input, must include id and name (same value usually)
  - option element descendant of select
  - label encloses input
  - textarea element size can be specified by rows and columns
  - input can have placeholder
  - submit button must have type="submit" and value="submit"
  - radio type input must have same name values if only one option is allowable
  - file can be uploaded as input if input type specified as file
  - form element can have method attribute. value for method was post and action was link
  - can use em as unit (relative size to current font)
- _**SURVEY FORM (CERTIFICATION PROJECT)**_
  - venom inspired because I watched the movie before working on the project
  - mostly made use of what I've learnt from the direct previous exercise, but really it was a mix of everything I've learnt so far
  - went a little further by using fonts from google
- ROTHKO PAINTING
  - learnt CSS box model
  - learnt filter: blur()
  - learnt border-radius can also take different values, starting from top-left going clockwise
  - transform: rotate(angle in deg); negative value gives anti-clockwise, positive value gives clockwise
  - reinforced that elements, e.g. width can take on values that are auto, minimum, maximum, percentage, etc.
- PHOTO GALLERY
  - learnt CSS flexbox
  - used header element
  - used * selector
  - used box-sizing: border-box;
  - no margin, margin value set to 0
  - font-family value no need ""
  - ::after pseudo-element creates an element that is the last child (no space)
- NUTRITION LABEL
  - learnt CSS typography
  - used 2 links, one to styles.css and one to __ to import the Open Sans font
  - Open Sans font needed to typed in as "Open Sans" while fallback font sans-serif is good on its own
  - two fonts were separated by comma
  - "*" selector selects all elements
  - reminder that each element/.class{} are called rules
  - font-weight is how bold the font is
  - rem unit stands for root em and is relative to the font size of the html element
  - learnt about span element and how to give it float
  - :not() pseudo selector can be used to select all elements that do not match the given CSS rule
- QUIZ
  - learnt accessibility
  - to use id attribute as selector, use #value
  - to use flexbox for display, wirte display: flex;
  - element within element in css is element > element{}
  - used method="post" for the form element, alongside action="<link to submitform to>"
  - used guide: https://design-style-guide.freecodecamp.org/
  - used aria-labelledby="" for section. id inside must match value.
  - element id can be used as href for anchor (a) element, href="#id-value"
  - made use of placeholders in input
  - placeholders may actually confuse users because they will think there is already an input, remove placeholder for better accessibility
  - select element nests option elements (select.option)
  - used required attribute
  - used break element </br> for line by line text
  - on the topic of accessibility, contrast between elements is key
  - usd inherit element for anchor tags to be of same colour as other text
  - text-decoration set to none for anchor tag
  - changed cursor: pointer; in anchor:hover
  - used aspect-ratio:35/4; for #logo rule
  - use border:none; instead of border:0;
  - list-style:none; can be used to remove list default styles
  - changed scroll-behavior to smooth
  - @-rule can nest rule
  - accesskey attribute an be used as shortcut

## Upcoming uploads:
- _**TRIBUTE PAGE (CERTIFICATION PROJECT)**_
  - ideas: chadwick boseman tribute
- BALANCE SHEET
- PICASSO PAINTING
- PIANO
- _**TECHNICAL DOCUMENTATION PAGE (CERTIFCATION PROJECT)**_
  - ideas: my own subjects, how to study for the diff subjects in uni, important websites?
- CITY SKYLINE
- MAGAZINE
- _**PRODUCT LANDING PAGE (CERTIFICATION PROJECT)**_
  -ideas: iron man suits
- FERRIS WHEEL
- PENGUIN
- _**PERSONAL PORTFOLIO WEBPAGE (CERTIFICATION PROJECT)**_
  - ideas: photographs, medium publications, socials, github projects, resume from linkedin
