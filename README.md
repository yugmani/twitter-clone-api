# twitter-clone-api

## TODO(API): Set up NodeJS Server

Return `Hello World` for the root `/` get request

[Example](https://expressjs.com/en/starter/hello-world.html)

## TODO(API, TOGETHER): Create API endpoint `/tweeets` to return a list of tweets based on query

Use [axios](https://github.com/axios/axios) for making an API request to Twitter API

Console log the data

Return as a response

## TODO(API): Create Twitter `get()` helper function to move the Twitter API logic

#### HINTS:

    - Create Twitter class inside `api/helpers/twitter.js`
    - Create a `get()` function that takes in the necessary parameters
    - Inside `get()` return `axios.get(...)`
    - Import Twitter class in `app.js` with `const twitter = new Twitter();`
    - Initialize and use the `twitter` object to now do somethong like `twitter.get(...).then(...).catch(...)`

## TODO(API, TOGETHER): Move the API Token to .env file and import it
