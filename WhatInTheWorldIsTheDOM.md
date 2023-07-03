#What in the World is the DOM?

So I'm writing this series blogs about topics that I feel like I should know because I hear people talk about them all the time as though I should know, but I have to make a confession, I have no idea what these things are really. Maybe it's because I don't have a proper CS degree, and if I'd only took this program in university, I would have all of the answers. I have of course done quite a bit of self study, and to be honest I think technical reading is a great way to put yourself to sleep or it really triggers my ADD. I want to help others like me get a bit more of a grasp on these kind of subjects.

When talking about the DOM I'll be pulling my information from the MDN. If you don't know about the MDN, you should definitely take a look. It is a project that was started by the people at Mozilla, which is the same people that started the Firefox browser. This is important because groups like this are fighting to keep the web free and open, and I highly recommend that if you can you should support them for these reasons.

Now, maybe you've heard about the DOM or the Document Object Model, but usually when people talk about the DOM, they usually talk in relatively abstract terms. For example, people talk about manipulating the DOM and how the DOM is a representation of the website. All of these things are true, and every website has their own instance of the DOM, but I want to try to get a little more hands on with the concept of the DOM.

The DOM itself is not a programming language but is really an interface that programming languages can use to manipulate and change a website (MDN). In many ways people describe the DOM as like a tree with nodes that represent each part of the site, such as the head, body, p, h1, and img tags. These are all nodes in this tree.

Document Object Model - Wikimedia Foundation
The Document Object Model - Wikimedia

The Document, which is what holds the entire website, actually is a part of the Window Object. When we interact with the Window Object, we can actually start to interact with things like the browser, but the Document inside of the the Window object can be seen in two ways. It can be seen as code inside of a text editor or an IDE, or it can be seen as a web page, just like you are seeing now.

When interacting with elements and objects on the DOM, we have to use DOM interfaces (MDN). If you've ever seen javascript before then you have definitely seen these interfaces. These interfaces are APIs that help us to manipulate the DOM. Maybe you see document.querySelector() or maybe you have seen document.getElementById() these are examples of the interfaces or APIs that are used to manipulate the DOM and they are used primarily be Javascript to make websites and apps to be interactive.

Many times these types of topics can be a bit frightening or even a little confusing. I know that I have definitely struggled to understand them before, and to be honest there are still many things that I am working to make clearer for myself. I plan to continue writing these blog posts to continue to make these topics more and more clear for people who are just beginning in the area of Computer Science but especially Web Development.

Introduction to the DOM - web apis: MDN. Web APIs | MDN. (n.d.). Retrieved March 18, 2023, from https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction

Wikimedia Foundation. (2023, February 23). Document object model. Wikipedia. Retrieved March 18, 2023, from https://en.wikipedia.org/wiki/Document_Object_Model
