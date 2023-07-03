#HTTP for Those That Are Afraid to Ask

I'm not sure how many of you have gotten a good introduction to HTTP when you were learning programming or web development, but I have to be honest, for me it's something that was always a bit mysterious to me.

I've recently started taking some Front End Development courses and this topic came up. I wanted to write about it not because I'm an expert but because I myself was someone who felt like they should know what this is but didn't and at the same time I was afraid to ask and feel dumb. I am a newbie. Let me try to explain this in words that even I can understand.

For my resources, I'm going to be using the MDN and Wikipedia. If there are other sources that you think I should use, please by all means be nice but please share, because at some point there may be another newbie just like me that comes along and they, along with myself, may benefit from the resources that you bring.

HTTP, or Hypertext Transfer Protocol was a technology that was invented in the early days of the internet by the famed Tim Berners-Lee and his team at CERN back in the beginning of the 1990's. They developed HTTP in order to support their idea of the "World Wide Web". (Wikipedia)

There are a few things that I really want to focus on when I talk about HTTP. I want to talk about the protocols that are built into HTTP, such as TCP and UDP, but I also want to talk about the main methods of HTTP, and the status codes that are important to HTTP.

Like I mentioned, there are two different protocols that underpin HTTP called TCP and UDP. TCP, or Transmission Control Protocol is the older protocol when it comes to usage within HTTP. Since the beginning TCP has been relied on over other protocols, because TCP has always been more reliable. However more recently UDP has started to be implemented in the recent transition to HTTP3. (Wikipedia)

Essentially, the process that HTTP uses to deliver the internet to us is a series of requests and responses. While there are a lot of methods that HTTP uses to move and manipulate data, there are four main methods that are used, POST, PUT, GET, and DELETE. Essentially, with POST the web server is looking to create new data. With PUT, the server is going to change existing data. GET is exactly as it sounds as it is retrieving data. DELETE is obviously removing data. As I said, there are also other methods but these are the most common. (MDN)

Finally, I wanted to talk about the status codes that HTTP uses to let the user know what is happening with their requests. These status codes come in the form of three digit numbers that HTTP uses to communicate to the user what is going on with the requested data. The 100 level numbers are information requests, like status code 102 Processing means that the request is being processed and there isn't any response yet. 200 level codes indicate successful responses. The most important of these is status code 200 OK meaning that the request has been processed successfully and as expected. This may be the request that we receive all the time but we never actually see it because all we see is the page that we actually requested, but this code is being displayed in the background. 300 level codes are redirection messages. The 400 level codes are for client errors. Of course the most common of these is the 404 Not Found. This is the code that all of us are very familiar with because it maybe the most forward facing of all of the status codes. We know that if we come across this status code, then we've come to the wrong place. Finally is the 500 level codes. These are for the server error responses. If you ever see a 502 Bad Gateway, this means that while the server was processing the request, it got an invalid response. (MDN)

I know that this blog post is not enough to explain about all of HTTP, nor was it supposed to. I know that I left out crucial parts and someone will need to give some corrections. I really wanted to share this because this is such an important piece of technology that almost all of us see everyday but we never know what it's for. Hopefully this was helpful to you, and please feel free to discuss down below.

An overview of HTTP - http: MDN. HTTP | MDN. (n.d.). Retrieved March 3, 2023, from https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview

Wikimedia Foundation. (2023, February 26). HTTP. Wikipedia. Retrieved March 3, 2023, from https://en.wikipedia.org/wiki/HTTP
