# Web-Development Quiz App

## About this project

This project was developed as part of Thinkful's full stack program. My goal was to create a mobile-first front-end application with a clean UI that supports multiple question libraries and automatically generates wrong answer options.

### Requirements

#### User experience requirements
The following requirements cover what the app must do, from the user's perspective.

- The starting screen should have a button that users can click to start the quiz. 
- Users should be prompted through a series of at least 5 multiple choice questions that they can answer. 
    - Users should be asked questions 1 after the other. 
    - Users should only be prompted with 1 question at a time. 
- Users should not be able to skip questions. 
- Users should also be able to see which question they're on (for instance, "7 out of 10") and their current score ("5 correct, 2 incorrect"). 
- Upon submitting an answer, users should:
    - receive textual feedback about their answer. If they were incorrect, they should be told the correct answer. 
    - be moved onto the next question (or interact with an element to move on). 
- Users should be shown their overall score at the end of the quiz. In other words, how many questions they got right out of the total questions asked. 
- Users should be able to start a new quiz. 

#### Technical requirements
Your quiz app must:

- Render answer choices in a `<form>`. 
- Use semantic HTML, along with CSS and jQuery. 
- Follow a11y best practices.
    - Refer back to the checkpoints on accessibility and forms for help.
- Use responsive design. 
- Be fully usable by keyboard (which will be easy enough if you start with a form). 

#### Process requirements
Before you dive into the app, you'll need to:

- gather content for your app. That means typing up the questions you'll ask and gathering any images or icons you'll need.
- think about the user experiences outlined above and how your design must make them possible.
- design your app using HTML wireframes, which are HTML- (and minimal CSS-) only versions of the different screens in your app.

### My approach

- Mobile first design
    - Kept the layout simple for mobile usage
    - Used media queries to resize the page for desktops
- No page re-loads
- Opted to keep as many elements on the page as static as possible to reduce visual confusion

### Future Features and Improvements
- ~~Randomized question order~~
- ~~Randomized answer order~~
- 'Learn more' link provided on wrong answers
- ~~Additional quiz libraries for study, with a way to switch between them~~
- ~~Fix the question section so that it doesn't reposition when the feedback view is rendered~~

### Development Road Map
1. ~~Create a function that assembles an array of wrong answers~~
2. ~~Make the renderQuestions grab 2 random elements from the wrongAnswers array~~
    1. ~~Check that the randomly selected elements do not have the same string value as the real answer~~
