# Website Challenge

## Overview

For your first project on the bootcamp, we want you to make a website all about your pair partner using HTML and CSS.

The person you are making your website for is your partner, aka The Client. It is your job as a programmer to understand what the client wants from a profile site, assess what information is available and useful, design what serves the audience of users (aka the other bootcampers) best from the experience, and then create something which best solves those needs. You won't be given any guidance of what to build - you'll need to empathise with your users to see what they would find useful (or even survey and talk to them), and plan your site accordingly.

## Outcome

- a single web page created with HTML and CSS
- a profile describing your client
- a short 1-page README.md file alongside it which describes how you went about the project (your thoughts, research, plans, and justification for decisions)

## Extra

This is not only a chance for you to practice the core skills of HTML and CSS, but also a chance to invest time in thinking about how to build a website for a client, and have a user-centric approach - a key learning objective of the course. You will need to actively communicate with the client to find out everything you need in order to design and build a website which represents them to the rest of the cohort.

Although you will each have an individual repository in which to make the website, there is nothing stopping you pair programming with your partner on the project. Organise your time so that you can spend an equal amount of time on each project. For example, if you spend three hours coding together on Sunday, you would spend 1.5 hours pair programming on one site, before moving over to the other site.

This project will span the first two weeks of the bootcamp, and you will be given time in live evening sessions to work on it as well.

# What I've Learnt So Far 

## Overview

 Well it's been a tough first week! I have spent alot of time diligently notetaking and at the end of the first week and the start of the second, **things are slowly sinking in**... and I've worked out where I need to add my learning so SOC can see it... Here's a few things I've learnt below. 
 
 ## The Web 

The web and the internet are **two different things**. 

* The **internet** is like the plumbing, ferrying all the information around the Network Layer of the [Open system interconnection model][OSI Model]. When data is transmitted from a node of one LAN to the node of a different LAN, the internet is used. Data is sent in **packets**. Inside a packet you will find:

  1. **Internet Protocol or IP Address** the unique numerical code that idnetifies your/any device on the internet. Kind of link a postcode!
  2. **User Datagram Protocol** which contains the **port** number of the computer you are sending it to, and your **checksum** which is the the total value your data which helps account for and track any data sent. 
  4. **Data** the data you want to send will be munched down into **bits**. The maximum value of bits you can send is 16 e.g. 9999999999999999. Any **overflow** will _not_ be transmitted. 

* The **web** is a collection of pages that sit on top of the internet. It is a single page of **hypertext** that links to other pages and forms a huge web of interconnected information, information which is stored across millions of computers. Each of these pages has a **domain name** that acts as an identifier. This is accessible through your **web browser**. 
  When you search for something on the internet: 

  1. Your computer does a **DNS look up** [Domain Name System][DNS lookup] e.g. find food
  2. Takes domain name as input replies with matching computer's IP address
  3. Now it has the IP address, your web browser opens a **Transmission Control Protocol** connection [TCP connection][TCP] to a computer running a special piece of   software called a **web server**.
  4. It asks the web server for the " find food" **hypertext page**, it uses HTTP address [Hypertext Transfer Protocol Address][HTTP]  
  5. This is interpretted by the web browser and then it renders it to your screen! 

Thems the basics! 

[OSI Model](https://www.cloudflare.com/en-gb/learning/ddos/glossary/open-systems-interconnection-model-osi/)  
[DNS lookup](https://www.cloudflare.com/en-gb/learning/dns/what-is-dns/)  
[TCP](https://en.wikipedia.org/wiki/Transmission_Control_Protocol)
[HTTP](https://www.extrahop.co.uk/resources/protocols/http/#:~:text=What%20is%20HTTP%20(Hypertext%20Transfer,on%20the%20World%20Wide%20Web.)
 
 ## HTML
 
HTML stands for **Hyer Text Markup Language**. It is the standard markup language for all web pages. HTML **elements** are the building blocks of HMTL pages. HTML elements are represented by tags which are created with these guys **< >**. I'm now gonna whip you through the HTML basics. 

* **HTML Elements**: these consists of start tag and end tag with content in between _<&h1>_
* **HTML Attributes**: elements can have attributes which essentailly means there's more info or detail for the element and come in **name/value** pairs   _charset="utf-8"_
* To structure your document you can add:
  1. Paragraphs
  2. Headings
  3. Web links
  4. Images
  5. Buttons
  6. Lists
  7. Tables 
* **ID and Classes** are really important for web developmenet and programming. They help us give specific attributes to elements so we can better identify them

A perfect HTML base looks something like this.[base](Perfect HTML Base.html)

 ## CSS
 

 

