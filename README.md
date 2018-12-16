# TG-Pre-Work

## When we hit https://www.techtonicgroup.com/ what happens? Don’t focus too much on architecture (Monolithic, SOA, Microservices, etc.). Try to focus more on how the web functions.

The (HTTP) request is sent to the web server for that page and the web server sends the code back to the client.

## From start to finish how does that data reach you to be rendered in the browser?

A request is first sent to the DNS (name server) to determine the IP address of the domain, then a connection is made from there to the domain web server with a HTTP request to load the page and page contents. The web server then serves the necessary code via packets through the internet (from the server to client – client being the end user’s web browser). The client-side web browser then interprets the html, css and JS code and renders in the browser. 

## What code is rendered in the browser?

HTML, CSS, and Javascript 

## What is the server-side code’s main function?

The web server listens or waits for client requests (GET, POST, DELETE, etc), processes them and then sends the necessary resources(html, css, js, images, files, etc) along with messages to the client to make sure that the whole process was completed (with a http 200 code meaning success). For dynamic websites, the server can send various data based on the user. For instance, the website Reddit has “sub reddits” which are unique pages. The site has unique users with names and profiles, containing data. The web server will also communicate with a database for storing data (such as comments, posts, likes, which belong to the users). The code on the server is necessary for making dynamic websites possible. The web server (using server side code) combines the data from the database, file directories, APIs, etc, and the HTML, CSS and JS to render a unique page or data for the client. Also the server doesn’t run on HTML and CSS but can run on Javascript (NodeJS runtime environment) or PHP, Ruby, C# etc.

## What is the client-side code’s main function?

The client side code is primarily responsible for making the page look nice readable by humans and for the behavior of the web page. The client side code is responsible for styling (css), content (html) and behavior (JS). In summary the difference between server side and client side code is the client-side code is responsible for determining what code is rendered to the client and validating data and requests, where client-side code is more responsible for the content itself and how it looks and or behaves.

## How many instances of the client-side assets (HTML, CSS, JS, Images, etc.) are created?

As many as the code says to!

## How many instances of the server-side code are available at any given time?

It depends on the infrastructure, the number of users, the number of requests at any given time, the memory of the server and its ability to handle the traffic. But generally multiple instances are available to multiple users.

## What is runtime?

Runtime is generally the library framework or platform that your code runs on. Not to be confused with compile time, which is how long it takes for the code to finish running. Runtime environment in your browser is what allows the Javascript to run, on the server side NodeJS runtime environment is the runtime which allows the Javasript to run on the server-side.

## How many instances of the the databases connected to the server application are created?

When a POST request is made to add an item or items to a database, the database is then updated with that data. The web app then dynamically uses the data from the database and renders the appropriate code combined with the database data.
