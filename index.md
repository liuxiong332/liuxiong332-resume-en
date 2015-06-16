---
title: Liu Xiong
tagline: Front end engineer, NodeJS, Python backend engineer
layout: page
---

# Personal information

* **Graduated**: *Beijing Institute of Technology*
* **Work Experience**: *3 years*
* **Blog**: [http://liuxiong332.github.io](http://liuxiong332.github.io)
* **Github**: [https://github.com/liuxiong332](https://github.com/liuxiong332)
* **Mobile**: *18518723392*
* **Email**: *liuxiong332@163.com*
* **Expected positions**: *NodeJS engineers, front-end engineer, backend engineer*

----

# Biography
* `Coffee` and `Ruby` fans, have a strong curiosity for a variety of new technologies;
* Get familiar with `C/C++` compiler language, the PC client programming technology and `chromium`, `v8` browser technology;
* Get familiar with `Python/Ruby/Javascript` dynamic languages ​​and ecosystems;
* Get familiar with `Coffee` , `Javascript` and other front-end language, get familiar with `ES6`, `Sass/Less` and other CSS template language;
* Get familiar with the MVC framework `Angular` , UI library `React` , `jQuery` and `Underscore` libraries and other tools;
* Get familiar with `Grunt` and `Gulp` automated build tools, get familiar with `browserify`, `lint` , `uglify` and other tools;
* Get familiar with `Nodejs` framework, Nodejs enthusiasts.
* Get familiar with the back-end development framework `express`, `tornado` and `rails`, there are some studies on the backend.

# Work experience

### Kingsoft(2014.7 - date)

#### Mail client

  WPS Mail is the WEB App. It uses `HTML5` to describe the interface, `Javascript/Coffeescript` to describe the logic and C++ to complete the performance-critical part.

  The main responsibilities are:

  * Implement and test the `Exchange` protocol API.
  * Achieve the sqlite ORM that make the upper layer user more convenient and more Object-Oriented.
  * Optimize the message download speed and reduce the number of requests.
  * Reduce database reads count and improve performance by LRU cache algorithm.
  * Use `Promise/Yield` asynchronous programming model, to avoid nested callback.
  * Make UI blocking operations run in HTML5 Worker.
  * Write part of the UI and style.

#### Mail Social Backend

  We use `Python` as a back-end language that is simple and powerful and use lightweight asynchronous library `tornado` as a program framework.

  The major tasks are:

  * Set up the development environment, use `pybuilder` for automation integration, `flake8` for the code lint, `pip` and `setuptools` to specify the program dependencies.
  * Use `mongodb` database and `motor` as `mongodb` asynchronous driver library.
  * Design Restful API interface.
  * Use the MVC design pattern to make the app more flexible and more logical.

### Zhiyuan Electronics(2012.7 - 2014.4)

  Be responsible for the development of the logic analyzer. We complete a high performance, fast response instruments.

  The main contributions are:

* Improve development efficiency by using of `chromium base` and `ipc` library.
* Use `MessagePool` and `Task` multithreaded programming skills to reduce the use of mutex.
* utilize data cache to optimize data storage and improve IO performance.

# Open source works

### Atom

`Atom` is **The hackable editor** that developed by `Github`。This project's code quality is very high and I'm fortunate to become the committer. The main contributions are:

* Fix some bug.
* Adds feature - the resizable panes.

### Yeoman plugins

* `generator-node-gulp-coffee`

  Generate the template `Nodejs` projects that use `coffee`and `gulp`. It used by many nodejs module.(integrate `lint`、`test`、`converage`、`Travis CI` and other features)。

* `generator-karma-browserify`

  Add `karma` and `browserify` support for the web App. `browserify` enables the use of `Nodejs` module for the front-end js，`karma` make the web app integration test simpler.

### http-ext

`http-ext` is a scalable, high flexible http client library. It's inspired by the `express`. Core only contains the basic framework. Other features and extensions can be expanded by plug-ins. Currently it contains the following plug-ins:

* `http-ext-ntlm`

  Achieve the `NTLM` authentication protocol.

The `basic` and `digest` authentication-support plug-ins is coming soon.

## libxmljs-builder

`libxmljs-builder` is a XML build nodejs library. It's inspired by `Ruby` module `Nokogiri`。This library simplifies the tedious process of constructing XML and greatly improves the efficiency of programming.

## Viewpoint

  Nodejs module that implement `Exchange` mail API.

## sqlite-orm

`sqlite-orm` is the ORM(object mapping model) library for sqlite. It dedicates to simplifying and optimizing the `sqlite` access. It's inspired by the rails of `ActiveRecord`.

## Xmail

`Xmail` is **The hackable mail client**。It develops upon the `Atom shell`. The project has achieved the `Exchange` and `IMAP` mail protocol。

It has the following features：

1. Use the latest HTML technology to develop UI，such as `Shadow DOM`(hide the details of UI element) and `registerElement`(define custom components)。
2. Use `Coffee` and `Less` to program, use `Grunt` to achieve automate build and `jasmine` for BDD test.
3. Encapsulate the UI component，utilize `React` library to write complex and efficient UI components and use **MVVM** pattern to decouple the model and the view.
4. Use the model-driven pattern(not the traditional event-driven pattern) to make the UI and model flexible and unified.
5. The code style is from the `Atom` that is clear and concise, also it has the high degree of modularity.
