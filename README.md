# Simple and super easy to create the react application
It is simple!!! react application is created with the help of command [create-react-app](https://create-react-app.dev/)

```
npm/npx create-react-app <<app name>>
```

###### Have a look Some difference between npx vs npm

NPM | NPX
------------ | -------------
The npm stands for Node Package Manager | The npx stands for Node Package Execute
NPM by itself does not simply run any package. If you want to run a package using NPM, you must specify that package in your package.json file. | NPX will check whether <command> exists in $PATH, or in the local project binaries, and execute it, also is the ability to execute a package which wasn't previously installed.
When executables are installed via NPM packages, NPM links to them: 1. local installs have "links" created at ./node_modules/.bin/ directory. 2. global installs have "links" created from the global bin/ directory (e.g. /usr/local/bin) | npx command may be helpful in the script section of a package.json file, when it is unwanted to define a dependency which might not be commonly used or any other reason: Example  "start": "npx gulp@3.9.1"



Before you start creating the app, please check whether node js is installed in your machine. 

Please run below command in command prompt.

```
node -v
```

![image](https://user-images.githubusercontent.com/81896060/127759318-2651f61f-e8f7-4c60-87b1-60c4e60c940c.png)

Also check npm(node package manager) version

```
npm -v
```

![image](https://user-images.githubusercontent.com/81896060/127759502-7878d655-dcd2-47a0-add1-8a8fdeee2f76.png)


Please [Download](https://nodejs.org/en/download) the node js and install, If Node JS is not installed in your machine.

## Lets Start Creating the app

Use below mentioned command to create the new react app

```
create-react-app first-react-app
```

Sometime you will get error like `'create-react-app' is not recognized as an internal or external command,
operable program or batch file.` it is due to command is not regstered globaly. Use below command to register the create-react-app then run again `create-react-app first-react-app`.

```
npm install create-react-app -g
```

OR use below command to create the react app(i.e with the help of *npx*)

```
npx create-react-app first-react-app
```

The above command generate a react app boilerplate within the path the command had run in, and ensures that you always use the latest version of a generator or build tool without having to upgrade each time you’re about to use it.

![image](https://user-images.githubusercontent.com/81896060/127759954-aebcf4ee-12ac-4ebf-82e0-d8fee4f50dcd.png)

![image](https://user-images.githubusercontent.com/81896060/127759974-41d829dd-82fe-47bb-bffc-c13762a7ccfa.png)

Greate we have created the first react app

Just Relax and redirected to created directory and run the application with the help of below commands

```
cd first-react-app
npm start
```

![image](https://user-images.githubusercontent.com/81896060/127760070-4ba80c12-326f-4faa-9d9c-67929917e11d.png)

Here is the Output screen

![image](https://user-images.githubusercontent.com/81896060/127760082-f0c4f56e-1bb9-47c2-9443-b7faa4d17a76.png)


## Lets Learn something about React App Folder Structure:

As we know already, ReactJs is a frontend Javascript library and its used for building rich and awsome User Interfaces.

React is also called as Single Page Applications because React contains only one html file and all others are handled by Javascript. In a traditional website like ASP.Net, Java, we would have a different html files being served for different features. But React is all about Components and Components refer to small independent parts of your specific functionality and UI.

After creation of react application, our project look like this:

![image](https://user-images.githubusercontent.com/81896060/127761602-030d67e4-c143-45a3-97e2-a7c25414b253.png)

## node_modules

node_modules folder contains all the dependencies & packages that may be used for building you react app, we should not modify this folder.

## public

All the static files kept under public folder like favicon, logo, robots.txt etc... Public folder files will be accessed via %PUBLIC_URL%
index.html file is the root file of the react application, Everything will be rendered through it on the front end. 

## src

In src folder we can keep all the items like css, components and other assets of our projects. This folder also consists file like startup.

###### App.Js

App.Js is a component also called as parent component file of our react application, we import this file inside index.js component to render content in the root element(public folder index.html).

![image](https://user-images.githubusercontent.com/81896060/127765911-8dd7c6e7-616d-4560-b73a-692e8ef193df.png)


`It is not mandatory that we should use file name as App.Js, we can keep any name same should be imported in index.js as wel as we should make sure that its extension must be .js and its name must start with an uppercase letter`

Next we will discuss about index.js

## index.js

It is satarting point of our application, all the component in our application renders through this file to the index.html(in public folder)

![image](https://user-images.githubusercontent.com/81896060/127765762-97a17169-dcef-4d41-801d-24eb4c82d4dc.png)

all the componet detail will be loaded in div with id root in index.html

![image](https://user-images.githubusercontent.com/81896060/127765830-aabb7462-7c23-40d2-b124-511826ab69fb.png)


## package-lock.json

This file is mainly used to maintain the version of installed dependencies

## package.json

This file help us to maintain the, which dependencies are necessary for our application

That's it for this article, in case any concerns please reach out to [Reach to Author](chakrapani24@outlook.com)

[Please Visit](https://lastbenchcoder.blogspot.com) our blog for detail.

** Have a great day **
