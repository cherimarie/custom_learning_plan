# Utah's Custom Learning Plan

## Topics

- positioning content with CSS
- accessibility
- HTML forms
- basic js for DOM interaction and manipulation
- exploring the powers of SASS
- building responsive sites

## Selected Learning Goals & Deliverables

- experience using grid layouts, floating, and flexbox for positioning
- comfort with the principles of accessible web design
- creating a checklist of highest return accessibility features that should be included in work projects, perhaps divided into priority items for future & past projects
- creating & giving a 30 minute presentation to colleagues on fundamentals of accessible web design and action items/tools that everyone can use to improve (including above checklist)
- experience building HTML forms with Javascript back ends
- experience building Rails HTML forms
- experience building small Javascript programs that interact with the user and manipulate the DOM
- retrofitting existing Rails projects with better styling, using SASS variables, partials, nesting, mixins, inheritance, and math
- reading [Responsive Design: Patterns & Principles](http://abookapart.com/products/responsive-design-patterns-principles) with colleagues, ideally leading a book club with discussions
- convert a styled existing Rails project to be responsive
- dissect how Bootstrap's responsive grid works
- convert an existing small Javascript project to be responsive

## Using This Repo
Fork this repository. Add my repo as an upstream remote connection so you can update content from me as necessary. Complete your work within your fork. For assignments that require retrofitting an existing project, submit the work by pasting a link to the Pull Request that contains the work in the existing repo to the assignment page.

## Assignments
Assignments can be done in whatever order the student chooses, unless otherwise specified. At least one should be completed per week. Student will submit a pull request to their fork of this repo (or an external, pre-existing repo for retrofit assignments) for each assignment, and recieve code review there.

### HTML & CSS

#####h1:
In the included 'positioning-practice' directory, complete the four provided stylesheets. Follow the instructions in each stylesheet on how to make the provided HTML match the mockup. The goal is to practice positioning items, so matching things like padding or positioning of content within elements is not strictly necessary.

#####h2:
In the included form1.html file, build an HTML form for an imaginary survey for pet owners. Have as much fun with the questions as you want.
Include the following types of inputs:

  1. text
  2. password
  3. telephone
  4. email
  5. number
  6. multi-line text
  7. radio buttons
  8. checkboxes
  9. select with options
  10. file upload
  11. keygen
  12. color
  13. date
  14. range
  15. time
  16. url
  17. submit

Include the following attributes on at least one input (some only work for certain types of inputs):

  1. accept
  2. autocomplete
  3. disabled
  4. inputmode
  5. maxlength
  6. min, max, and step (they all work together)
  7. placeholder
  8. required
  9. BONUS: pattern

Do not include an 'action' attribute for the form, as it will not be submitted to a server. Options, radio buttons, and checkbox elements should include 'value' attributes. Every input should have an appropriate, screen-reader-friendly label. Note in PR description which fun HTML5 attributes & elements do not yet have universal browser support (note: please tell Cheri immediately if Firefox and Safari have started recognizing 'required' because it will make her sleep better at night). This resource may help you: https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Forms

#####h3 (do after h2):
After you've gotten the hang of building forms, build a more reasonable one (like, that doesn't necessarily use every single input possible) in form-w-js.html. It should be a registration form for an imaginary web application, and ask the user some questions about themselves so they can get customized content. You'll later incorporate javascript in this form to make it react to user input.

#####h4 (do after h2):
Revisit one of your Rails application and build a form in it. The form should be to create/edit an object. This will require adding new, create, edit, and update controller methods if they do not already exist, plus 'new', 'edit', and 'form' views. The form should use the 'form-for' syntax. This is different than the 'form-tag' syntax, and the difference can be really obtuse at first. Feel free to grab a buddy to pair with on this. When this assignment is complete, users should be able to create new objects and edit them, with successful database operations. These resources will help:

  1. http://guides.rubyonrails.org/form_helpers.html
  2. http://guides.rubyonrails.org/getting_started.html#the-first-form

### JS

#### j1: In the provided javascript1.html file's <script> tag, write javascript that:
  1. finds all elements on the page with a class of 'cta' and assigns them to a variable
  2. loops through that variable and adds the class 'pink' to every element
  3. loops through that variable again and adds the class 'red' to every other element

  When adding/removing classes, I recommend using the ['classList' property](https://developer.mozilla.org/en-US/docs/Web/API/Element/classList).

#### j2:

#### j3:

#### j4:

### SASS

#### s1:

#### s2:

### Accessibility

#### a1:
Create a checklist of highest return accessibility features that should be included in work projects, perhaps divided into priority items for future & past projects.

#### a2 (do after a1):
Build curriculum for a 30 minute presentation to colleagues on fundamentals of accessible web design and action items/tools that everyone can use to improve (including above checklist).

#### a3 (do after a1 & a2):
Give the presentation on fundamentals of accessible web design. This could be to coworkers as a "lunch and learn", at a meetup event, or just to friends. If it goes well, consider submitting it as a talk proposal to a conference!

#### a4 (do after a1):
Use your checklist on a work project! This isn't really an assignment, because you should be getting paid for it as real work, but I want you to get "credit" for using the cool tool you built.

### Responsive Design

#### r1:
In the provided bootstrap-responsiveness-analysis.md file, explain how Boostrap's responsive grid works. Include details about how users trigger it and how it is implemented. This will require a study of the [Bootstrap source code](https://github.com/twbs/bootstrap). Include code samples and screenshots as necessary. This should be at least 500 words long.

#### r2:

#### r3: