(Developer: Slava Kondriianenko)
<hr>
The website represents three pages with Guess a Number game, Quiz about math and contact form which send an email to site owner.

![Responsible mockup of the website](docs/am-i-responsive.png)

[Live website](https://viacheslav1510.github.io/Portfolio_Project_2-Guess_game-Math_quiz/)

## Table of Content
- [Table of Content](#table-of-content)
- [Project Goals](#project-goals)
  - [User Goals](#user-goals)
  - [Site Owner Goals](#site-owner-goals)
- [User Experience](#user-experience)
  - [Target Audience](#target-audience)
  - [User Requirements and Expectations](#user-requirements-and-expectations)
  - [User Stories](#user-stories)
    - [First-time User](#first-time-user)
    - [Returning User](#returning-user)
    - [Site Owner](#site-owner)
- [Design](#design)
  - [Design Choices](#design-choices)
  - [Colour](#colour)
  - [Font](#font)
  - [Structure](#structure)
  - [Wireframes](#wireframes)
- [Technologies Used](#technologies-used)
  - [Languages](#languages)
  - [Frameworks, Libraries \& Tools](#frameworks-libraries--tools)
- [Features](#features)
  - [Guess a Number game page](#guess-a-number-game-page)
    - [Page loaded](#page-loaded)
    - [Game started](#game-started)
  - [Quiz game](#quiz-game)
    - [Page loaded](#page-loaded-1)
    - [User started quiz](#user-started-quiz)
    - [Quiz finished](#quiz-finished)
  - [Contact page](#contact-page)
    - [Page loaded](#page-loaded-2)
    - [Submitted message](#submitted-message)
  - [Footer](#footer)
- [Validation](#validation)
  - [HTML Validation](#html-validation)
  - [CSS Validation](#css-validation)
  - [JavaScript Validation](#javascript-validation)
  - [Accessibility](#accessibility)
  - [Performance](#performance)
  - [Browser compatibility](#browser-compatibility)
- [Testing user stories](#testing-user-stories)

## Project Goals
### User Goals
- Have fun playing the Guess a Number game
- Pass the math test and get the highest possible score
- Contact developer to suggest an idea or get feedback
### Site Owner Goals
- Entertain the website user
- Find an interested client for further site development
- Allow the user to contact the developer

## User Experience
### Target Audience
- People who want to have fun
- Developers who want to get an idea for their projects
- Customers who want to find a developer for their product
### User Requirements and Expectations
- Great interactive content that will make the customer think about hire a developer
- Intuitive navigation which will help you navigate the site easily
- A pleasant design that will make the user stay on the site
- An easy way to contact the site owner

### User Stories
#### First-time User 
1. As a first time user I want to understant what this site about
2. As a first time user I want to play interactive game
3. I want program to memorize my high score
4. I want play game as many times as i want
5. As a first time user I want to navigate easily between pages
6. I want to try another game
7. I want to pass quiz and get the highest possible score
8. As a first time user I want to see quiz progress
9. I want to contact the website owner
#### Returning User
10. As a a returning user I want to play game again
11. As a a returning user I want to make my best on quiz
12. I want to contact site owner and get feedback
13. As a a returning user I want to find developer on social media
#### Site Owner
14. As the site owner I want users to easy find what this website about
15. As the site owner I want to interest the user in my games
16. As the site owner I want users to contact me easily

## Design
### Design Choices
The design across the pages was kept simple and consistent. Background presented with Background image and main container background was taken from [mycolor.space - color palettes](https://mycolor.space/)
### Colour 
Red color chosen to math reset game button and highlight the high score. Maroon color chosen for buttons and footer navigation. Color palette gradient was chosen for main game bakcground and quiz progress bar. To narrow down the colours I used Adobe Color. 
<br>
![Colour scheme](docs/features/colors.png)

### Font
Google Fonts were implemented on the website. Roboto with sans-serif fallback was used across all screens as I found it highly readable and clear.
### Structure
The pages is structured in a well know, recognizable, user friendly, and easy to learn way. Each screen of the website appears in the similar containers with maintained harmony of all elements within.
The website cosists of three separate pages:
- First page / Guess a Number game:
  - Game main section with changable message, GIF animation, input for number and Guess button for check answer
  - Current score and Attempts left labels under the Guess button
  - Reset game button and Highest score label above main section
  - Footer with links for Quiz, Contact form and link for social media Linkedin
- Second page / Math Quiz:
  - Maing section with questions, four answer variants and button for answer
  - Current score label and progress bar above main section
  - Footer with links to Guess a Number game, Contact form and link for social media Linkedin
- Third page / Contact form:
  - Maing section with name, email and message input. Button Send Message under the message text area
  - Footer with links to Guess a Number game, Quiz and link for social media Linkedin
### Wireframes
<details><summary>Big Screens</summary>
<img src="docs/wireframes/big-screens.png">
</details>
<details><summary>Medium screens - tablets</summary>
<img src="docs/wireframes/medium-screens.png">
</details>
<details><summary>Small screens - mobile</summary>
<img src="docs/wireframes/small-screens.png">
</details>

## Technologies Used
### Languages
- HTML
- CSS
- JavaScript
### Frameworks, Libraries & Tools
- [Am I Responsive](https://ui.dev/amiresponsive) was used to create the multi-device mock-up you can see at the start of this README.md file
- [ColorSpace](mycolor.space) - used to make background palette for main containers
- [Balsamiq](https://balsamiq.com/) to create the wireframes for the project
- [Font Awesome](https://fontawesome.com/) - Icons from Font Awesome were used for footer icons
- [Favicon.io](https://favicon.io) for making the site favicon
- [GIPHY - Be Animated](https://giphy.com/) - Was used for Guess a Number game main images
- [Google Fonts](https://fonts.google.com/)
- Microsoft Paint was used to create pictures for docs
- [Walpapers Platform](https://wallpaperset.com/) was used for background image
- [gitpod.io](https://www.gitpod.io/) was used for coding and to push the code to GitHub
- [GitHub](https://github.com/) was used as a remote repository to store project code
- [Chrome dev tools](https://developers.google.com/web/tools/chrome-devtools) were used for debugging of the code and check site for responsiveness
- [WC3 Validator](https://validator.w3.org/), [Jigsaw W3 Validator](https://jigsaw.w3.org/css-validator/), [JShint](https://jshint.com/), [Wave Validator](https://wave.webaim.org/), [Lighthouse](https://developers.google.com/web/tools/lighthouse/) and [Am I Responsive](http://ami.responsivedesign.is/) were all used to validate the website

## Features
The website has 3 webpages
### Guess a Number game page
#### Page loaded
  - When the page is loaded you can see title what this game about
  - The user has input field and guess button to play. User is asked to enter their
  guess in numbers  
  - The user can refresh the game with refresh button
  - The user can see attempts left, current score and highest score labels
  - User stories covered: 1, 10, 14.
<details><summary>See feature</summary>
<img src="docs/features/guess-loaded.png">
</details>

#### Game started
  - Depends to user input program checks is it copares to guess number and changes title GIF and message.
  - With each input program decreases attempts left and current score
  - Program memorize highest score and shows it in "Highest score" label
  - User can reset the game and start to beat their score.
  - User stories covered: 2, 3, 4, 10
<details><summary>See feature</summary>
<img src="docs/features/guess-started1.png">
<img src="docs/features/guess-started2.png">
</details>

### Quiz game
#### Page loaded
  - Main quiz container shows random answer and four answer options
  - User can choose answer radio button submit it with "Answer" button
  - Webpage shows current score on the top of the page
  - Progress bar under current score is clear before first answer
  - User stories covered: 7
<details><summary>See feature</summary>
<img src="docs/features/quiz-loaded.png">
</details>

#### User started quiz
  - Main quiz container shows another questions
  - Progress bar start fill up
  - Current score changes when answer is right
  - User stories covered: 8
<details><summary>See feature</summary>
<img src="docs/features/started-quiz.png">
</details>  

#### Quiz finished
  - User can see their finish score
  - User receives message about their progress and have oportunity to pass quiz again with "Play Again" button
  - Progress bar is filled up to 100%
  - User stories covered: 7, 11
<details><summary>See feature</summary>
<img src="docs/features/finished-quiz.png">
</details>

### Contact page
#### Page loaded
  - When page loaded user can see contact form with name input, email input and message textarea
  - All inputs have to be filled up
  - Message button submit user inputs
  - Site owner receives user meassage on his email
  - User stories covered: 9, 16
<details><summary>See feature</summary>
<img src="docs/features/contact-loaded.png">
</details>

#### Submitted message
  - When user send message they receive status notification
  - If submit successful user see "Thank You" gif and have opportunity to send another message
  - User stories covered: 12
<details><summary>See feature</summary>
<img src="docs/features/contact-submitted.png">
</details>

### Footer
  - Footer links help user to navigate through website
  - Every page has Linkedin social media link and another two links are different
  - User stories covered: 5, 13
<details><summary>Guess footer</summary>
<img src="docs/features/guess-footer.png">
</details>
<details><summary>Quiz footer</summary>
<img src="docs/features/quiz-footer.png">
</details>
<details><summary>Contact footer</summary>
<img src="docs/features/contact-footer.png">
</details>

## Validation
### HTML Validation
Tested HTML code with [W3C Validator](https://validator.w3.org/). Passed with no errors. 
<details><summary>Guess page</summary>
<img src="docs/validation/html/guess-html-validation.png" alt="HTML Validation">
</details>
<details><summary>Quiz page</summary>
<img src="docs/validation/html/quiz-html-validation.png" alt="HTML Validation">
</details>

HTML validation for contact page shows two warnings about JavaScript type attribute , but I didn't want to change it because this script was taken from EmailJS documentation.
<details><summary>Contact page</summary>
<img src="docs/validation/html/contact-html-validation.png" alt="HTML Validation">
</details>

### CSS Validation
Tested CSS code with [W3C Jigsaw CSS Validation Service](https://jigsaw.w3.org/css-validator/). Passed with no errors.
<details><summary>All site</summary>
<img src="docs/validation/css/css-validation.png" alt="Css Validation">
</details>

### JavaScript Validation
[JSHint](https://jshint.com/) JS Validation Service was used to validate the Javascript files. Passed with no errors.
<details><summary>guess.js</summary>
<img src="docs/validation/js/game-js.png" alt="Js Validation">
</details>
<details><summary>quiz-code.js</summary>
<img src="docs/validation/js/quiz-js.png" alt="Js Validation">
</details>
<details><summary>contact.js</summary>
<img src="docs/validation/js/contact-js.png" alt="Js Validation">
</details>

### Accessibility
[Wave Validator](https://wave.webaim.org/) web accessibility evaluation tool was used to ensure the website met high accessibility standards.
<details><summary>Guess a Number page</summary>
<img src="docs/validation/accessebility/accessebility-guess.png" alt="Accessebility Validation">
</details>
<details><summary>Quiz page</summary>
<img src="docs/validation/accessebility/accessebility-quiz.png" alt="Accessebility Validation">
</details>
<details><summary>Contact page</summary>
<img src="docs/validation/accessebility/accessebility-contact.png" alt="Accessebility Validation">
</details>

### Performance
Google Lighthouse in Google Chrome Developer Tools was used to test the performance of the website.
- Guess a Number page. Performace is not good enough because I'm using external link for main GIF animation instead of video format.
  - <details><summary>Desktop</summary>
    <img src="docs/validation/performance/guess-performance-desktop.png" alt="Performance">
    </details>
  - <details><summary>Mobile</summary>
    <img src="docs/validation/performance/guess-performance-mobile.png" alt="Performance">
    </details>
- Quiz page
  - <details><summary>Desktop</summary>
    <img src="docs/validation/performance/quiz-performance-desktop.png" alt="Performance">
    </details>
  - <details><summary>Mobile</summary>
    <img src="docs/validation/performance/quiz-performance-mobile.png" alt="Performance">
    </details>
- Contact page
  - <details><summary>Desktop</summary>
    <img src="docs/validation/performance/contact-performance-desktop.png" alt="Performance">
    </details>
  - <details><summary>Mobile</summary>
    <img src="docs/validation/performance/contact-performance-mobile.png" alt="Performance">
    </details>

### Browser compatibility
The website was tested on the following browsers:
- Google Chrome
- Mozilla Firefox
- Microsoft Egde
- Safari

## Testing user stories
1. As a first time user I want to understant what this site about

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Guess a Number game page| Open Webpage | User can see main message what to do next to play| Works as expected |

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/story1.png">
</details>

2. As a first time user I want to play interactive game

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Guess a Number game page | Enter number in input field | User can see their input| Works as expected |
| Guess a Number game page | Click "Guess" button or press "Enter" | User can see message about their guess| Works as expected |

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/story2-1.png">
<img src="docs/user-story-testing/story2-2.png">
</details>

3. I want program to memorize my high score

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Guess a Number game page | Play all game | User can see their high score| Works as expected |

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/story3.png">
</details>

4. I want play game as many times as i want

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Guess a Number game page | Click reset button | User can try to guess another number| Works as expected |

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/story4.png">
</details>

5. As a first time user I want to navigate easily between pages

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Footer | Click any link | User can navigate between pages| Works as expected |

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/story5-1.png">
<img src="docs/user-story-testing/story5-2.png">
</details>

6. I want to try another game

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Footer | Click quiz link | User can see quiz page| Works as expected |
| Quiz game | Chose answer option and click "Answer" button | User can pass 10 questions quiz | Works as expected |

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/story6-1.png">
<img src="docs/user-story-testing/story6-2.png">
<img src="docs/user-story-testing/story6-3.png">
</details>

7. I want to pass quiz and get the highest possible score

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Quiz game | Pass the quiz | User can see their score and message| Works as expected |

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/story7.png">
</details>

8. As a first time user I want to see quiz progress

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Quiz game | Anwer the question | User can see progress bar in %| Works as expected |

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/story8.png">
</details>

9. I want to contact the website owner

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Footer | Click envelope icon | User can see contact form| Works as expected |
| Contact page | Fill out the from and click  | User can see contact form| Works as expected |

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/story9-1.png">
<img src="docs/user-story-testing/story9-2.png">
</details>

10. As a a returning user I want to play game again
    
| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Guess a Number game page| Open Webpage and play game | User can see main message what to do next to play| Works as expected |

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/story10.png">
</details>

11. As a a returning user I want to make my best on quiz

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Quiz game | Pass the quiz | User can see their score and message| Works as expected |

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/story11.png">
</details>

12. I want to contact site owner and get feedback

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Contact page| Send message | User can see their feedback and contact form send message on site owner email| Works as expected |

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/story12.png">
</details>

13. As a a returning user I want to find developer on social media

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Footer| Click LinkedIn link| User can site owner LinkedIn page| Works as expected |

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/story13-1.png">
<img src="docs/user-story-testing/story13-2.png">
</details>