# Day 7 
Today is the last day of week 3 , this week we try to make todo list with using redux.

## What i learn this week ?

### Styled Components

styled-components is a package that allows us to decorate our components in the CSS-in-JS way in React.

![image](https://user-images.githubusercontent.com/85722211/199765262-fbbe38fa-9b1a-4c08-912b-3438d5096c0c.png)

### useEffect

useEffect is a Hook that can be set to perform a specific action whenever a React component is rendered. we also can add dependency array in useEffect to trigger only when the dependency/state has changed.


### Redux
For using redux we need instal the redux and react-redux library then we need some set up

* First add provider and wrap app in it

![image](https://user-images.githubusercontent.com/85722211/199762045-f599fa26-2810-4db0-bce0-18cd8333b38a.png)

* Create redux folder then add config and modules folder

![image](https://user-images.githubusercontent.com/85722211/199762628-14051f62-c55f-4256-8205-3a2e343433f1.png)

* Add module.js in modules folder, in this week i create todos module. In this file we need to make reducer 

![image](https://user-images.githubusercontent.com/85722211/199764247-43033a45-a75c-4d20-9875-24f87cf6a216.png)

* Add configStore.js in config folder

![image](https://user-images.githubusercontent.com/85722211/199763240-f4e23dfd-abb3-4d11-ae8a-5dad4be1f80f.png)

* and redux ready to use

### Routing using React Router Dom

react-router-dom is a library to use routing in react

To use this library we need some set up

create Router.js that contain all the routes with their element (component)

![image](https://user-images.githubusercontent.com/85722211/199767567-cfb9a1e4-122f-4c54-b83e-debc6fe58105.png)

To call the route we can use some way

* Link 
we can use Link component from react-router-dom

![image](https://user-images.githubusercontent.com/85722211/199767901-0235a0ce-fbc8-4b46-983c-5a063f10371e.png)

then add to attribute in Link that contain route that we already set up

![image](https://user-images.githubusercontent.com/85722211/199768159-8a3e7141-a219-4e0d-a201-75f0ead59675.png)

* useNavigate 
we can also use useNavigate from react-router-dom

![image](https://user-images.githubusercontent.com/85722211/199768447-ad758085-b5ae-4f40-8a1f-9356fa489ad7.png)

then call the function in handler in component with adding the route path as parameter

![image](https://user-images.githubusercontent.com/85722211/199768565-0e2cb9fe-efeb-434c-81a0-12cf994af2f8.png)


 







