# Food-Hut-

 FOOD HUT 
A Dissertation submitted in partial fulfilment of the 
requirements for the award of the degree of
 BACHELOR OF COMPUTER APPLICATIONS Of
 AMITY UNIVERSITY ONLINE 
 
 By
KEERTHI J 
 Under the Guidance of
 Project Guide 
 NAGESH BS 
 Assistant Professor 
 Department of MCA 
 RNSIT 
 Bengaluru–98 
 
 
June 2023 
DECLARATION 
I, KEERTHI J student of 6th Semester, Department of BCA, Amity University Online, 
declare that the project entitled “FOOD HUT”, is a record of the original work done by 
me under the guidance and supervision of, NAGESH BS Assistant Professor, Department 
of PSC, RNSIT Bengaluru and this project work has not formed the basis of any other 
Degree/Diploma/Associateship/Fellowship or similar title to any candidate of any 
university. 
 
Name: KEERTHI J Signature of the candidate 
 
I
ACKNOWLEDGEMENT
The successful completion of a project depends on the co-operation and help of many 
people, along with those who directly execute its work. 
I take this opportunity to acknowledge the help received for valuable assistance and cooperation from many sources, right from the stage when the project was conceived to the 
stage of its completion. 
I express my sincere words of gratitude to Amity University for creating an academic 
environment to enlighten our career. 
I am also deeply indebted 
I express my heartfelt thanks to Project Guide, NAGESH BS, Assistant Professor, 
Department of MCA, RNSIT Bangalore for her constant guidance and devoted support. 
I also express my heartfelt thanks to all the faculty members, technical staff, non-teaching 
staff of amity university, my family, friends, and well-wishers for their constant 
encouragement. 
 
KEEERTHI J 
II
Running head: My title 1
 TABLE OF CONTENTS
PAGE NO 
DECLARATION----------------------------------------------------------------------------------------------- I 
ACKNOWLEDGEMENT------------------------------------------------------------------------------------ II 
TABLE OF CONTENTS------------------------------------------------------------------------------------- III 
LIST OF FIGURES------------------------------------------------------------------------------------------- V 
LIST OF TABLES-------------------------------------------------------------------------------------------- V
BIBLIOGRAPHY------------------------------------------------------------------------------------------ VII
ABSTRACT---------------------------------------------------------------------------------------------------- VII
1. INTRODUCTION 10
1.1 Project description 10
2. LITERATURE SURVEY 13
2.1 Existing and proposed system 13
2.2 Feasibility study 15
2.3 Tools and Technologies 
2.4 Hardware and Software Requirements 
16
22
3. SOFTWARE REQUIREMENTS SPECIFICATION 
3.1 Users 
24
24
3.2 Functional Requirements 25
3.3 Non-Functional Requirements 31
4. SYSTEM DESIGN AND ANALYSIS 34
4.1 System Perspective 34
4.2 Context diagram 35
5. DETAILED DESIGN 39
5.1 Use Case Diagram 40
5.2 Sequence Diagram 42
My title 5
 III
6. IMPLEMENTATION 45
6.1 Screen shots 45
7. SOFTWARE TESTING 51
7.1 Types of testing 
7.2 Test Cases 
52
53
8. CONCLUSION 
9.FUTURE ENCHANCEMENTS 
57
58
IV
My title 6
LIST OF FIGURES 
Figure No. Caption 
Page 
No. 
2.1 TypeScript Compiler 17
2.2 Angular Architecture 18
2.3 CSS code sample 19
2.4 SCSS code sample 19
2.5 Angular Web Application Output 21
2.6 JSON Array 22
2.7 JSON Values 22
4.1 Architecture of Proposed Framework 35
4.2 Level 0 - DFD for Online FNB 36
4.3 Level 1 DFD for Online FNB 37
4.4 Level 2 DFD for Online FNB 38
5.1 Detailed Design of Online FNB 39
5.2 Use case diagram for Online FNB 41
5.3 login page Sequence Diagram 42
5.4 Choose your delivery pop-up 43
5.5 Pickup in store 43
5.6 On Delivery 44
5.7 Add an address pop-up Sequence diagram. 44
6.1 Homepage 45
 V
My title 7
6.2
 
Sign In pop-up 46
6.3 OTP verification pop-up 46
6.4 Choose you pick up store pop-up. 48
 6.5 
 6.6
 6.7
 6.8
 pickup-from-nearby-store pop-up. 
 Cart Screen 
 Product search layout 
 Order confirmation screen 
 50
49
49
50
VI
My title 8
LIST OF TABLES
Table No. Table Name Page No. 
2.1 Hardware Requirement 15 
2.2 Software Requirements 16 
 
 
 VII
My title 9
ABSTRACT 
The people over the world have become a digital nomad who live an entirely digital existence! 
Also, the thing we have learned all through in this generation is that we can get anything we 
need with a couple of snaps on our adored shrewd gadgets like Desktops, Laptops, Tablets, and 
handhelds and so on. Even food – all varieties of it -to satisfy the desires of various person on 
various days of the week. It is truly a time when there is something for everyone, whether they 
are consumer or the providers. The Food Industry is a complex network of operations involving 
supply, use and catering of food items and services, and it plays an important role in every 
country’s economic development. 
 
The Food and Beverages sector – online, Eatery activities are as a rule incredibly affected by 
the web and innovation upgrades. With the vast majority spending a critical segment of their 
day on the web, eateries have an extraordinary business opportunity. Truly, Online Feast 
requesting is getting progressively well known among café benefactors. Café chiefs and 
proprietors are consistently watching out for approaches to allow purchases to make orders on 
the web and have their food conveyed rapidly. Without a doubt, as more café’s embrace this 
plan of action, internet requesting, and conveyance frameworks are progressively turning into 
the norm. 
 
Food hut is a web-application developed using angular Framework, where the Customers, 
restaurant partners, and delivery partners are all connected through this platform, which serves 
their various demands. Customers can use this website to find restaurants, read and write the 
customer reviews, see, and upload images, order the food online for delivery or to directly pick 
up from them from near-by restaurant. 
 
 
 
 
 
My title 10
Chapter 1 INTRODUCTION 
1.1 Project Description 
Food hut is web-based application developed using angular platform, which can be accessed by 
the customers at any time on various smart devices such as desktops, palmtops, laptops, mobile 
phones etc... Food – bucket is an online food ordering system from various restaurants. An 
Online food ordering system’s main goal is to give the client a method to order food from a 
client’s favourite restaurant over the internet. The customer can get the food delivered to their 
home directly, else they will also be given an option to pick up from there nearby store if their 
address is not supported for delivery. 
 
In point of fact, Online supper requesting is getting progressively mainstream among 
consumers. Eatery proprietors and administrators are consistently watching out for approaches 
to allow the buyers to make orders on the web and have their food conveyed rapidly and have 
similarly, independent of time and spot. Also, more eateries embrace this plan of action, webbased requesting and conveyance frameworks are step by step turning into the trend. 
 
