# New York Times Article Saver
> Save and comment on the best news

## You can try it out yourself here: 
https://ny-times-articles.herokuapp.com/

## What Is it

This is a single-page web app, built with the MERN stack, that utilizes the New York Times API to query news of the user's choosing. The displayed articles can be saved by clicking the save icon next to the article. Once the article is stored, the user can save their comments for each article.

## Technologies Used

1. React - For client-side routing and state
2. Express - For serving and api routing
3. Node - For compiling Javascript
4. MongoDB - To store article and comment data
5. Bootstrap Framework
6. HTML
7. CSS
8. Javascript

## Starting the app locally

You will need to get an NYT API (get one here: https://developer.nytimes.com) and paste the key on line 12 of the articlesController.js file. Then install the front and backend dependencies. While in the root directory, run the following commands:
yarn install
cd client
yarn install
cd ..
After both installations complete, run the following command in your terminal:
yarn start

That's it, your app should be running on <http://localhost:3000>. The Express server should intercept any AJAX requests from the client.