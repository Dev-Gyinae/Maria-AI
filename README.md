# Maria-AI (13/05/2023)

TITLE: BUILDING OF AI MARIA (A personalized AI fashioned after chap gpt?

BODY
The app has 2 main components;
a. the client side 
b. the server side 

A. The Client Side
This is basically the front end interface of the app and it makes requests to the serverside via the openai API
and displays the responses to the user interface. hosted on vercel.com

B. The Server side
it is made from Node and is hosted on render.com. This contains details about the server, keys and environmental variables.

Conclusion:
It is fully functional on https://maria-ai.vercel.app/ 
the open ai server is mostly crowded so responses could be slow or even get a 429 or 500 error which at this stage
is perfectly normal.

Problems:
The main problems are 
a. request server overload (openai.com)
the evolution of ai and chatgpt has overloaded the server and the free requests are mostly overloaded.

b. CSS issues
so with the new updates to the web browsers a few adjustments maybe needed in the future to clear the
'scrollbar-width' is not supported by Chrome, Chrome Android, Edge, Opera, Safari, Safari on iOS, Samsung Internet.

*** this error affects the scrolling function of the app in some browsers. 
