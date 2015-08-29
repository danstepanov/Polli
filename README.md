# Polli 
## A polling app for iOS
### _Dan's Notes on the initial Design and how to go about building the app_

#### Comments on the Design

##### General Questions
1. Is the keyboard dismissible on any of the screens on which it appears?
##### App Icon

![App Icon](https://github.com/danstepanov/Polli/blob/master/Images/icon.png?raw=true)

1. Is this the app icon?

##### Onboarding
![Screen 10](https://github.com/danstepanov/Polli/blob/master/Images/screen%2010.png?raw=true)

1. Where is this screen used? Is this a launch screen?
2. Is there any kind of onboarding? 
##### User Asks a Question
![Screen 1](https://github.com/danstepanov/Polli/blob/master/Images/screen%201.png?raw=true)![Screen 2](https://github.com/danstepanov/Polli/blob/master/Images/screen%202.png?raw=true)

1. Is this the first page that the app opens to?
2. Is the keyboard always up on this page?
3. Should there be a cursor in the text field where the user can type a question?

##### User Asked a Question
![Screen 3](https://github.com/danstepanov/Polli/blob/master/Images/screen%203.png?raw=true)

1. Should these 3 buttons appear only after a user hits the **Done** button?
2. If so, wouldn't it look nice if they were reactive and appeared as the user started typing a question?
3. How should these buttons animate onto the screen?
4. What do these buttons do? The right-most **Share** seems pretty intuitive but I'm not sure about the others.
5. What should the highlighted state of these buttons look like? I assume they will never be disabled.

##### User Creates Options for Question
![Screen 4](https://github.com/danstepanov/Polli/blob/master/Images/screen%204.png?raw=true)![Screen 5](https://github.com/danstepanov/Polli/blob/master/Images/screen%205.png?raw=true)

1. What event triggers the appearance of the initial options text box?
2. Why did the buttons disappear?
3. Should there be a cursor in this options text box?
4. How does the user back out of creating an option and return to the screen with the buttons?
5. How should the initial option text box animate into the view? 
6. How does a user trigger the creation of a new option beyond the first one? Is this only possible via the **Done** button? 
7. How should subsequent options text boxes animate into the view?
8. How does a user delete the last option? 
9. What is the animation for the deletion of an option?

#####  User Creates More Options
![Screen 6](https://github.com/danstepanov/Polli/blob/master/Images/screen%206.png?raw=true)![Screen 7](https://github.com/danstepanov/Polli/blob/master/Images/screen%207.png?raw=true)

1. Why has "Or tap DONE to start" suddenly appeared in this option but not the others?
2. What does "to start" mean?

##### User is Finished Adding Options
![Screen 8](https://github.com/danstepanov/Polli/blob/master/Images/screen%208.png?raw=true)

1. How does the user communicate to the app that they are done adding options?
2. Furthermore, what triggers the keyboard to go away?
3. Furtherfurthermore, there is no obvious navigation from this page, how does a user proceed? The 3 buttons have not reappeared. 
