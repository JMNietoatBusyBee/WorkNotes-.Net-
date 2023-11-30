API Gateway notes 

3rd party integrated service 

monolithic application segmented into services (microservices) 

**API GATEWAY IS LIKE API CONTROLLER**

SSL Termination: API gateway is responsible for handling the ssl handshake, decrypting the incoming traffic then forwarding the unencrypted requests to the backend services.
Benefits of it:

*** Security** - API gateway can handle the security -related tasks such as authentication , authorization and traffic inspection after decrypting the SSL/ TLS traffic. 
This allows for better control and monitoring of API requests.
*** Simplified certificate management** - ssl certs can be managed centrally at the API gateway
* Content transformation -Examples: converting an XML to JSON
Image or Media Optimization - optimize image resizing compressing or converting them to suitable format
Adding or removing headers - can be useful on enforice security policies, modifying caching behavior or other customization

  

Main benefits: 
* Client's Performance (mas mabilis & efficient) 
* Security
* Protocol Translation ( we can change https -- http )
* Common functionality offload

  *rate limiting ex: 10 request for every 60 seconds
  * API Logging so you can monitor kung kelan mga tinatawag yung mga API

Lastly Caching - for further improve of performance -- technique used to store copies of frequently accessed data in a location that allows for faster retrieval.

