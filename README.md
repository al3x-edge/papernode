PaperNode
========

##Overview
PaperNode is aimed to provide an easy to use API for building both simple and complex web applications.
PaperNode is comprised of two core parts, the API and Interfaces.

##API
The core of PaperNode is the API which is the only way to interact with the data stored within PaperNode.
The API provides a configurable, modular link to your data; whether it is user accounts, blog posts, comments, site pages, recipes or anything else you would need to store.
This easy to use interface to your application allows you to focus on the user experience rather than on how your data is stored or retrieved.
The API for PaperNode is also modular allowing you to turn off and on any features you wish, or to add your own if need be.

##Interfaces
Interfaces are how users interact with your data. Interfaces can be a simple web page, a cli script, a mobile or desktop application or even none at all.
Because of the abstraction between the interface and API layers, interfaces can be written using any technology.
This means that with PaperNode running as the API to your data you can write your interface in PHP, Python, ASP.NET, JavaScript or any other technology that supports sockets.

By default PaperNode provides three interfaces:
* CLI: A simple CLI interface to aid in configuring your application from a terminal.
* Web: A Web interface that allows users to browse your web site.
* Admin: A Web based admin interface useful for adding/editing content and configuring your application.

##Installation
```
npm install papernode --global
```

##Configuration
```
cd my/project/dir
papernode init
papernode run
```
