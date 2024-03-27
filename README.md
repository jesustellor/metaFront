https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup

$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com

Again, you need to do this only once if you pass the --global option, because then Git will always use that information for anything you do on that system. If you want to override this with a different name or email address for specific projects, you can run the command without the --global option when you’re in that project.



Title: How does the internet work?
When 2 devices connect to each other wired or wirelessly forming something called a network. you can connect multiple devices to the same network, and can be complicated as each device needs to be connected to all the other devices in the network in order to communicate effectively with each other. A Network Switch allows multiple devices to connect and communicate with each other in a network. The network switch can connect to other network switches to form a larger network, until you have something called an interconnected network(the internet).
a client server model is a way to stream or view website on the internet. the services are provided by servers. Our devices are called clients. (the internet connects the entire world). There are more details but this is the big picture of how things work.

A server is a computer that runs applications and services ranging from websites to instant messaging. its called a server because it provides services to another computer and its user or the client, its stored in a database, with 100s or 1000s of servers, all running different services connected to the internet, there are many different systems in data centers to ensure that servers have power internet, and are kept cool 24hrs a day. Data centers are all over the world and many websites use these to provide the services nearest to you. the database servers are built on the services they render, if the server is only used to store images then it will need more storage space, if it need to compute calculations the server might have faster processor and more memory(ram). The Hardware is the physical components of the server. and the software is soft or easy to change, you just replace the code running on the server. we will focus on web servers.
Web servers have many function, which include website storage and administration, data storage, security and managing emails, and handling web requests. when you open a web browser and type the name of the website, its the job of that website to send you back to that websites content, this process is known as the request and response cycle. Web servers are designed to respond to thousand of requests per second.

Webpages and Website, a webpage is a document that displays video, images, text and other content in the browser. A website is a collection of webpages that link together. They also do not have to link to the same website and can link to other websites as well. Hundreds of thousands of websites are launched every day. In its most basic form a webpage is just a text document, you can open and edit it in a text editor. HTML, CSS and Javascript make up a webpage, HTML is the structure of the webpage, CSS is the style of the webpage, and Javascript is the programming language that allows user interaction.

Brief Overview of HTML, CSS and Javascript.
HTML, Hypertext Markup Language. it works by using markup tags, these tags describe the content that is displayed, things like headings, paragraphs, images, and multimedia such as audio and video, the way HTML describes the content is called markup.
CSS, Cascading Style Sheets.
CSS, adds visual enhancements like colors, fonts, and layout to HTML. it works by enhancing the HTML elements and telling them how to display.
JavaScript, is a programming language built into the browser. JS provides developers with tools for interactivity, data process, control, and action, like logins or youtube updates. JavaScript has the ability to manipulate the content as you interact with it.
Page Rendering is the process of displaying content on the screen.

A web Browser or Browser for short is a software that allows you to view the World Wide Web. it works by sending a request to a web server and then receives a response containing the content to be displayed on the screen of your device. once the browser is open there is the address bar where you input the address of the website you want to visit. the address is known as the URL (Uniform Resource Locator). The URL contains the protocol, the domain name and the file path. when you make a request the browser and server communicate using a protocol known as the Hyper text Transfer Protocol, or HTTP. this is known as the request and response cycle.

By using your favorite search engine, the name you type is called a domain name, the browser sends a request to another computer on the internet called a web server, a special type of computer that allows other computers to make requests for data, the web server responds by sending a webpage back to the browser. the webpage is a coded document that is rendered by the browser, then presented visually to you. by searching something, the request is sent to the same search engine web server, this time the request contains the added instructions for the phrase you are searching for. the search engine web server processes the request by taking the keyword and using it to find the requested data. this data is stored in a database which is connected to the web server the web server picks up that data and sends it back to the browser, rendering the Links, Maps, and other related content such as reviews and reservations, all made possible by computers having a conversation, this is an insight on how the request and response cycle works.