Websites are available for the customer from anywhere anytime, there is no need for registration 
or signing up to the application until and unless the customer is willing to order the food and 
complete the transaction. Food hut is purely build using the Angular Web framework using 
Media queries and general flex boxes to make the website to be accessed in smart devices with 
different width and height. Angular web framework is an amazing platform for developing a 
single page client application that uses HTML as a mark-up language, SCSS to make the 
website creative and typescript as a programming language. Since the application is developed 
in Angular platform, Customer can use the Food hut website as smooth as possible with all the 
effective features available. 
 
Using Food hut website is easy and fun, the customer can order the food and get it delivered to 
their home at a minimal step. Customer browses for: https://hostname/home/ and an application 
is loaded on the Landing page. The landing page of the website gives a simple and easy vision 
My title 11
of navigation and aids the visitors in accessing the available sections of the application, it also 
provides the banner in landing page (home page), that lets the customer to know the offers 
available at various restaurants, cuisines, offers that are intended at locations along with the 
current location of the visitor using the website. The objective of a Food hut banner is to create 
a focal point, since customer browses the website and get loads on the landing page, banner is 
the first thing noticed, which is why is it so important to have a banner, because it only has a 
few seconds to spark a visitor’s attention and encourage them to stay on the site for further 
browsing. 
 
After the banner section customer will be displayed with the product search layout, display 
group items, followed by the signature products. Customer can search for their food based on 
the cuisines, restaurants, dish that displays a list of available items. To see the menu and 
additional specific information, visitors must simply feel free to click on the dishes or the 
cuisines or the restaurant name or image. If the user is not registered patron, initially after the 
page load customer will click one of the menu links in the landing and selects the delivery mode 
from the list of options available based on the admins site configurations. If the customer is 
already a registered user and ordering the food for second time from the same place, by then 
customer will be directly viewing an available product. 
 
One of the coolest features of Food hut is that customer will be given with two delivery options, 
one is that the customer can order the food and pickup by himself from the store that is near to 
him/her, secondly, he/she can order the food directly to their home. If the customers enter the 
address that will not support for delivery or that is not a delivery zone, system automatically 
displays a customer with a list of pick-up stores that is near to their residence. 
Patrons selects all the desired options from the website, visits all the products and adds them to 
the cart, in middle of adding to the cart process customer will also be given an option to replace 
their products with the upsell products, is the customer is not ready to upgrade their product 
they can simply continue with the transaction by clicking on the checkout in the cart screen else 
customer must select one of the upsell product that will be replaced with the previously selected 
product also they go through the products modification screens if applicable . 
My title 12
The visitors can go through the website without registration, customers login and personal 
information is required only after the customer enters the checkout. One more efficient feature 
is that if customer remains unlogged until the checkout page, system will automatically detect 
and direct them to login page that has 3 classifications, they are login section, registration 
section and the guest login section. Customer can also edit their product before they enter the 
payment and complete their transaction. Once the order is placed successfully, the customer 
will be provided with an email of order confirmation and the customer can also view the status 
of their order like, whether the order is confirmed, food is being prepared, is the food out for 
delivery or the food is delivered or not etc. 
 
The registered customer is also provided with their dashboard, where in as when required they 
can change the personal information that was added earlier, they can add the new addresses to 
get delivered or can remove it from the portal and can set the address into 3 categories either to 
be a home, default, and work address. Customer will also be given access to view their orders 
history and just a click of order number they can again re-order the products. If the customer 
wants to track their product, they do not want to stay on the same page after the transaction is 
completed since in the dashboard, they can enter the order number and email ID or phone 
number to track the status of their product. 
 
In this way the people who has a busy lifestyle, can comfortably order their food at any time 
anywhere and feed themselves with mouthwatering foods. This is the ideal place to look for 
and order delectable restaurant-cooked meals prepared with love! On this website, you may 
order a wide range of cuisines and menus, as well as have numerous delicious delights delivered 
right to your house. 
 
 
 
My title 13
Chapter 2 
LITERATURE SURVEY 
2.1 Existing and Proposed System 
This section provides a brief overview of the present system, including its benefits, 
shortcomings, and limitations. The proposed system intends to improve the system’s 
performance by removing restrictions and increasing accuracy. 
2.1.1 Existing System 
In the Existing System, those in the food and beverage sector have always had to telephone to 
place orders or drive through restaurants to pick up their meals, which is not the easiest way to 
get meals from restaurants, especially for people who lead busy lives. In terms of business, it’s 
tough to keep track of client data, and it takes time for restaurants to reach out to the customers. 
Customers who wish to order meals in the current system must make a call on telephone to put 
requests or drive to cafes or restaurants to get, then, at that point trust that the food will be ready 
and conveyed which is not the best answer for individuals who lead busy lives. Also, there may 
be scenarios for the customers to dine-out for a day, in existing traditional system customers as 
to pre-book tables a week before or several days in advance, which is not a better option and 
does not develop a robust Customer Relationship Management (CRM System). 
The Conventional Approach has several drawbacks are as follows: 
• It makes ordering difficult, causing customers to phone restaurants or drive for pick-up. 
• There is no efficient way to manage clients and orders. 
• Business Merchants, manually keeps track of all expenses incurred in real time. 
• Customer data cannot be saved to improve customer experiences and forecasts. 
• Difficult for the restaurants to reach the greater customers. 
• Could not be ahead of the competition. • Not convenient for mobile ordering 
• Marketing costs would be higher. 
Switching to online ordering of food and beverages is the greatest option for this since it 
simplifies the ordering process, improves, and manages the relationship between customers and 
the restaurants managers, and allows for free and low-cost marketing. 
My title 14
2.1.2 Proposed System 
Our website is primarily focused on convenience of use, with the ability to be used at anytime, 
anywhere in any sort of smart devices. The organization am working for as already as their 
strong foundation on Family Entertainment Centre and Park sectors, they are also having 
services of Food and beverages, but it is windows application and limited only to the point ofsale machines and cannot directly used by the customers to order the food as we do in Zomato 
and Swiggy websites. Food hut is the new try by the organization, to bring food and beverages 
industry available online and make it as an online sale application, that is not only limited to 
point of sale machines and can be used by customers to order their foods. 
The windows application is replaced with the web application, which was developed using 
Angular framework. In recent years, Angular has exploded in popularity, and for good cause, 
with its justifying features that includes functionality out of box, typescript as programming 
language, known for its consistency, productivity, maintainability, for its modular development 
structure also supporting an angular material element. Along with the angular framework the 
usage of CSS to style the websites as made the website Responsive and mobile friendly using 
one of the CSS techniques known as Media Queries and flex boxes. The combination of two 
powerful technology is used to build a powerful website. Proposed system was able to 
overcome many issues that the conventional system had in terms of accuracy, speed, and ease 
of use that made lots of difference between them. 
The planned system’s items of interest are: 
• Food ordering as become an easy process. 
• No need of registration and login until and unless the customer wants to buy something 
from the website. 
• Very user friendly and easy to use. 
• Scalable website can be expanded on the user’s feedback. 
• Website can be used by the customers it is not limited only as a point-of-sale application. 
• Customer is given with two convenient delivery options. 
• Customer can also change their delivery method option just before entering into the 
payment phase. 
• Customers will get order-confirmation email, so as when required they can track the 
status of their order. 
My title 15
• It also overcome all the issues of exiting system and the customer does not want to have 
any additional skills to us this website. 
 
