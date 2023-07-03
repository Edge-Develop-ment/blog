#Semantic HTML Elements vs the DIV

So lately, I started to take a Front End Web Development class because I wanted to go over and review basic concepts and also fill in any knowledge gaps that I may have. While taking this class I came across something that we are all very familiar with but I believe that maybe with work within our different tech stacks or focus on Javascript, we are losing sight of more and more.

I remember when I first learned about HTML elements when I was in high school during the 1990's. Yes we actually had computers back then and many of us already had the internet in our house. In my high school, this had to be around 1998 or so, we really had a basic HTML class. We of course talked a bit about styling, but there wasn't any discussion about separate style sheets, and we didn't even touch javascript.

I remember writing my first HTML tags and I thought they were really interesting how with only text I could change the way something looks. If you're reading this, I don't need to tell you how conventions over the decades have changed but also habits have changed as well.

For those that don't know, semantic HTML elements are descriptive and really work to help both the developer and the browser to layout the website in a very clear and coherent way. The very basic form of this is as follows:
```
<html>
  <head>
    <title></title>
  </head>
  <body>
    <h1></h1>
    <p></p>
    <h2></h2>
    <p></p>
  </body>
</html>
```
Really there is more that I could put in the example but this is simple, it's easy for another developer to read and you know very easily what goes where and what everything will look like. Writing semantic HTML is also great for accessibility, such as things like screen readers, etc.

At the same time, habits change and I wonder how much a focus towards Javascript libraries and frameworks has destroyed the practice of using semantic HTML. Typical non-semantic HTML instead of using different tags for each element, is just full of div elements. A typical piece of non-semantic HTML may look something like this:
```
<div id="header"></div>
<div class="section">
    <div class="article">
        <div class="figure">
            <img>
            <div class="figcaption"></div>
        </div>
    </div>
</div>
<div id="footer"></div>
```
Source (freecodecamp.org)

Any developer with experience of course will tell you that this code is more difficult to read, many times it's harder to follow the developer's logic, and it is not very accessible at all. So why do we write our HTML in this way, including myself? I am just as guilty of this. This is faster and doesn't necessarily need as much thought maybe, but I think many of the frameworks and libraries really encourage people to write this way.

I'm not saying that we shouldn't use those resources, on the contrary, they are indispensable. I know that there will be some Vue or maybe Angular developer who will say that they don't have this problem at all, and maybe they are right.

I develop with React and of course you don't always have to use the

but it's definitely the default and it is encouraged many times for the sake of convenience. I really don't have any solutions to this problem and I know that this is a problem that has been talked about ad nauseum in many different forums, but if there are people that are smarter than me, and I know that there are mountains of you out there, let's talk about this. Let's try to push for a way that we can have the functionality that we crave but also keeping order with what we write.
freeCodeCamp.org. (2021, April 28). Semantic HTML5 elements explained. freeCodeCamp.org. Retrieved March 31, 2023, from https://www.freecodecamp.org/news/semantic-html5-elements/
