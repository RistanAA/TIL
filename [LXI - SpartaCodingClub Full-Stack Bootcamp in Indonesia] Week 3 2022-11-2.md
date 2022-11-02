# Day 6
Today is the deadline of personal task for creating todo list app using redux, i have already finished it yesterday. 

![image](https://user-images.githubusercontent.com/85722211/199523050-debc6be3-ffea-4a03-9501-b4f93c6bedc2.png)

But after mentor review my app, i already make validation if empty using .length but its not cover if users fill the input with space " " and i have done that by change it to .trim

![image](https://user-images.githubusercontent.com/85722211/199547980-4c5adc0a-029d-4be7-91d2-c9871c2a69b0.png)


after that i use Date.now() for my id, but mentor said that will be problem if we accidentaly double click the function, so i change that with using package react-id-generator for the id and will generate  a unique  id

![image](https://user-images.githubusercontent.com/85722211/199548534-2ae37c76-3dab-4016-869d-b18facb11a13.png)

So, in this project i use redux for state management, in useState we can passing the data using props from parent to child setp by step, but it will causing a props drilling ,Prop drilling is the unofficial term for passing data through several nested children components. 

![image](https://user-images.githubusercontent.com/85722211/199550240-8b681a87-b007-4066-b3ae-454e22dc0f16.png)

but if we use redux, we just need to store the state in global, then the others components will able to access it from any where.

![image](https://user-images.githubusercontent.com/85722211/199550557-2f49e57c-3565-4a8a-ba0f-ddcf28698961.png)

we also implement react-router-dom for handle the routing in our web, in react there unique way to handle the routing, when we try to move to other route in other web framework it will call new page and refresh it , but in react it's not exaclty changing the entirely new page but it only show new component and hide the others. so if we try to go back, the state will stay there and not refreshed. 

when i do this project, i always not used to styling component, i just cant imagine what i want how my component looks like and design it form css. but i'm sure i will get used to it. Also i need read more about the behavior from all the react hook that i learn before in this week, so i can know exacly why and when i need that hook in my code.





