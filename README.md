# movie-database - Created with Redux and React

### Run 'npm start' in root folder to run application at http://localhost:3000

React Redux Application that fetches movie details from https://api.themoviedb.org/3/ and displays details such as film title, poster, synopsis, revenue and other details. Films are listed in a grid and can be searched by title or further films loaded by clicking a 'Load more' button.

### The following actions are added:

- GET_POPULAR_MOVIES - to load initial movie listing view
- SEARCH_MOVIES - to look up movies by title using a text input
- LOAD_MORE_MOVIES - to load the next page of movies upon clicking 'Load more' button
- CLEAR_MOVIES - to reset the movie listing view

Reducers are used to dispatch the actions and update the State of the Application accoding to the actions payload.
