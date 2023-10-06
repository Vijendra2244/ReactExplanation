1.What is React?
Ans:=React is a javascript library for build user interface(UI).React is used to create a single page application(SPA).React allows us to create reusable user Interface(UI) components.Also react is open source and free library.Main purpose to learn react React provide a virtual dom is means we can not direct code on dom.Firstly we write a code on virtual dom and after that react compare both the dom and which are updated component this component render on web Dom.so with react our website flexible and more efficient.

2.Who made React?
Ans:= React was created by "Jordan Walke".

3.What is Babel?
Ans:=Babel is like compiler of javascript.Babel convert JSX into javascript friendly language.

4.How does Babel convert html code in React into valid code?
Ans:= Babel is used to transpiled JSX code into plain JavaScript. It does transforming JSX elements and components into JavaScript function calls.

5.What is ReactDOM used for? Write an example?
Ans:=ReactDOM is a package in used for render react component into the real DOM(Document Object Model) of a web page.it is provide a methods to interact with the dom,and it is allowing to us to create and manage the user interface of our react app.

For Examples :=
Firstly we have a root element in index.html after we catch with id and it's id root,
before that we import react DOM from React like this-:import ReactDOM form "react-dom"
let root = document.getElementById("root)
let ele = <>

<div>Hello React App</div>
</>
let rootElement = ReactDOM.createRoot(ele);
rootElement.render(ele)

6.What are the packages that you need to import for react to work with?.
Ans:= First = import react from "react";
      second = import reactDom from "react-dom";


7.How do you add react to a web application?   
Ans:=Firstly if we are create a react app make sure in our system install a node.js and npm.So basically we have  to two way to add react in our application first is manually and second one is use external source like create-react-app and create @vite Latest and much more.
 1.first we are install in our file react and react dom for using terminal with this command  for add to react dom install react "react-dom" and add to react in our application  react react-dom after that we create a our react components and render on webpage with the help of React DOM package.
 2.second way to create react app is we are using a external way in this we are simply go in  terminal and write npm install create-react-app and npm install create @vite latest. so in this packages have all the dependencies that we are need to out react application.



 8.What is React.createElement?
 Ans:= So if we want to create a element inside a React so we write a React.createElement and using this we are able to create a element.
 And React.createElement it takes a three argument first is type of element and the second is property like className and id and attribute also,it takes a children it means what do you want to inside this element. for examples:=
                               let element   = React.createElement("div",{
                                className: "main",
                                children:"Hello this is our React App"
                               })

9.What are the three properties that createElement accept?
Ans:= create element takes three properties first it takes a  type of element and second is optional is takes a property like className and id and src (attribute) and third it takes a children.

10.What is the meaning of render and root?
Ans:= Render =  If we are talk about render it is basically used to render our component in web page.render refers to the process of take to our webpage and generate a virtual dom of its output in the form of react element tree.

Root = So in root where we mount our full html document in our react application.In a simple language we said our full react mount in one root element.Because in  react we can not create one more then root element.


