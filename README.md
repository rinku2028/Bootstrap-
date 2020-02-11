# Bootstrap-

Bootstrap is a framework to help you design websites faster and easier. It includes HTML and CSS based design templates for typography, forms, buttons, tables, navigation, modals, image carousels, etc. It also gives you support for JavaScript plugins.



Why Use Bootstrap?
Advantages of Bootstrap:

Easy to use: Anybody with just basic knowledge of HTML and CSS can start using Bootstrap
Responsive features: Bootstrap's responsive CSS adjusts to phones, tablets, and desktops
Mobile-first approach: In Bootstrap, mobile-first styles are part of the core framework
Browser compatibility: Bootstrap 4 is compatible with all modern browsers (Chrome, Firefox, Internet Explorer 10+, Edge, Safari, and Opera)
Here’s what you need to know:

1.      First of all, Bootstrap is the most popular framework for creating layouts. Here are some additional reasons to use Bootstrap:

Bootstrap's responsive CSS adjusts to phones, tablets, and desktops
Mobile-first styles are part of the framework
Bootstrap is compatible with all modern browsers (Chrome, Firefox, Internet Explorer, Safari, and Opera)
The Challenges of Cloud Integration

Download
Preparing for the Internet of Things: What You Need to Know

Download
2. Bootstrap has a big community and friendly support. For resources visit:

Check out the Bootstrap Blog.
You can chat with Bootstrappers with IRC in the irc.freenode.net server, in the ##bootstrap channel.
Have a look at what people are doing with Bootstrap at the Bootstrap Expo.
3. Bootstrap is easy to set up and create a working layout in less than an hour

They have a basic template available at http://getbootstrap.com/getting-started/#template and also a set of examples for different needs (http://getbootstrap.com/getting-started/#examples). You can just download the bootstrap repository, go to docs/examples folder, copy/paste the example you need and work on it.

4. You don't need to know HTML and CSS well to use bootstrap, it's a plus if you're a backend developer and need to do some UI changes.

5. It's fully customizable, I can choose which components I'd like to use and use variables file to get do even more color and behavior customization.

All you need to do is visit http://getbootstrap.com/customize/ , choose the plugins you need and click download. Bootstrap also provides a way to override its internal variables for advanced users, but they provide pretty decent defaults, so you shouldn't worry about this unless you need to.

6. When you update the version of Bootstrap, you won't see tons of errors because their core team cares about backwards compatibility.

7. Their documentation is great! Here are some resources to check out:

Bootstrap 3 Tutorial
Code Academy: Bootstrap
Web Design Tutorials: Bootstrap
8. Bootstrap offers a lot of helper classes that make development of a responsive website easy and fast.

You can turn any fixed-width layout into a fluid one by simply changing your parent .container class to .container-fluid.

Bootstrap also has .visible-*-* classes to help you control the way your sections are displayed on tablets and mobile devices. Example:

<div class="visible-xs-block visible-sm-block"></div>

In this case, the div will be displayed as a section with display: block only on phones and tablets. It will be hidden on desktop.

9. Bootstrap’s components are well-adopted to the ecosystem of popular JS MVC Frameworks like Angular. Bootstrap provides several ways to include it into your project:

Using bower:

bower install bootstrap

Using npm:

npm install bootstrap

And just simply adding a script tag with the url to bootstrap source on CDN.

We also have ui-bootstrap for Angular.js and react-bootstrap for React. You can also install them via Bower and npm. And then, for example, to create a collapse element, you just need to create similar markup:

<div uib-collapse="isCollapsed">

<div class="well well-lg">

Content of the collapse

</div>

</div>

Instead of doing a lot of jquery configuration like you would normally.

10. Bootstrap resolves a lot of cross-browser issues and you don't need to worry about that most of the time.

Note: Bootstrap is designed to work with latest desktop and mobile browsers. This means that displays might be different in older browsers and might render differently, though according to the documentation, the displays should be fully functional.
