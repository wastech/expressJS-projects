# What is Express?
[Express](https://expressjs.com/) is a relatively small framework that sits on top of Node.js’s web server func-
tionality to simplify its API s and add helpful new features. It makes it easier to orga-
nize your application’s functionality with middleware and routing; it adds helpful
utilities to Node.js’s HTTP objects; it facilitates the rendering of dynamic HTML views;
it defines an easily implemented extensibility standard. This book explores those fea-
tures in a lot more depth, so all of that lingo will be demystified soon.

<p>If you have written any serious apps using only the core Node.js modules, you most likely found yourself
reinventing the wheel by constantly writing the same code for similar tasks, such as: </p>

- Parsing HTTP request bodies
- Parsing cookies
- Managing sessions
- Organizing routes with a chain of if conditions based on URL paths and HTTP methods of the
requests
- Determining proper response headers based on data types
- Handling errors
- Extracting URL parameter (e.g., /messages/3233)
<br>
 <p>  Later, you might have created your own libraries to reuse the code, but your libraries would not be as thoroughly
tested as the best community supported libraries. Also, the maintenance would be fully on you and your team. So, my
recommendation is to use the community module if it suites your needs. This advice applies to using small libraries
and web frameworks as well.</p>
<p>
[Express](https://expressjs.com/) solves these and many other problems. It provides ways to reuse code elegantly and provides a
model-view-controller (MVC)-like structure for your web apps. The model (M) part needs to be supplied by an
additional database-driver library (e.g., [Mongoose](https://mongoosejs.com/). Those apps could vary from barebones, back-end-only
REST APIs to full-blown, full-stack, real-time web apps with additional libraries such as [jade-browser](https://npmjs.org/package/jade-browser) and [socket.io](http://socket.io).
