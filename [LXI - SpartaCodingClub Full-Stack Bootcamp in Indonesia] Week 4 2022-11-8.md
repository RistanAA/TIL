# Day 7 
Today we are continuing diy section on team task,

The key word that we select are :

## What is function memo() ?
Memo() its not a hook that we used in react javasciprt, but instead it is used for callback, in order to use `useCallback` or `useMemo`. 

To improve user interface performance, React offers a higher-order component `React.memo()`. When `React.memo()` wraps a component, React memoizes the rendered output of the wrapped component then skips unnecessary renderings. This post describes the situations when `React.memo()` improves the performance, and, not less important, warns when its usage is useless.

![image](https://user-images.githubusercontent.com/85722211/200617900-8a056009-dd22-424a-b21d-8566fc5e987c.png)

## What are the http status codes, and what is the meaning of each code?
HTTP response status codes indicate whether a specific HTTP request has been successfully completed. Responses are grouped in five classes:

1. Informational responses (100 –  199)
2. Successful responses (200 – 299)
3. Redirection messages (300 – 399)
4. Client error responses (400 – 499)
5. Server error responses (500 – 599)

## What are the advantages Axios over Fetch?
- **Basic syntax :**
    
    Axios automatically transforms the data returned from the server, but with `fetch()`
     you have to call the `response.json` method to parse the data to a JavaScript object.
    
    With Axios, the data response provided by the server can be accessed with in the [data object](https://github.com/axios/axios#response-schema)
    , while for the `fetch()`  method, the final data can be named any variable
    
- **Backward compatibility**
    
    One of the main selling points of Axios is its wide browser support. `Fetch()`, on the other hand, only supports Chrome 42+, Firefox 39+, Edge 14+, and Safari 10.3+
    
- **Response Timeout**
    
    In Axios, you can use the optional `timeout` property in the config object to set the number of milliseconds before the request is aborted. `Fetch()` provides similar functionality through the `AbortController` interface. It’s not as simple as the Axios version
    
- **Automatic JSON Trasformation**
    
    Axios automatically stringifies the data when sending requests (though you can override the default behavior and define a different transformation mechanism). When using `fetch()`, however, you’d have to do it manually.
    
- **HTTP interceptors**
    
    One of the key features of Axios is its ability to intercept HTTP requests. As default,`fetch()` doesn’t provide a way to intercept requests, but it’s not hard to come up with a workaround. You can overwrite the global `fetch()` method and define your own interceptor.
    
- **Download Progress**
    
    JavaScript programmers used the `XMLHttpRequest.onprogress` callback handler to implement progress indicators. The [Fetch API](https://blog.logrocket.com/patterns-for-data-fetching-in-react-981ced7e5c56/#:~:text=these%20alternative%20implementations.-,Using%20the%20Fetch%20API,-I%E2%80%99ve%20used%20Fetch) doesn’t have an `onprogress` handler. Instead, it provides an instance of `ReadableStream` via the body property of the response object. Implementing a progress indicator in Axios is simpler, especially if you use the [Axios Progress Bar](https://github.com/rikmms/progress-bar-4-axios/)
     module.
     
Than we continuing the team project
