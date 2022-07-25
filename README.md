# Netflix Web App
The Netflix Web App allows users to register for an account and will be allowed to save and/or delete their favorite movie/tv show from a list listed under their accoount.

![netflix-min](https://user-images.githubusercontent.com/57330874/180817614-8a694ea4-7cae-4076-98df-0cac00512aa8.gif)

Link to project: [https://netflix-v.netlify.app/]

## How It's Made:
**Tech used:** React, Tailwind CSS, Tailwind Scrollbar, Firesore DB, The Movie DB API, Context API, React Icons, UseState, UseEffect, Axios, React Router DOM

I created a wireframe for the website to design the UI. Then I broke the react application down to 5-6 modules to oragnize the code and identify different sections of the website to divide my code into container components and presentational commponents. After filling my presentational and container components with the nesccessary data, I implemented Tailwind CSS for the styling and adjusted the styles accordingly to my liking as well as keeping the styles very similar to the actual Netflix website.

## Optimizations

I plan to add more content to the user dashboard where users can handle account and billing information. I plan to add more features as well to the website after reasearching what type of features could make the user experience better.

## Lessons Learned:
From making this project I learned more about handling data when making API calls and utilizing the React Hooks API. I also learned how to improve my time management skills by making a detailed wireframe and serperating my code into presentational and container components before coding my project which made it easier to identify which components would handle displaying cotent and which components that would handle managing data vs trying to build an application from scratch estimating where the content should go and which components that should manage the data. 

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

#### `npm install`
#### `npm i axios`
#### `npm i react-icons`
#### `npm install -D tailwindcss`
#### `npx tailwindcss init`
#### `npm i firebase`
#### `npm i tailwind-scrollbar`

#### Copy and paste `"./src/**/*.{html,js}"` into the content array inside of tailwind.config.js
```js
module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
}

```
#### Copy and paste inside of index.css
```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```
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
