# Class - Breakout - Code Quality

## Description 

Improve your code quality by updating your code.

Try to solve the stretch challenges. 

### Why this assignment?

Writing quality code up to professional standards is important. It's hard to know aht professional standards are without a guide. The linter will help you write code that meets industry best practices. 

Trying the stretch challenges is an opportunity to stretch your abilities by solving problems.

## Project requirements

Create a new branch for for your Break Out Repo. You'll place the work for this assignment there. 

Try all of the challenges below. 

### Challenges 

**Challenge 1** Install the Linter. Follow the instructions from class. 

Create an npm project in your project directory and install eslint. 

You'll need to install the linter plugin/extension for your code editor also. 

You'll also need to use a style guide. For this assignmen you should be using the AirBnB JavaScript style guide. 

**Challenge 2** Solve the errors the linter idenitifies in your code. The linter will identify the errors with a red underline and provide some hints as to what the problems are. 

With each change ask yourself why the style guide is asking for that change. Discuss this with other students, TA, or instructor. 

This process should cover the following areas: 

- const, let, and var
- arrow functions 
- template string literals

Pay close attention to these. They are effected by hoisting. A function or var declare lower in code may need to be declared earlier to work properly. 

**Challenge 3** Write a function to draw the background for the game. Currently the `draw()` function clears the canvas on it's first line with: 

`ctx.clearRect(0, 0, canvas.width, canvas.height);`JS

Add a function called `drawBackground()`. Call this on the first line of `draw()`. 

Try these cahllenges: 

- Fill the background with a color other than the default color. Do this by drawing a rectanlge that starts at x 0, y 0 with a width and height that match your canvas. Do all of this in the `drawBackground()` function. 

### Deliverable

A link to the branch of your repo with the code changes used to solve the challenges in this assignment. 

### Due date

Tue, January 28

## Assessing the assignment

Use this rubric to measure the success of your work against expectations of the assginment. You should striving for an average score of 1 or greater.

| Aspect | Does not meet (0) | Meets (1) | Exceeds (2) |
|:-------------|:--------------|:-----|:---------|
| **Linter** | Linter and or style guide not installed | Linter and style guide installed | Style guide customized or adjusted for your preferences |
| **Completion** | Linter errors not addressed | Linter errors addressed | Code is well formatted and includes comments |
| **Work Ethic** | < 3 comits.   | Commits show consistent work| commits show full 3 hours of work |

## Assessing your knowledge

Use this rubric to assess how your understanding of the learning objectives. You should striving for an average score of 1 or greater

| Expectations | Does not meet (0) | Meets (1) | Exceeds (2) |
|:-------------|:--------------|:-----|:---------|
| **const, let, and var** | Can not describe the difference between const, let, and var | Can describe the difference between const, let, and var | Can provide use case examples for const, let, and var |
| **Arrow functions** | Could not write an arrow function without reference | Can write arrow functions without a reference | Can write arrow functions in various sytaxes |
| **Linting and style** | Can't exaplain why using a linter with a style guide is a best practice | Can explain why using the linter with a style guide is best practice | Can constrast situations where the linter might not bne useful agaist cases where it would be useful |