2.2 Feasibility Study 
The Feasibility study has been conducted prior to undertaking of Food hut project to make the 
investors and the principals of companies to ensure that the proposed project we have planned 
to develop is actually “feasible”. The funds required to finish the project, the market 
opportunity, government laws, strengths and weaknesses, risk considerations, the management 
team, and the company’s financials are all included in a feasibility study. 
Feasibility analysis is necessary for the following reason: 
• When we wish to incorporate and integrate new features into the project, we need to 
conduct a feasibility study. 
• Determine whether the project will generate a return on investment. 
• If there is no way to know how long a project will take to complete, then estimate how 
long it will take to accomplish it. 
• Determine how much manpower or personnel will be necessary to complete the project 
successfully. 
• To acquire sufficient evidence to ensure that the project is worthwhile. 
 
2.2.1 Technical Feasibility 
The technical and mechanical assets available to the association are the subject of this 
assessment. It aids companies in determining whether technical resources are adequate for the 
job and whether the technical team can turn the system into the concepts of interpretational. 
The system that is proposed now, its hardware, software, and other technical needs are also 
evaluated for technical viability. The Food hut web application is produced by utilizing the 
Angular Web framework, that creates a single page web application that is available for free. 
The web application takes up a lot less space and works very efficiently because it uses so little 
memory. 
My title 16
2.2.2 Economic Feasibility 
The cost benefit analysis of the project is generally included in this review, which helps firms 
determine the project’s viability, cost, and benefits before devoting financial resources. It also 
serves as an unbiased project evaluation, enhancing project credibility by aiding 
decisionmakers in assessing the project’s favourable economic benefits of the company. 
 
2.2.3 Operational Feasibility 
This evaluation involved doing research to determine if – and to what degree – the project could 
satisfy the needs of the organization. Operational feasibility studies examine how a project plan 
complies with the requirements established during the system development requirement 
analysis phase. One of the examples in food hut website is, Users who are visiting the website 
for the first time should have no problems scrolling through the application because it was 
designed with the input of diverse users in mind. In the event that a user has any difficulties, 
the software is extremely user-friendly and self-explanatory. 
 
2.3 Tools and Technologies Used 
There are lot of tools and technologies out there, and they are widely used. The number of tools 
and technologies to be used must be carefully considered. The most up-to-date technology with 
heigh reliability and precision, as well as convenience of use, can be included as a piece. In 
terms if strategy the project’s progress and dependability are heavily reliant on the technologies 
used 
 
2.3.1. Type Script 
TypeScript is an open-source language that extends JavaScript with static type definitions to 
JavaScript, one of the most widely used programming languages. Types gives a means to 
specify the geometry of an object, allowing TypeScript to test that our code is working correctly 
and giving the better documentation. Type interface lets us to acquire a lot of power without 
writing any more code, therefore creating types is optional with TypeScript. 
All TypeScript code is legitimate JavaScript code. We may receive type-checking error, but this 
will not prevent us from running s JavaScript results. While harsher behaviours are an option, 
it still means we have control. 
My title 17
 
Figure 2.1: TypeScript compiler 
The typescript compiler or Babel is used to convert TypeScript code is converted to JavaScript 
code. This JavaScript code is simple and tidy, and it can be used everywhere that Java Script 
is supported, such as in a browser, Node.JS, or other programmes. 
 
2.3.2 Angular 9.0
Angular is a Single-page client application platform and framework built on HTML and 
Typescript. Angular is written in TypeScript. It provides core and optional functionality as a 
series of Typescript libraries that we load into our projects. Angular 9 is the most recent version 
of Angular, a framework for developing online and mobile client-side programs using 
JavaScript, or more accurately, Microsoft’s TypeScript super-language. It includes TypeScript 
3.7 support, as well as improvements to the IDE and language service extension, which will 
boost Angular developers’ efficiency and help them discover problems while developing apps. 
The Architecture of an Angular application is built on a few fundamental ideas. The basic 
building blocks of the Angular framework are Angular components, which are organized into 
Ng modules, which are functional groups of connected code. To enable bootstrapping, an 
application must have at least one root module and most applications have multiple root 
modules. 
The components define views, which are groupings of screen components that Angular may 
pick and change based on our program’s logic and data. Components rely on services to provide 
functionality that is not tied to views directly. Components may utilize service providers as 
My title 18
dependencies, making our code more modular, reusable, and efficient. Modules components, 
and services all utilize decorators. These decorators specify the sort of element they are and 
provide information to Angular on how to use it. The metadata of a component class links it to 
a template that specifies a view. A template combines ordinary HTML with Angular directives 
and binding syntax, allowing Angular to modify the HTML before generating it for display. A 
service class’s metadata provides Angular with the information it requires to inject dependency 
injection into its components. 
Many views are typically defined by an application’s components, which are arranged 
hierarchically. The Router service from the Angular allows us to define navigation paths 
between views. The router has powerful navigational features within the browser. 
 
Figure 2.2: Angular Architecture 
2.3.3 HTML 
HTML is a Hyper Text markup language, in which most websites are written. HTML is used to 
create pages and make them functional. The connections or the links that associates online 
pages inside a solitary site or between sites are alluded to as “hypertext” in HTML. The Internet 
is comprised of a ton of connections. By transferring, we have all become dynamic members
on the web, distributing stuff on the web and connecting to others’ sites. 
2.3.4 SCSS 
The superset of CSS is SCSS (Syntactically Awesome Style Sheet). SCSS is a further developed 
rendition of SCSS. CSSS is a CSS variety was made by Hampton Catlin and created by Chris 
Eppstein and others. Natalie Weizenbaum is to be sure an essayist. Sassy CSS is the name given 
My title 19
to it because of its sophisticated features. The SCSS files extension is scss. The difference 
between CSS and SCSS are as follows, 
1. SCSS is full of advanced features. 
2. Variables are available in SCSS, and we can use them to shorten our code. It has a 
significant benefit over traditional CSS. 
3. SCSS provides all the functionality of CSS as well as additional features not found in 
CSS, making it a good alternative for developers. 
4. Finally, SCSS is fully documented, which makes it a solid option to employ. 
Here is the sample code to get clarity on the difference between CSS and SCSS. 
CSS Code: 
 
Figure 2.3: CSS code sample
 
SCSS Code: 
 
