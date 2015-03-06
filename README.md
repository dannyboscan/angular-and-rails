# angular-and-rails

## AngularJS Tutorial: Learn to Build Modern Web Apps with Angular and Rails
you can found this tutorial [here](https://thinkster.io/angular-rails/)

### Introduction
The goal of this tutorial is to guide you through the creation of a Reddit/Hacker News clone using Rails 4 and AngularJS. By completing this tutorial, you will gain a basic understanding of Rails and AngularJS, using Rails to build a JSON REST API that interacts with an AngularJS frontend.

### Prerequisites
This course assumes knowledge of programming and at least basic knowledge of JavaScript and Ruby, and you should be comfortable with basic web application concepts including [REST](http://en.wikipedia.org/wiki/Representational_state_transfer) and [CRUD](http://en.wikipedia.org/wiki/Create,_read,_update_and_delete). Before you begin, you will also need to have Node.js and Rails already installed. We'll need Node.js and [npm](https://www.npmjs.com/) in order to use [Bower](http://bower.io/) to manage our front-end dependencies. Follow [these installation instructions](https://github.com/joyent/node/wiki/Installing-Node.js-via-package-manager) in order to install Node.js. Installation instructions for Rails can be found [here](http://railsapps.github.io/installing-rails.html). Rails ships with [sqlite3](http://www.sqlite.org/) by default so follow [these instructions](http://mislav.uniqpath.com/rails/install-sqlite3/) to install sqlite if you don't already have it on your system.

### Project Specifications
Before beginning work on any project, it's usually a good idea to know what you're building. Below is a basic list of things we want our users to be able to do:

* Create new posts
* View all posts ordered by upvotes
* Add comments about a given post
* View comments for a given post
* Upvote posts and comments
* Create a user authentication system using [Devise](https://github.com/plataformatec/devise)
