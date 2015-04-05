# ComputerNetworksHandbook
A Book for Newbie Web Developers

## Introduction
For a Web Developer, a basic knowledge of Internet is truly crucial. I am one of the Newbies in the Web development world but really want to consolidate the basic concept of the Internet World in my mind. 

The propose of this project is to start a online reading group for Networks knowledge. No matter how you are familiar with Internet knowledge. You are always welcome to become one of the project contributors.

I use a textbook named ["Computer Networks: A System Approach (5th)"](http://books.google.com.tw/books/about/Computer_Networks.html?id=BvaFreun1W8C&redir_esc=y). I make a lot of notes from this great textbook and the structure project is according to the book's outline. If there are some mistakes or ambiguous parts, please let me know and correct it together.

Also, the implementation is an easy way to learn how to build an internet from the ground up. To become a great Web developer, I will do the implementation as much as possible.


If you like this project. Please follow me or star it :). It is a kind of encourage to make a high quality material.

## Outline
### Chapter 1: Foundation

### Chapter 2: Getting Connected

### Chapter 3: Internetworking

### Chapter 4: Advanced Internetworking

### Chapter 5: End-to-End Protocols

### Chapter 6: Congestion Control and Resource Allocation

### Chapter 7: End-to-End Data

### Chapter 8: Network Security

### Chapter 9: Applications



## Chapter 1: Foundation

### What's going on when we enter the url on our browser and press "enter"?

Using web browser 

This identifier, called a Uniform Resource Locator (URL), provides a way of identifying all the possible objects that can be viewed from your web browser.

An example: 
http://en.wikipedia.org/wiki/Main_Page

It's a url for a page providing the indicated resources.

String http is "Hypertext Transfer Protocol" 's abbreviation which browser download the resource with.

en.wikipedia.org is the machine name which serves the page.

When we do a simple click for viewing the page resources, most of the users are not aware of is there are dozen of messages exchanges happen behind the screen.

The messages include 6 for translating server name into IP (Internet Protocol) address, 3 to set up a TCP(Transmission Control Protocol) connection between the browser and the server, 4 for your browser to send the HTTP “GET” request and the server to respond with requested page. Finally, there are 4 messages to terminate the TCP connection.

### How the networks are built?

The creation of networks is based on the connection of the computers. We can build a small netwrok with two or three computers connecting each other. In contrast, the Internet we use all the time is the result of billions computer clusters.

The network is the set of the nodes and links. Nodes, as we know, are the devices we are using to connect with the digital world. Links are the mediums the devices communicating with each others such as the physical cables or wireless. 

### 

## Uncatogorized Questions :
1. What is log? When is the log produced? 

2. What is load balanicng? 

3. Can we distribute load by using multiples urls pointing to the same Webs?

4. What is OSI?

5. What is CDN? 

6. Datagram? What is it about? 

7. Do we need an IP address when we buy a VPS services from the providers? 