Figure 2.4: SCSS Code Sample 
My title 20
2.3.5 Visual Studio Code 
Visual Studio code is a source-code supervisor for Windows, Linus, and macOS by Microsoft. 
Among the highlights are investigating, linguistic structure featuring, savvy code finishing, 
pieces, code refactoring, and installed Git. The topic, console alternative ways, box 
determination, and different highlights would all be able to be redone by clients. Introduce 
expansions that give new usefulness, such well as auto-space an inclination. With regards to 
genuine codding, apparatuses that see more code than simply squares of text will normally be 
useful. Visual Studio Code accompanies IntelliSense code consummation, progresses semantic 
code comprehension and route, and code refactoring. 
The steps to be followed to set up an IDE for Angular Development is as follows, 
• Install these extensions to make the job easier and more organized. 
1. Debugger for Chrome 
2. Any code formatter with reviews 
3. Angular language Service 
4. TS Lint (for typescript) 
• Download the visual code from the following URL: 
https://code.visualstudio.com/download.
• PowerShell must be opened in admin mode and install Angular CLI, using the following 
command – npm install -g @angular/cli. 
• Redirect to the folder where the Angular App must be created. In PowerShell, Navigate 
to C:/directory and ran the following command. My app is called “my-new-angular 
app,” we can title the project name as whatever we want. 
ng new my-new-angular-app 
• Change the directory to the new project created using cd command using the below 
command: C:\> cd .\my-new-angular-app\ 
• Start the server by building the app 
“ng serve” or “npm run ng serve” 
My title 21
• Navigate to https://localhost:4200 and browse, it gives the following result 
 
 
Figure 2.5: Angular Web Application Output 
• Now, In visual studio code framework, click on open folder menu and navigate to the 
desired folder 
• Package.json will be having all the dependencies of angular and all the other related 
packages. 
• Components must be added in the root level that is in App folder. 
• Hit Y and ctrl+c, to stop the running server. 
Developers can also start the server using the terminal available in the visual studio 
2.3.6 JSON 
JSON is abbreviated as JavaScript object notation that helps to exchange data. It is a fairly light 
weighted format and can be represented in different ways, they are: 
My title 22
• It would be a collection of key-value pairs. 
• It would be an order list of value. 
 
Figure 2.6: JSON Array 
 
 
Figure 2.7: JSON Values 
2.4 Hardware and Software Requirements 
A Computer is made up of two components, namely hardware and software. Hardware can be 
seen, touched, and felt; however, software is hidden inside the computer and cannot be seen. 
Typically, input is provided into the machine via hardware, while software is the component 
that performs all the calculations and displays the results on the terminal. 
2.4.1 Hardware and Software Requirements for Development 
The following specifications are required for the construction of the web application for testing 
purposes. 
My title 23
Table 2.1: Hardware Requirements for Development 
Hardware Specification 
Processor Intel or AMD 2.0 GHz or higher 
RAM 4GB or higher 
Hard Disk 20GB minimum 
Keyboard Standard Keyboard and optical Mouse 
Mouse Wired or wireless mouse or touchpad 
Table 2.2: Software Requirements for Development 
Software Specification 
Web Frameworks Angular 9 
Backend Database SQL Server 
Operating System Windows XP/2003, 7 or higher version 
Browser Google Chrome, Mozilla Firefox, Internet 
Explorer 
Programming Language Type Script 
Script language HTML and SCSS 
IDE Visual Studio Code 
My title 24
Chapter 3 
SOFTWARE REQUIREMENTS SPECIFICATION 
A Software needs specification (SRS) is a document that outlines the requirements for software. 
It also explains what the software will accomplish and how it will work. It also outlines the 
functionality that the products must have to meet the needs of all the stakeholders that includes 
the business and the users. It is primarily generated by the analyst after gathering the client’s 
requirements. A typical SRS must comprise the following: 
• A purpose 
• Specific Requirements 
• An overall description of the project 
 
3.1 Users 
Administrator 
Admin has all the rights to control the activities or processes of over website, he can control the 
processes such as order, delivery, location, save and remove options, tracking and payment etc., 
Admin can also change the settings if required. 
Customers 
The user is the sole controller of the online application. Customers are the end users of the 
application, who will be having authentication to register and login to the system, they may be 
the guest users or the registered users who will access the application to order the food. 
Scope of Objective 
Since several conditional working definitions can be used, the System’s scope is expansive, 
acknowledged and may be fine-tuned with the use of a system that is cost-effective. Any big 
firm that wants to link multiple operations at once. 
The objective of the system is to provide a food delivery service that helps the customers to 
find outstanding restaurants in their area to order the food. It offers several characteristics that 
provide an excellent dining experience for the user. This covers things like internet ordering 
My title 25
and looking up nearby dining options. Having said that, one of the application’s main features 
is the ability to order the food online. 
Assumption and Dependencies 
The system assumptions should be that users have working knowledge and should have a 
refined concept of how the system should be used, thus whether its clients or staff, they should 
be added with suitable precise working references. 
The system’s most important dependency is that all sorts of centralized working will be linked, 
necessitating corresponding authentication and login. 
3.2 Functional Requirements 
A declaration that outlines the service that the programme must deliver is known as a functional 
requirement. It refers to a piece of software or a part of one. A function is nothing more than a 
software system’s inputs, actions, and outputs. A computation, information control, business 
technique, client association, or whatever other exceptional usefulness that determines what 
function a system is likely to conduct can all be taken into account. Functional Requirements 
are also known as functional specifications. 
The preceding menu choice is available to all categories of system users: Sign In, Language 
translation dropdown, cart, my Account, eat and drink etc. 
The meal ordering system’s users will interface with it via a simple top navigation menu: 
• As and when the customer browser for the applications’ link, application is loaded on 
the home page that comprises of navigation menu links, banners at the top and footer 
at the bottom. The customer can click on the menu links on the navigation bar and go 
through all the modules or the section of the website. Some of the menu links would 
be restricted such as customer can view the dashboard only if he/she is logged into the 
application. The banners are used to bring attention to the company offers and 
products. They are immediately noticeable due to their size or colour, which attracts 
attention it acts as a first impression to the visitor. The footer provides the information 
about the Food product website and related information. 
• Sign In, if the customer wants to order the food, then he/she must get logged into the 
application. Customer can login only if registration is done, through sign in menu link
My title 26
unregistered user should register to the application. This menu link also accompanies 
OTP verification, forgot password and forgot password verification operations. 
 
The sign in menu link is also found in checkout page, if in case customer forgets to 
login or to register to the application, the system lets them to do it before they enter the 
payment phase. Customer usually logins to the application using Registered phone and 
an OTP. If in case customer does not want to manually register, then he/she can just 
click on Continue with google or continue with Facebook buttons. If they area 
registered user, they just click on sign in menu link on the home page, enters the 
registered phone number. Customer receives the OTP and enters the system. On valid 
OTP entered Customer is logged into the application. 
 
Some of the visitors of the website do not like to give the personal information like 
phone number and residential addresses to be known to the third parties, in that case 
that visitor can choose a guest login option on the checkout page and proceed with the 
transaction. 
 
