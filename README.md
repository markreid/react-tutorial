# Intro to React Tutorial

This follows the [Intro to React](https://reactjs.org/tutorial/tutorial.html) tutorial from [reactjs.org](https://reactjs.org).



### Getting Started

You'll need Node and git installed to begin.

```
git clone https://github.com/markreid/react-tutorial.git
cd react-tutorial
npm install
npm start
```


This will clone the repository, install its dependencies and run a dev server.

A new browser window will automatically open with the app running, and the dev server will take care of updating it automatically when you make changes to the code base.



### Following the tutorial

Start by checking out the first step:
```
npm run first-step
```

This code is the _Starter Code_  from the [Getting Started](https://reactjs.org/tutorial/tutorial.html#getting-started) section.


You can step through the code every time you see a **View the current code** link in the tutorial, by running:

```
npm run next-step
```

**Note!** This will override any local changes you've made and bring your code up to date with the tutorial code; so your best bet is to only do this if you end up getting stuck.


You can step back with `npm run prev-step` and go to the end with `npm run last-step`.

You can clear any changes you've made to the current step with `npm run clear-step`.


Behind the scenes, this is just using git to check out different branches.
