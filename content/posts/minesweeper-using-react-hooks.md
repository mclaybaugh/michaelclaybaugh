---
title: "Minesweeper Using React Hooks"
date: 2019-04-19
images:
tags:
  - react
  - parcel
  - css-grid
---

I created minesweeper using React and Parcel. Check it out!

![minesweeper example gif](/images/minesweeper.gif)

The goals of this implementation were as follows:

1. Use React and React hooks
2. Keep the dependencies and build process as simple as possible

## State management in React

As I began working on the project, I started using the ‘useState’ hook
and then shortly after upgraded to ‘useReducer’. While this hook was
able to do everything I needed for this app, I do not believe that
going through the React documentation for hooks is a good way for
developers to get introduced to state management. For developers
looking to get more experience in managing state in applications, I
would instead recommend looking into [Elm](https://elm-lang.org) and
[Redux](https://redux.js.org). However, it is
still very early in the life of React hooks. From the features they
provide while remaining class-free, I think that eventually they will
be the best method for managing state and side effects in React apps.

## Building React Applications

To keep the build process simple, I used
[Parcel](https://parceljs.org/). It worked great,
although I had some issues with the auto-reloading while developing in
Vim. For those looking for a no-hassle bundling/build tool, Parcel is
a solid tool to consider.

## Next Steps

Some areas of improvement that I have identified already for this
implementation include separating out functions from the component
files into an organized folder structure, and also incorporating
strategies to enforce the immutability of state variables.

Going forward, I plan on implementing and improving this Minesweeper
project in various other methods and frameworks, including with React
and Redux, with Elm, and with Vue.

View this project on GitHub at
[https://github.com/mclaybaugh/minesweeper-react](https://github.com/mclaybaugh/minesweeper-react)