OTP Verification – Once the customer enters a phone number in sign in screen and 
click on send OTP button, customer must receive the OTP and enter the same 
into the following screen in a specified time say in 30 seconds. In the stipulated 
time if the customer does not receive any OTP, customer should be able to click 
on resend OTP button and repeat the process. 
Sign Up – If the customer wants to login to the application first, he/she has to get 
registered to the application, in the sign-up screen customer will be provided 
with a form that contains various fields with the CustomerDTOs. Customer 
enters all the fields and registers to the application. They can also edit the saved 
details on My Account Dashboard. 
Forgot-password – This system does not only provide one way of logging into the 
system, but it also provides other way that is using Registered email and 
password. On valid credentials entered customer s will be authenticated if in 
case customer forgot the password by then they can click on forgot button. Later 
system will ask for the email address to be entered in the field provided on valid 
email entered the reset password is sent to the entered email address. 
My title 27
Forgot-password-verification – When the system successfully sends the Reset 
password link to the entered email address, forgot-password-verification screen 
is displayed on the screen. 
• Display the products details - The system will display the display groups, product 
layout, signature products and other products with an image and name of the product 
along with the original price, discount applied on the product and the discounted price. 
• Select food items – items are selected from the provided list along with cross sell 
products and added to the cart. Customers can directly click on the products and set the 
quantity of the products using increment and decrement buttons. Customer clicks on 
add to cart button on the screen and it get added on to the cart. 
The unique thing about this application is that, customer will not be provided with buy 
now button, if the customer adds only one product or multiple products, he must go to 
checkout screen only via a cart screen. 
• Changes to the order – Customer can change the products that are added to the cart 
using product upgrade sections where in the product selected is replaced with upsell 
product. 
• Edit the products – Customer will be able edit the selected product using product 
modifiers. This is one of coolest feature of this application, because in many of the 
application customer will not be able to edit the products in the checkout screen. 
• Customers must be able to buy more than one product from the application. He must 
also be able to track the placed orders and edit the personal information that was fed to 
the application during registration. 
• Based on the navigation of the customer from the home page to the cart page, customer 
will be provided with options in checkout page. 
• Eat and Drink – Typically, customer clicks on this link to choose the convenient delivery 
methods. The system provides two types of delivery method, one is pick up from store 
and secondly delivery option. 
Pick up from store option – This option is visible on the screen based on the 
configurations made by the admin in the master site. If the customer selects this option 
and proceeds, he will be landed on choose-your-pickup-store screen which contains 
all the locations that are set a picking up store. This screen will also be having a search 
input field, so on entering the desired address on the input field, locations will be 
filtered based on the search value. 
My title 28
Since this is an ongoing project, for now the API is replaced with a JSON file, 
so all these locations are fetched from JSON using the angular feature known as 
services and displayed in the template using string interpolation and ng-For 
directive. This option can be selected by all the types of users namely signed I 
user, non-Signed in user and guest user. The flow of navigation will be the same. 
 
The customer has all the rights to change their delivery method in the checkout 
out screen, using the change button that is adjacent to the store name label. 
 
Delivery Option – As soon as the customer lands on the home page, he has first click 
on eat and drink menu link and select the delivery method intended by the customer, 
only then he or she is navigated to the products landing screen that comprises of 
product layout, display groups, recommended products and other products. The 
options on the delivery method screen will be based on the set configurations made 
by the admin. Customer can be provided with pickup option alone, or delivery option 
alone or both pickup and delivery option. 
 
There are three different scenarios on delivery option selection, they are: 
1. Non-Signed in user using zip code – If the customer directly selects the 
delivery option without signing into the application, then they must provide 
with a sign in button along with an input field to enter the zip code. When 
the customer enters the zip code that supports delivery then customer will 
be landed on products page and can sign in later in checkout page. In case if 
the customer enters the zip code where the delivery is not available by then 
customer will again be redirected to choose-nearby-store screen, that 
provided all the addresses that are near to the customers current zip code. 
User just clicks on the location and proceed s to products landing page. 
2. Signed User – If the customer logins to the application and later clicks on 
east and drink menu link to the selection the delivery option, by then 
customer must be provided with Add address button and an input field to 
enter the zip code. This is for the logged in user who has not added any 
address for the delivery. On click of add address button, customer is 
redirected to add address screen which contains a form that included all the 
My title 29
address attributes. Customer enters all the mandatory fields and clicks on 
add address and proceed button - AddressDTO, on click customer is 
redirected back to delivery method screen with auto-populated address 
details. Adjacent to the address details edit option is also provided for the 
customer. 
 
If the customer is willing to add more than one address to the application, 
he must be having add address button on top of the added address container. 
So, whenever the customer wants to add address, he will just click on the 
button and follows the same procedure. The delivery method screen will be 
auto populated with the multiple addresses one below the other. 
 
On selecting the added address that supports delivery customer is redirected 
to products landing page, else system displays a message saying sorry, we 
do not deliver to the selected address with tow buttons namely no and yes, 
restart order. 
 
3. Signed In user using zip code. 
If the customer is signed in and selects the delivery option, again the system 
display the list of added address one below the other, it’s not mandatory for 
the customer to select the delivery address only from the added list of 
address he or she can just type a zip code on the input field provided and 
continue the shopping, by then system shows the customer only those 
products that are applicable in that zip code 
 
• Payment – Customers can choose from a variety of secure billing options, such as 
prepaying with debit card or credit card, and many other gateways. 
• Provide delivery and payment details – Bill should be generated by the system that 
should include order number, order date, products detail along with description price 
and grand total etc. 
• Checkout screen must provide reliable options to the customer, 
My title 30
Usually, the checkout screen as four steppers by name cart, sign in/sign Out, address 
and payment along with the price details section. 
There exist five different scenarios in checkout page: 
Customers select pickup option and reaches to the checkout screen without login – by 
then system must not directly give entry to the payment screen, and checkout must
contain three steppers namely cart ----- sign in/Sign Out ---payment. ✓ Customers 
logins to the system and selects the pickup option – 
▪ By then checkout screen must have the following stepper cart-----payment 
Customers logins to the system and selects the delivery option without selecting the 
delivery address - 
▪ Checkout screen must display the following floe cart---- address---- payment. 
Customers selects the delivery option and reaches to the checkout screen without login 
– by then application displays the checkout screen with cart----sign in/sign out ----
address-----payment. 
Customer logins to the application, chooses the delivery option and selects the delivery 
address – 
▪ Customer views a checkout out screen with the following cart----payment 
 
 
• Once the transaction is completed successfully, customer must be able to get the 
confirmation of their order. 
The confirmation email will be sent to the customers registered email ID. Customers 
must also be able to print the order confirmation receipt that contains the order number, 
order date, the products purchase along with the description and the price, details of 
coupons if applied, tax details discount details and the grand total of the transaction. 
The end-user can also track their order by click of a button. There are again two scenes 
in tracking their order, where the different status is shown when pick up option is 
selected and when delivery option is selected. 
Pickup option 
When pick up from store option is selected by the customer, he has to go to the 
store and pick up his order, so therefore the system displays three status steppers 
for these types of users namely, order confirmed, food is being prepared and 
Ready to pick up status. All these three status labels are connected with dots and 
My title 31
lines. As and when that status job is done grey coloured dots and lines are 
updated into green colour, that signifies the status. So, whenever he finds Ready 
to pick to up in green colour, he can just go and receive the order. In turn this 
track order element saves the time of the customer as in traditional method. That 
is customer is waiting out of the restaurant to collect the ordered food. 
Delivery option 
When the customer selects a delivery option, the order will be directly delivered 
to the provided address. So, in this case the system displays four status steppers 
namely, order confirmed, food is being prepared, food is out for delivery and 
delivered status. Same a pickup in store option, as and when the status job is 
accomplishes the steppers are updated. 
This makes sure the customer does not bother about where the order is and when 
he is going get out. The Anxiety of the customer can be kept in normal state. 
 
