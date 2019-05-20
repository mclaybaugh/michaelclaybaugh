---
title: "Vanillajs to React to Elm"
date: 2018-11-23
toc: false
tags:
  - elm
---

![Elm sample code](/images/elm-sample-code.png)

## Controlling a complicated UI is hard

In the interest of simplicity, I have leaned towards writing plain
ES5 JavaScript for my web projects. However, it is inevitable that
situations arise with more complicated user interfaces where
multiple components begin to depend on multiple other components,
and writing the logic to control the parts becomes both tedious and
prone to errors.

I encountered a problem like this when making a form where the first
two select inputs combined determined which fields would show in the
rest of the form. Even for this relatively simple design, I found
writing the logic to switch the form between the various states to be
difficult in that I had to account for each possible variation of how
a user may switch between the states. It became a game of testing the
form myself and finding all the ways it could break, and then fixing
them and repeating the process. It was not too difficult to complete,
but I knew that continued updates and maintenance on that form were
likely to be mired in danger and unforeseen bugs.

## Frameworks exist for a reason

I know of multiple frameworks that solve this problem, such as React
and Vue, but want to avoid downloading additional assets and adding
more requirements to the programming knowledge of future developers.
I strove to find a solution to this problem using plain JavaScript.

Thus far I have come to the conclusion that the best way to make a UI
is to declaratively describe how a view should look based on its
state, and have some mechanism to manipulate the DOM to render the
view (If you have other clever ideas on how to solve problems like
this one in vanillaJS, then please let me know).

I went so far as to start a new project on Codepen and write some of
the state logic, but then quickly realized that the rendering part of
this solution was fairly involved (creating new DOM elements and
removing them dynamically), and that was exactly why things like React
were created.

Next I started looking up more information about Redux as a possible
state management architecture to emulate, and found it referenced Elm
as a source of inspiration.

## Finding enlightenment

I looked into Elm, and then my eyes were opened.

In Elm I found a single tool (a language really) that enables (what I
find to be) elegant solutions to state management, declarative views,
and static typing. Before Elm, the only way I knew to incorporate
these features was to use three different tools (React/Vue,
Redux/Vuex, Typescript/Flow). And the tools I previously was familiar
with are inspired by functional languages, but are still written in
JavaScript. Elm provides solutions for all of these and it is a truly
functional language. It knows the difference between an int and a float.

Because of all of these things, I am excited to dig deeper into the
Elm language and create some new projects.
