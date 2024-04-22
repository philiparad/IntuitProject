# IntuitProject
Intuit Project

intro
=====
Finite state machines are a conceptual model for dealing with conditional UI, connectivity monitoring & 
management to initialization and more.State machines simplify tangled paths of asynchronous code and easy to test.
In this project we will implement a FSM for a React application.

Library
=======
fsm-react@1.3.1
https://www.npmjs.com/package/fsm-react

Project
=======
This the list of components used in the project
1. index.js: This file is the entry point of the application. It renders the `App` component.

2. App.js: This file contains the `App` component, which serves as the main component of the application. 
   It imports the `DataLoader` component and applies styles generated by the `createStyles` function.

3. createStyles.js: This file contains the `createStyles` function, which generates CSS styles for the application components.

4. useFSM.js(For local use): This file contains the `useFSM` custom hook, which implements a finite state machine for managing the state of the application.
   Currently using the library `fsm-react`
   
6. DataLoader.js: This file contains the `DataLoader` component, which orchestrates the fetching of data and renders different components based 
   on the current state of the application (`IDLE`, `LOADING`, `SUCCESS`, `ERROR`).

7. DataDisplay.js: This file contains the `DataDisplay` component, which renders a table displaying information about random countries fetched from the API.

8. DataIdle.js: This file contains the `DataIdle` component, which represents the idle state of the application and renders a placeholder for data loading.

9. DataLoading.js: This file contains the `DataLoading` component, which displays a spinning spinner icon indicating that data is being fetched.

10. utils.js: This file contains the `getRandomCountries` function, which picks random countries from the fetched data.

This structure separates each component and functionality into its own module, making the codebase modular and easier to manage. 
Each component is responsible for a specific part of the application's UI or logic.

Tests
=====
npm test

Running environment
===================
Reat project under Node.js 21.7.3 / Webpack 5.38.1 / React 18.2.0

Demostration of Project
=======================
A working demo deployed on GitHub https://philiparad.github.io/


