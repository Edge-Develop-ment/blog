#Should I Choose Tailwind or Vanilla CSS?

So lately, I've started to break some habits. I am not great at managing CSS but I've really pushed myself to keep myself organized. I've tried to use inline styles only sparingly and I've really seen the benefit of using a separate stylesheet and working with classes to give style individual elements. This for the most part has worked pretty well and I like it. One of the main things that I like about this method is that it pushes me to be more organized. Everything has its place and everything looks cleaner and more organized.

Now more recently, I started to look into Tailwind CSS because of course it's the newer trendier thing that seems like everyone is using. I've used a bit of the other CSS libraries out there, of course especially Bootstrap, but I wanted something that can of course make things easier but also give me some flexibility. I don't know about you but I'm kind of tired of everything looking like Bootstrap.

Lately, as I dive into Tailwind, there are of course many things to like about it. While I like the idea of keeping everything very clean, I do like the idea that I don't need to leave the HTML or JSX to see changes. Also, it seems as though I can make changes to style much quicker than with the old way of doing things. There is much less typing than there is in Vanilla CSS to accomplish some of the same things. Also, there are so many more options than there is with Bootstrap and even if I don't like the built in options, which there are very many, I can very easily adjust the style to how I like it.

All of this being said, I'm not exactly sure if I'm sold on Tailwind, and this is for one reason. Tailwind definitely makes the HTML or JSX a bit more difficult to read because now there are many more classes that are written into the elements. It doesn't look as clean nor as organized as it was before and there is a part of that that bothers me. I'm not sure if I just need to get over that or move on and find a different alternative.

Let me give an example, let's say that I want to adjust the margin and the padding of a div. With Vanilla CSS I would create a class in a separate CSS file, and inside of this class I would put all of my adjustments. Then I add the class to that div element which applies that style.
```
.vanilla {
  margin-top: 12px,
  margin-bottom: 12px,
  padding-left: 12px,
  padding-right: 12px
}

<div class="vanilla"></div>
```
In Tailwind the same can be achieved by putting everything into the div element.
```
<div class="mx-3 py-3"></div>
```
When I insert mx-3, this adjusts the margin of the element on the x axis by 12 pixels, and py-3 adjusts the padding on the y axis by 12 pixels. This is much less code than the Vanilla CSS. Also, if you want to have a separate CSS file you can but it's not necessary. It's also very fast to change styling on the fly.

I know that many people will tell me about Sass or many different libraries, and I think that's all great but right now for me, I think I'm going to try Tailwind for a while.
