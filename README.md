# myarticles

This is a simple Ruby on Rails crud code

Ruby version: 3.0.3

* To run this project first install the bundles using "bundle install" command

* Run "rails db:create" to create the myarticles database used in this project.

* Run "rails db:seed" to run the initial seeds

* Run "rails s" to start the server. It will use port 3000 so make sure this port is not being used by any other programs.

# Routes

* Start using the system by any API platform you like.

* Since it's running locally we will use localhost:3000 as our server URL.

* All routes are public and doesn't require authentication.

* The POST route is http://localhost:3000/api/v1/articles and the body is: { title: string, body: text } JSON format.

* The GET route is http://localhost:3000/api/v1/articles/:id

* The PUT route is http://localhost:3000/api/v1/articles/:id and the body is { title: string, body: text } JSON format.

* The DELETE route is http://localhost:3000/api/v1/articles/:id
