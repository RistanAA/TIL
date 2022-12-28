Today i continuing my work to create report api

I have some dificult while trying to do array sort function, so the idea is i have 2 data from different tables and try to mix them in one array 

![image](https://user-images.githubusercontent.com/85722211/209836744-bdfa294d-e817-4935-9480-ae5f05906814.png)

![image](https://user-images.githubusercontent.com/85722211/209836760-296a14ba-562a-4f6a-bdd4-b254f43d44a0.png)

and after that i try to do the sort function 

![image](https://user-images.githubusercontent.com/85722211/209836809-54fef272-eb64-4884-b57e-cfb37f14b4c2.png)

but it keeps failed, and i try to find what is the problem and i get i cant access a.postTime, then i try call different key and it works, maybe because postTime is a alias form the db so it wont work, but i still confuse why it doesnt work. but after i change to not use alias and just call the createdAt it works.

### Tommorow Goals
* Finish the report api ( combine with other code )

