
# Table of contents
1. [How does the Internet Work?](#internet)
2. [What is HTTP?](#http)
4. [What is a Domain Name?](#domain)
5. [What Is Web Hosting?](#hosting)
6. [The Domain Name System (DNS)](#dns)
7. [How Browsers Work?](#browsers)
8. [Features](#features)
    - [hr](#hr)
    - [Task list](#todo)

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


<div id='hosting'/>
    
## What Is Web Hosting? Explained
one pair \* or \_ will make the text italic ;<br>
two pairs \* or \_ will make the text bold ;<br>
three pairs of \* or \_ will apply both styles ;<br>
two tildes \~\~ will strike out the text. Crossed out.<br>

To escape Markdown service characters, you need to put a backslash in front of each of them ( `\*`, `\_`, `\*\*`). 

<div id='dns'/>

## The Domain Name System (DNS)
To insert a link in line style, you must use the following construction: [Link text] (URL). It is possible to add a hint; to do this you need to add text in quotes after the URL: [Link text] (URL "Hint").<br>
`Hello, [world](https://i.pinimg.com/564x/5b/02/47/5b0247d140ff9659066d61fa63edc79a.jpg)!`<br>
Hello, [world](https://i.pinimg.com/564x/5b/02/47/5b0247d140ff9659066d61fa63edc79a.jpg)!
<div id='browsers'/>

## How Browsers Work




