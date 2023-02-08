# Tic-Tac-Toe

## Description:
This project was an assignment for the MIT XPRO course. We were given some files and code to work with and were instructed to make the tic-tac-toe game functional. We focused on Parent And Child components in A game, Mounting And Unmounting square components, Parent And Child Re-render and what we could to to improve the Tic-Tac-Toe game.

## How to Run:  
 To view the live page, click the link here [netlify](https://main--tranquil-dasik-658a2c.netlify.app/).  
 To Run it using React follow the Getting Started with Create React App documentation below.
 
## Roadmap of future improvements: 
I will make it so that the buttons are disabled after they have been clicked. When a player places their piece (x and o) on that square it can't be used again. I will implement this by giving the buttons a disable function once clicked. I will also use a strikethrough or highlight to show where there are 3 in a row. I'm not sure how I will implement this yet. I can use strikethrough but not sure yet how to manipulate only the pieces that are 3 in a row. I will change the "Winner is:" section to a pop up after there is a winner. I can do this by hiding the element until there is a winner. Once there is a winner the div will then be visible and appear as a pop up. I would also change the placement of the div to "popup" within the gameboard so that the players will see that there is a winner on the gameboard. I will create a score element to add a point to the player each time there is a winner and create a button to start a new game without restarting and resetting the score. I can implement this by adding a score function that allows the gameboard to reset while adding and keeping the score. I could implement the new game button by clearing the buttons. I could implement a score card by adding a score element and placing it where it will look good on the page.  I would like to use clipart or png for the pieces instead of X and O. I'm not sure how to implement that but I think I can add a function to hold the art as players. I would also style the game with colors and borders etc to match the art. I would implement the styling by utilizing CSS.

## License information: 
MIT License

Copyright (c) 2023 Jennifer Gerred

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
