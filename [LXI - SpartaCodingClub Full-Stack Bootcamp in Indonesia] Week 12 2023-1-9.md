Today i try to handle the date for the dashboard report page 

![image](https://user-images.githubusercontent.com/85722211/211340698-461388f9-9844-4f19-8b61-d425b5fd040a.png)

so we try to devide the date to 3 step : < 1 day = "yesterday" , == 1 day = the hour, > 1 days = the date

first when i try to edit the data that i've get forn find function, and try to add the new item using spread operator i got the problem. when i try to spread, i not only the data that we want get called, but also the details about collection. then i try to search any solution in internet and i got findonupdate function, but it not solve to my case. finally somehow i got idea to access the data from the collection object and it works, so i just implement the function to handle the date 

![image](https://user-images.githubusercontent.com/85722211/211342250-f6ffb67b-93a6-4378-89f1-227cb191def2.png)

![image](https://user-images.githubusercontent.com/85722211/211342322-c557aea6-4c59-44e2-b20a-b981a8c718c3.png)

### Tomorrow goals
* change the report schame in backend to match the data from front end side
