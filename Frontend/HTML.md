
# Table of contents
1. [How does the Internet Work?](#internet)
2. [What is HTTP?](#http)
4. [What is a Domain Name?](#domain)
5. [What Is Web Hosting?](#hosting)
6. [The Domain Name System (DNS)](#dns)
7. [How Browsers Work?](#browsers)

<div id='internet'/>
    
## How does the Internet Work?
*There are two main concepts that are fundamental to the way the Internet functions: packets and protocols.*

### Packets
In networking, a packet is a small segment of a larger message. Each packet contains both data and information about that data. The information about the packet's contents is known as the "header," and it goes at the front of the packet so that the receiving machine knows what to do with the packet. To understand the purpose of a packet header, think of how some consumer products come with assembly instructions.

When data gets sent over the Internet, it is first broken up into smaller packets, which are then translated into bits. The packets get routed to their destination by various networking devices such as routers and switches. When the packets arrive at their destination, the receiving device reassembles the packets in order and can then use or display the data.

Compare this process to the way the United States' Statue of Liberty was constructed. The Statue of Liberty was first designed and built in France. However, it was too large to fit onto a ship, so it was shipped to the United States in pieces, along with instructions about where each piece belonged. Workers who received the pieces reassembled them into the statue that stands today in New York.

While this took a long time for the Statue of Liberty, sending digital information in smaller pieces is extremely fast over the Internet. For instance, a photo of the Statue of Liberty stored on a web server can travel across the world one packet at a time and load on someone's computer within milliseconds.

Packets are sent across the Internet using a technique called packet switching. Intermediary routers and switches are able to process packets independently from each other, without accounting for their source or destination. This is by design so that no single connection dominates the network. If data was sent between computers all at once with no packet switching, a connection between two computers could occupy multiple cables, routers, and switches for minutes at a time. Essentially, only two people would be able to use the Internet at a time — instead of an almost unlimited number of people, as is the case in reality.

### Protocols
Connecting two computers, both of which may use different hardware and run different software, is one of the main challenges that the creators of the Internet had to solve. It requires the use of communications techniques that are understandable by all connected computers, just as two people who grew up in different parts of the world may need to speak a common language to understand each other.

This problem is solved with standardized protocols. In networking, a protocol is a standardized way of doing certain actions and formatting data so that two or more devices are able to communicate with and understand each other.

There are protocols for sending packets between devices on the same network (Ethernet), for sending packets from network to network (IP), for ensuring those packets successfully arrive in order (TCP), and for formatting data for websites and applications (HTTP). In addition to these foundational protocols, there are also protocols for routing, testing, and encryption. And there are alternatives to the protocols listed above for different types of content — for instance, streaming video often uses UDP instead of TCP.

Because all Internet-connected computers and other devices can interpret and understand these protocols, the Internet works no matter who or what connects to it.

<div id='http'/>

## What is HTTP?

### HTTP
**HTTP** stands for *Hypertext Transfer Protocol*. It is the underlying protocol used by the World Wide Web to define how messages are formatted and transmitted, and how web servers and browsers should respond to various commands. It is the foundation of data communication for the World Wide Web and is used to transmit and receive web pages and other resources on the internet.

### HTTPS
**HTTPS** stands for Hypertext Transfer Protocol Secure. It is a secure version of the HTTP protocol, which is used for secure communication over a computer network. HTTPS encrypts the data being transmitted, making it more secure and less vulnerable to interception or hacking. It is commonly used for secure communication on the internet, such as when making online purchases or accessing sensitive information.

<div id='domain'/>
    
## What is a Domain Name? 
A **domain name** is the address of a website on the internet. It is the text-based label that is used to access a specific website, such as www.example.com. Domain names are used to identify and locate websites on the internet and are an essential part of the internet infrastructure.

<div id='hosting'/>
    
## What Is Web Hosting? Explained
Web hosting is a service that allows individuals and organizations to make their websites accessible via the World Wide Web. In other words, web hosting providers offer the technology and services needed for a website to be viewed on the internet. This includes storing website files, images, videos, and other content on a server, which is then connected to the internet and accessible to anyone who visits the website. Web hosting providers also offer other services such as domain registration, email hosting, and website building tools. There are different types of web hosting, including shared hosting, VPS hosting, dedicated hosting, and cloud hosting, each offering different levels of resources and control for website owners.

<div id='dns'/>

## The Domain Name System (DNS)
**The Domain Name System (DNS)** is a decentralized naming system for computers, services, or any resource connected to the Internet or a private network. It translates domain names, which are easy-to-remember human-readable addresses, into numerical IP addresses that computers use to identify each other on the network. The DNS plays a crucial role in the functionality of the internet by enabling users to access websites, send emails, and perform other online activities using familiar domain names instead of having to remember and use complex IP addresses. The DNS also supports various other types of information, such as mail server records and service location pointers, making it an essential component of the internet infrastructure.
<div id='browsers'/>

## How Browsers Work
Web browsers are software applications that allow users to access and navigate the World Wide Web. Here's a simplified explanation of how browsers work:

1. User Input: When a user enters a web address (URL) into the browser's address bar or clicks on a link, the browser sends a request to the server hosting the website.

1. Request and Response: The server processes the request and sends back the website's files, including HTML, CSS, JavaScript, images, and other resources, in the form of a response.

1. Rendering: The browser receives the response and begins to render the web page. It parses the HTML to create the Document Object Model (DOM) and the CSS to create the CSS Object Model (CSSOM), which together form the structure of the web page.

1. Layout and Display: The browser uses the DOM and CSSOM to determine the layout of the web page and how elements should be displayed. It then renders the page, displaying the content and applying styles as specified in the HTML and CSS.

1. JavaScript Execution: If the web page includes JavaScript, the browser executes the scripts, which can modify the DOM, handle user interactions, and perform other dynamic actions.

1. User Interaction: The browser allows users to interact with the web page, such as clicking on links, filling out forms, or interacting with media elements.

1. Additional Features: Browsers also offer additional features, such as bookmarking, history, extensions, and security measures to protect users from malicious websites and online threats.

1. Overall, web browsers play a crucial role in enabling users to access and interact with the vast array of content available on the internet.



