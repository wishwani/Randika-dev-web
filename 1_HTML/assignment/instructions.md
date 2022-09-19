# Assignment for the lesson 1 of the Web Development course

Autumn 2022.

## Planning

- 15/09/2022 : Lesson 1 (Basic HTML+CSS)

Assignment 1 (this one), to begin during the 1st lesson.

- 22/09/2022 : Lesson 2 (HTML forms, CSS preprocessors)

Assignment 2, based on the result of assignment 1. To begin during the 2nd lesson. It is to be submitted
for the 8/10/2022 in the evening.

## Instructions

### Mockup 

Given a mockup that is provided to you, thanks to the work of a web graphic designer and an UX designer,
you have to implement with HTML and CSS the designed webpage.

You will find the raw mockup `./mockups/musicca_mockup.png`, and the annotated mockup 
`./mockups/mockup_annotated.pdf`.

Additionnal data is provided to you in the file `./mockups/variables.md`.

### Integration files

The integration skeleton has already be made for you, it is in the folder `./integration`.
You will find an HTML template, already configured with the correct stylesheets, 
some default CSS stylings and links to the fonts.

You need to write the HTML document `./main.html` and the stylesheet `./style.css` in order
to get a webpage that follow the mockup specifications.

Write your code following the best practices I showed you in the demo example, in particular :
- Give clear and logical (from a semantical point of view) class names to your elements (that 
  is the same as naming correctly your variables)
- Be consistent in the way you write your code : indentation, line breaks, upper/lowercase are important
  and the code must be nice to read.


### Additionnal info

- The "buttons" at the top are links. Set the `href` attribute to a random URL, even if invalid (ex : `href="./404"`)
- You will need to search how to make rounded borders for the buttons at the top. See the CSS property `border-radius`
- Of course, you can find the real "Musicca" website, however you will lose more time trying to copy their code rather than writing it yourself. The goal of this exercise is to write HTML and CSS code by yourself, and try to solve the problem of integrating a mockup, in the most straightforward way. Existing code you may find online is going to be bloated, overly complicated, because the real life scenario is more complex than the one I gave you. Don't fool yourself it's easy to see if you write your own code or try to copy existing code.

# Getting the webpage running 

- You need to run a small web server, use the script `./run.sh` at the root of the repository. 
- Open the URL http://localhost:8000/1_HTML/assignment/integration/main.html