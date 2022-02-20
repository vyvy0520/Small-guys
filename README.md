# Small-guys
**Team name** 
Small Guys

**Group member**
  
  Minh Ngo (Minh61@my.yorku.ca)
  
  Vy Le (vyvy0520@my.yorku.ca)
  
  Gracie Zhou (gz1342@my.yorku.ca)
  
  
**Overview**

This app can help everyone count their calories they need to consume in a day. In addition, it can help them count the BMI and Fat percent in their body. Through all the gathered data, our app can come up and provide a plan  for users to have a good diet as long as the exercises workout with the proper plan. Furthermore, This app also makes a level from basic to Advanced to help the trainer not feel panic when they start to plan their diet. I hope with this app people can make a good plan to diet and have a good body in the future.

**Functional Requirements**

When the app is first opened, it will display “Welcome to our fitness and diet app!” in bold at the top of the screen. 

A fitness image will be displayed at the middle of the screen.

Right below the image, the app will ask you “How can we help you?” and there will be 3 choices to choose from and they are all listed in a bulleted list in multiple choice format: “I want to lose weight”, “I want to maintain my weight”, and “I want to gain weight”.

Once the user clicks on one of the options, the app will turn the page and ask for their current weight and height and their goal weight.

Validations will appear when the user enters their current weight, height, and their goal weight. The height must be a double value rounded to 2 decimal places. If the user selects “I want to lose weight”, their current weight must be greater than their goal weight. If the user selects “I want to gain weight”, their current weight must be less than their goal weight. And if the user selects “I want to maintain my weight”, the app will turn to the next page. If any of the user inputs violate the requirements, an error message will appear at the bottom of the page. If all of the user inputs fulfill the requirements, it will go to the next page.

On the next page, the app will ask the user for the level of challenge. There will be 3 choices to choose from: “easy”, “medium”, and “hard” and they are listed in a bulleted, multiple choice format.

Once the user selects one of the options, a page describing the diet and workout plan will be displayed according to the level selected.
The user can always exit the app by clicking the “exit” button on the lower left corner of each page
When the “exit” button is pressed, the app will navigate to a page thanking the user for using the app.

**User Interfaces**
Page 1: The 3 choices "I want to lose weight", "I want to maintain my weight" and "I want to gain weight" are listed in a bulleted list. Users can only select one of the choices and they click "Next", which turns to page 2. If the user hits "Next" without selecting any of the choices, there will be a message saying "Please select 1 of the options".

Page 2: The user is required to enter their current weight, current height, and goal weight. If their goal is to maintain their weight, then from page 1 just turns to page 3 without stopping at page 2 since obviously their current weight and goal weight are equal (I don't know how to do that yet. I'll figure it out for sure) If their goal is to lose weight, validations check whether their goal weight is less than their current weight. If their goal weight is greater or equal to their current weight, a message saying "Error! Goal weight must be less than the current weight!" will appear. If their goal is to gain weight, validations check whether their goal weight is greater than their current weight. If their goal weight is less than or equal to their current weight, a message saying "Error! Goal weight must be greater than their current weight!" will appear.

Page 3: Here, like page 1, users have to choose between 1 of the 3 choices. They will be listed in a bulleted list. The user is required to select the level "easy", "medium" or "hard" depending on which one they want. When they hit "Next", depending on the level chosen, the app will turn to the 4th page which shows a view only diet and fitness plan which corresponds to the level chosen. There will be 3 different possible views for page 4 depending on the level chosen. I'll find those pages later. If they hit "Next" without selecting an option, a message saying "Please select 1 of the options" will appear.

Page 4: Displays a page of suggestions for diet and fitness plan based on the level the user chose. 3 different options in total. Which one pops up depends on the level the user chose.

Exit page: Users are always welcome to press on the "Exit" button, which is located on the lower left corner of every page. Whenever the "Exit" button is pressed, it will take the user to the exit page.

**Wireframes**

![IMG_20220212_234241](https://user-images.githubusercontent.com/92197567/154828416-50c68dae-d931-4894-a149-229f312cb83a.jpg)
![IMG_20220212_234226](https://user-images.githubusercontent.com/92197567/154828419-68ea3918-985f-484a-aac6-f09aa34228c1.jpg)

