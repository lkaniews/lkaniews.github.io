---
layout: post
title: "Cookies and Sessions"
date: 2016-02-04 09:12:00
comments: true
description: "Cookies and Sessions"
keywords: "website"
categories:
- website
- Seventh Post
tags:
- websites
- programmer
---

Liza Kaniewski 
Computer Science - A Block 
Ms. Pilgrim 
Blog Post 7: Cookies and Sessions
May 6, 2016
Blog Post 7: Cookies and Sessions

HTTP is a stateless protocol meaning that there is nothing within the protocol that requires the browser to be identified after making a request to the server as well as the connection is not continuous as it is cannot keep connection from one page to the next. The extent of HTTP is a request from the browser to the server and a reply from the server to the browser. Cookies are used to help identify the client. So what if we need to carry information over from one page to the next? We can use cookies. Cookies are parameters also used to transport data between two or more requests. Cookies are small strings of text used to gain specific information about the user that need to be carried over page by page, i.e. an online shopping cart. For example, you have experienced cookies when logging in on a site, once you log in and the credentials are validated, a cookie is sent with your own unique information with the reply. Cookies also remember past user actions. This helps store memory during HTTP transactions. A session keeps the connection prolonged between the client and the browser. It is a continuous connection until ended. A session is also responsible for keeping you logged in on a site, establishing a constant connection between the browser and user until ended. 

	The problem with cookies is that if sensitive data is stored in cookies then someone with access to the computer can gain access to it. Cookies need to be encrypted/protected in someway. Cookies are sent over plain text so they are not encrypted which means they can be intercepted during transaction, this process is called packet sniffing. The packet value can be intercepted. Once intercepted a false session can be set up to gain the information. The most common way to protect information is to use SSL which encrypts the browser request before sending the info so the packet value cannot be gained. 

	Overall, cookies are bits of information containing data unique to a person on the internet such as their login habits and account information while a session prolongs the connection between the client and browser. 


http://lifehacker.com/5853483/a-guide-to-sniffing-out-passwords-and-cookies-and-how-to-protect-yourself-against-it
http://stackoverflow.com/questions/3804209/what-are-sessions-how-do-they-work
http://shiflett.org/articles/the-truth-about-sessions
https://www.nczonline.net/blog/2009/05/12/cookies-and-security/
http://blog.teamtreehouse.com/how-to-create-totally-secure-cookies
http://guides.rubyonrails.org/action_controller_overview.html
