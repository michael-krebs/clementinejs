---
layout: site
---

# About Clementine.js

Clementine.js started as a personal project to create a boilerplate that would help me easily stand up a new project using the MEAN stack (MongoDB, Express, Angular.js & Node.js). As a novice, I found that other boilerplates were often too feature-rich and contained a lot of moving pieces that were difficult to untangle. Additionally, I wanted to ensure that each piece of the application was well-documented and easy to grasp for new developers.

The purpose of Clementine.js is to provide a lightweight boilerplate for projects where the developer wishes to perform most of the integration him or herself without having to remove many (or any) features. 

Over the next few months, Clementine.js will evolve to include new features and offer a rich, but lightwweight boilerplate for MEAN stack projects.

## Why X Library / Framework / Etc?

Clementine.js does include a few frameworks & libraries in an attempt to make the developer's life a bit easier. However, all or some of these can be stripped out easily for a completely custom experience. Below, I will explain my choice to include certain libraries and frameworks.

### Why the MEAN stack?

Put simply, because it's the stack I use and prefer for development at the moment. I appreciate that I can query the database, write front-end code and write back-end code all with one language: JavaScript. That makes this stack extremely powerful and flexible. However, feel free to mix and match any of these to fit your taste.

### Why Jade?

Jade is my template engine of choice, and although there is not any templating in this boilerplate -- I really enjoy the syntax that Jade provides for HTML. In my opinion, the use of Jade is worth it entirely for the syntax, and I believe that it makes HTML easier to read and write.

### Why Mongoose?

I come from an SQL background where DB schemas are the norm. In this case, I like the definition that Mongoose brings to the table. Additionally, some of the syntactical sugar is helpful. It's extremely easy to simply use the Mongo NodeJS driver (which is also great), but Mongoose feels a little like home for me when working with a document-store DB like MongoDB.

### Why Gulp?

I feel like the streams in Gulp are more user-friendly than Grunt. Both are really great, but my preference is Gulp.

###Why Sass?

Sass is really great. The syntax makes CSS easier to read and faster to code. The imports enable a modular approach to CSS that makes it easier to find what you're looking for. Working in and navigating a huge style sheet can be extremely painful and time-consuming. The availability of variables for commonly-used styles ensures consistency and readability.

## Why 3 versions?

Originally, there was only going to be the standard version. As I continued to build out the boilerplate, I continued to realize that I would need a simple version for beginners and a bare bones version for someone who wanted to get started quickly. 

Below is a table showing the features between the three versions.

| Features 				| Beginner 	| Standard 	| Bare 		|
|:---------				|:--------:	|:--------:	|:---------:|
| Commented Code		| _Yes_ 	| _No_ 		| _Yes_		|
| Example Controller 	| _Yes_ 	| _Yes_		| _Yes_		|
| Example Directive 	| _No_ 		| _Yes_		| _No_		|
| Jade					| _No_ 		| _Yes_ 	| _Yes_	 	|
| Mongoose				| _No_		| _Yes_		| _Yes_		|
| Gulp				 	| _No_		| _Yes_		| _Yes_		|
| Sass					| _No_		| _Yes_		| _Yes_		|
| Bower					| _Yes_		| _Yes_		| _Yes_		|