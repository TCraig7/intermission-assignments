## How The Web Works

### Background:

Review the materials below.

* First let's read [MDN HOW WEB WORKS](https://developer.mozilla.org/en-US/Learn/Common_questions/How_does_the_Internet_work)
* Next let's watch a few quick examples of [how the internet works](https://www.youtube.com/watch?v=7_LPdttKXPc).
* And [how IP addresses work](https://www.youtube.com/watch?v=KFooN7Mu0IM   - how IP addresses work).
* Finally let's tie these things together and watch a video about [DNS - what happens when you type an address into a web browser](https://www.youtube.com/watch?v=72snZctFFtA).
* Lastly, let's read a little about [the anatomy of a URL](https://doepud.co.uk/blog/anatomy-of-a-url)

### Questions:

Now we have a better grasp about the internet, and how some of the things are working. Now, let's answer a few questions to check our understanding. Don't be afraid to do additional research (googleing) for an answer. Fork this gist and answer the following questions:

1. Describe, step by step, what happens when I type `www.example.com` into my browser and try to go to the page?

      Step 1: When you type in www.example.com, your operating system and browser will determine if they already know the IP address. If they do, they will direct you to that webpage.
      
      Step 2: If they do not already know the IP address, the OS will ask a Resolving Name Server (RNS) for the IP address.
      
      Step 3: The RNS will then ask the Root Name Servers.
      
      Step 4: The Root name servers will direct the RNS to the Top Level Domain name servers.
      
      Step 5: The RNS will go to the Top Level Domain name servers, who will direct the RNS to the example.com name servers.
      
      Step 6: The example.com name servers will give the IP address to the RNS, which will relay this info back to the OS, which then sends it to the browser. The browser uses the IP address to connect to the web page.

1.  What does HTTP stand for?

       Hypertext Transfer Protocol
   
1. 	What protocol does the World Wide Web use?

       HTTP or HTTPS
   
1. 	Each computer on the Internet is assigned an IP address, what does IP stand for?

       Internet Protocol
   
1. 	What does DNS stand for?

  * A. Domain Name System
  * B. Digital Number System
  * C. Domain Number System
  * D. Domain Name Service
  * E. Digital Name Service
  
       Answer: A
              
1. 	How are text domain names matched to their respective numeric IP addresses.

       DNS creates a mapping between the numeric IP address and the text domain name.

1. 	What is the client?

  * A. A purchaser
  * B. Internet shopping customer (Consumer)
  * C. The software which requests information from a server (browser)
  * D. The server to which a particular computer sends data
  * E. The computer which the IP address belongs to
  
       Answer: E
  
1. 	What does URL stand for?

       Uniform Resource Locator

1. 	What are protocols

 * A. The standardisation of IP addressess
 * B. The DNS standard method for data transfer
 * C.	The standardised network address system
 * D.	The standardised method for transferring data or documents over a network
 * E.	The standardised method for prioratising data or document storage over a network
 
      Answer: D
 
1. What does DNS stand for?

      Domain Name System
       
1. what is the `www` portion of a url?

      World Wide Web - a prefix in the url
      
1. What is The markup language used for all web documents?

      XML - Extensible Markup Language
      
1. What is the organization that monitors web technologies?

      W3C - World Wide Web Consortium
      
1. What is the Protocol for transferring web documents on the Internet?

      HTTP, or Hypertext Markup Language (not sure which is being asked for here)

1. What matches the domain names with numeric IP addresses?

      DNS