Web Hosting, is a service that lets you launch websites to the internet without having your own data center. You place your website and files on the hosting companies web server, essentially renting the space in return for stable and secure storage. some of the different types of hosting include Shared hosting, Virtual Private Hosting, Dedicated Hosting, and Cloud Hosting.
Cheapest form of web hosting is known as shared hosting, you pay for a location on a web server containing many other hosting accounts with shared hosting, this means that you share, the servers processing power, memory, and bandwidth, with other websites that might slow your performance. this option is best for a small website, with a small number of visitors. many developers use this as well as a low cost sandbox environment to test and practice deploying or hosting a website. some companies offer free shared hosting with limitations and often have advertising embedded in their webpages.
Virtual Private Servers (VPS) is a virtual server with dedicated resources, CPU, memory and bandwidth resources. it will be running on hardware with other VPS instances, the resources are fixed per VPS instance. Your website will not be affected by the performance of other VPS instances. VPS is more expensive than shared web hosting.
Dedicated hosting, is a hardware server that is dedicated to you. all hardware cpu, memory and bandwidth are yours to use, it is more expensive than VPS.
Cloud Hosting and the cloud has grown in popularity, with cloud hosting, your website is run in something called a cloud environment, which span multiple physical and virtual servers. if a physical or virtual server fails, your website will run on a different server and stay online. the advantage of cloud hosting is that you can use as many resources as you need without hardware limitations.  you pay based on resource used. it allows to scale your cost as popularity grows this is how many of the major web applications operate.

Internet core technologies.
IP addresses act like addresses in the postal system where they facilitate the delivery of information.
when you send data to another computer across the internet, the computers are the destinations that request and receive data. and the network are the roots that the data travels across, ipv4 and ipv6 are the 2 protocols used today. In ipv4 the ip address contains four octets, for example, 192.168.117.1 in ipv6 the ip address contains 8 hexadecimal octets. when you send data you send data in ip packets known as datagrams. at a high level ip packets contain a header and a payload that contains the data. the header contains information about the source and destination of the data, and the payload contains the actual data and other protocols. the 2 most common protocols used today are tcp and udp, transmission control protocol and user datagram protocol respectively. tcp can solve the problem of data being out of order at the cost of a small delay when sending the data, text or image files. UDP solves the corrupt, but data can still arrive out of order or not arrive at all, udp is used in voice calls or live video streams. and both of them have more protocols inside of them. these protocols help in data to arrive in order, doesn't become corrupted, and doesn't get dropped or lost during transit.

HTTP and HTTPS hyper text transfer protocol and secure.
HTTP is the protocol you  use whenever you use the web, it is the protocol used to transport images web pages (html) and other files. HTTP is a request-response protocol. a web browser or client sends an http request to a server an the server sends and HTTP response to the client or browser.
and HTTP request consists of a method, path, version and header information. the method describes the action the client wants to perform, the most commonly HTTP methods are GET, POST, PUT, DELETE.
the GET method is used to retrieve information from a given server, the POST method is used to send information / data to the server. the PUT method updates what is already on the server with something else and the DELETE method removes the resource from the server.

HTTP request -
GET / HTTP/1.1              the method, the path, and the HTTP version.
Host: www.google.com        this part is the Headers containing information about the request.
accept-language: en

HTTP response -
HTTP/1.1 200 OK
content-type: text/html
content-length: 1000
connection: keep-alive
last-modified: Mon, 01 Jan 1990 00:00:00 GMT
server: Apache

following the header the response contains the Message Body, which is the content of the web page, in this case html, images etc.

HTTP status codes
there are 5 groups of status codes.
1xx - 199 Informational
2xx Success
3xx Redirection
4xx Client Error
5xx - 599 Server Error

