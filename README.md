# Form Validation

##  Overview
Form validation is a mini project that I built while taking a udemy [course](https://www.udemy.com/course/web-projects-with-vanilla-javascript) by [Brad Travise](https://twitter.com/traversymedia).
This project validate user input from the client side before it can be send to the server. First of it check if username is provided and if it is provided, it check if is a valid username. When the user provide email, the email get tested to see if it is a real email. And lastly it check if password is strong enough to be accepted. The project also have clean user interface that let a user know if the input is not valid and why is not valid

##  Preview 
![alt text][screenshot]

##  The Design
Although the project is part of  the Udemy course I decide to do a different design from the course. This made me  spent more time than I wish I should to this project. The design is from daily Ui, I just customised it to fit the goal of this project


##  Preview
You can preview the project here on [here](),

##  Folder structure

```
form-validate/
|   form/
|   |   form.html
|   |   style.css
|   |   validate.js
|
|   |fonts/
|   |   sans-serif.tff
|
|   Screenshot/
|   |   screenshot.png
|   
|   README.md
```

##  Technology
This project is mainly built with web Technology while using an open source text editor called visual studio code running on windows operating system


| Technology  | Fetures                         | What is used for                      |
|-------------|:-------------------------------:|--------------------------------------:|
| HTML5       | `form` `data-*` `label` `span`  | To display the form in the screen     |
| CSS3        | `css variable`                  | To style the form to look good        |
| JavaScript  | `ES6` `DOM API`                 | To validate the input from the form   |



##  Challenge
The process of building the projects was nice and easy since I was following a totorial. The project from a totorial didn't have checkbox, and I decided to add checkbox as most online form these days require you to accept terms and conditions and the design from daily UI came with checkbox, I didn't wanna just omit that. It happen that HTML doesn't allow you to target the checkbox input element to style it. I checked on stack overflow on how to style checkbox and they directed me to this blog which done a good job explaining how to style checkbox.  I also wanted to style the focuse state of the checkbox and it turns out the checkbox doesn't have focus state

 ###    what I leaned from
  1. Styling checkbox input
  2. Manipulating the DOM base on state of application
  3. Best way to structure JavaScript code


#   Licence 

This project is free to use
Feel free to use this project for a commercial and none commercial projects

[screenshot]: https://github.com/henkhodryza/form-validation/blob/master/screenshots/screenshot.png