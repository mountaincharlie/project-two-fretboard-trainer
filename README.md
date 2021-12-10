# Fretboard Trainer (finish)

Fretboard Trainer is an interactive website which uses an adjustable multi-choice style quiz, to help those who want to improve their ability to recognise the notes on a 6-stringed guitar in standard tuning. The rules and design are simple and intuative and since the Trainer is based on the layout of a real guitar fretboard, it has a real life application.

This site provides a quick and easy way for guitarists, with different levels of experience, to test and train their knowledge of the guitar fretboard. The Trainer can be used on any platform from a laptop to a phone and for as long or short a time as the user wishes. 

![Viewing my website on the Am I Responsive site](./assets/images/am-i-responsive-screenshot.jpg "Fretboard Trainer website on the Am I Responsive site")

[Image made using <a href = "http://ami.responsivedesign.is/">Am I Responsive Website</a>]

## Contents
---

* [Technologies Used](https://github.com/mountaincharlie/project-two-fretboard-trainer#technologies-used)
* ['section name'](full github url from deployed site)
* 
* 
 
## Technologies Used 
---

* HTML
* CSS
* JavaScript

## Game Instructions  (finish)
---

1. The game is started by clicking either the 'START GAME' or

## Features (finish)
---

### Header
* [image]
* Heading and guitar icon

### Favicon
* [image]
* same as the guitar icon in the header 

### The fretboard
* [image]
* open string notes
* fret numbers 
* [image shows highlight]
* strings where the random note is highlighted 

### Game Settings section
* [image whole]
* Instructions/warnings [image]
    * None of the settings have to be used as there are set defaults so the user can start playing right away.
* Adjustable settings [image example of what they affect]
    * 'Number of questions' dropdown list
    * 'Number of answers' dropdown list
    * 'Hide open string notes' checkbox
    * 'Hide fret numbers' checkbox
* APPLY & START button [image]
* RESET GAME button [image]

### Game Play section
* Instructions screen [image]
* Questions Screen [image]
* Answer Check Screen [image] 
    * message
    * red/green highlights
* Score Screen [image]
    * fraction and percentage scores
    * highlight red/green for 50% or over
    * instructional message for continuing

### Game Progress section
* [image]
* Question counter 
    * Out of 10 by default
    * Can be adjusted by Game Settings
    * Is used to trigger the score screen
* Right/wrong counters
    * Set to 0 initially 
    * Are updated when the Answer Check Screen is displayed 


## User Experience Design (finish)
---

### Styling 
The styling and layout of the game remains consistent throughout the sections, making it more intuative for the user to interact with and understand the purpose of each section.
* Colour scheme: I chose a dark teal (#2f6168) for the main colour of the game, an orange (#ff8c3f) accent colour throughout the different sections and kept a white background behind the sections and fretboard diagram and white text for the instructional messages, for good contrast.
* Fonts: 
    * Google Font's 'Titillium Web' for all the headings (h1, h2 and h4 elements).
    * Google Font's 'Dosis' for all of the other text on the screen (Instructions, scores, settings, questions and counters).
* Icons:
    * Icon8's 'Guitar icon in Pastel Glyph Style' as an icon with the Fretboard Trainer logo next in the game heading.
    * Favicon made from the same 'Guitar icon in Pastel Glyph Style', for continuity.
* Continuity throughout the game: 
    * The styling and layout of the game remains consistent throughout the sections.
    * Game feedback and instructions are always presented in the central Game Play section making it more intuative for the user.

### Content and Interactivity
* The fretboard diagram:
    * remains at the top of the screen throughout the game so that the user is always aware of where to find it if they are viewing it on a mobile device and have to scroll.
* Layout on smaller screens:
    * when viewed on screen with a width of 830px or less, CSS Media Queries have been used to organise the three game sections ontop of one another. 
    * in order to reduce the user needing to scroll while playing the game, the Game Play section is positioned immediately below the fretboard diagram, with the Game Progress directly below this and the Game Settings at the bottom since they are not required while the game is being played.    
* The central Game Play section:
    * contains clear instructions for the game and the other two sections (Game Settings and Game Progress) to ensure the user understands the purpose of the site and the functions of each section as soon as they land on the page. 
    * this section displays the Instructions screen, Check Answer screen and Score screen each with clear feedback for the user and buttons labelled specific to their function (e.g. the 'CHECK ANSWER' button to check if the right answer was selected or the 'NEXT QUESTION' button to generate and display the next question).
* The Game Settings section:
    * remains unchanged during the game, but can be accessed by the user at any point. 
    * dropdown boxes and checkboxes have been used instead of free typing inputs for the user. This is to both make it simpler and quicker for the user to adjust settings and also prevents the user inputting values which would break the game.
* The Game Progress section:
    * the counters are updated as neccessary during the game, as part of the feedback to the user and are reset/adjusted any time the game is refreshed or new settings are applied. 
    * they are also styled to fit with the rest of the site, but differently enough from the buttons so that the user doesn't confuse them as something that can be clicked.


## Interactivity
---

### To do:
* breakdown all the interactivity and how the JS makes it possible (INCLUDE SCREENSHOTS)
    * Default settings
    * User settings (how they override the defaults - Number of questions, number of answers, hide open notes and hide fret numbers)
    * Fret check button (which shows the notes - IF YOU INCLUDE IT - and why it disables the game etc)
    * Answers section 
    * Counter section (how it updates and is affect by default/user settings and IF YOU INCLUDE THE PLOT PROGRESS button)

## Accessability
---

### To do:

### Semantic elements
* which elements u used to define the strcuture of the page

### Aria-labels
* IS IT POSSIBLE FOR THE SCREEN READER TO READ OUT THE LOCATION OF THE HIGHLIGHTED NOTE?    
* to internal/external links ??
* to inputs which display text which may not be interactive ??

### Attributes
* alts added to image elements
* any role attributes used (on divs, spans, or anything none semantic)

## Testing
---

### To do:

### HTML & CSS validator warnings and fixes
* any warnings that come up and how you fixed them

### HTML Validation in Offical W3C Validator
* SHOULD BE: No errors or warnings
* LINK TO THE 'by url'

### CSS Validation in Offical Jigsaw Validator
* SHOULD BE: No errors or warnings
* LINK TO THE 'by url'

### JS Check in JSHint
* SHOULD BE: No errors or warnings
* LINK IF ONE AVALIABLE

### Lighthouse Accessability score

![Screenshot of Google Dev Tool's Lighthouse Score for my website](#image-location "Google Dev Tool's Lighthouse Score for my website") 

### Bugs and Fixes
* [date] any bugs
    * their fixes (links/images where relevant)
* I used the 'select' element for the 'Number of questions' and 'Number of Answers' settings to limit the user's options to the most reasonable ones so that the user doesn't have to type in their own value and can't choose a value which would cause an error.
* 

### Unfixed bugs
* SHOULD BE: No unfixed bugs

## Deployment
---

### To do:

### Deployment Process on GitHub
* How you diployed it with GitHub Pages 
* ...

### Live website link
* link to live website

## Credits
---

### To do:

### External Code:
* anything used from external sources ??

### Research on ...
* anything you did research on for the site ??

### Page styling
* Google fonts links ??
* Colour pallette links ??

### Icons
* any icons used ??

### Images
* any images used ??

### Page content
* anything you used particularly for page content ??

##  Site Expansion Ideas
---

Features that could be added to expand and improve the website in the future.

### To do:

### Improvement idea
* How it would work/why it would be good