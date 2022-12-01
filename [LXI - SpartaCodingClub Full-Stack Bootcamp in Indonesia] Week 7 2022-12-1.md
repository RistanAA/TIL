# Day 7
Today we have weekly test, the test is tricky but i tried to answer all the question.
In this test we need to fix some error in the project, the tricky part is there are some route that has same url so at first i quite confuse why when i tried to make some changes in that route, it doesnt change. but when i realize that, i can keep up with the question.

### What i learn this week
This week we focused to creating token, cookie, session, middleware, and MySQL

* cookie : When the browser receives a Set-Cookie header as a response from the server, it saves the data and sends it with all requests.
    - Because data can be shared across multiple sites, it can be a security vulnerability.
    - Cookies exist in string format, such as `userId=user-1321;userName=sparta` , separated by semicolons (`;`) between cookies.

* session : A technology configured based on cookies. However, unlike cookies, where the client can check data at will, session is secure because data is stored only on the server. easy to occur.

* jwt : 
- It allows you to securely exchange and use JSON-formatted data.
- It is a standard that has been established as an Internet standard.
- Several encryption algorithms are available.
- It contains three pieces of data in the format of `header.payload.signature` . (**Head**, **chest** and **belly** like an ant)

* middleware

![image](https://user-images.githubusercontent.com/85722211/205097088-01fa07d4-2c93-499e-90a5-48a0d4989edd.png)

middleware base format

![image](https://user-images.githubusercontent.com/85722211/205097309-f260ef0a-cbea-4cfb-a3a5-dc8a3eb64dec.png)

* MySQL using Sequelize ORM

ODM (Object Document Mapper) is a tools to connecting the NoSQL database with our backend code, in this case is node.js. In NoSQL database the data is stored in JSON format in the collection. with this tools we can execute ‘query’ from database like mongodb such as find, insertOne, etc.

ORM (Object Relational Mapper) is like ODM, but it is form RDMS database. we can use DDL, DML query in our code. in RDBMS like MySQL, PostgreSQL, Oracle, etc there is a slightly different query to perform any process like ddl or dml , but with using ORM we dont need to worry about that because we already have function to handle any query, example if we using Sequelize and we want to to select * from users query, we can use find() to get multiple data or findOne() to get a single data. because of this, we can easily to change to any RDMS database.

### Next week goals
* Watch all video during weekend
* Finish all task before deadline
