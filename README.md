This is my first mini-project using node, express, ejs and railway hosting.

The main focus of this project is to really understand how everything nets together in the backend. First I created the app using express generator, adding -ejs as my templating engine.

Then I created an index.js in the routes directory, and in here managed what would be rendered with the "/" and "/new" routes. These use the render method to render the given views in the views directory.

A sample array of messages was created, and also a form page in views. When this form is submitted, a post request is made to "/new" route, which pushes the formatted data into the messages array.
