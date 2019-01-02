https://reactjs.org/tutorial/tutorial.html

This setup requires more work but allows you to complete the tutorial using an editor of your choice. Here are the steps to follow:

Make sure you have a recent version of Node.js installed.

Follow the installation instructions for Create React App to make a new project.
https://reactjs.org/docs/create-a-new-react-app.html#create-react-app

npx create-react-app my-app
cd my-app
npm start


Delete all files in the src/ folder of the new project
Note: don’t delete the entire src folder, just the original source files inside it.. We’ll replace the default source files with examples for this project in the next step.

cd my-app
cd src

# If you're using a Mac or Linux:
rm -f *

# Then, switch back to the project folder
cd ..


Add a file named index.css in the src/ folder with this CSS code.
https://codepen.io/gaearon/pen/oWWQNa?editors=0100

vim src/index.css


Add a file named index.js in the src/ folder with this JS code.
https://codepen.io/gaearon/pen/oWWQNa?editors=0010


vim src/index.js


Add these three lines to the top of index.js in the src/ folder:

import React from 'react';
import ReactDOM from 'react-dom';
import './index.css';
Now if you run npm start in the project folder and open http://localhost:3000 in the browser, you should see an empty tic-tac-toe field.

We recommend following these instructions to configure syntax highlighting for your editor.