Logout – After the successful transaction customer can click on logout button and log 
off from the application. 
Once the customer logins to the application using the above-mentioned procedures, the 
sign in menu link on the navigation bar is replaced with the name of the logged in user 
with a dropdown icon. This menu link now become the way for the user’s dashboard. 
On expanding the dropdown icon on a click, customer would see many options such as 
order-history, addresses, track-order, and logout. On click of every option system takes 
the customer to the respective screens. On click of logout button customer will be 
logged off from the application and the menu link on the navigation bar with username 
is replaced back with sign in button. 
 
3.3 Non-Functional Requirements 
Non-functional needs are more difficult to establish, quantify, test, and track than functional 
requirements. This can lead to teams employing solely functional requirements or needing to 
constantly check for validity of non-functional needs. Non-functional references are critical to 
achieve the goals, and they must be given in such a way that the users a=can define their own 
working criteria, which might be based on referential security, scalability, reliability, usability, 
responsiveness and so on. 
My title 32
Security 
This component of internet ordering is frequently forgotten, yet it is a valuable resource to have. 
Allowing customers to remember their information, such as delivery and billing addresses, 
credit card information, and the opportunity to highlight preferred items, makes ordering from 
the customer easier. 
With this aspect customers will be motivated to order more frequently because they will no 
longer have to re0enter their information. Making customer information private and encrypted 
protects our customers’ information from identity thieves and hackers attempting to take 
advantages of restaurant customer information databases often inadequate security. Overall, it 
is safe. 
 
Performance 
Since the application uses encoders to encode all the information that are passes between the 
client as the server, performance become an important asset. Food hut is the web application is 
being developed using Angular Framework which gives the best performance. Since the 
programming language used by the angular is sometimes clients side rendering heavy burden 
is not overloaded on server so that the application runs in any decent internet connection. 
Although when we are designing mission-critical online application, apps that are content heavy 
and architecturally complicated, unanticipated issues may arise. And these problems can be 
easily fixed with some of the angular optimization techniques such as 
Using On Push Change detection strategy 
Usage of pure pipes 
AOT (Ahead of Time) Compilation 
Lazy loading and preloading the modules etc. 
Responsiveness 
Over 70% of the users use a tablet, iPhones, smart phones, or other mobile devices to access 
the internet. Since, it is online ordering system, both must be mobile-friendly and properly 
tested using numerous mobile browsers version and devices. To Accomplish the responsiveness 
in the Food hut website we have used the technologies of Style sheets namely, media queries 
and flexboxes. 
My title 33
There exist various kinds of mobile with various pixels, screen widths, screen heights, view 
ports etc., to match to all the devices we have used a standard media query that includes the 
following: 
 
 Figure 3.1: Standard Media Queries 
The above media queries support both portrait and landscape. First three of those are for mobile 
devices and last two of those are for tablet devices. 
 
Availability 
The user must be able to use the web application anywhere anytime under only one constraint 
that the device must have a decent or minimal internet connection. The application mist be able 
to maintain a consistent degree of availability under normal operating volumes and 
concurrency, with no decrease in application performance over a period between scheduled 
application restarts. Between scheduled application restarts, the application’s CPU and Memory 
utilization must not be declined these are some of the availability attributes to be considered. 
There Exists many such Non-Functional Requirements, such a Reliability, Usability, 
Maintainability, operability, scalability and so on. 
 
 
 
 
My title 34
Chapter 4 
SYSTEM DESIGN 
 
A System design is the way towards characterizing framework attributes including modules, 
structures, parts and their interfaces, and information for a framework dependent on 
characterized necessities. It is the way toward distinguishing, creating, and planning 
frameworks to meet the particular points and assumptions for a company or association. 
A well-functioning and coherent system require a systemic approach. A bottom-up or top-down 
strategy is necessary to take into account all of the system’s related factors. Modelling
languages are used by designers to express information and knowledge in a system structure 
that is based on a set of consistent rules and definitions. 
It is one of the primary designs in which primary method of dealing with an addressing the 
problem is chosen. The most important priority is to carefully design the system while keeping 
all the factors in mind. In the later stages of design, more distinctive features are pushes in, and 
more and more new things come in and out of production. Newer features are included in the 
stages of design. 
The designer who designs the system divides the system into several subsystem, which makes 
it easier for development, by settling on abnormal condition is applied to the full system and it 
is settled in the abnormal condition. Some of the examples if graphical languages are, 
Flowchart, Unified Modelling Language, System Modelling language, and Business Process 
Modelling Notation are some of the well-known examples of the graphical languages. 
4.1 System Perspective 
From the standpoint of the system, the v=developer has viewed the design as a replacement 
piece of software; no one is allowed to divide the structure into distinct pieces. Alternatively, it 
may be decided to downgrade the system, after all factors have been considered. 
What if the parcel is used a s component of the system attributed in various parts? This is merely 
a bit of an aggregate portrayal of the lead in the entire system, which may be unpleasant when 
it is included in the sub system. Therefore, it must provide a definition of the relationships 
between these pieces, as we as any extra information that will be contributed or that is expected 
to reflect the overall structures direct. 
My title 35
Figure 4.1: Architecture of Proposed Framework
Furthermore, when it comes to system design, one must be very careful to examine the new 
scope and architecture, as there are various interconnections between the system a sub system. 
4.2 Context Diagram 
The context diagram shows the system in issue as a single high-level process, followed by its 
connections to various external entities like system, organizational groupings, and external data 
repositories. It also helps the analyst and the stakeholders to understand the context of the 
system which is been designed without the need of technical knowledge. 
Context diagrams are also known as context-level data-floe diagrams or data flow diagram4.2.1 Level 0 – Data Flow diagram 
An information stream outline is a graphical portrayal of how information travels through a 
data framework. DFDs are one of three parts utilized in the organized frameworks 
investigations and configuration measure. Processes (circle), Data storage (ellipses or parallel 
My title 36
lines), External entities (rectangle), and Data flows are the four basic components depicted in 
a DFD – straight or curved lines with arrowhead indicating the flow direction. 
 
Figure 4.2: Level 0 - DFD for Online FNB 
The system’s input and output are displayed at this level. With input and output at this level, 
the system is designed and established all over the world. Food order is an input as the primary 
job of customer is to order the food and output from the system would be, Receipt of the order, 
to process the order the order is passed to the respective restaurant’s kitchen and finally the 
managers of the restaurant manager get the report of bill and management. 
4.2.2 Level 1 – Data Flow Diagram 
This Level of graphical framework displays the broader component of the data framework’s 
primary requirements. They are primarily employed as part of the system’s progress. For 
current materials, a data stream plot is occasionally the diagram of choice. 
My title 37
 
Figure 4.3: Level 1 DFD for Online FNB 
The above diagram depicts all information that passes in and out between the client and the 
server on processing activities. The entire dialogue is treated as a single procedure. The 
information streams pass between the framework and the external elements. 
 
