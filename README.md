# Play with javascript nodeJs

In this repo, we will play with javascript, nodejs and [Electron](https://www.electronjs.org/docs/latest/tutorial/quick-start)

## 1. **What is JS?**
JavaScript is a programming language initially designed to interact with elements of web pages. In web browsers, JavaScript consists of three main parts:

- `ECMAScript` provides the core functionality.
- `The Document Object Model (DOM)` provides interfaces for interacting with elements on web pages
- `The Browser Object Model (BOM)` provides the browser API for interacting with the web browser

When a web page is loaded, i.e., after HTML and CSS have been downloaded, the JavaScript engine in the web browser executes the JavaScript code. The JavaScript code then modifies the HTML and CSS to update the user interface dynamically.

The `JavaScript engine` is a program that executes JavaScript code. In the beginning, JavaScript engines were implemented as `interpreters`.

However, `modern JavaScript engines are typically implemented as just-in-time compilers` that compile JavaScript code to bytecode for improved performance.

**Client-side vs. Server-side JavaScript**
When JavaScript is used on a web page, it is executed in web browsers. In this case, JavaScript works as a client-side language.

`JavaScript can run on both web browsers and servers. A popular JavaScript server-side environment is Node.js`. Unlike client-side JavaScript, `server-side JavaScript executes on the server that allows you to access databases, file systems, etc.`

For more details on JS, please visit this [page](./js_tutorials.md) 

## 2. What is Node.js

**Node.js is an open source server environment which runs JavaScript on the server.**

- Node.js can generate dynamic page content
- Node.js can create, open, read, write, delete, and close files on the server
- Node.js can collect form data
- Node.js can add, delete, modify data in your database

**What is a Node.js File?**
- Node.js files contain tasks that will be executed on certain events
- A typical event is someone trying to access a port on the server
- Node.js files must be initiated on the server before having any effect
- Node.js files have extension ".js"

## 3. Setup dev env for nodeJs

### Install nodeJs

You can find the complete installation doc on all OS [here](https://github.com/nodesource/distributions#debinstall)

In our case, it's an unbuntu, you can follow the below steps:


```shell
# get the source
curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash - &&\

# install the nodejs
sudo apt-get install -y nodejs

# check the installation
node --version

# the default package manager of Nodejs is npm. So it's intalled with node
# you can check your npm version
npm -v

# update the npm version
sudo npm install -g npm@latest
```

Here we choose the version 18.x, because it's the LTS version. The latest 19.x is not LTS.

