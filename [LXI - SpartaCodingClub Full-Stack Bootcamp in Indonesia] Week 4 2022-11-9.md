# Day 6
Today is the submision time of team project, but we are not finish all the requirement.

### What have we done 

* Create a server and deploy it in heroku 

![image](https://user-images.githubusercontent.com/85722211/200894204-bb8e0b71-1abe-4e4f-b0f7-b0df616916e7.png)

* create the ui of the app

![image](https://user-images.githubusercontent.com/85722211/200894770-aa0f4515-5e2f-42f9-a439-2a565df4ebf2.png)

* implement redux toolkit

![image](https://user-images.githubusercontent.com/85722211/200894922-ade4e88a-7dd4-477f-bc3e-1405da5bf2e8.png)

![image](https://user-images.githubusercontent.com/85722211/200894974-75603c8d-e632-49c0-9d06-23cdbd45c817.png)

* Search function
* 
![image](https://user-images.githubusercontent.com/85722211/200895211-6a1a23b8-4c72-4966-a6b3-2efe449605cf.png)

the function it self can return what we searching, but it affect the plus and minus quantity that somehow can't be clicked when we click on the result of the search. 

### Problem that we've met

the biggest problems that i've met is there some error but i dont realy know why, i try to debuging all the flow of the function 

![image](https://user-images.githubusercontent.com/85722211/200896424-8af461cb-d2b0-4b3f-ae8c-f7bc9d1749d6.png)

but its working fine, i get the axios error on network, but sometimes it just fine and working perfect. so i asked my teammate to try it in his browser (mozilla firefox) and it has different error  

![image](https://user-images.githubusercontent.com/85722211/200898545-fed8d6c3-e8dd-42fa-996d-7756d2475976.png)

so i think the problem its not in the code but something with the server. so when mentor justin came, i ask him about this, an he said that it can happend when we using server and the front end app in same localhost server although it has different port. so i just deploy the server on heroku than use the url from the deployed server

![image](https://user-images.githubusercontent.com/85722211/200899542-27ce72d0-9fee-459d-843e-6eb1e8be1907.png)

and it solve the problem


