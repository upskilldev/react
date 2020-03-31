# React - Step by Step guide

## Preparing yourself for React:

For learning React, there are some prerequisites to be fulfilled first :

1. **Learn basic HTML:** Just have the knowledge of the tags, else you can always look up to
   resources like [W3Schools](https://www.w3schools.com/html/). These can work as a cheat
   sheet while developing React applications.
2. **Learn basic Javascript:** Get familiar with ES6 Javascript syntax, DOM manipulations and
   prototyping. A better resource can't be found than [W3Schools](https://www.w3schools.com/js/).

Why this is required first in order to learn React will be cleared in the upcoming section.

## What is React?

According to [React official documentation](https://reactjs.org/) it states:
_"A JavaScript library for building user interfaces"_

In React, logic and UI is coupled into one module called the _component_. These components are nothing but the fusion of JS(Javascript) and HTML. Consider one element declaration:

```javascript
const element = <h1>Hello, world!</h1>;
```

If you've a slight knowledge of the above languages, you can spot right away that it is both JS
and HTML combined. This is called the JSX syntax and it is the primary foundation of React applications.

These elements or _JSX components_ are the building blocks of React applications.

## Already familiar with HTML and JS:

For those, who have been first completing the prerequisites, I know there is no end to gaining knowledge. You try and something new comes out of it, may be it is a new observation or an error.
But as I told, basics are enough to get started with React. You can learn more of HTML and JS while learning React as I did.

Reading through the documents for a long time is as boring as reading a Mathematics books looking at the problems and not solving them. So set up React and dive right into it.

### Setting up environment and get started:

1. Get familiar with [Node Package Manager(npm)](https://www.npmjs.com/) and setup [Node](https://nodejs.org/en/) in your system.
2. Install `create-react-app` in your system as directed in the [docs](https://reactjs.org/docs/create-a-new-react-app.html#create-react-app)
3. That's it! You can now create a new React app by just typing the command: `create-react-app myFirstProject` and tadaa, the instructions come to your terminal to start the React application. It forms a basic React application to get you started and edit the code in the way you want your application to work like.
4. Install a decent code editor which supports variety of plugins. There are various code editors available in market for free such as [VSCode](https://code.visualstudio.com/), [Atom](https://atom.io/) or [Sublime Text](https://www.sublimetext.com/).
5. Open up the application in your code editor and start editting the code as you like.

**Note for those who do not have systems meeting the minimum requirements to set up the environment**:
Don't worry, you can start creating React applications on online backgrounds such as: [CodePen](https://reactjs.org/redirect-to-codepen/hello-world), [CodeSandBox](https://codesandbox.io/s/new), [Glitch](https://glitch.com/edit/#!/remix/starter-react-template) and [StackBlitz](https://stackblitz.com/fork/react).

## Resources to start learning React:

**Disclaimer: Redux is not yet discussed in this documentation as this part is meant to get started for React. Redux is an advanced topic in React which comes later into the picture. If any of the tutorials mention to teach you Redux, please don't fall into it and keep it for later.**

1. My only resource to learn React was to go through the [official docs of React](reactjs.org/). It has an excellent guide to get you started with React and the guide is not overwhelming at any point or topic.
2. Youtube Resources: There are some pretty decent channels that claim to make you zero to hero in React but the reality is the level of skill depends on how much you dare to take the challenges(the errors that pop up every time you mess up something) and play with the code. But if you are more comfortable with visual learning aids such as video tutorials rather than reading the documentation, I will suggest couple of channels for you:
   1. [Codevolution](https://www.youtube.com/watch?v=QFaFIcGhPoM&list=PLC3y8-rFHvwgg3vaYJgHGnModB54rxOk3)
   2. [The net ninja](https://www.youtube.com/watch?v=OxIDLw0M-m0&list=PL4cUxeGkcC9ij8CfkAY2RAGb-tmkNwQHG)
   3. [FreeCodeCamp](https://www.youtube.com/watch?v=DLX62G4lc44&list=PLWKjhJtqVAbkArDMazoARtNz1aMwNWmvC): I haven't tested it out yet, feel free to try it though.
   4. [Ben Awad](https://www.youtube.com/watch?v=p6c7QA9ofvI&list=PLN3n1USn4xlntqksY83W3997mmQPrUmqM): It is somewhat advanced for begginners. Keep it for later when you are done with creating one full functioning React application. It focuses more on how to write cleaner code etc. and other advanced concepts.

### Projects for begginners:

As truly said: you cannot learn to code without coding. When familiar with how React works and it's syntax, you can try out your hands on creating some basic level projects on React:

1. [Calculator](https://github.com/ahfarmer/calculator)
2. [BMI Calculator](https://github.com/GermaVinsmoke/bmi-calculator)
3. [Todo Application](https://scotch.io/tutorials/create-a-simple-to-do-app-with-react)

### Advance React:

This section is supposed to be meant for those who are now completely familiar with react and can build at least basic or begginner level applications in React. For moving on into advance react:

1. Learn [Hooks](https://reactjs.org/docs/hooks-intro.html): For cleaner code and development.
2. Learn [Redux](https://react-redux.js.org/): It focuses primarily on state management.
3. Learn [Testing in React](https://reactjs.org/docs/testing.html).
