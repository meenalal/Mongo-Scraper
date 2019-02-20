# mongo-news-scraper
The app scrapes Wired for top stories on their homepage and enables the user to save articles for later. This was a difficult assignment as it uses many technologies for the functionality. In fact, the app should allow the user to comment and store comments on individual stories, but I couldn't get this to work. There is a lot going on behind the scenes in this app technology - wise, which contributed to my difficulity in completing the app. The app scrapes using Cheerio and mutiple REST API routes to gather JSON. Next, it is connected to MongoDB to push the stories into the database and schemas are created using Mongoose. It also uses Handlebars templating to render the results on the DOM. The front end framework uses Materialize components and server side programming is accomplished with Node.JS and Express. Finally, Heroku is used to host the app. I enjoyed programming this and am relatively happy with how it turned out. I'll eventually figure out the commenting functionality, but due to time constraints, it isn't yet complete.

# Technologies Used
Built with HTML, Javascript, JQuery, CSS, Materialize, Node.JS, Express, Handlebars, Mongoose, MongoDB & Heroku.

# Link to App.
https://.herokuapp.com/

# Screen Shots
![scrape1](https://user-images.githubusercontent.com/27470842/37533480-31543b1e-28ff-11e8-98c2-e6efc81d2734.PNG)
![scrape2](https://user-images.githubusercontent.com/27470842/37533483-3346b6cc-28ff-11e8-9712-57adcec77daf.PNG)
![scrape3](https://user-images.githubusercontent.com/27470842/37533489-361f2564-28ff-11e8-923e-18c0d831419d.PNG)