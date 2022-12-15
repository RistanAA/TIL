# Day 4
Today i try to implement what mentor said yesterday, 
first i fix the file management of the project and use react-router-dom, then i implement the game progress feature that able to store the progress of user game in redux.
This feature is for save the game progress if the user try to navigate to somewhere else in the web. so if the user back to the game page the game will start again based on last progress.

![image](https://user-images.githubusercontent.com/85722211/207907127-51f43717-34ce-42d3-b166-d1f99b07c830.png)

So here's my code 
i use redux toolkit

![image](https://user-images.githubusercontent.com/85722211/207906813-2de38067-5220-46b2-80dd-8c20b7c6c9fb.png)

and i use useEffect to hook the dispatch function whenever cards state has changes

![image](https://user-images.githubusercontent.com/85722211/207907044-bc6e218b-c782-4fe3-8fea-b45567631ee8.png)

### Tomorrow goals
* fix addProgress function (currently has performance issue)
* finish the leaderboard page before 4 pm