My title 38
4.2.3 Level 2 Data flow diagram 
Level 2 DFD provides the detailed information about the order processing 
 
Figure 4.4: Level 2 DFD for Online FNB 
 
 
 
 
 
 
 
 
 
 
My title 39
Chapter 5 
DETAILED DESIGN 
Design is a specification of all key components of the systems’ internal parts, including their 
attributes, relationships, processing, and, in some cases, algorithms and data structures. 
The intricate design must incorporate the following elements: 
• Major system components are broken down into program units. 
• Units re assigned functional duties. 
• Interaction of data and control between units. 
• Interactions with users. 
• State changes and unit states 
• Data packaging and deployment, as well as program scope and visibility difficulties. 
• Lastly, Data structures and algorithms. 
 
Figure 5.1: Detailed Design of Online FNB 
The above diagram explains the micro apps and their interaction with the libraries. There are 
application specific libraries and reusable libraries across web platform. 
My title 40
5.1 Use Case Diagram 
Use case charts are utilized to gather a framework’s necessities, including interior and outside 
components. A significant number of these determinations are identified with the plan of the 
item. At the point when a framework is explored to assemble its usefulness, use cases are 
created and entertainers are distinguished. It is also the most common kind of system 
requirement for new software under development, and they explain the application’s intended 
behaviour. It is usually straightforward and does not delve too far into the design or structure. 
• Use cases – A use case defines how to obtain information and the requirements for a 
series of exercises that provide an entertainer with a motivational factor. 
 
• Actors – A performer, also known as a user, is a man, organization, or external system 
that accepts a section in at least one relationship with the defined structure. 
 
• Associations – Associations are the group of people who work as craftsmen and use 
cases with solid lines. When an entertainer is merged with a participation identified by 
a use case diagram, there is a relationship. 
My title 41
5.1.1 Users Use case Diagram 
The below Figure 5.2 demonstrates the use case chart of the users. Users are landed on the 
home page, where they can get idea of models and algorithms utilized in the Online FNB 
website. 
Figure 5.2: Use case diagram for Online FNB 
Since the project is in development phase for now, we have only two users namely customers 
and admin once the functionality of these modules is completely achieved, the system will be 
enhanced with the third user that is the restaurant employee (owner or a manager). In the 
proposed system customer and admins will be having access to the above-mentioned entities. 
My title 42
5.2 Sequence Diagram 
UML sequence outlines, for instance, show how tasks are performed. In a community- oriented 
circumstances, they catch the cooperation between objects. Grouping Diagrams are time
centred and outwardly portray the request for a connection by addressing time and messages 
sent and got on the upward pivot of the outline. 
5.2.1 Sign In – Sequence Diagram 
The Figure 5.3 illustrates the sequence diagram for Login Screen: 
 
Figure 5.3 login page Sequence Diagram 
The Customer browses the website, and an application is landed on the home page, customer 
clicks on eat and drink menu link to select the delivery method, on the process customer is 
redirected to sign screen, as shown in the above diagram. 
5.2.2 Choose Your Delivery Method Screen 
The customer clicks on eat and drink menu link on the home page, the screen is displayed to 
the user with the options that are configured by the admin in the master site. The options may
be pickup in store alone or delivery option alone or both the options that includes pickup and 
delivery options. The same flow is depicted in the below diagram from menu to landing page 
to the delivery method pop up over the landing page. 
My title 43
 Figure 5.4 Choose your delivery pop-up 
5.2.3 Pickup in store and On Delivery – Sequence Diagrams 
My title 44
Figure 5.5 Pickup in store 
Figure 5.6 On Delivery 
Figure 5.5 and 5.6 depicts the sequence of flow when the customer selects pickup in store and 
delivery as a delivery option. 
5.2.4 Add an Address pop-up 
The below figures depict the flow of add an address popup from delivery method screen. 
 
Figure 5.7: Add an address pop-up Sequence diagram. 
My title 45
Chapter 6 
IMPLEMENTATION 
Here is where all the implementation details are stacked in, similar to bringing it all together 
after a lot of training, analysis, and research. This is the most exciting phase because we get to 
see all the hard work that has gone into it. We will actually visualize and test out all of the 
requirements that were mentioned earlier while the specification that was written meets the 
requirements or not. 
6.1 Screenshots 
Below are the screens of Online Fnb – Food hut project, that provides a good overview of the 
complete system. 
6.1.1 Home page 
Figure 6.1: Home page 
The Above screen is where the customer lands on when the application is browsed. It contains 
the navigation menu bar with menu links to navigate to other sections and a banner which will 
see in different information in the future. 
My title 46
6.1.2 Sign In pop-up 
Figure 6.2: Sign In pop-up 
Figure 6.3: OTP verification pop-up 
Customer lands on the landing page and clicks on the sign in menu link on the navigation bar, 
by then system displays a pop-up as shown in the above image. Visitors can sign in using the 
registered phone number. If the visitor is an unregistered user, he can register himself using by 
using the sign-up option provided, Or, he/she can register directly on click of continue with 
google or continue with Facebook buttons. 
My title 47
6.1.3 Choose your pickup location pop-up 
Figure 6.4: Choose you pick up store pop-up. 
 
Once the customer logins to the application and selects the pickup in store as preferred delivery 
method, then system displays the above screen. The locations here are fetched from the JSON 
file. The search input field is provided for the customer, based on the search value locations get 
filtered. 
 
My title 48
6.1.4 pickup-from-nearby-store 
Figure 6.5: pickup-from-nearby-store pop-up. 
When the customer selects the delivery option and selects the address where the delivery is not 
available, by then customer is provided with the above screen to select one of the addresses, on 
click of the locations in this screen customer will be automatically redirected to products 
landing page. 
If the customer is not willing to select any of the address provided, they can simply click on try 
another address button, and add another address in the delivery method screen with delivery 
option auto selected. 
My title 49
Figure 6.6: Cart screen 
All the products selected by the customer to buy are added into then cart, on expansion of the 
cart the following screen is displayed. The customer can expand and contract the products 
container. 
6.1.7 Product search layout 
Figure 6.7: Product search layout 
The customer can search for the desired products, foods, restaurants and the cuisines, in the 
search input field provided. based on the search input value the products are filtered. 
Customer will also be able to view the delivery method option that have selected previously 
as mode of delivery. If in case the customer would like to change, he can change by clicking 
on the dropdown. 
My title 50
6.1.8 Order Confirmation and track order screens 
Figure 6.8 Order confirmation screen 
My title 51
Chapter 7 
SOFTWARE TESTING 
Software testing is a procedure for surveying a product application’s working fully intent on 
recognizing whether the created programming meets the characterized prerequisites and 
distinguishing blunders to offer a great outcome. It is significant in light of the fact that it 
permits any shortcomings or blemishes in the product to be found early the fixed before the 
product items is conveyed. An all-around tried programming item gives constancy, security, 
and great execution, which sets aside cash, time, and further develops the consumer loyalty. 
Testing of software is usually divided as follows: 
• Functional Testing 
• Performance testing (Non-Functional Testing) 
• Regression testing (Maintenance testing) 
 
