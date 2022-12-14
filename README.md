# Description
This a quick project that implements a Single Page Application using an API call to extract data and display it using React Components. Some of the tools I used/learned are:
- React.js
- Bootstrap
- ESLint
- Javascript Fetch
- Webpack
- Babel

# Notes
- The official documentation for React doesn't state any preferred approach regarding how to structure our React project, although two common approaches are popular within the community: either structuring your files by feature/page or structuring them by file type.
- The previous method that we used to retrieve information from JSON files using fetch doesn't take into account that the request to this file may fail. If the request fails, the loading state will remain true, meaning that the user will keep seeing the loading indicator. If you want to display an error message when the request doesn't succeed, you'll need to wrap the fetch method inside a try...catch block