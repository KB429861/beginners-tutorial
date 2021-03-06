# Beginners Tutorial

This tutorial contains information about common tools and frameworks used to create web applications.

## Git

[Git](https://git-scm.com/) is a free and open source version control system.

If you are new to git, you can read [Pro Git book](https://git-scm.com/book/en/v2), primarily chapters 1, 2, 3 and 5.

Also you can get acquainted with git from the [interactive course](https://try.github.io) or learn about git branching from the [interactive tutorial](https://learngitbranching.js.org/). 

After that you can read about three popular git workflow and branching models:

* [A successful Git branching model](http://nvie.com/posts/a-successful-git-branching-model/)
* [A stable mainline branching model for Git](http://www.bitsnbites.eu/a-stable-mainline-branching-model-for-git/)
* [Introduction to GitLab Flow](https://docs.gitlab.com/ee/workflow/gitlab_flow.html)

## Database

### JDBC

[JDBC](https://en.wikipedia.org/wiki/Java_Database_Connectivity) is a Java API to connect and execute query with the database.

### JPA / Hibernate

[JPA](https://en.wikipedia.org/wiki/Java_Persistence_API) is a Java API specification that describes the management of relational data in applications.

As an implementation of JPA can be used [Hibernate](http://hibernate.org/) framework. 

An example of using Hibernate JPA can be found [here](http://tomee.apache.org/examples-trunk/jpa-hibernate/README.html). 

### Flyway

[Flyway](https://flywaydb.org/getstarted/) is the open-source tool that makes database migrations easy.

Official site contains general information on [database migrations](https://flywaydb.org/getstarted/why) and [how Flyway works](https://flywaydb.org/getstarted/how).

Also there you can find information about how to implement [database migrations with Flyway on Java](https://flywaydb.org/getstarted/java).

## HTML & CSS

Here is a simple and comprehensive [guide](https://learn.shayhowe.com/html-css/) dedicated to helping beginners learn HTML and CSS.

It contains a set of lessons with a practical part.

Also there are good [HTML](https://www.w3schools.com/html/default.asp), [CSS](https://www.w3schools.com/css/default.asp) and other tutorials with examples on the [W3Schools](https://www.w3schools.com/) website.

## JavaScript

If you are already familiar with JavaScript, you can just [refresh your JavaScript knowledge](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript).

For a better understanding of JavaScript, yo can read the [modern JavaScript tutorial](https://javascript.info/), primarily Part 1.

If you want get a stronger JavaScript foundation, read the [Eloquent JavaScript](http://eloquentjavascript.net/) book. 

#### Practice

As a practical task, try to create a pure-javascript calculator. 

Additional functional requirement is to preserve the history of operations and show it to the user.

Use HTML and CSS to create a user-friendly interface.

## AngularJS

[AngularJS](https://angularjs.org/) is a structural framework for dynamic web apps.

A great way to get introduced to AngularJS is to work through [this tutorial](https://docs.angularjs.org/tutorial).

#### Practice

For a some practice you can try to create an app that monitors changes in the Bitcoin Price Index (BPI).

Use [CoinDesk Bitcoin Price Index API](https://www.coindesk.com/api/) to retrieve price information.

By default, the CoinDesk website publishes the BPI in USD, EUR, and GBP, but you can add an additional field to show BPI for any custom selected currency.

Here is an example of application layout:

|...|...|...|
|---|---|---|
| ![Screenshot 1](https://user-images.githubusercontent.com/33935506/34460771-4309303a-ee21-11e7-8a41-867a266e092c.png) | ![Screenshot 2](https://user-images.githubusercontent.com/33935506/34460772-4337f320-ee21-11e7-9cc5-aa3b78f5f6b0.png) | ![Screenshot 4](https://user-images.githubusercontent.com/33935506/34460774-43a80264-ee21-11e7-8323-fbee96ccce35.png) |

## ReactJS

[React](https://reactjs.org/) is a JavaScript library for building user interfaces.

In [this tutorial](https://reactjs.org/tutorial/tutorial.html) you can learn how to build an interactive tic-tac-toe game with React.

On the official site you can read [documentation](https://reactjs.org/docs) for a better understanding of React.

Also here is an [interactive guide](http://buildwithreact.com/tutorial) to React.

#### Practice

Try creating a Social Card component like on the image below.

![Social Card](https://daveceddia.com/images/social-card.png)

Once you have a single SocialCard component rendering, try making a list of them with some fake data.

### React Router

[React Router](https://reacttraining.com/react-router/) is the standard routing library for React.

### Redux

Redux is a predictable state container for JavaScript apps.

On the [official site](https://redux.js.org/) you can find [general information](https://redux.js.org/introduction) about Redux, as well as [basics](https://redux.js.org/basics) and [advanced](https://redux.js.org/advanced) walkthroughs.

You can use Redux together with React, or with any other view library.

#### Practice

Try creating a Weather App which displays a 5-day weather forecast, where each day shows the high and low temperatures, and an image for sunny/rainy/cloudy/snowy. Use fake, hard-coded data until you’ve got everything rendering correctly.

![Weather App](https://daveceddia.com/images/weather.png)

For added practice, here are a few ways you could expand on the app:

* Add the ability to click on a day, and see its hourly forecast. You can just maintain the current view in the top-level App state.
* Add React Router to the project and add routes, such that `/` shows the 5-day forecast, and `/[name-of-day]` shows the hourly forecast for a particular day.
* Sign up for a free API key from [Open Weather Map](https://openweathermap.org/), fetch a real 5-day forecast, and feed that data into your app.

You can see how this app starts off simple, but can be expanded at will to increase the challenge and the learning.

## Vaadin Framework

[Vaadin Framework](https://vaadin.com/framework) is a Java UI framework that simplifies web app development.

[This tutorial](https://vaadin.com/docs/v8/framework/tutorial.html) gives you an overview of how you can use Vaadin Framework to build single-page web UIs for your Java application.

## Spark Framework

[Spark](http://sparkjava.com/) is a micro framework for creating web applications.

Here you can find [documentation](http://sparkjava.com/documentation) and [tutorials](http://sparkjava.com/tutorials/).

#### Practice

To improve your practical skills you can go through the following tutorials:

* [Building a JavaScript todo-list app](http://sparkjava.com/tutorials/ajax-without-writing-javascript)
* [Building a contact app](http://sparkjava.com/tutorials/cloud-contact-app)
* [Building a Twitter clone](http://sparkjava.com/tutorials/twitter-clone)

## Play Framework

[Play](https://www.playframework.com/) is a high-productivity Java and Scala web application framework that integrates the components and APIs you need for modern web application development.

All the necessary information can be found in the [official documentation](https://www.playframework.com/documentation/1.4.x/home).

#### Practice

Create an expense tracker application that combines Play Framework and AngularJS.

Create a simple interface you can use to add and categorize your expenses. Generate monthly reports based on the inputs and write custom alerts.

## Spring Framework

[Spring Boot](https://projects.spring.io/spring-boot/) is a framework for easy Spring application creation.

[This page](https://spring.io/guides) contains a list of official Spring guides.

I recommend to begin with the following tutorials:

* [Building an Application with Spring Boot](https://spring.io/guides/gs/spring-boot/)
* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)

If you need more information about Spring (e.g., integration with [ReactJS](https://spring.io/guides/tutorials/react-and-spring-data-rest/)/[AngularJS](https://spring.io/guides/gs/consuming-rest-angularjs/)/[Vaadin](https://spring.io/guides/gs/crud-with-vaadin/), [securing](https://spring.io/guides/topicals/spring-security-architecture/) an application) you can find it by the [link](https://spring.io/guides) above.

#### Practice

Make a simplified version of Github’s Issues page. [Here’s an example](https://github.com/facebook/create-react-app/issues).

Use Spring Data REST and its powerful backend functionality combined with React’s features to build an application.

Make use of React Router to implement page navigation and Redux to organize application state.

The application must show a list of available issues, and allow creating and commenting/changing states of issues.

Other functional requirements are:

* The application should retrieve the data from and store it in the database.
* All forms must support validation and display errors.
* User authentication and authorization is required.

For added difficulty, implement the issue detail page too. Render the issue’s Markdown text and its comments using something like [react-markdown](https://github.com/rexxars/react-markdown).
