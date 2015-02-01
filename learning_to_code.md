##Intro
So I am hiring again for my venture 100x(the name is crap, I know. Its a working title). Web developers are in high demand, the higher the level the higher the demand.

//If you ever read the rough draft of my book, [Ship Or Get Off The Pot](), you can

I have had great success taking young untested but highly motivated and intellegent people with very little if any training in web development and have trained them up to become profeccient junior developers in a very short time. This isn't to say that eventually they couldn't become senior developers or even reach a web app architect level, that just takes alot more time and expiremnce.




This post is intended to guid a user from zero coding but a fundemental knowladge of how to turn on a computer, browse the internet and use a text editor to basic professicency in the MEAN stack.

###The M.E.A.N. stack:
The MEAN Stack is a combination of web languages and frameworks both serverside and browser side that, when put together, allow developers to rapidly build and scale the web applications you use everyday.


####[Mongo Database](http://www.mongodb.org/):
A NoSQL or non relational database. The syntax for interacting with MongoDB is similar to JavaScript.

####[ExpressJS](http://expressjs.com/):
Express is a web server framework that runs on NodeJS. Its a highly customizable serverside(sometimes referd to as "Backend" framework.

####[Angular JS](https://angularjs.org/):
Angular is a browser side or "frontend" framework for building interactive applications that have advanced functionality that runs in the browser.

####[Node JS](http://nodejs.org/):
NodeJS is an extreamly flexable 


_This is kind of redundant being as you need NodeJS to run express but I guess 'M.E.A. stack' does not have the same ring to it_

###100x:




###About this guide:


--More important to index than memorize

--Importance of cross-functional skills
----No silos - SOGOTP

###Why I started with HTML:
Though a lot of what I will guide you twards is JavaScript based I started with HTML. T
he reason is because most of you are familar with web pages.
 Web pages are built with HTML then made interactive with JavaScript.
 Some of the concepts in programming are highly intangable and difficult to explain.
 Starting with HTML should give you a good frame of reference to start out with.




###Step 1:

Open a text editor on your computer. You can use the default but I recomend one of the following:

* Notepad++
* Sublime

On your desktop create a file called **index.html**

Copy and paste the following into **index.html**

```
<html>
    <head>
        <title>My test web app</title>

    </head>
    <body>
        <h1>Hello World</h1>
    </body>
</html>
```

Save the file then open the file in your browser of choice.

_I strongly recomend [Chrome](http://www.google.com/chrome/)_

####What is HTML:
A long time ago when the internet was first starting out and no one ever dreamed we would have fancy realtime updating applications like Facebook, Youtube, and Twitter developers just wanted a way to create an share documents through the browser.

They took an existing language [XML or EXtensible Markup Language](http://www.w3schools.com/xml/
) and created a specilized version of it to run in these new things called browsers. That specialized form of XML was [HTML or Hypertext Markup Language](http://www.w3schools.com/html/).

#####XML:
XML is meirly a syntax. Computers are not incredibly smart so you have to give it very specific directions.

I would NOT bother to go through the tutorials on W3 but I would make it a point to understand how XML works.



#####HTML:

There is acuatlly a pretty good graphic of how HTML is pretty much laid out from a programatical standpoint later on in the [Document Object Model Section](http://www.w3schools.com/js/js_htmldom.asp)


The DOM - A living breathing thing
HTML is just a blueprint


####Notes on "paths":

Say for example you are editing the following web page: `http://mywebsite.com/dir1/dir2/page.html`

`<img src="image.jpg">` Would open `http://mywebsite.com/dir1/dir2/page.html`

`<img src="/image.jpg">` Would open `http://mywebsite.com/page.html`

`<img src="/dir3/image.jpg">` Would open `http://mywebsite.com/dir3/page.html`

`<img src="http://otherwebiste.com/image.jpg">` Would open `http://otherwebiste.com/image.jpg`

Now assuming you are on an https `<img src="//otherwebiste.com/image.jpg">` Would open `https//otherwebiste.com/image.jpg` . It will look at the protocol that the currently loaded web page is on and use that.



###Step 2:
Since I am not going to even try and compete with the sheer amount of free tutorials on the web and I often use the exact same tutorials as a reference as I build my projects I will now refer you to a series of web tutorials.

####Warning:
You might be tempted to get side tracked learning everything these tutorials recomend, that is fine and all but remember I crafted this list to get you to a specific destination, those sites may not have the same destination in mind.


I suggest you start by familarizing your self(NOT MEMORIZING) the [W3 Schools](http://www.w3schools.com/html/]


Stop when you hit the section on **HTML Tables** and return to guide for the next steps, Any thing past that is not essential to moving tward the goal of this guide so skip it for now but feel free to come back and study later.

###Step 3:
HTML by nature does not have much brains behind it, its purpus is primarily to look display information in a pretty way.
Originally HTML was not really intended to perform logical calculations or be interactive beyond linking to other pages.
Modern HTML/HTML5 has a little but is still limited.

This is where JavaScript comes into play. Javascript allows you to create interactive websites

Check out the [W3Schools JavaScript](http://www.w3schools.com/js/default.asp)

####JavaScript Fundementals:
There are a couple of interesting things that make JavaScript as a language unique. Other languages typically don't have the following things so make sure you understand these principals.

#####Scope/Closures:
[Scope](http://www.w3schools.com/js/js_scope.asp)
[Closures](http://www.w3schools.com/js/js_function_closures.asp)
#####Non-Blocking/Async:


####JavaScript in the browser:
Once you are familar with Javascript fundementials

[Javascript and the Browser's DOM](http://www.w3schools.com/js/js_htmldom.asp)


###Step 4:
The next step is to get familar with one of the tools that can be used to make development easier.
So far in this guide you have been working with basic js.
Almost every major web application uses these **Frameworks** to make development easier.
Each framework does something different. The first framework I will show you is Twitter Bootstrap

####Bootstrap:
As a hardcore hacker type Bootstrap is far from the coolest framework I use on the frontend, Angular is much cooler.
But because of its graphic nature and their for easier to wrap your head around.

Bootstrap was developed to make building **Responsive** Web Pages. This means a page that will easily resize and fit in smaller browsers like mobile and tablets.
It is primarily a graphical framework though it does have some functional additions and new components that are not available in basic HTML.


Their getting started page is overly complex. To keep from getting overwhelmed I would follow these steps:

* Start with by  [http://getbootstrap.com/getting-started/#download](Downloading Bootstrap).
* Then set up a [Basic Template](http://getbootstrap.com/getting-started/#template)
* Then skip ahead to the [Css Section](http://getbootstrap.com/css) and work your way forward through the [Css Section](http://getbootstrap.com/css), [Components](http://getbootstrap.com/components/), and the [JavaScript](http://getbootstrap.com/javascript/) sections in a linear fashion



###Step 5:
Now it is time to learn a bad ass framework, AngularJS. Angualr is a next generation browswer based framework for building really interactive web applications.
It is quite powerful.

I suggest you start by following the free tutorial on [The Angular homepage](http://campus.codeschool.com/courses/shaping-up-with-angular-js/level/1/section/2/our-first-controller).



####Basic app setup

####Modules

####HTML binding

####Directives

####Controllers

####Save services for last

####http resources

###Step 8:
Enter [NodeJS](http://nodejs.org/):

NodeJS allows you to write non-browser based applications in JavaScript. What kind of applications:

* Simple command line scripts
* Server Side Web Applications
* [Desktop Apps](https://nodesource.com/blog/node-desktop-applications)
* [Hardware](http://sbstjn.github.io/noduino/)

####Quick Exercize:

Start by clicking the install link on the  site

Got through the install procedure then create a file called `node_cli_test.js` on your desktop.

Copy and paste the following code on to your desktop:

```
var fs = require('fs');
console.log("About to create a file");
var file_loc = __dirname + '/node_test_file.txt';
fs.writeFileSync(file_loc, 'This is a test');
console.log("Successfully created a new file:", file_loc);
```

Open up your terminal and navigate to your desktop then type the following:

```
node ./node_cli_test.js
```

This should exicute the code and create a file on your desk top.




####Using NPM:
NPM stands for **Node Package Manager**.
A "Package" is like an angular module. Its library of code to help you complete a task.
All of the 3rd party packages for NodeJS are managed on [https://www.npmjs.com/](https://www.npmjs.com/).

You will need to know how to install various packages using NPM. It is pretty simple, just type ` npm install package_name`.
For example:

`npm install underscore`

####Tutorials:
I don't have a lot of tutorials on NodeJS that I recomend but if you want to play around check out [http://nodeschool.io/#workshoppers](http://nodeschool.io/#workshoppers)


###Step 9:
[Express JS](http://expressjs.com/) is a framework for quickly building Sever Side Web Applications using node:

Start out by [Installing](http://expressjs.com/starter/installing.html) express and continuing through their Getting Started and Guide section.

Their guide section is fairly robust starting with [Routing](http://expressjs.com/guide/routing.html) and [Using Middleware](http://expressjs.com/guide/using-middleware.html) and going through advanced topics.

#####Common Middleware:
Check out the common [3rd party middleware](http://expressjs.com/resources/middleware.html)

Not included in this list but vital is [Passport JS](http://passportjs.org/)


###Step 10:
Saving Data with [MongoDB](http://www.mongodb.org/).
Start by going over the [in browser demo for mongo](http://try.mongodb.org/?_ga=1.263434828.1335229757.1422827841).

Once you feel comfortable you will want to [install MongoDB locally](https://www.mongodb.org/downloads?_ga=1.260764237.1335229757.1422827841) and play around locally.

Finally start playing around with [Mongoose.js](http://mongoosejs.com/), the NodeJS package that we will use to talk to the MongoDB Database.

-

##Advnaced Topics:
###Hosting/Infrastructure:



###Mobile:

####Ionic/Cordova:


###Your IDE- Your weapons of choice


####My setup:
Ubuntu with a 9 workspace setup