Information responses are Provisional responses sent by the server, these responses are interim before the actual response the most common informational response is 100 Continue, to continue the request or ignore the response if the request is already finished.
Successful responses indicate that the request was processed successfully. these responses are 200 OK, 201 Created, 202 Accepted, 203 Non-Authoritative Information, 204 No Content, 205 Reset Content, 206 Partial Content.
The meaning of ok depends on the HTTP method, for example if you send a GET request, it means that the resource was found/included, if the method is POST then the resource was successfully transmitted to the web server, as well with PUT, and DELETE, means that the resource was deleted.
Redirection responses indicate to the web client that the request resource has been moved to a different path. the most common responses are 301 moved permanently and 302 found. the difference between 301 and 302 is that 301 is permanent and 302 is temporary. when web browsers receive these response they will automatically submit the request for the resource at the new path.
Client Error responses indicate that the request contained bad syntax or content and can not be processed by the web server. the most common codes used are 400, used for when the web browser or client submit bad data to the web server, 401 is used to indicate that the user must be logged in to an account before the request can be processed. 403 is used when the user or client is not authorized to access the requested resource, the request vas valid. 404 is used when the requested resource is not found.
Server Error responses indicate that the server encountered an error while processing the request. the most common responses are 500 internal server error the server failed to process the request, 501, 502, 503, 504 and 505.

HTTPS, when buying things online you would use HTTPS. it is the secure version of HTTP. it is used for secure communication between two computers so that nobody can see the information being sent and received. it does it by encryption. Like in HTTP the request and responses behave in the same way. the big difference is that before the content is sent it is turned into a secret code (encrypted). Only the other computer can turn the secret code back into its original content.
Overview of HTTP, it is a protocol used by web clients and web servers. it works to transfer resources such as HTML files and is the foundation of any data exchange on the web. also remember that by using HTTPS you are encrypting the data. Request are sent by the client usually a web browser and the server responds with responses of an image or HTML file. HTTP request have a syntax that include the method, the path and the HTTP version, and headers. HTTP responses follow a similar format as the request, the HTTP status codes indicate if the request successfully completed. the status code is a three digit number that corresponds with groups representing different types of results.

Webpages are based on three core technologies, HTML, CSS and Javascript. together you can create webpages and applications to offer any content you have seen online. On the first example there is a webpage that displays a digital clock, it shows the hour minute and seconds. the time is updated every second. made only with 3 files HTML CSS and Javascript. to create the clock element, first create a file called clock.html. the html code has an element that describes the content in hours minutes and seconds. if you only used an HTML file you would not see position change or styling. to apply styles to the HTML element, the HTML code references a CSS file. web browsers retrieve the file.css file and process it. the CSS tells the browser the position, size, color, background and font type and size of each element on the screen with that the HTML would be styled. finally we need to ensure that the clock updates at the correct time. Javascript is used to update the clock. the JavaScript code updates the Hour, minutes and seconds. in this example js is updating the clock dynamically. Javascript can also be used for interaction. In a webpage that play videos, the button that starts and stops the video is an example of Javascript. the HTML page describes the video element and the button element. The HTML code references a CSS file to apply styling to video and button, the HTML also references a Javascript file. the code in the JS file performs 4 actions, it registers a listener that will execute some code when the button is clicked, the second function is that when the code is run it checks the status of the video, the result is if the video is playing or not, and changing the play button to stop icon.

Intro to Front End Course - Core Internet Technologies - Other Internet Protocols.
HTTP is used on top of TCP to transfer webpages and other content from websites.
DHCP is used to get an IP address. the server keeps track of computers on the network and their IP addresses.
DNS is used to map the domain name to an IP address.
IMAP is used to transfer emails, this protocol is used to download and manage your emails.
SMTP is used to download emails to an email client. you can also use it to send emails, but IMAP is more commonly used.
POP the main difference in using POP vs IMAP is that POP will delete the emails on the server once they have been dowlaoaded.to your local device.
FTP is used to transfer files between computers. or a way to transfer files between a computer and a server.
SSH Is used to log in and interact with the computer remotely, all data over SSH is encrypted.
SFTP SSH is used to transfer files between computers.

Websites, Webpages, and Web Applications. - What are the differences.