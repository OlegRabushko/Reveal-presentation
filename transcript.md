# React

Hi, my name is Oleg, I’m frontend developer and now a want tell you about React.

---------------

React – what is it? Official documentation presents us such a definition: React - is a JavaScript library for building user interfaces.
React - a great instrument for building scalable applications. That is, React help us creating applications, which easy break into small components and also help increase productivity for every component separately.
At first, React was intended for the web, but then appeared the React Native platform, designed for mobile device. 

--------------

Next block - main features of React
First, I'll list the features and then I'll go into more detail about each.

JSX - It is a JavaScript syntax extension that allows you to use HTML-like syntax to describe the structure of an interface.
Now I want show you difference between JS and JSX code.
Without JSX code is like this: we are creating element, using method createElement. Then we are return element with method innerHTML. 
Or code can look like this: at first creating element, then creating next element and return first element with use method append(). 
With JSX, code seems like this: we are only return HTML code.

+:  
1) Visual understanding. More comfortable for ours eyes when code have different colors, this is help us work faster. Maybe in my example this no so visibly, but in long code it’s noticeable.
2) Brevity. Because we are don’t create separate element, but return ready HTML code.
---------------

Virtual DOM
All structure of a web page can be represented using the DOM. Document Object Model – It’s HTML elements organization, which we can manipulate, deleting or adding new. For interaction with DOM used JavaScript. 
Virtual DOM appear a copy of usually DOM. React work with Virtual DOM. If we want get information about state of elements, we are appeal to Virtual DOM.
If necessary change element of web-page, changes at first added in Virtual DOM. Then new state Virtual DOM is compared with the current state. And if this states difference, React finding minimal counts of manipulation and then rerender DOM. As you can see in this gif-picture.

-----------------

Last feature which I have highlighted: Reactive programming. 
React was built on Reactive programming paradigm. This declaration approach proposes to describe data as set of affirmation or formulas. If one params changed, dependencies are automatically recalculate.  

--------------------

Now tell you, how get started work with React
It’s so easy. All we need to do, It’s open your terminal and run the following command:
npx create-react-app 
But npx uses NodeJs to load commands. Therefore, you need to install NodeJs. If you don’t installed earlier. 

Next step – run “npm start” command. React will open for you window in browser on localhost:3000.

That’s all. Congratulations! you are launched React!

------------------------

Ok, I finished my presentation and I would like to summarize. I briefly told you about React library, what is it, main features and how start to work with him.
