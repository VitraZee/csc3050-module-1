Walmart.com

GET - https://i5.walmartimages.com...safeframe.html - 200 OK - Cache-Control how long and how to store cached content - Content-Encoding how the resource body was compressed or transformed

GET - https://s.xlgmedia.com/static/2.179.0/main.js - 200 OK - Content-Length size of the body - Expires date and time where the cached response won't exist anymore

GET - https://i5.walmartimages.com...sparky_expanded_fab.gif - 200 OK - Content-Type type of content sent or recieved - Server server software

The JavaScript was the slowest, followed closely by the image. The image time is probably due to the size of the image and the fact it was a gif. For the JavaScript I have no clue why it took so long, maybe the JavaScript can only run after all the other basic files have ran? Like the JavaScript relies on the HTML and CSS files to be completed before it can finish? Or the JavaScript file is so large that it takes a long time. The response methods were all the same GET because they were all getting content to display on the web page, and all returned 200 OK which is expected. The only thing that really surprised me was the sheer amount of files that are sent when you load a simple web page.