# Day 3 
Today i continuing the game feature, i make a change to the card cover and it size to this 

![image](https://user-images.githubusercontent.com/85722211/207641254-1db0af8e-179b-4661-bb61-133c5f262f35.png)

And also add some other features like timer, score, and turn
* Turn is how many move that you have done
* You will get 10 score when can match a image
* Timer is a time limit for finishing the game

For this timer feature i use some custom hook from react-timer-hook library
React timer hook is a custom react hook, built to handle timer, stopwatch, and time logic/state in our react component.

this is how we use the useTimer

![image](https://user-images.githubusercontent.com/85722211/207642265-d541a17a-cc07-4057-bd2d-e94d6d4f67a6.png)

with this custom hook we can easily to manage some function that relate to the timer, the example is when the timer is expired we will run a timesUp function to disable any interaction with card and give notification to user

### Today result 
![image](https://user-images.githubusercontent.com/85722211/207642914-7b4a255c-3c93-4c52-b0f0-f02e22c1752c.png)

### Tomorrow Goals
* combine Login and register page to this page
* add leaderboard feature 
* try to implement history to handle unfinished game
