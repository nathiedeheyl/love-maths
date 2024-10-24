# A walkthrough practice project: Love Maths

## Bugs

- a media query for tablets seems to be missing. At least in my Chrome browser the design lacks responsiveness. The Submit Answer button is floating over the score area. 

## Learnings 

- About button data-type property 
- Writing out a structure of functions: function() {} !! The curly brackets are important, otherwise the code will produce an error and not load correctly. 
- First I put 'operand1'.innerText inside the brackets of getElementById() which produced an error in the calculateCorrectAnswer function. Correct is this: 
``` 
function calculateCorrectAnswer() {
    let operand1 = parseInt(document.getElementById('operand1').innerText);
    let operand2 = parseInt(document.getElementById('operand2').innerText);
}