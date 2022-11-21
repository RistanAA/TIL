# Day 4
Today we are discussing about the team task, and I am responsible for question number 2

Question 
What is the difference between an Array-Like Object and Array in JavaScript?
What process do we have to go through to make changes to each components of the Array-Like Object?

Answer
Array is a list that each item is stored in index start at 0 in the order of their entry. Array-like object is a object but instead the data is stored in key value format, it will stored in index that should start at 0 like Array did and also should have length property that return non-negative integer.
We can access each element using “ [index] “. 

example :

const arr_like = {0: ‘I’, 1: ‘am’, 2: ‘array-like’, length: 3};
arr_like[0] = ‘new value‘. so value in index 0 change from ‘I’ to ‘new value’
or we want to add data to arr_like, we can’t just use arr_like.push method, we can use push like this Array.prototype.push.call(arr_like, 'add value');

And We also discussing about the lecture video, i got an error while setting up the environment variable, but ali help me out 

### Tomorrow Goals
* complete the team and personal task