All aspects will be checked for quality references since we want the system, to be of good 
quality and operate exactly as it was meant for domestic use. Software testing will assist us in 
accommodating various work processes on a single references system, and we must ensure that 
the working should be properly done in various circumstances. Because various channels are 
used in the system, the realization of software testing is significant reference. Each channel 
must be examined correctly for Merchandize working. We are also consolidating many sorts of 
automated references, where the system should automatically refine the compliances that will 
develop, as well as all forms of criteria that must be met in term of regulations. 
Apart from the above-mentioned Testing areas there also exist User interface testing which is 
the basic level of testing once the website is developed without functionalities. 
 
 
 
My title 52
7.1 Types of Testing 
7.1.1 User Interface Testing 
User Interface testing is a testing approach that uses a graphical user interface (GUI) to 
determine the presence of faults in a product or program under test. User Interface testing is 
one of the significant factors of testing the software process. Quality and Assurance personnel 
should test all interface components to ensure that programmer have the intended functions and 
are user-friendly. This does not improve only the software’s quality, but it also assures that 
targeted customers are at ease when using it. Shadings, textual styles, menus, radio catches, text 
boxes, checkboxes, toolbars, and that is just the beginning of testing the UI. 
GUI Testing Checklist must include the following: 
• Verify the object states. 
• Check screens validations. 
• Verify all navigations. 
• Verify data integrity. 
• To Verify the formats of date fields. 
• Verify the numeric field formats. 
 
7.1.2 Cross Browser Testing 
Cross Browser testing - is one sort of non-functional testing that allows us to see if the 
developed website functions as expected when viewed using the following browsers: 
• Different browser-OS combinations, such as on common browsers such as Chrome, 
Firefox, Chrome, Edge, and safari – on any of the main operating systems such a 
Windows, macOS, iOS, and Android. 
• Assistive tools, that is, the website is accessible to people with disabilities using 
assistive technologies such as screen readers. 
• Various gadgets Users may access and interact with the website on a variety of devices, 
including smartphones, tablets desktops and laptops, among others. 
Browser testing comprises many components, many of which are self-explanatory. 
Understanding the numerous elements can have massive impact on an online application and 
My title 53
boost client happiness but disregarding their significance can harm the reputation and bottomline goals. 
7.1.3 Unit Testing 
A unit testing is a method of been testing a unit or the individual module of the web application, 
which is the smallest amount of code in a system that can be logically separated. That is a 
function, a subroutine, a method, or a property is most programming languages. It is crucial to 
focus on the solitary component of the term. Working with unit testing on any project that at 
least ties to be serious is a requirement whether we employ a test-driven development 
methodology or not, we will real many benefits from doing so. 
Angular uses jasmine and karma configurations within the project for unit testing purpose. The 
benefits of Unit testing are as follows: 
• It improves the design of implementation: 
A common mistake made by developers is to begin coding feature without first 
considering the design. Using nit testing forces us to think about and think the design. 
• Add new Features without breaking anything: 
You can use the tests to check that we do not break anything else in the program when 
we ass a new feature. 
• Allows refactoring. 
Because we already have tests in place to guarantee that everything is operating as it
should, we can make modifications to the code with confidence that we will not 
introduce any errors. 
• Test make developers more confident about their work. 
• Tests are good documentation. 
7.2 Test Cases 
Here are some of the test cases of user interface testing: 
The following are the sample test cases that was carried out: 
1. All the fields that are mandatory should be marked with asterisk - 
My title 54
In the event that a field on the screen requires information passage, it is a smart thought 
to feature the necessary fields with red nark and give an agreeable admonition if the 
information is left clear. 
2. Loaders – 
On the off chance that the outcomes take longer than 5 seconds to show up on the screen, 
a loader to progress bar ought to be given so the client knows that the activity is as yet 
in progress. 
3. Keep Onscreen Instruction Short – 
While onscreen instruction is important, keep the test useful yet succinct. 
4. Widths of the fields – 
In the event that the screen contains text boxes for information section, ensure the width 
of the information entered does not surpass the table field’s width. For instance, an item 
title with an information base restriction of 180 characters ought not permit in excess 
number of characters on the UI to be entered. 
5. Errors that may occur on the types of data – 
Guarantee that possibly real information can be entered if the screen If the screen 
contains dates, numbers, monetary forms, or other explicit information types. entered. 6.
Abbreviations Inconsistencies – 
The screens contain ambiversions for example Tx for tax, GST, and for amount - amt 
etc., They ought to be uniform across all screens in the application, which is the place 
where the style guide proves to be useful. 
7. Confirmations should be provided to the customer before deletion – 
If someone deletes something., it is better to double check the deletion. Nevertheless, it 
the user interface allows users to delete multiple records in a row, we might consider 
enabling users to disregard the confirmation in some circumstances, as clicking the 
confirmation over and over can be tedious. 
8. Save the confirmations – 
If the screen allows us to change the data without saving it, it should remind the user to 
save when user navigate to another record or screen. 
My title 55
Chapter 8 
CONCLUSION 
The Food hut is an online sale application, that enables the users to comfortably order their food 
from home, anywhere at any time. Customers, restaurant partners, and delivery partners are all 
connected through this technological platform, which serve their various demands. Customers 
use Food hut platform to find and order the food for delivery as well as for pickup, read and 
write customer reviews, see the uploaded images, and pay their meals when dining out. On the 
other hand, it equips the restaurant partners with industry-specific marketing tools that enabled 
them to interact and gai customers in order to develop their business while simultaneously 
offering a dependable and effective last-mile delivery service. 
Food hut services is very much helpful for the people who are leading the busy lifestyle, since 
it is an online service, it makes it possible during anytime, No confusions on the menu items, it 
will be simple and straightforward for the customer to select their products, it allows the 
customers to order more than one product at a time, customer can use coupons on the payment, 
it also gives the customer an option track the placed order and it allows them to add the cooking 
instructions to the customer. Towards the business perspective too their maintenance becomes 
easy, and they save other expenses. 
My title 56
Chapter 9 
FUTURE ENHANCEMENTS 
 
Future enhancements considerations are critical because we must acknowledge that the system 
is not perfect. Since it is based on service, and all forms of consolations are possible when 
system is based on the service. In new references are needed, they must be provided. The users 
will be audited, and new users will be added. There will be more requirements added. Some of 
the enhancements that can be made in future are: 
• For now, only the restaurant owners are the third-party user of the application, in future 
we can also include the home makers who cook delicious - On the order placed by the 
customer to a particular food they can take time to cook and send it to the customer. 
• Th existing systems does not take in orders in bulk, we must access different websites 
for that, so it will be efficient if the system accepts simple and the bulk orders. 
• Websites can be improved based on the feedbacks provided by the customers and third 
parties. 
• As any other e-commerce website, this system can also contain the gift section, so that 
a person can surprisingly order the food to other person. 
My title 57
REFERENCES 
• www.wikipedia.org
• Google images 
• www.w3schools.com 
• w3schools.com/angular 
books referred: -
• Html and CSS: Design and build website by Jon Ducket 
• Angular Up and running by Tom Reilly
