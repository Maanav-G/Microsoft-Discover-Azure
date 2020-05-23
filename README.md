# subiff.ai
##### A speech-to-text platform designeed for the Microsoft Discover Azure case competition
##### Placed 2nd

Launch sample-server.js

1. `echo YOUR_BING_SPEECH_API_KEY > speech.key`

2. `npm install`
 
3.  * The server and the client are on the same subnet:
    `node sample-server.js`.
    * The server and the client are on different subnets, server is not accessible from the outside:
    `node sample-server.js enableTunnel` 
    
   

